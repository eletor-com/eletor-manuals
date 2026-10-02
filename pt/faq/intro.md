---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Perguntas mais frequentes sobre a seleção, configuração, diagnóstico
  e assistência técnica dos dispositivos ELETOR.
keywords:
- ELETOR
- FAQ
- controladores de ventilação
- reguladores
- ventiladores
- atuadores
- alarmes
- variadores de frequência
- assistência técnica
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Perguntas frequentes

As FAQ foram elaboradas com base numa análise anonimizada de conversas reais com utilizadores e clientes da ELETOR. As respostas foram generalizadas para ajudar em situações típicas e não conter dados de pessoas ou instalações específicas.

:::note Âmbito das FAQ

As respostas referem-se a situações típicas. As designações dos terminais, as funções e a forma de ligação podem variar entre modelos e versões dos dispositivos. Em caso de dúvida, consulte a documentação correspondente ao produto específico.

:::

:::warning Segurança

Execute os trabalhos na instalação elétrica de acordo com a documentação do dispositivo e as normas de segurança em vigor. Os trabalhos com tensão de rede devem ser executados por uma pessoa com as qualificações adequadas.

:::

## Seleção do controlador e da potência

### Como selecionar um controlador para os ventiladores?

A seleção baseia-se sobretudo na corrente total dos ventiladores, e não apenas no seu número.

:::tip Prepare os dados antes da seleção

Quanto mais precisos forem os dados sobre os motores e o modo de funcionamento da instalação, mais segura será a seleção do controlador.

:::

Antes da seleção, convém preparar:

- o número de ventiladores,
- a tensão de alimentação,
- a potência ou a corrente nominal de cada ventilador,
- a informação sobre se todos os ventiladores devem funcionar com regulação contínua,
- a informação sobre se os ventiladores podem ser divididos em grupos,
- as informações sobre dispositivos adicionais, por exemplo, aquecedores ou entradas de ar.

O controlador não deve ser dimensionado exatamente no limite. Deve manter-se uma margem adequada em relação à carga máxima.

### Basta somar a potência dos ventiladores em watts?

A potência pode ser utilizada para uma estimativa inicial, mas a seleção final deve basear-se na corrente nominal dos dispositivos e nas características da carga.

Durante o arranque, um motor pode consumir mais corrente do que durante o funcionamento normal. Por esse motivo, dois conjuntos de ventiladores com potência nominal semelhante nem sempre constituem uma carga equivalente para o controlador.

### Tenho vários ventiladores pequenos. Posso ligá-los em paralelo a uma única saída?

Sim, se:

- forem concebidos para esse modo de controlo,
- devem funcionar em conjunto,
- a soma das cargas não exceder a corrente admissível da saída,
- a forma de ligação estiver de acordo com a documentação do controlador.

Com um número maior de ventiladores, convém considerar a divisão em grupos ou a utilização de uma expansão de potência.

### Quando é necessária uma expansão de potência?

Utiliza-se uma expansão de potência quando a carga excede a capacidade da saída do controlador ou quando se pretende ampliar a instalação com um número maior de ventiladores.

Nesse caso, o controlador transmite o sinal de controlo, enquanto a carga propriamente dita é gerida por um módulo adicional.

### É possível ampliar posteriormente a instalação com ventiladores adicionais?

Em muitas instalações, sim. As soluções mais utilizadas são:

- uma expansão de potência adicional,
- um grupo de ventilação adicional,
- um contactor que liga outro grupo,
- um variador de frequência no caso de motores trifásicos.

É preferível prever a ampliação planeada logo durante a seleção inicial do controlador.

### Todos os ventiladores têm de funcionar com regulação contínua?

Não. São comuns duas soluções:

1. todos os ventiladores funcionam com regulação contínua,
2. o primeiro grupo funciona com regulação contínua e os grupos seguintes são ligados por etapas, por exemplo, através de contactores.

A segunda solução permite gerir uma instalação maior sem regulação contínua de cada ventilador.

### Tenho 10 ventiladores. Preciso de um controlador muito grande?

Nem sempre. Podem ser utilizados vários modos de controlo:

- divisão em grupos,
- expansões de potência,
- contactores,
- variador de frequência.

