---
sidebar_position: 3
title: Manual SC-12
description: Controlador de climatização para instalações pecuárias com corrente de
  saída admissível até 12A
keywords:
- eletor sc-12
- controlador de ventilação
- controlador de climatização
- controlador de ventilação para instalações de suínos
- controlador de microclima
- controlador para instalações de suínos
- ventilação de instalações de suínos
- controlador para instalações de recria
---

# Controlador SC-12

Controlador de climatização com microprocessador pertencente à série SPEED CONTROL. A versatilidade do dispositivo é garantida pelo elevado número de entradas/saídas do sistema e pelo software intuitivo em polaco e inglês. Além das definições básicas de temperatura, renovação de ar, aquecimento suplementar, níveis mín./máx. de ventilação e alarmes, o programa do controlador permite testar e guardar a calibração dos atuadores que funcionam com o controlador.

**Parâmetros e características:** 
- Ventilação do grupo I: 
  - corrente máx. da saída de regulação contínua 12A,
  - proteção térmica do sistema, 
  - arranque suave da ventilação – arranque suave,
  - relé de derivação com comando à potência máxima, 
  - calibração da rotação mínima, 
  - programa de poupança de energia com sistema de comportas de abertura antecipada.
- Ventilação do grupo II, contacto isolado até 6A.
- Aquecimento suplementar, contacto isolado até 6A
- Saídas de alarme NO e NC: 
  - sinalização de falha de alimentação,
  - sinalização de ultrapassagem do limiar de temperatura mín. ou máx.,
  - sinalizador acústico integrado.
- Saídas independentes 3 0..10V:
  - funcionamento com módulos de expansão,
  - controlo do sistema de comportas, 
  - regulação do aquecimento com capacidade variável.**
- Duas entradas analógicas para medição da temperatura.
- Porta digital para medição da temperatura (até 4 sensores).
- Duas saídas de relé funcionais (selecionáveis):
  - funcionamento com atuadores lineares, 
  - III e IV grupos de ventilação
- Duas entradas analógicas 0-10V.
- Alimentação para o potenciómetro DC 10V.
- Alimentação adicional DC 12V.
- Possibilidade de funcionamento com um computador até 1200m.
- Invólucro hermético IP65.
- Tensão de alimentação 230VAC 50Hz.
- Potência consumida pelo sistema < 10V

# Instalação do controlador
:::danger 
 Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão em alguns componentes é perigosa para a vida e a saúde. Recomenda-se que a instalação seja realizada por uma pessoa qualificada.  Esta ação é perigosa
:::

## Seleção do local de montagem
O local de montagem deve ser escolhido de forma racional, tendo em conta a facilidade de acesso ao aparelho por pessoas autorizadas e a inacessibilidade para animais e crianças. Devem também ser consideradas as condições climáticas, ou seja, o dispositivo deve funcionar no intervalo de temperaturas de -10°C a 40 °C, num local não exposto à luz solar direta. Deve existir livre circulação de ar em redor do dispositivo. O dispositivo inclui um sensor de temperatura.  

### Aplicam-se várias regras à montagem do sensor de temperatura:
 - o sensor não deve ser montado num local sem circulação de ar ou exposto à luz solar direta,
 - o sensor não deve ser montado numa parede portante (exterior) do edifício,
 - evitar a proximidade de dispositivos que emitam calor, como radiadores e lâmpadas,
 - o sensor não deve ser colocado diretamente junto de portas e aberturas de ventilação,
 - o sensor não deve ser colocado em locais acessíveis aos animais,
 - recomenda-se instalar o cabo de ligação do sensor afastado dos cabos de alimentação.

# Montagem
O dispositivo pode funcionar em condições climáticas agressivas. Quando corretamente montados, o controlador e o sensor de temperatura são resistentes aos efeitos nocivos do ambiente.  

