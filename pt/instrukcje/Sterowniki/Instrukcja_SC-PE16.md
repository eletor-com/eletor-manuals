---
id: sc-pe16
title: SC-PE16 — manual de instruções
sidebar_label: SC-PE16
sidebar_position: 5
description: Manual do módulo de expansão de potência SC-PE16 — montagem, ligação,
  colocação em funcionamento, menu e proteções.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


O módulo de expansão de potência SC-PE16 destina-se ao controlo de ventiladores quando a carga excede a capacidade do controlador principal. O dispositivo regula a tensão de alimentação dos ventiladores com base num sinal analógico ou numa definição manual. A corrente total máxima de saída é de 16 A.

![Módulo de expansão de potência ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parâmetros e características

- modos AUTO e MANUAL e suspensão do dispositivo;
- visor gráfico e teclado tátil;
- controlo analógico 2–10 V ou 4–20 mA;
- limiar de ativação programável do grupo de ventilação 2.;
- byPASS com nível estabilizado de 100%;
- proteção térmica do circuito de potência;
- safeRUN: nível de funcionamento de emergência ajustável;
- calibração do nível mínimo de ventilação;
- teste da ventilação, do relé e do alarme;
- bloqueio do teclado e bloqueio para limpeza;
- idioma polaco, inglês ou ucraniano;
- alimentação 230 V AC, 50 Hz; caixa IP65.

:::info Versão do software

A descrição das funções refere-se ao software fornecido **vers. 2.1**. A disponibilidade das funções deve ser verificada em relação à versão instalada no dispositivo.

:::

## Instalação do controlador

:::danger Desligue a alimentação

Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, uma vez que a tensão presente em alguns componentes constitui um perigo para a vida e a saúde. Recomenda-se que a instalação seja confiada a uma pessoa qualificada.

:::

### Escolha do local de montagem

O dispositivo deve ser instalado num local acessível aos operadores, fora do alcance de crianças e animais e sem exposição direta à luz solar. O intervalo de temperatura ambiente é de −10°C a +40°C. Deve ser assegurada a livre circulação de ar em redor da caixa e do dissipador de calor. Não obstruir o dissipador de calor nem instalar o dispositivo junto de fontes de calor.

### Montagem

Fixar a parte inferior da caixa a uma parede plana com quatro buchas, utilizando os orifícios de montagem situados fora do compartimento vedado. Montar a tampa com a dobradiça incluída no conjunto. Antes de fechar, verificar o estado e o posicionamento da junta de vedação.

Utilizar cabos com secção exterior circular, adequados aos bucins. Apertar os bucins de modo a vedar e imobilizar o cabo. Tapar as passagens de cabos não utilizadas. Apertar a tampa com todos os parafusos. A estanquidade depende da montagem correta da caixa e das passagens de cabos.

### Preparação das ligações

Efetuar todos os trabalhos no interior da caixa após desligar a alimentação e verificar a ausência de tensão. Se a remoção do painel exigir a desconexão do cabo plano, desligá-lo cuidadosamente e voltar a encaixá-lo antes de fechar a caixa. Não ligar nem desligar o cabo plano com a alimentação ligada.

Encaminhar os cabos de sinal INPUT e ENABLE separadamente dos cabos de alimentação e de saída. Seguir as marcações dos terminais existentes no exemplar específico do dispositivo. A massa das entradas de sinal e o terminal de proteção PE desempenham funções diferentes e não são intercambiáveis.

## Ligação elétrica

:::danger Desligue a alimentação

Antes de ligar o circuito, certifique-se de que a alimentação está desligada!

:::

![Terminais de alimentação, ventiladores, GR 2, ENABLE, CAN e INPUT](./img/sc-pe16/zaciski.png)

| TERMINAL | FUNÇÃO |
| --- | --- |
| L, N, PE — alimentação | Alimentação 230 V AC, 50 Hz: L — fase, N — condutor neutro, PE — condutor de proteção. A documentação original indica uma proteção B20; a seleção das proteções e dos cabos deve ter em conta a instalação e a carga. |
| U, N, PE — ventiladores | U — saída de fase regulada; N e PE — terminais comuns correspondentes do dispositivo. A soma das correntes dos ventiladores não pode exceder 16 A. Cada ventilador necessita de uma proteção individual. Utilizar motores aprovados para regulação por tensão. |
| GR 2: C, NO | Contacto isolado do relé do grupo 2. Fecha quando o nível de ventilação definido é igual ou superior ao limiar «Grupo de ventilação 2». Corrente máxima do contacto segundo o manual fornecido: 6 A. Para o controlo direto de uma carga, a documentação indica uma proteção externa B6. |
| INPUT: V, massa | Entrada de tensão. Selecionar «Tipo de controlo → Entrada V». No programa analisado, o intervalo de regulação é de 2–10 V. Não ligar a esta entrada a tensão da rede nem a saída regulada de alimentação dos ventiladores. |
| INPUT: I, massa | Entrada de corrente 4–20 mA. Selecionar «Tipo de controlo → Entrada I». Ligar o sinal de acordo com as marcações da fonte e do recetor. |

Para o controlo, utilizar a entrada selecionada V ou I. SC-PE16 necessita de alimentação própria da rede; a entrada analógica transmite apenas o valor de controlo.

## Entrada ENABLE e comunicação

### ENABLE: E e massa

A entrada funciona com um contacto livre de potencial. Os terminais E e massa apenas podem ser ligados entre si ou separados; não aplicar tensão externa. O fecho permite o funcionamento, a abertura define o nível 0%. A paragem obedece à definição «Tempo de desaceleração».

A função ENABLE é ativada separadamente para AUTO e MANUAL no menu «Avançado → Ventilador». Ambas as funções estão desativadas de fábrica, pelo que, nesse caso, não é necessária uma ponte. A abertura de ENABLE não equivale à suspensão: o painel permanece ativo. Em AUTO, com o bloqueio ENABLE ativo, o programa ignora a leitura do sinal de controlo e não ativa safeRUN.

### CAN e Wi-Fi

As opções «Entrada CAN» e «Entrada WiFi» constam do menu, mas, no software vers. 2.1, não efetuam o controlo: ambas as funções devolvem o nível 0%. Para colocar o dispositivo em funcionamento com este programa, selecionar a entrada V ou I. Não configurar a instalação com base em CAN ou Wi-Fi sem confirmar o suporte na versão de software instalada.

## Princípio de funcionamento

SC-PE16 é um regulador de potência que executa as instruções do controlador principal ou do operador. Não mede a temperatura do espaço e não dispõe de definições próprias de temperatura, arejamento, aquecimento suplementar ou comportas de entrada de ar. O nível percentual de ventilação representa um valor de controlo e não uma medição da velocidade real do motor.

| SINAL NOMINAL | NÍVEL DE VENTILAÇÃO DEFINIDO |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Entre os valores-limite, o programa determina o nível de forma linear e arredonda-o para percentagens inteiras. Para a entrada V, o aumento inicia-se quando a leitura ultrapassa 2,04 V e, para a entrada I, 4,04 mA. O estado final da saída depende também de ENABLE, do arranque e da proteção térmica.

## Funcionamento de emergência e proteções

### safeRUN — perda do sinal de entrada

No modo AUTO, o alarme «Entrada» surge quando a leitura de tensão é inferior a 1,50 V ou a de corrente é inferior a 2,00 mA, consoante a entrada selecionada. O programa define então o nível «Funcionamento de emergência» no intervalo 0–100%; valor de fábrica 30%. Quando o sinal regressa ao limiar de deteção ou o ultrapassa, o alarme de entrada desaparece e o dispositivo regressa ao controlo analógico.

O intervalo 1,50–2,04 V e 2,00–4,04 mA produz o nível 0% sem alarme de entrada. O sinal 0 V não constitui, nesta versão, um comando normal de paragem — ativa o funcionamento de emergência. Um controlador principal com saída 0–10 V deve ser configurado para o intervalo 2–10 V sem corte para 0 V. Em MANUAL, o sinal analógico não controla a ventilação e o alarme de entrada é anulado.

### Proteção térmica

O alarme «Sobreaquecimento» é ativado quando a leitura da temperatura do dissipador de calor ultrapassa 87°C. É anulado quando a temperatura desce abaixo de 80°C. Durante o alarme, o programa altera o nível definido: para valores iguais ou superiores a 50%, define 100%, e para valores inferiores a 50%, define 0%. A alteração da saída obedece ao algoritmo de arranque e desaceleração. A proteção não garante o funcionamento contínuo da ventilação em todas as situações.

O estado do relé GR 2 é determinado antes da correção térmica: depende do nível anterior à imposição de 0% ou 100%. O nível de funcionamento de emergência também está sujeito à correção térmica. Em caso de sobreaquecimento, verificar as condições de arrefecimento, a sujidade do dissipador de calor e a carga; confiar os trabalhos no interior da caixa a uma pessoa habilitada.

### byPASS e arranque suave

Com um nível de saída estabilizado de 100%, o programa ativa o relé de derivação do circuito de regulação de fase. O arranque pode incluir uma subida até 100%, a manutenção em 100% e a transição para o nível definido. Os parâmetros «Arranque suave» também influenciam a rapidez de resposta da saída a uma alteração do valor solicitado.

## Primeira colocação em funcionamento do controlador

:::warning Calibração dos ventiladores

Atenção! Na primeira colocação em funcionamento do dispositivo, é obrigatório definir a faixa de funcionamento proibida do motor.

:::

1. Com a alimentação desligada, verificar as ligações da alimentação, PE, ventiladores e sinal analógico. Confirmar a aprovação dos motores para regulação por tensão e uma corrente total não superior a 16 A.
2. Ligar a alimentação. Se for apresentada a seleção do idioma, premir OK e selecionar o idioma. Desbloquear o teclado com o botão com o símbolo do cadeado.
3. Em «Tipo de controlo», selecionar «Entrada V» ou «Entrada I». Definir o nível «Funcionamento de emergência» e o limiar «Grupo de ventilação 2». Se necessário, ativar ENABLE separadamente para o modo correspondente.
4. Aceder a «Avançado → Ventilador → Faixa proibida». Nesta opção, o programa impõe o nível 1% e a alteração do parâmetro afeta imediatamente a saída. O intervalo é de −20 a 200, com valor de fábrica 0. Um valor positivo aumenta o nível mínimo de controlo; um valor negativo diminui-o.
5. Ajustar o valor de modo que todos os ventiladores rodem de forma estável, sem paragens nem aquecimento excessivo. Observar cada ventilador, de preferência com a ajuda de uma segunda pessoa. A simples elevação da comporta não substitui a verificação do funcionamento correto do motor. Confirmar com OK; ESC repõe a definição anterior.
6. Verificar a saída em vários níveis, incluindo 0%, um nível baixo e 100%. Repetir a calibração após a substituição dos ventiladores ou a alteração da sua configuração.
7. Em AUTO, verificar a resposta aos sinais mínimo e máximo. Em seguida, verificar a interrupção do sinal e a transição para o funcionamento de emergência, bem como o regresso após o restabelecimento do sinal. Se ENABLE estiver ativo, verificar também o seu funcionamento.
8. Verificar GR 2 e a sinalização de alarme no menu «Testes». Após concluir os testes, sair desta opção e selecionar o modo de funcionamento pretendido.

:::warning Ativação real das saídas

Os testes e a calibração controlam as saídas reais. Podem acionar os ventiladores, e o teste de ventilação impõe um nível independentemente do controlo normal. Assegurar condições de ensaio seguras e supervisão permanente.

:::

## Programação do controlador

### Painel frontal — indicadores e botões

| ELEMENTO | OPERAÇÃO |
| --- | --- |
| Alimentação / suspensão | O botão com o símbolo de alimentação apresenta uma confirmação de suspensão; confirmar com OK. Premir novamente reativa o dispositivo. A suspensão define o estado desligado nas saídas; não desliga a tensão da rede. |
| Cadeado | Ativa ou desativa o bloqueio do teclado. Após o desbloqueio, o indicador junto ao cadeado acende-se. No ecrã principal, o bloqueio é reposto após cerca de 30 s de inatividade. |
| A — AUTO | Seleciona o controlo pela entrada analógica após confirmação com OK. O indicador A assinala o modo selecionado. |
| M — MANUAL | Seleciona o controlo manual após confirmação com OK. No ecrã principal, as teclas + e − alteram a definição 0–100%. O indicador M assinala o modo selecionado. |
| +, −, OK, ESC | OK abre o menu, acede à opção e confirma o valor. + e − selecionam a opção ou alteram o valor. ESC regressa ao nível anterior ou cancela a edição. |
| Alarme e grupo 2 | O indicador vermelho assinala um alarme. O indicador junto ao símbolo do ventilador «2» assinala a ativação do relé GR 2. |
| Visor | Em AUTO, apresenta o nível de ventilação definido, a leitura da entrada selecionada, o gráfico de barras e os alarmes. Com ENABLE ativo, apresenta também o seu estado. Em MANUAL, o valor principal representa a definição manual; as proteções podem alterar a saída. |

### Memorização das definições

Os parâmetros do menu são guardados na memória não volátil após confirmação com OK. As alterações do nível MANUAL têm efeito imediato e são guardadas após um breve período de inatividade. Após uma falha de alimentação, são repostas as definições guardadas, incluindo o modo AUTO/MANUAL, o nível manual e o estado de suspensão. Não desligar a alimentação imediatamente após alterar a definição manual.

Em caso de soma de verificação incorreta ou de um valor fora do intervalo, o programa repõe os valores de fábrica. Nesse caso, devem ser novamente verificadas todas as definições, em especial a calibração dos ventiladores, a entrada de controlo e o funcionamento de emergência.

## Funções do menu básico

| MENU | INTERVALO / VALOR DE FÁBRICA | DESCRIÇÃO |
| --- | --- | --- |
| Tipo de controlo | Entrada V | Seleção de V, I, CAN ou Wi-Fi. Para a versão analisada, utilizar V (2–10 V) ou I (4–20 mA). CAN e Wi-Fi não efetuam o controlo. |
| Grupo de ventilação 2 | 1–100% / 100% | Limiar de fecho do contacto GR 2. O contacto está fechado quando o nível é igual ou superior ao limiar e aberto abaixo do limiar. O programa não define uma histerese separada. |
| Funcionamento de emergência | 0–100% / 30% | Nível definido em caso de perda do sinal analógico selecionado em AUTO. O valor 0% significa paragem em caso de perda do sinal. |
| Bloqueio para limpeza | 60 s | Bloqueia a utilização das teclas durante 60 segundos e apresenta uma contagem decrescente. A regulação da ventilação continua a funcionar. A função destina-se à limpeza superficial do painel, não a trabalhos elétricos nem à lavagem do interior. |
| Avançado | Submenu | Acesso aos testes, idioma, calibração do ventilador, ENABLE, arranque suave, som do alarme, definições de fábrica e informações do programa. |

## Funções do menu avançado

| MENU / PARÂMETRO | INTERVALO / VALOR DE FÁBRICA | DESCRIÇÃO |
| --- | --- | --- |
| Testes → Ventilação | 0–100% | Imposição temporária da saída regulada. As alterações têm efeito durante a edição. Ao sair com OK ou ESC, o controlo normal é retomado. |
| Testes → Vent. do escalão 2 | Não / Sim | Imposição temporária do contacto GR 2 e do respetivo indicador. |
| Testes → Alarme | Não / Sim | Teste temporário da sinalização de alarme, incluindo o som, independentemente da definição normal «Sinal de alarme». |
| Idioma | Polaco | Seleção entre polaco, inglês e ucraniano. |
| Ventilador → Faixa proibida | −20–200 / 0 | Calibração do nível 1%. Durante a edição, é imposta a saída real 1%. O parâmetro não é expresso em percentagem nem em segundos. |
| Ventilador → Ativação EN AUTO | Não / Sim; Não | Ativa a dependência do modo AUTO em relação à entrada ENABLE. |
| Ventilador → Ativação EN MANUAL | Não / Sim; Não | Ativa a dependência do modo MANUAL em relação à entrada ENABLE. |
| Arranque suave → Tempo de aceleração | 0–50 / 5 | Velocidade de subida do nível durante o arranque até 100%. Um valor maior significa uma alteração mais lenta. O valor 0 omite a etapa de subida. |
| Arranque suave → Tempo 100% | 0–250 / 100 | Manutenção do nível 100% durante o arranque. O valor 0 omite a etapa de manutenção. A definição conjunta da aceleração e da manutenção para 0 omite o sopro inicial até 100%. |
| Arranque suave → Tempo de desaceleração | 0–50 / 5 | Velocidade de aproximação ao nível solicitado, incluindo quando este é alterado. O valor 0 significa uma alteração sem aproximação gradual. |
| Sinal de alarme | Não / Sim; Não | Ativa o som de sinalização de alarme. A definição Não não elimina a mensagem no ecrã nem a sinalização pelo indicador. |
| Definições de fábrica | Não / Sim | Ao selecionar Sim, repõe e guarda os valores predefinidos, incluindo a calibração 0, a entrada V, AUTO, o funcionamento de emergência 30%, o limiar GR 2 igual a 100% e ENABLE desativado. Após a operação, voltar a configurar e verificar o dispositivo. |
| Programa | vers. 2.1 + data de compilação | Apresenta a versão e a data de compilação do programa. Esta descrição foi elaborada com base no código-fonte fornecido SC_PX16_v02. |

Os parâmetros de arranque suave são definições adimensionais dos contadores do programa, e não tempos indicados em segundos. Com 50 Hz, um único passo corresponde aproximadamente a (definição + 1) × 20 ms: para a aceleração e a desaceleração, este é o tempo de alteração de 1 ponto percentual; para «Tempo 100%», é o tempo de manutenção. O valor 0 tem o significado descrito na tabela. Os tempos reais dependem da fase do algoritmo.

## Mensagens de erro e aviso

| MENSAGEM | SIGNIFICADO E PROCEDIMENTO |
| --- | --- |
| Entrada | Leitura demasiado baixa do sinal selecionado em AUTO. O dispositivo define o funcionamento de emergência. Verificar a fonte de sinal, os cabos, a massa comum e a seleção V/I. |
| Sobreaquecimento | Leitura do dissipador de calor &gt;87°C; anulação &lt;80°C. Ventilação definida como 0% ou 100%, de acordo com a descrição da proteção térmica. Verificar o arrefecimento e a carga. |
| Alimentação | Perturbação da sincronização do circuito de potência com a rede. Verificar a alimentação e a instalação. Em caso de perda total da alimentação, o visor não funciona. |
| Memória CRC | Erro da soma de verificação ou do intervalo das definições guardadas. O programa repõe os valores predefinidos. Verificar a configuração e repetir a calibração; se o erro se repetir, contactar a assistência técnica. |

## Notas e avisos

:::danger Desligue a alimentação

Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, uma vez que a tensão presente em alguns componentes constitui um perigo para a vida e a saúde. Recomenda-se que a instalação seja confiada a uma pessoa qualificada.

:::

Antes da instalação e utilização, ler o manual. Confiar as reparações e os trabalhos no interior do dispositivo a pessoal habilitado. A suspensão, o bloqueio do teclado, ENABLE e a definição 0% não constituem uma desconexão da alimentação e não asseguram condições seguras para trabalhos elétricos.

Selecionar as definições de ventilação e de funcionamento de emergência de acordo com as necessidades dos animais e da instalação. Verificar regularmente o funcionamento real de todos os ventiladores. A sinalização SC-PE16 não substitui a monitorização independente das condições nas instalações e da perda de alimentação. A régua de terminais apresentada não dispõe de um contacto ALARM separado para a central.

:::note Eliminação do dispositivo

No final da vida útil do produto, este não deve ser eliminado juntamente com os resíduos urbanos indiferenciados, mas sim de acordo com a legislação em vigor (diretivas WEEE da União Europeia 2012/19/UE).

:::

O produto foi fabricado em conformidade com os requisitos RoHS (diretiva da União Europeia 2011/65/UE).

## Dados técnicos do controlador

| PARÂMETRO | VALOR |
| --- | --- |
| Alimentação / consumo próprio | 230 V AC, 50 Hz / &lt;10 W |
| Corrente total máxima da saída U | 16 A |
| Corrente máxima do contacto GR 2 | 6 A; contacto C–NO, isolado |
| Entrada V / entrada I | 2–10 V / 4–20 mA, selecionáveis no menu |
| Limiar de perda do sinal (leitura do programa) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Contacto livre de potencial E–massa; ativação separada para AUTO/MANUAL |
| Proteção térmica (leitura do dissipador de calor) | Alarme &gt;87°C; reposição &lt;80°C |
| Temperatura ambiente / caixa | −10°C a +40°C / IP65 |
| Dimensões / resistência a sobretensões | 34 × 29 × 12 cm / 210 J |
| Idiomas do menu | Polaco, inglês, ucraniano |

Conteúdo do conjunto segundo a documentação fornecida: 4 buchas de expansão, 2 bucins PG13,5, 1 bucim PG9 e 1 dobradiça.

## Condições de garantia

O conteúdo das condições de garantia foi mantido a partir do documento fornecido pelo fabricante.

1. O fabricante ELETOR, com sede na Polónia, endereço: Pod Sosno 28, 87-305 Zbiczno (doravante designado por garante), concede ao Adquirente uma garantia de qualidade do produto para o qual foi emitido o presente certificado de garantia, desde que seja utilizado de acordo com a sua finalidade e com as regras estabelecidas no manual de instruções entregue ao Adquirente juntamente com o produto.
2. O período de garantia é de 24 meses a contar da data de venda. As avarias ou os defeitos do produto detetados durante este período serão reparados gratuitamente. Após o termo do período de garantia ou em caso de perda dos direitos de garantia, a reparação das avarias ou dos defeitos será paga.
3. A garantia não abrange:

   - quaisquer defeitos resultantes da utilização inadequada do produto (incluindo a realização de operações não descritas no manual de instruções, etc.);

   - quaisquer defeitos resultantes de reparações, modificações, etc., realizadas por uma pessoa que não seja o garante;

   - quaisquer defeitos ou danos resultantes do transporte ou da queda do produto, se estes acontecimentos tiverem ocorrido após a compra do produto, bem como danos mecânicos resultantes de manuseamento incorreto pelo utilizador;

   - quaisquer defeitos ou danos resultantes de incêndio, terramoto, inundação, queda de raio ou outras catástrofes naturais, poluição ambiental, ação de radiação ionizante externa ou de um campo magnético, bem como de fornecimento irregular de eletricidade ou de eletricidade com parâmetros não conformes aos exigidos;

   - quaisquer defeitos resultantes de armazenamento incorreto (por exemplo, armazenamento do produto fora do intervalo de temperatura ou humidade indicado nas especificações, nas proximidades de produtos químicos), manutenção ou limpeza inadequadas, etc.;

   - quaisquer defeitos resultantes do esgotamento das pilhas de alimentação, etc.;

   - quaisquer defeitos causados por areia, lama, poeiras, água e outros líquidos, etc., que tenham penetrado no interior da caixa do produto;

   - danos resultantes do desgaste natural, parcial ou total, do produto de acordo com as suas características ou finalidade;

   - operações indicadas no manual de instruções cuja execução é da responsabilidade do utilizador, pelos seus próprios meios.

4. O Adquirente perde os direitos de garantia em consequência de:

   - qualquer reparação ou modificação do produto realizada por uma pessoa que não seja o garante;

   - constatação de violação, dano ou rutura de qualquer um dos selos;

   - constatação de dano, alteração, ocultação ou remoção dos números de série ou de outras marcações de identificação do produto.

5. O prazo de reparação é de até 21 dias úteis a contar da data da comunicação do defeito e da entrega do produto completo no centro de assistência técnica do garante. Em casos especialmente justificados, relacionados com a necessidade de importar elementos ou componentes do estrangeiro ou com danos particularmente complexos ou difíceis de reparar ou diagnosticar, o prazo de reparação poderá ser prolongado pelo período necessário ao cumprimento das obrigações de garantia.
6. Os direitos do Adquirente ao abrigo da garantia apenas podem ser exercidos mediante apresentação de um certificado de garantia válido e corretamente preenchido no dia da compra, bem como do comprovativo de compra (fatura, recibo, etc.). Alterações não autorizadas das inscrições no certificado de garantia (incluindo rasuras, apagamentos, aditamentos, etc.) implicam a perda dos direitos de garantia. Um certificado de garantia sem o nome, modelo e número de série do produto, a data e o local de compra do produto, bem como o carimbo legível e a assinatura do Vendedor, é inválido e não constitui fundamento para a apresentação válida de uma reclamação.
7. O Adquirente é obrigado a entregar o produto, a expensas próprias, numa embalagem adequada ao equipamento que assegure o transporte e o armazenamento seguros e corretos, ou a suportar os custos de deslocação do garante. Se se verificar que o produto entregue para reparação está tecnicamente operacional e isento de defeitos, ou que a avaria detetada não está abrangida pela garantia, serão cobrados ao Adquirente os custos dos serviços e do transporte.
8. O Adquirente é obrigado a levantar o produto reparado no prazo de 90 dias a contar da data em que o garante o notificar da reparação. Se o comprador não levantar o produto dentro deste prazo, assume o risco de perda ou dano acidental do produto.
9. O período de garantia é prolongado pelo tempo de duração da reparação, contado desde a data de entrega do produto até à data acordada para o levantamento após a reparação. O garante é obrigado a emitir um documento que indique o período e o âmbito dos defeitos do produto eliminados.

10. O Adquirente apresenta as reclamações através do Vendedor do produto ou diretamente para o endereço do garante: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polónia.

11. O garante não se responsabiliza:

    - por rendimentos perdidos em resultado da manifestação de um defeito e do tempo necessário à sua eliminação;

    - por perdas resultantes da manifestação de um defeito nem por quaisquer danos decorrentes da instalação, utilização ou programação incorretas das funções do dispositivo.