A seleção final depende dos parâmetros elétricos dos ventiladores e de todos eles terem ou não de alterar a velocidade de rotação simultaneamente.

### Os controladores 6 A e 12 A diferem apenas na carga admissível?

Não se deve pressupor que a única diferença é o valor da corrente. As diferentes versões e gerações dos dispositivos podem diferir no equipamento ou na construção.

Ao substituir o dispositivo, deve verificar-se o modelo exato e a documentação atual.


## Ventiladores e controlo da ventilação

### O controlador regula os ventiladores de forma contínua?

Nos controladores destinados à regulação contínua da ventilação, a velocidade dos ventiladores varia em função da necessidade, determinada, entre outros fatores, pela temperatura.

No entanto, deve verificar-se se o tipo de motor em questão é adequado ao método de regulação utilizado.

### O que significa temperatura de referência?

A temperatura de referência é o valor com o qual o controlador compara a medição atual da temperatura.

Com base nessa comparação, o controlador aumenta ou diminui a intensidade da ventilação de acordo com as restantes definições, por exemplo, a banda de regulação e os níveis mínimo e máximo.

### O que significa nível mínimo de ventilação?

É o valor mínimo de controlo do ventilador durante o funcionamento automático.

Esta definição evita o funcionamento abaixo do nível em que o ventilador poderia funcionar de forma instável ou proporcionar uma renovação de ar insuficiente.

### O que significa nível máximo de ventilação?

É o limite superior do valor de controlo da ventilação.

Por exemplo, definir um valor inferior a 100% pode limitar a velocidade máxima de rotação do ventilador, se a instalação assim o exigir.

### O que significa banda de ventilação?

A banda de ventilação define o intervalo de temperaturas em que o controlador passa do nível mínimo para o nível máximo de ventilação.

Quanto menor for a banda, mais rapidamente o controlo reage a uma alteração da temperatura aumentando o caudal.

### Após o arranque, o ventilador atinge primeiro 100% e só depois abranda. Porquê?

Pode estar ativa uma função de arranque cuja finalidade é iniciar momentaneamente o motor com maior potência.

Consoante a versão do controlador, devem verificar-se as definições relacionadas com:

- a função de arranque suave,
- o tempo de aceleração,
- o tempo de funcionamento a 100%,
- o tempo de desaceleração.

Se a função não for necessária na instalação em questão, os parâmetros correspondentes podem ser alterados de acordo com o manual do dispositivo.

### Porque pode o ventilador ser acionado momentaneamente à potência máxima no arranque?

Este tipo de arranque pode ajudar a garantir um arranque fiável do ventilador e ser útil em instalações em que os elementos mecânicos podem oferecer maior resistência durante o arranque.

No entanto, não é necessário em todas as instalações.

### O que significam tempo de aceleração e tempo de desaceleração?

**O tempo de aceleração** define a forma como o valor de controlo aumenta durante o arranque do ventilador.

**O tempo de desaceleração** define a forma como a velocidade diminui.

Ambos os parâmetros permitem limitar alterações bruscas da velocidade de rotação e do funcionamento da instalação.

### Porque podem dois controladores idênticos arrancar os ventiladores de forma diferente?

A causa mais frequente são definições diferentes.

Convém comparar sobretudo:

- a temperatura de referência,
- a banda de ventilação,
- o mínimo e o máximo,
- as definições de arranque suave,
- os tempos de aceleração e desaceleração,
- a configuração dos grupos de ventilação.

### O controlador pode ativar periodicamente a ventilação independentemente da temperatura?

Consoante o modelo, está disponível uma função de arejamento periódico.

Esta função pode ativar a ventilação durante um período definido, a intervalos estabelecidos, mesmo quando a regulação da temperatura não exige um aumento da ventilação.

### Para que servem os grupos de ventilação?

Os grupos permitem aumentar gradualmente o caudal da instalação.

Por exemplo:

- o grupo 1 funciona com regulação contínua,
- o grupo 2 ativa ventiladores adicionais,
- o grupo seguinte é ativado quando a necessidade é ainda maior.

Isto permite controlar um grande número de ventiladores sem regulação contínua de cada um deles.

### É possível ligar um grupo adicional de ventiladores através de um contactor?

Sim. A saída de relé do controlador pode controlar a bobina de um contactor devidamente selecionado.