### Durante a montagem, é necessário prestar atenção aos seguintes aspetos:
 - antes de apertar os parafusos, verificar a junta da tampa,
 - a tampa deve ser apertada com todos os parafusos,
 - os cabos utilizados para ligar o controlador devem ser redondos,
 - após a ligação do cabo, apertar os bucins de modo a vedar e imobilizar o cabo; recomenda-se a utilização de silicone,
 - as passagens não utilizadas (bucins) devem ser obturadas,
 - fixar o controlador (a parte inferior do invólucro) numa parede plana com 4 buchas de expansão.

# Ligação elétrica
:::danger 
 Antes de ligar o sistema, certificar-se de que a alimentação está desligada!
Esta ação é perigosa
:::

Antes de proceder à ligação do controlador, desapertar e retirar a tampa. Introduzir os cabos através dos bucins de borracha e proceder à sua ligação. Os terminais do controlador são apresentados na figura abaixo.

![Ligação ](./img/sc-12.png)

**Ligar o conector AC 230V** à alimentação (quadro de distribuição). É obrigatória a utilização de um disjuntor de proteção contra sobreintensidades 1P-B6 e de dispositivos de proteção contra sobretensões do tipo T1 T2. Ao ligar vários dispositivos, é uma boa prática agrupar os controladores em diferentes «fases» (L1, L2, L3), para distribuir uniformemente a carga da linha de alimentação.

**O conector FAN** deve ser ligado diretamente ao ventilador; no caso de controlo de vários ventiladores, a carga total não pode exceder 6A e cada ventilador deve ter proteção individual. Não se deve derivar PE e N da alimentação (quadro de distribuição); é obrigatório ligá-los aos terminais do controlador.

**O conector FAN 2** pode ser utilizado para ligar os ventiladores do grupo 2 ou sistemas de aspersão. A saída é isolada, a corrente máxima do contacto é 6A (é obrigatório um disjuntor externo de proteção contra sobreintensidades do tipo 1P-B6 em caso de controlo direto da carga); o contacto fecha quando a temperatura medida é superior à soma da temperatura definida e da banda de ventilação.

**O conector HOT** pode ser utilizado para ligar um aquecedor de ar. A saída é isolada, a corrente máxima do contacto é 6A (é obrigatório um disjuntor externo de proteção contra sobreintensidades 1P-B6 em caso de controlo direto da carga); o contacto fecha quando a temperatura medida desce abaixo do valor definido.

**O conector ALARM** tem saídas isoladas NC, C e NO destinadas à ligação à central de alarme. O alarme é ativado nos seguintes casos:
    - a temperatura é demasiado baixa ou demasiado alta,
    - o controlador ou o sensor de temperatura está avariado,
    - ocorreu uma falha da tensão de alimentação do controlador,
    - ocorreu um funcionamento incorreto do controlador (por exemplo, sobreaquecimento do controlador)
A figura abaixo apresenta a forma de ligação do ventilador à central de alarme.

![Ligação de alarme](./img/alarmsc-s.png)

**O conector FUNC1 e FUNC2** destina-se à ligação de um mecanismo elevador para abertura das entradas de ar, baseado num motor com rotação nos dois sentidos. O relé FUNC1 liga a corrente para o atuador e FUNC2 comuta o sentido de rotação do motor. Exemplo de esquema de ligação do mecanismo elevador (é obrigatório um disjuntor externo de proteção contra sobreintensidades 1P-B6):
Ao desativar a função do mecanismo elevador, as saídas FUNC1 e FUNC2 funcionam como contactos dos grupos de ventilação 3 e 4, respetivamente.

![Ligação do mecanismo elevador](./img/Sc-12fan.png)

**O conector 12V** destina-se à alimentação de sensores externos.

**O conector V1 0-10V** destina-se à ligação de módulos de expansão de potência. A tensão neste terminal é proporcional ao nível de ventilação.

**O conector V2 0-10V** destina-se à ligação do atuador de abertura das comportas de entrada de ar.