Nesse caso, a corrente de carga dos ventiladores não deve passar diretamente por um pequeno contacto de controlo.

### O que significa o símbolo do ventilador ou o indicador amarelo no controlador?

Consoante o modelo, os indicadores informam sobre o estado atual das saídas e das funções.

A indicação amarela pode significar uma função operacional ativa, por exemplo, o funcionamento da ventilação, do aquecimento ou de outro grupo.

O significado exato deve ser consultado no manual do modelo em questão.

### O que significa o símbolo do modo manual?

O modo manual significa que o valor de controlo foi imposto pelo utilizador e não está, nesse momento, a ser calculado automaticamente com base na temperatura.

Após concluir os testes, deve confirmar-se que o controlador foi reposto no modo automático adequado.


## Entradas de ar e atuadores

### O controlador pode controlar as entradas de ar?

Sim, determinados controladores permitem trabalhar com os acionamentos das entradas de ar.

A forma de ligação depende do tipo de atuador e do seu modo de controlo.

### Que tipos de atuadores podem ser utilizados nas entradas de ar?

Nas conversas técnicas, surgiram mais frequentemente duas soluções:

- atuador controlado por um sinal analógico 0–10 V ou 2–10 V,
- atuador reversível de abertura/fecho com sinal de realimentação, por exemplo, de um potenciómetro.

Antes da compra, deve verificar-se a compatibilidade do modelo específico com o controlador existente.

### A tensão de alimentação do atuador 24 V ou 230 V tem influência no sinal 0–10 V?

O sinal de controlo e a alimentação do atuador são parâmetros distintos.

O atuador pode ser alimentado com uma tensão diferente da tensão do sinal de controlo. Ambos os parâmetros devem estar de acordo com a documentação do atuador e do controlador.

### O que significa controlo 0–10 V?

O controlador envia um sinal analógico de tensão que representa a posição ou o nível de controlo pretendido.

Numa aplicação típica, um valor mais baixo significa uma abertura menor e um valor mais alto uma abertura maior, mas a característica real deve ser verificada na documentação do atuador.

### Qual é a diferença entre 0–10 V e 2–10 V?

Em ambos os casos, a posição é definida por um sinal analógico.

No padrão 2–10 V, a parte inferior do intervalo está deslocada e pode permitir ao dispositivo distinguir o sinal de controlo da sua ausência.

O controlador e o atuador devem suportar um intervalo compatível.

### Como selecionar o atuador em função do número de entradas de ar?

O atuador não deve ser selecionado apenas com base no número de comportas.

É necessário ter em conta:

- a força ou o binário necessários,
- o comprimento e a disposição do mecanismo,
- a resistência das comportas,
- o comprimento do curso,
- a velocidade de atuação,
- a tensão de alimentação,
- o tipo de controlo,
- a realimentação necessária.

### Um único atuador pode acionar várias comportas?

Sim, se a mecânica da instalação permitir ligar as comportas através de um sistema comum e o binário ou a força necessários não excederem a capacidade do atuador.

Na prática, a seleção é determinada pela resistência de todo o mecanismo, e não apenas pelo número de comportas.

### É possível ligar vários atuadores em paralelo e controlá-los com um único sinal?

Em alguns sistemas, é possível, mas devem verificar-se a documentação dos atuadores e a carga admissível da saída de controlo.

No caso de acionamentos reversíveis sem realimentação independente, pode também ocorrer um desvio gradual entre as posições dos diferentes atuadores.

### Porque podem vários atuadores assumir posições diferentes ao longo do tempo?

Mesmo motores idênticos podem funcionar a velocidades ligeiramente diferentes devido a:

- cargas diferentes,
- resistências mecânicas,
- tolerâncias dos parâmetros do motor,
- diferenças nas transmissões.

Por isso, quando é necessária uma sincronização precisa, é indispensável uma realimentação adequada ou um controlo individual da posição.

### As entradas de ar podem ser controladas proporcionalmente à ventilação?

Sim. Em sistemas devidamente configurados, a posição das entradas de ar pode estar associada ao nível atual de ventilação.

Assim, à medida que o caudal dos ventiladores aumenta, a abertura das entradas de ar também aumenta.

### O atuador 24 V necessita de uma fonte de alimentação separada?