**O conector V3 0-10V** destina-se à ligação de um sistema de aquecimento com capacidade regulável de forma contínua. A tensão nesta saída aumenta proporcionalmente à descida da temperatura, a partir da temperatura de aquecimento suplementar.

**O conector 10V** destina-se à alimentação do potenciómetro do mecanismo elevador ou de outros sistemas do tipo 0-10V.

**Ligar o conector SENS1 (SENS2)** ao sensor de temperatura 1 TS3 ou TS5; a polaridade é indiferente. No caso de ligação simultânea de 2 sensores, é calculada a média das temperaturas medidas. É uma boa prática afastar os cabos de medição dos cabos de alimentação.

**O conector 1-WIRE** pode ser utilizado para ligar um maior número de sensores digitais de temperatura, no máximo 4, ligados em paralelo (deve ser respeitada a polaridade correta). O comprimento máximo do cabo de ligação dos sensores é 150m (o comprimento não influencia a medição da temperatura); recomenda-se a utilização de cabo blindado.

**O conector RS-485** pode ser utilizado para construir sistemas de ventilação e para comunicação com um computador PC.

**O conector IN1 0-10** destina-se à entrada do sinal de realimentação do sistema de entradas de ar – determina a posição atual das entradas.

**O conector IN2 0-10** destina-se à ligação do controlador a outros sensores, por exemplo de humidade, CO2, ou ao funcionamento do controlador como expansão de potência.

# Princípio de funcionamento
A principal função do controlador é manter a temperatura na instalação de criação ao nível definido pelo criador. Deve ter-se em conta que o controlador é apenas uma ferramenta destinada a ajudar a garantir condições climáticas ideais na instalação de criação. No entanto, o papel principal neste processo cabe ao criador, que deve adaptar as definições do dispositivo às condições climáticas variáveis no exterior e, sobretudo, às necessidades dos animais no edifício pecuário, bem como monitorizar o estado de funcionamento do dispositivo através da central de alarme.

## Primeira colocação em funcionamento do controlador
:::danger 
 Na primeira colocação em funcionamento do controlador, é obrigatório definir a banda proibida de funcionamento do motor.

:::
O controlador funciona com ventiladores baseados num motor assíncrono monofásico com um consumo total máximo de corrente de 12A. Após ligar os ventiladores selecionados, o utilizador deve adaptá-los ao funcionamento com o controlador. Por outras palavras, é necessário definir o nível mínimo de funcionamento (rotação) do ventilador. Esta função denomina-se «Banda proibida» e é definida pelo utilizador uma única vez nas «Definições avançadas». Para realizar esta operação corretamente, recomenda-se a ajuda de uma segunda pessoa, que possa observar continuamente o comportamento do ventilador enquanto a outra pessoa define o valor da «Banda proibida» (o valor de fábrica é 0). A ausência de definição da banda proibida pode provocar o funcionamento incorreto do dispositivo. O valor da «Banda proibida» pode ser considerado correto quando a pressão produzida pelo ventilador começa a levantar ligeiramente as comportas da chaminé de ventilação. A operação de definição da «Banda proibida» deve ser repetida quando o ventilador ligado ao controlador for substituído.

## Renovação periódica de ar
A renovação de ar é uma função executada pelo controlador, que é ativada quando a temperatura na instalação desce abaixo da temperatura definida. Esta função assegura aos animais um fornecimento cíclico de ar fresco. No menu Renovação de ar encontram-se 3 parâmetros:
- **«Tempo de funcionamento»** - determina durante quantos minutos o ventilador deve permanecer ligado;
- **«Tempo de pausa»** - determina o tempo de paragem do ventilador;
- **«Nível de renovação de ar»** - determina a potência de ventilação durante o «Tempo de funcionamento».

Todos os parâmetros acima mencionados são definidos pelo utilizador. 