Se o controlador não tiver uma saída de alimentação adequada com a potência necessária, é necessária uma fonte de alimentação separada.

A sua potência deve ser dimensionada em função do consumo de corrente do atuador e dos outros dispositivos alimentados pela mesma fonte.

### É possível utilizar um atuador de outro fabricante?

Muitas vezes, sim, se os seus parâmetros elétricos e o modo de controlo forem compatíveis com as saídas do controlador.

Antes da ligação, devem verificar-se:

- a tensão,
- o tipo de sinal,
- o esquema dos condutores,
- os sentidos de funcionamento,
- o sinal de posição,
- a carga admissível.


## Sensores de temperatura e humidade

### Onde ligar o sensor de temperatura?

O sensor deve ser ligado à entrada de sensor prevista pelo fabricante, à entrada de sensor indicada na documentação do modelo em questão.

Não se deve pressupor que as designações dos terminais são idênticas em todas as versões dos dispositivos.

### O sensor de temperatura indica um valor diferente do termómetro de referência. O que fazer?

Se o controlador tiver uma função de calibração do sensor, é possível corrigir a indicação após a comparar com um termómetro de referência fiável.

Antes de alterar a calibração, convém confirmar que:

- ambos os sensores se encontram no mesmo local,
- a medição estabilizou,
- o sensor não é aquecido pelo sol ou por dispositivos,
- não se encontra diretamente numa corrente de ar frio ou quente.

### O sensor de humidade indica um valor incorreto. É possível calibrá-lo?

Isso depende da versão do controlador, do sensor e do software.

Em algumas soluções, a correção pode exigir uma função de software adequada ou um tipo de sensor compatível. Se a diferença for grande e repetível, deve verificar-se a versão do dispositivo e contactar a assistência técnica.

### Uma medição incorreta significa sempre que o sensor está danificado?

Não.

A causa também pode ser:

- a localização incorreta do sensor,
- o cabo,
- a ligação elétrica,
- a configuração,
- um tipo de sensor inadequado,
- a necessidade de calibração,
- humidade ou corrosão.


## Alarmes e notificações

### É possível ligar uma sirene diretamente à saída de alarme do controlador?

Não se deve pressupor que isso seja possível.

A saída de alarme do controlador é normalmente uma saída de controlo ou um contacto de relé. A sirene pode necessitar de alimentação separada e de uma central de alarme.

### Para que se utiliza uma central de alarme?

A central pode:

- receber sinais de alarme dos controladores,
- alimentar o sinalizador,
- manter o funcionamento durante uma falha de alimentação,
- sinalizar o alarme por som ou luz,
- enviar notificações GSM nas versões que dispõem dessa função.

### A central pode emitir um alarme em caso de falha de alimentação do controlador?

Sim, se o sistema tiver sido devidamente ligado.

A solução pode detetar não só a ultrapassagem da temperatura, mas também a perda do sinal do controlador causada pela falha da sua alimentação.

### Onde se definem as temperaturas mínima e máxima de alarme?

Numa configuração típica, os limiares de alarme são definidos no controlador que gere a câmara ou o compartimento em questão.

A central de alarme recebe então a informação de que o controlador emitiu um alarme.

### A central GSM necessita de um cartão SIM?

Para efetuar chamadas e enviar mensagens através da rede móvel, é necessário um cartão SIM ativo ou outra solução de comunicação prevista no modelo em questão.

Sem uma ligação ativa à rede móvel, as funções de chamadas e SMS não funcionarão.

### O alarme pode enviar informação sobre o controlador que originou o evento?

Num sistema devidamente configurado, sim.

As entradas da central podem ser atribuídas a compartimentos ou controladores específicos, permitindo que a mensagem identifique a origem do alarme.

### Quantos controladores podem ser ligados a uma única central de alarme?

Isso depende do modelo da central.

Nas transcrições, surgiram centrais que suportavam até oito entradas, mas, antes de executar a instalação, deve verificar-se a especificação atual do dispositivo específico.

### Que bateria é utilizada na central de alarme?

Em alguns dos dispositivos discutidos nas conversas, era utilizada uma bateria 12 V 7 Ah.