### Devem ter-se em conta algumas regras ao definir os parâmetros de renovação de ar:
- a renovação de ar é ativada exclusivamente quando a temperatura na instalação de suínos desce abaixo da temperatura definida,
- a função básica da renovação de ar é assegurar aos animais um fornecimento cíclico de ar fresco, e não manter a temperatura definida na instalação,
- recomenda-se renovar o ar das instalações durante períodos curtos, mas frequentes,
- devem evitar-se períodos longos de renovação de ar, pois podem provocar oscilações excessivas da temperatura,
- é obrigatório adaptar os parâmetros definidos ao comportamento dos animais e às condições existentes tanto no interior como no exterior da instalação.

## Modo de funcionamento do dispositivo
O controlador regula continuamente a ventilação de **«Mín.1» a «Máx.1»** no intervalo entre a **«Temperatura definida»** e a soma da **«Temperatura definida»** e da **«Banda de ventilação 1gr.»**. Acima deste intervalo, é ativado o grupo de ventilação 2 e o grupo 1 altera o nível para **«Mín.2»**; com o aumento subsequente da temperatura, a ventilação aumenta até **«Máx.2»**, no final do intervalo da **«Banda de ventilação 2 gr.»**. Se a **«Banda de ventilação 2 gr.»** estiver definida como zero e a ventilação funcionar em **«Máx.1»**, será ativado o grupo de ventilação 2 e o aumento subsequente da temperatura já não provocará alterações na ventilação (parte pontilhada do gráfico). Se a temperatura na instalação descer abaixo da **«Temperatura definida»**, o controlador renova periodicamente o ar da instalação; com uma descida adicional, é ativado o aquecimento suplementar. Tudo depende das definições introduzidas pelo utilizador. O programa do controlador também prevê o funcionamento com uma central de alarme, que pode ser ativada quando a temperatura na instalação de suínos se desvia dos parâmetros definidos. 

![Ventilação](./img/Sc-12wentyl.png)  

## Programação do controlador
O controlador possui um conjunto de definições predefinidas, que são gravadas na memória não volátil em dois casos:
1. Primeira colocação em funcionamento do dispositivo,
2. Erro na memória de dados.
Em caso de ausência ou falha de alimentação, o controlador não perde as definições do utilizador anteriormente introduzidas e guardadas.

## Painel frontal – indicadores, botões e visor
![Painel](./img/SC-12panel.png)  
    1. Indicador luminoso vermelho que sinaliza a ultrapassagem da temperatura máxima admissível.
    2. Indicador luminoso vermelho que sinaliza a descida abaixo da temperatura mínima admissível.
    3. Indicador luminoso amarelo que sinaliza o aquecimento suplementar.
    4. Indicador luminoso amarelo que sinaliza a ventilação do grupo 2.
    5. Indicador luminoso verde que sinaliza a definição manual do nível de ventilação.
    6. Indicador luminoso verde que sinaliza o funcionamento da comunicação RS485.
    7. Visor do menu; no estado normal de funcionamento, apresenta a temperatura.
    8. Indicador de barras que sinaliza o nível de ventilação.
    9. Tecla para navegar para cima no menu ou alterar o valor do parâmetro.
    10. Tecla ESC - sair do menu ou de um determinado parâmetro sem guardar o valor.
    11. Tecla OK - entrar no menu ou confirmar (guardar) um determinado parâmetro.
    12. Tecla para navegar para baixo no menu ou alterar o valor do parâmetro.

## Utilização do menu
O controlador dispõe de várias funções que permitem adaptá-lo à aplicação específica. Estas funções estão agrupadas num menu, ao qual se acede premindo uma das teclas **(«+», «-» ou «OK»)**. As teclas **«+»** e **«-»** permitem selecionar a função, e a edição, a gravação de dados ou o acesso ao nível seguinte podem ser realizados com a tecla **«OK»**. Premir a tecla **«Esc»** para regressar ao menu superior ou cancelar a gravação de um determinado parâmetro.