Antes de comprar uma bateria de substituição, deve verificar-se a identificação na bateria existente e a especificação da central, pois outras versões dos dispositivos podem necessitar de uma bateria diferente.

### A central envia mensagens de baixa tensão. O que verificar?

Em primeiro lugar, devem verificar-se:

- o estado da bateria,
- a sua idade,
- as ligações da bateria,
- a presença de alimentação da rede,
- o funcionamento do carregador ou da fonte de alimentação da central.

Uma bateria desgastada pode causar mensagens cíclicas de baixa tensão.

### Com que frequência se deve substituir a bateria da central de alarme?

Não existe um único intervalo adequado a todas as condições.

A bateria deve ser testada periodicamente, sobretudo em instalações em que o alarme durante uma falha de alimentação tem importância crítica. Com a idade, a sua capacidade real diminui.

### A sirene, por si só, é suficiente como proteção?

A sirene só é eficaz quando alguém a pode ouvir.

Em instalações que ficam temporariamente sem supervisão, convém utilizar também notificações remotas e alimentação de reserva por bateria.


## Variadores de frequência

### Como selecionar um variador de frequência para os ventiladores?

É necessário conhecer:

- a tensão de alimentação,
- o número de fases,
- a potência e a corrente de todos os motores,
- a forma como estão ligados,
- as condições de funcionamento,
- o modo de controlo necessário.

O variador de frequência deve ter uma margem adequada em relação à carga, sobretudo quando vários motores funcionam em paralelo.

### O variador de frequência deve ter exatamente a mesma potência que a soma das potências dos motores?

O variador de frequência não deve ser selecionado apenas com base na simples soma das potências, nem se deve escolher um dispositivo que funcione exatamente no limite dos seus parâmetros.

Devem ter-se em conta as correntes nominais, as características da carga e as recomendações do fabricante do variador de frequência.

### O variador de frequência parou os ventiladores e apresentou um erro. O que fazer?

O mais importante é registar o código de erro completo antes da reposição.

:::tip Tire uma fotografia do ecrã

Se a situação o permitir, tire uma fotografia do visor antes da reposição. O código de erro completo facilita significativamente o diagnóstico.

:::

Apenas o início da mensagem é frequentemente insuficiente para determinar a causa. O código completo permite distinguir, entre outros:

- sobrecarga,
- sobrecorrente,
- sobreaquecimento,
- tensão incorreta,
- outros erros do acionamento.

### É possível simplesmente repor o erro do variador de frequência?

A reposição pode restabelecer o funcionamento, mas não elimina a causa do alarme.

Após o evento, deve verificar-se o código de erro e determinar-se a causa antes de voltar a colocar a instalação em funcionamento prolongado.

### O variador de frequência funciona num compartimento com poeiras. É necessário limpá-lo?

Sim.

O pó e os depósitos no dissipador de calor ou no ventilador de arrefecimento podem prejudicar a dissipação de calor e causar o sobreaquecimento do variador de frequência.

A limpeza deve ser efetuada de acordo com o manual do fabricante, após desligar a alimentação em segurança.

### O que pode causar o sobreaquecimento do variador de frequência?

As causas mais frequentes são:

- elementos de arrefecimento sujos,
- fluxo de ar obstruído,
- temperatura ambiente demasiado elevada,
- sobrecarga,
- avaria do ventilador de arrefecimento,
- montagem incorreta.

### Uma tensão de rede elevada pode provocar um alarme no variador de frequência?

Sim. Os variadores de frequência monitorizam a tensão do circuito de alimentação e podem indicar um erro quando o nível admissível é excedido.

Se o problema se repetir, devem verificar-se a instalação e a qualidade da alimentação.


## Avarias e diagnóstico

### O controlador funciona, mas o visor não apresenta nada. Qual pode ser a causa?

As causas possíveis incluem, entre outras:

- avaria do visor,
- problema na regulação do contraste em soluções mais antigas,
- danos na ligação,
- corrosão,
- danos na placa principal.

Se o dispositivo não tiver sido utilizado durante muito tempo ou tiver funcionado num ambiente húmido, convém também verificar o estado da placa.

### O controlador apresenta um problema no visor após vários anos sem utilização. Porquê?

Um longo período de inatividade num ambiente húmido ou agressivo pode causar:

- oxidação dos conectores,
- corrosão,
- deterioração dos contactos,
- danos nos componentes eletrónicos.

Nesse caso, convém realizar uma inspeção completa, em vez de substituir componentes sem um diagnóstico prévio.

### O controlador ficou enegrecido após uma sobretensão transitória. Isso significa que a placa tem de ser substituída?

Nem sempre.

Um componente de proteção pode ficar danificado e deixar muitos resíduos, embora a restante parte da placa possa ser reparada.

No entanto, se o laminado estiver carbonizado ou queimado, ou se as pistas estiverem danificadas, a reparação pode não ser economicamente viável ou duradoura.

### O que pode danificar vários controladores simultaneamente?

Se vários dispositivos avariarem ao mesmo tempo, deve verificar-se a instalação de alimentação.

Uma das causas possíveis é um problema no condutor neutro que, numa instalação trifásica, pode provocar tensões incorretas nos recetores monofásicos.

Também são possíveis sobretensões transitórias provenientes da rede ou do grupo gerador.

### O que fazer após uma avaria relacionada com uma sobretensão transitória?

Antes de ligar um controlador reparado ou novo, deve determinar-se a causa do problema.

:::danger Não volte a ligar o dispositivo sem verificar a instalação

Se a causa da avaria tiver sido uma tensão incorreta, um condutor neutro danificado ou uma sobretensão transitória, o controlador reparado ou novo pode voltar a ficar danificado.

:::

### O que é o componente de proteção contra sobretensões transitórias na placa?

Nos dispositivos eletrónicos, utilizam-se componentes que limitam as sobretensões transitórias, por exemplo, varístores.

A sua função é absorver parte da energia da sobretensão transitória e proteger os circuitos a jusante. Após um evento intenso, esse componente pode ficar permanentemente danificado.

### É possível colocar o dispositivo em funcionamento após remover o componente de proteção queimado?

Isto não deve ser considerado uma reparação normal.

Após a remoção da proteção, o dispositivo pode perder a proteção contra uma nova sobretensão transitória. Estas intervenções só podem ser realizadas como um procedimento de assistência técnica consciente, por uma pessoa com as qualificações adequadas e após eliminar a causa da avaria original.

### O controlador sofreu entrada de água ou apresenta corrosão intensa. Vale a pena repará-lo?

Isso depende do grau dos danos.

A corrosão superficial e os danos isolados podem frequentemente ser eliminados. Se a corrosão tiver afetado as pistas, os conectores e muitos componentes, a reparação pode ser demorada, incerta e economicamente injustificada.

### A lavagem sob pressão pode danificar o controlador?

Sim.

A eletrónica não deve ser exposta à ação direta da água ou de detergentes se a caixa e a forma de montagem não forem concebidas para isso.

A humidade que entra no interior pode causar corrosão e avarias posteriores difíceis de diagnosticar.

### Porque podem as avarias após entrada de água reaparecer depois da reparação?

A corrosão pode continuar a progredir também em locais não visíveis durante a primeira inspeção.

As vias, pistas e ligações danificadas podem funcionar durante o teste e, mais tarde, voltar a perder o contacto.

Por isso, no caso de uma placa com corrosão intensa, a assistência técnica pode recomendar a substituição em vez de novas reparações.

### O dispositivo funciona de forma intermitente. Por onde começar?

Antes de contactar a assistência técnica, convém reunir:

- o modelo exato,
- a descrição do sintoma,
- o momento em que ocorre,
- os valores apresentados no ecrã,
- o código de alarme ou de erro,
- informações sobre as últimas alterações na instalação,
- uma fotografia do interior e dos terminais, se puder ser tirada em segurança.

Quanto mais precisa for a descrição, mais fácil será o diagnóstico.


## Assistência técnica e reparações

### O que enviar à assistência técnica se o controlador estiver danificado?

É preferível enviar um conjunto que permita reproduzir o problema.

O envio deve incluir uma breve descrição de:

- o que não funciona,
- quando o problema ocorre,
- se a avaria é permanente ou intermitente,
- se, antes da avaria, ocorreu uma sobretensão transitória, entrada de água ou outro evento,
- os dados necessários para o contacto e a devolução do dispositivo.

:::note Dados para o pedido de assistência técnica