## Funções do menu básico

| MENU                          | Descrição       | 
|:-----------                   |:---------- |
| Temperatura 20,8o C W16% A    | **Modo informativo** - funcionamento normal. O visor apresenta a temperatura atual e, quando o ventilador está em funcionamento, o valor do nível de ventilação. Significado dos símbolos adicionais:A-indica alarme ativado,D  - indica aquecimento ativado, W - indica ventilação adicional| 
|   Temp. definida   20,0o C      |**«Temperatura definida»** – Determina a temperatura a partir da qual se inicia o processo de ventilação com regulação contínua. Deve selecionar-se um valor adequado em função do tipo de animais de criação.| 
| Renovação de ar     | **Renovação de ar** – são definidos dois valores de tempo.    1.**Tempo de funcionamento** Determina o número de minutos de funcionamento da ventilação.    2.**Tempo de pausa** Determina o número de minutos de paragem da ventilação entre ciclos de funcionamento consecutivos.    3.**Nível de renovação de ar** - Determina a intensidade da ventilação durante a renovação de ar.| 
| Alarme |  1.**Alarme ativo Sim** - Ativação/Desativação do contacto de alarme; para que o controlador não emita um sinal de alarme na saída (para a central de alarme), selecionar «NÃO» no menu.  2. **Temp. Mín. 15,0o C** - Determina a temperatura mínima absoluta à qual o alarme será ativado.  3.**Temp. Máx. 25,0o C** - Determina a temperatura máxima absoluta à qual o alarme será ativado.  4.**Sinal de alarme Sim** - Ativação/Desativação do sinal acústico no interior do controlador. | 
|    Ventilação        |  1.**Banda vent. 1 5,0o C**   - Determina a velocidade de resposta do controlador (alterações do nível de ventilação do mínimo 1 ao máximo 1) ao aumento da temperatura.  2.**Nível mín. 1 1 %** - Determina o nível de ventilação correspondente à temperatura definida.  3.**Nível máx. 1 100 %**-Determina o nível constante de ventilação para uma temperatura que exceda o intervalo de regulação contínua, quando «Banda vent. 2gr.» = 0; caso contrário, determina o nível máximo de ventilação regulada para uma temperatura igual à soma da T. definida e da banda do grupo 1.  4.**Banda vent. 2 0,0o C**-Determina a velocidade de resposta do controlador (alterações do nível de ventilação do mínimo 2 ao máximo 2) ao aumento da temperatura para o grupo 2. Função inativa quando a banda é igual a zero.  5.**Nível mín. 2 1 %**-Determina o nível mínimo de ventilação do grupo 1 no ponto de fecho dos contactos do grupo 2.  6.**Nível máx. 2 100 %**-Determina o nível constante de ventilação para uma temperatura que exceda o intervalo de regulação contínua, quando o grupo 2 está ativado.  7.**Grupo 3  5,0o C**-Determina o nível constante de ventilação para uma temperatura que exceda o intervalo de regulação contínua, quando o grupo 2 está ativado.  8.**Grupo 4 7,0o C**-Determina a temperatura de ativação do grupo de ventilação 4 relativamente à temperatura definida (a função do mecanismo elevador deve estar desativada).| 
|    Aquecimento suplementar  |  1.**Temp. aquec. supl. 15,0o C**-Determina a temperatura de ativação do aquecimento suplementar.  2.**Banda aquec. supl. 5,0o C** -Determina a proporção da potência dos sistemas de aquecimento suplementar (na saída V3 0-10V) em função da temperatura. | 

## Funções do menu avançado
O menu avançado destina-se principalmente aos instaladores e permite adaptar o controlador à instalação e ao ventilador, testar circuitos e selecionar o idioma do menu. Para aceder às definições avançadas, premir e manter premidas duas teclas do menu durante aproximadamente 10s. 

| MENU                          | Descrição       | 
|:-----------                   |:---------- |
|Teste  |Esta função permite verificar os vários circuitos de acionamento do controlador; todas as definições são temporárias enquanto se permanece na respetiva opção do menu. Após premir «ESC» ou «OK», a saída em questão regressa ao estado resultante do funcionamento do controlador.  1.**Ventilação 0 %**  Permite introduzir manualmente o nível de ventilação para verificar o sistema de ventilação. Após confirmar a função, acende-se o indicador luminoso verde (mão).  2.**Alarme Não** A ativação liga 2 indicadores luminosos vermelhos, o sinal sonoro e o circuito de alarme.  3.**Aquecimento suplementar Não** A ativação liga o indicador luminoso amarelo (chama) e o circuito de aquecimento suplementar.  4.**Vent. 2 estágio Não** A ativação liga o indicador luminoso amarelo (ventilador) e o circuito do grupo 2.  5.**Saída V1 0,0 V  Saída V2  0,0 V Saída V3  0,0 V**-Teste das saídas 0-10V; utilizando as teclas «+» ou «-», pode definir-se a tensão selecionada para os sistemas, respetivamente: módulos de expansão, comportas de entrada de ar, aquecimento suplementar com regulação contínua. Função particularmente útil na calibração da Saída V2 das comportas de entrada de ar.  6.**Mecanismo elevador 0** Permite verificar o sistema de comportas de entrada de ar; «+» - abre as entradas, «-» - fecha as entradas; o visor apresenta a posição atual do atuador lida pelo potenciómetro.  7.**Grupo 3 Não**  A ativação liga o circuito do grupo de ventilação 3. (a função do mecanismo elevador deve estar desativada)  8.**Grupo 4 Não**  A ativação liga o circuito do grupo de ventilação 4. (a função do mecanismo elevador deve estar desativada)|
|Idioma        | Seleção do idioma do menu. Pode selecionar-se polaco ou inglês. | 
|Ventilador         |  1.**Banda proibida 0**- Calibração da rotação mínima dos ventiladores ligados diretamente ao controlador; este parâmetro corresponde ao nível de ventilação «1%». Um valor positivo do parâmetro aumenta a rotação e um valor negativo diminui-a.  2.**Módulo exp. Mín. 1,9 V** -Tensão mínima aplicada ao módulo de expansão de potência (saída V1 0-10V).  3.**Módulo exp. Máx. 10,0 V** -Tensão máxima aplicada ao módulo de expansão de potência (saída V1 0-10V).  4.**Corte do módulo Não** - Desligação do módulo de expansão de potência; quando se seleciona «SIM», a tensão na saída de controlo dos módulos de expansão (V1 0-10V) desce para o nível 0V, e não para o valor mínimo definido, quando o nível de ventilação é 0%.  5.**Inversão  Não**-A ativação inverte a característica da saída V1. A tensão diminui com o aumento do nível de ventilação no intervalo definido por mín.-máx. O sinal na saída V1 será do tipo 10-0V.| 
| Comportas de entrada de ar       |  1.**Anticipação 0,0o C**-Abertura antecipada das comportas de entrada de ar. O parâmetro definido determina a diferença de temperatura antes da «Temperatura definida» à qual as comportas de entrada de ar devem abrir.  2.**Fecho completo  Não**- A ativação faz com que a tensão na saída de controlo das comportas de entrada de ar (V2 0-10V) desça para o nível 0V, e não para o valor mínimo definido. Em caso de ausência de ventilação (nível de ventilação 0%).  3.**Comportas mín.  1,9 V**- Tensão mínima aplicada às comportas de entrada de ar (saída V2 0-10V).  4.**Comportas máx.  10,0 V**- Tensão máxima aplicada às comportas de entrada de ar (saída V2 0-10V).  5.**Inversão   Não**-A ativação inverte a característica da saída V2. A tensão diminui com o aumento do nível de ventilação no intervalo definido por mín.-máx. O sinal na saída V2 será do tipo 10-0V. |  
| Medição da temperatura  |  1.**Calibração S1 23,0o C -> 23,5o C**,**Calibração S2 23,0o C -> 23,2o C** - A calibração das entradas analógicas permite reajustar a escala da temperatura lida pelos sensores S1 e S2.  2.**Tempo de cálculo da média 60 s**- Este parâmetro define o período durante o qual é calculada a média das leituras atuais de temperatura. O valor da temperatura média é o parâmetro básico das funções do controlador. As alterações do estado das saídas (ventilação, aquecimento suplementar, comportas, grupos de ventilação seguintes, alarmes,...) estão estritamente ligadas a este parâmetro e não podem ocorrer com uma frequência superior à correspondente ao tempo aqui definido. | 
| Mecanismo elevador      |  1.**Calibração abertura 1024 -> 853**,**Calibração fecho 0 -> 324** -A calibração do mecanismo elevador é indispensável para o funcionamento correto do sistema de entradas de ar. A tecla «+» abre as entradas e a tecla «-» fecha as entradas. Durante a abertura das entradas, o parâmetro de posição deve aumentar e, durante o fecho, diminuir; caso contrário, deve verificar-se a ligação do atuador (alimentação e potenciómetro). Na calibração da abertura, abrir as entradas até ao máximo e confirmar a posição com a tecla «OK». Na calibração do fecho, fechar as entradas e confirmar a posição com a tecla «OK». A tecla «ESC» permite sair da função sem guardar. A diferença entre a posição de abertura e a de fecho deve ser de, no mínimo, 100 unidades.  2.**Desativação Não**-A desativação liberta os contactos FUNC1 e FUNC2 do controlo do mecanismo elevador; estes contactos passam então a desempenhar a função de ventilação dos grupos 3 e 4.| 
| Arranque suave               | Os parâmetros deste grupo do menu são responsáveis pelo arranque da ventilação. A ativação da ventilação no grupo de regulação contínua é precedida de um arranque gradual até 100%, de um breve funcionamento a 100%  e de uma redução para o nível de ventilação necessário. Isto faz com que, no arranque da ventilação, seja produzido um sopro de ar que facilita a abertura das válvulas de borboleta nas chaminés.   Os valores são expressos em períodos da tensão de alimentação para 1% de ventilação.  1.**Tempo de aceleração 5**- O parâmetro determina a velocidade de aumento da rotação da ventilação do nível zero até ao máximo – ativação suave dos ventiladores. O valor 0 desativa a aceleração suave.  2.**Tempo 100%   100**- O parâmetro determina o tempo de funcionamento no arranque a 100% do nível de ventilação. Definir o tempo de aceleração e 100% como 0 desativa completamente o sopro de ar no arranque da ventilação.  3.**Tempo de desaceleração 5**-  O parâmetro determina a velocidade das alterações do nível de ventilação. | 
|Aquecimento suplementar              |  1.**Inversão do contacto Não**-A ativação inverte a característica da saída HOT. O contacto abre com a descida da temperatura medida.  2.**Histerese  0,5o C** - Determina o nível de histerese da temperatura para o contacto de aquecimento suplementar.  3.**Funcionamento relativo Não**-A ativação permite definir a temperatura de aquecimento suplementar relativamente à temperatura definida. O menu básico de aquecimento suplementar é alterado, passando a introduzir-se a diferença relativamente à temperatura definida.  4.**Aquecimento suplementar mín. 1,9 V** - Tensão mínima aplicada ao controlo contínuo do aquecimento – aquecedor de ar com capacidade variável do ventilador (saída V3 0-10V).  5.**Aquecimento suplementar máx. 10,0 V** - Tensão máxima aplicada ao controlo contínuo do aquecimento – aquecedor de ar com capacidade variável do ventilador (saída V3 0-10V).| 
| Programa 	|  **vers. 2.4  Abr 13 2018** - 	Leitura da versão do software e da data de compilação|