Forneça os dados de contacto e de envio diretamente à assistência técnica. Não os publique em pedidos abertos nem em materiais públicos.

:::

### É necessário enviar o controlador completo ou apenas a placa?

Depende da avaria.

Em caso de problemas com o visor, os botões, a alimentação ou um comportamento ambíguo, é preferível enviar todo o conjunto necessário para reproduzir o sintoma.

Numa reparação previamente acordada de um módulo específico, a assistência técnica pode solicitar apenas a placa.

### A ELETOR repara os controladores em vez de os substituir imediatamente?

As transcrições indicam que os dispositivos são primeiro diagnosticados.

Se a reparação for possível e fizer sentido, os componentes ou módulos danificados são substituídos. Em caso de danos graves, a assistência técnica pode propor a substituição da placa ou de todo o dispositivo.

### O que acontece se a placa danificada não puder ser reparada?

É possível substituir o módulo danificado por um novo, desde que a peça adequada esteja disponível e seja compatível com o dispositivo.

Nos dispositivos mais antigos, a assistência técnica deve primeiro confirmar a compatibilidade das versões.

### Vale a pena comprar imediatamente uma placa nova após uma sobretensão transitória?

Nem sempre.

Se os danos afetarem um componente de proteção ou uma pequena parte do circuito, a reparação pode ser justificada. Convém realizar primeiro um diagnóstico.

### A assistência técnica também pode verificar o visor e os botões?

Sim, se os componentes forem fornecidos juntamente com o dispositivo ou o módulo.

Isto é particularmente útil quando não se sabe se o problema se encontra na placa principal ou no painel do utilizador.

### Vale sempre a pena recuperar um controlador com corrosão intensa?

Não.

Se o custo do diagnóstico e da reparação aumentar e a fiabilidade após a reparação continuar incerta, a substituição pode ser mais sensata.

Isto aplica-se sobretudo aos dispositivos dos quais depende a ventilação da instalação.

### Como acelerar o diagnóstico da assistência técnica?

Inclua uma descrição precisa do sintoma, em vez de apenas indicar «não funciona».

Também são úteis:

- fotografias,
- o código de erro,
- a descrição da instalação,
- o tipo de recetores ligados,
- informação sobre uma sobretensão transitória ou falha de alimentação,
- informação sobre entrada de água ou lavagem do dispositivo.


## Instalação e cablagem

### Como ligar os dispositivos aos terminais de relé C e NO?

C e NO são designações típicas dos contactos de relé:

- C — contacto comum,
- NO — contacto normalmente aberto.

A forma de utilização depende do dispositivo e do esquema da instalação. O contacto pode ser utilizado, por exemplo, para controlar a bobina de um contactor, mas os seus parâmetros admissíveis não podem ser excedidos.

:::warning Trabalhos elétricos

As ligações à tensão de rede devem ser efetuadas por uma pessoa com as qualificações adequadas, de acordo com o esquema do dispositivo específico.

:::

### Uma saída de relé pode alimentar diretamente um ventilador grande?

Normalmente, esta não é uma utilização adequada de uma pequena saída de controlo.

Para cargas maiores, utiliza-se um contactor, um relé de potência ou um módulo de acionamento dedicado.

### Para que servem os terminais A1 e A2 do contactor?

São os terminais da bobina do contactor.

Ao aplicar a tensão adequada à bobina, o contactor altera o estado dos seus contactos de potência.

A tensão da bobina deve estar de acordo com o projeto da instalação e a documentação do contactor.

### É possível montar aparelhos adicionais no interior da caixa do controlador?

Apenas se a construção da caixa específica o permitir e se isso não prejudicar:

- o grau de proteção,
- o isolamento,
- o arrefecimento,
- a segurança,
- o acesso para assistência técnica.

Todos os novos orifícios devem ser executados de forma a manter a estanquidade necessária.

### Os interruptores adicionais dos ventiladores são úteis?

Podem facilitar a assistência técnica e permitir desligar cada ventilador de forma independente.

No entanto, a execução deve ter em conta as proteções elétricas e não pode provocar estados perigosos do controlador.

### Os cabos de controlo podem ser encaminhados juntamente com os cabos de potência?

Deve evitar-se o encaminhamento de cabos de sinal sensíveis em paralelo e muito próximos de cabos de elevada potência, sobretudo em percursos longos.