## Mensagens de erro e de aviso

As mensagens de erro destinam-se a informar o utilizador sobre anomalias no funcionamento do controlador. As possíveis mensagens de erro são apresentadas abaixo

|ERRO                            |	DESCRIÇÃO      |
|:-----------                    |:---------- |
|Alarme     Sobrecarga 	     |Alarme de sobrecarga, ativado a 75°C. O dispositivo suspende o funcionamento até arrefecer.|
|Alarme  Sensor ausente|Sinaliza a ausência ou avaria do sensor ou do cabo de ligação.|

# Observações e avisos 
:::danger 
 Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão em alguns componentes é perigosa para a vida e a saúde. Recomenda-se que a instalação seja realizada por uma pessoa qualificada.

:::
- Para evitar problemas na operação do dispositivo, é obrigatório ler as instruções antes de proceder à instalação e à utilização.
- Não é permitido modificar a construção nem efetuar reparações por iniciativa própria. Isto aplica-se, em particular, a alterações de elementos e componentes. 
- As operações de manutenção ou assistência devem ser realizadas por pessoal autorizado (instalador ou serviço de assistência do fabricante). Nos edifícios pecuários com ventilação forçada, é obrigatório um sistema de alarme. O fabricante do dispositivo não se responsabiliza por danos causados por instalação incorreta, programação incorreta das funções, consequências de acontecimentos fortuitos e fatores externos. 
- O controlador de ventilação exige a definição dos parâmetros de acordo com as condições existentes na instalação de criação. Estas definições são individuais e dependem da decisão do criador. O fabricante do dispositivo reserva-se o direito de alterar a construção do dispositivo e o software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> No fim da vida útil do produto, este não deve ser eliminado juntamente com os resíduos urbanos não triados, mas sim tratado de acordo com a legislação em vigor (diretivas WEEE da União Europeia 2012/19/UE).
O produto foi fabricado em conformidade com os requisitos RoHS (diretiva da União Europeia 2011/65/UE).
  </p>
</div>
:::
:::tip

## Dados técnicos do controlador
|Parâmetro                        |	DESCRIÇÃO      |
|:-----------                    |:---------- |
|Tensão de alimentação|	230VAC 50Hz|
|Corrente máxima da saída de regulação contínua FAN|	12A|
|Intervalo de regulação da tensão de saída|	70V ÷ 230V|
|Corrente máxima da saída (contacto) FAN 2|	6A|
|Corrente máxima da saída (contacto) HOT|	6A|
|Corrente máxima da saída (contacto) ALARM|	4A|
|Corrente máxima da saída (contacto) FUNC1 e FUNC2|	4A|
|Intervalo de temperatura de funcionamento|	-10 +40oC|
|Intervalo de medição da temperatura|	0 +50oC|
|Resolução da medição de temperatura|	0,1oC|
|Deteção de avarias do sensor de temperatura|	SIM|
|Número máximo de sensores analógicos|	2|
|Precisão da medição da temperatura – entrada analógica|	1oC|
|Dependência da medição em relação à resistência dos cabos – entrada analógica|	15,8Ω/oC|
|Número máximo de sensores digitais|	4|
|Precisão da medição da temperatura – entrada digital|	0,5oC|
|Dependência da medição em relação à resistência dos cabos – entrada digital|	Nenhuma|
|Comprimento máximo da linha de ligação dos sensores digitais|	150m|
|Resistência a sobretensões (máx. E)|	210J|
|Proteção contra sobrecarga|	75oC|
|Dimensões do dispositivo|	34x29x12 [cm]|
|Grau de proteção do invólucro|	IP56|
:::

:::info
O controlador SPEED CONTROL-12 v2  inclui no conjunto:
 - 1 sensor de temperatura,
 - 4 buchas de expansão,
 - 2 bucins PG13,5.
 - 3 bucins PG11,
 - 4 bucins PG9.
:::















































