Os requisitos dependem do tipo de sinal e do ambiente eletromagnético.

### Que cabo utilizar para ligações de rede e dispositivos PoE?

Nas instalações discutidas, foi indicado como mínimo um cabo de par entrançado de categoria 5e.

Se o cabo passar por um ambiente com um nível elevado de interferências ou risco de cargas eletrostáticas, pode justificar-se a utilização de um cabo devidamente blindado e de um sistema de ligação à terra correto.

### É necessário um cabo cruzado para PoE?

Nas instalações típicas, utiliza-se uma ligação direta padrão.

No entanto, devem verificar-se sempre os requisitos do dispositivo de rede e da fonte de alimentação PoE utilizada.


## Utilização e manutenção

### Como reduzir o risco de avaria dos controladores em edifícios agrícolas?

O mais importante é limitar a influência de:

- humidade,
- amoníaco e ambiente agressivo,
- poeiras,
- lavagem direta com água,
- sobretensões transitórias,
- alimentação incorreta.

Convém também verificar periodicamente o estado dos cabos, das ligações e das caixas.

### Os dispositivos eletrónicos devem ser limpos regularmente?

Sim, sobretudo os dispositivos equipados com dissipadores de calor, ventiladores e aberturas de ventilação.

O pó acumulado prejudica o arrefecimento.

A limpeza deve ser efetuada após desligar a alimentação e de acordo com o manual do dispositivo.

### Vale a pena realizar uma inspeção do controlador após vários anos de funcionamento?

Sim, sobretudo em condições ambientais difíceis.

A inspeção pode incluir:

- avaliação do estado dos conectores,
- verificação de vestígios de humidade e corrosão,
- verificação dos elementos de arrefecimento,
- verificação do painel e dos botões,
- teste dos sensores,
- verificação das baterias nos sistemas de alarme.

### O que convém registar após a ocorrência de uma avaria?

Os dados mais úteis são:

- a mensagem completa,
- o código de erro,
- a hora do evento,
- a temperatura,
- o estado da ventilação,
- informação sobre uma falha de alimentação,
- informação sobre o funcionamento do grupo gerador,
- uma fotografia do ecrã ou do dispositivo.

Não se deve efetuar a reposição do dispositivo antes de registar o código, se a situação permitir fazê-lo em segurança.

### Vale a pena ter um alarme independente do controlador de ventilação?

Sim, sobretudo onde uma avaria da ventilação pode rapidamente criar condições perigosas.

Uma central independente com bateria própria e notificações remotas proporciona uma camada adicional de proteção.

### Que informações preparar antes de contactar a assistência técnica?

É preferível preparar:

1. o modelo exato do dispositivo,
2. a descrição da instalação,
3. o número e os parâmetros dos dispositivos ligados,
4. as definições atuais relacionadas com o problema,
5. o sintoma exato,
6. o código completo de erro ou de alarme,
7. fotografias do dispositivo e das placas de características,
8. informação sobre as últimas alterações na instalação.

Isto permite reduzir significativamente o tempo de diagnóstico.


## Nota importante sobre dispositivos mais antigos

Os nomes, as designações dos terminais e as funções disponíveis podem variar entre versões de dispositivos fabricados em anos diferentes.

Se o dispositivo tiver vários anos ou mais de uma década, antes de aplicar as instruções de um modelo mais recente, deve confirmar-se:

- a identificação exata do dispositivo,
- a versão da placa,
- o tipo de visor,
- a versão do software,
- o esquema dos terminais.

:::warning Versões mais antigas dos dispositivos

Não pressuponha uma compatibilidade total apenas com base num aspeto semelhante da caixa. Antes de utilizar um esquema ou manual, confirme o modelo e a versão exatos do dispositivo.

:::


## Contacto com a assistência técnica

Se as FAQ não resolverem o problema, prepare antes do contacto:

- uma fotografia do controlador,
- uma fotografia da placa de características do recetor,
- os parâmetros dos motores ou dos atuadores,
- o esquema de ligações,
- uma descrição precisa do modo de funcionamento pretendido.

Assim, a seleção do dispositivo ou o diagnóstico do problema pode ser efetuado com base nos parâmetros reais da instalação, e não em suposições.
