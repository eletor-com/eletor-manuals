---
sidebar_position: 4
title: Manual da fonte de alimentação DC50W24VB
description: Fonte de alimentação DC50W24VB  de emergência para o sistema de entradas
  de ar.
keywords:
- eletor IC-AC
- controlador de entradas de ar
- controlador climático
- controlador de ventilação de instalações suinícolas
- controlador de microclima
- controlador para instalações suinícolas
- ventilação de instalações suinícolas
- controlador para instalações de recria
---


# Fonte de alimentação DC50W24VB

Fonte de alimentação de emergência com função de abertura automática e manual das entradas e saídas de ar. Utilizada para garantir a segurança dos animais de criação em caso de falha de alimentação ou avaria do controlador. Após detetar uma irregularidade, o dispositivo emite um alarme e abre os mecanismos de elevação até ao nível definido.

## Parâmetros e características: 
-  Seletor do modo de funcionamento: 
    - MANUAL
    - AUTO.
-  Botão rotativo do grau de abertura das entradas de ar.
-  Compatibilidade com os padrões:
    - 0-10, 2-10, 10-0, 10-2.
-  Possibilidade de inversão do sinal de controlo.
-  Saídas de alarme NO e NC.
-  Sinalização de falha de alimentação.
-  Monitorização da tensão de controlo 2-10V.
-  Monitorização de curto-circuitos nas saídas 24VDC.
-  Monitorização de curto-circuitos nas saídas 0-10V.
-  2 entrada 0-10V.
-  2 saídas 0-10V.
-  Proteções eletrónicas das entradas, saídas e linhas 24V.
-  Banco de baterias 24V 4.0 Ah.
-  Invólucro hermético IP65.
-  Tensão de alimentação 85~264VAC 47~63Hz.

# Instalação do controlador  
:::danger 
Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão presente em alguns componentes representa um perigo para a vida e a saúde. Recomenda-se que a instalação seja confiada a uma pessoa qualificada.
:::

## Escolha do local de montagem  

O local de montagem deve ser escolhido criteriosamente, tendo em conta a facilidade de acesso ao dispositivo por pessoas autorizadas e a inacessibilidade para animais e crianças. Devem também ser consideradas as condições climáticas, ou seja, o dispositivo deve funcionar num intervalo de temperaturas de -10°C a 40 °C, num local não exposto à luz solar. Deve existir livre circulação de ar em redor do dispositivo.

# Montagem  

O dispositivo pode funcionar em condições climáticas agressivas. Quando montado corretamente, o dispositivo é resistente aos efeitos nocivos do ambiente.

### Durante a montagem, deve prestar-se atenção aos seguintes aspetos: 
 - a tampa deve ser apertada com todos os parafusos,
 - os cabos utilizados para ligar o dispositivo devem ter secção circular,
 - após ligar o cabo, devem apertar-se os bucins de modo a vedar e imobilizar o cabo; recomenda-se a utilização de silicone,
 - as passagens não utilizadas (bucins) devem ser obturadas,
 - a parte inferior do invólucro deve ser fixada a uma parede plana com 4 buchas de expansão.


# Ligação elétrica  

:::danger 
Antes de ligar o sistema, certifique-se de que a alimentação está desligada!
:::

Após desapertar o dispositivo, deve retirar-se o painel frontal. Para tal, retira-se o cabo de fita do conector identificado como P1. Introduzem-se os cabos através dos bucins de borracha e pode proceder-se à sua ligação. A ligação deve ser efetuada de acordo com a descrição.

![Ligação](./img/DC50W24VB.png)

**Alimentação 230V AC:** liga-se à alimentação (quadro de distribuição). É obrigatória a utilização de um disjuntor de sobrecorrente (tipo «S» B6) e de limitadores de sobretensão de classe «C». O dispositivo pode ser alimentado num amplo intervalo de tensões, de 85V a 264V, e de frequências, de 47 a 63Hz, sem afetar o seu funcionamento.  

**Conector In1 e In2** deve ser ligado ao controlador para fornecer o sinal de controlo aos sistemas de mecanismos de elevação. O dispositivo pode funcionar com dois controladores ou com um único controlador com secções separadas de entradas e saídas de ar (os terminais I1 e I2 devem ser ligados por uma ponte).  

**Conector ALARM** liga-se à central de alarme, consoante o sistema – fechado (NO e C), aberto (NC e C). O alarme é ativado nos seguintes casos:  •falha da tensão de alimentação do dispositivo,  •perda do sinal de controlo 2-10V em pelo menos uma das entradas,  •ocorrência de curto-circuito no sinal de saída ou quando o seu valor difere do valor medido,  •ocorrência de curto-circuito no barramento +24V que alimenta os mecanismos de elevação.  

**Conector Ouput 1 e Ouput 2** liga-se ao atuador (mecanismo de elevação) da forma exigida pelo dispositivo utilizado; a descrição da ligação deve constar do manual do respetivo atuador (mecanismo de elevação).  

**Seletor do modo de funcionamento S1** deve selecionar-se o modo de funcionamento adequado ao atuador (mecanismo de elevação) utilizado. Por predefinição, os seletores 1,2,3,4,5,6 estão na posição off – funcionamento 2-10V.
 
| Canal 1 | Canal 2| Função |
|------|------|----------|
| 1 – off | 4 – off | Modo de funcionamento no intervalo de sinais 2-10V, uma tensão de controlo inferior a 1,5V gera um alarme.   |
| 1 – on| 4 – on  | Modo de funcionamento no intervalo de sinais 0-10V, sem reação de alarme a um sinal inferior a 1,5V.   |
| 2 – off | 5 – off  | Modo de funcionamento proporcional, sinais de saída no intervalo 0-10V ou 2-10V.  |
| 2 – on | 5 – on  | Modo de funcionamento invertido, sinais de saída no intervalo 10-0V ou 10-2V.   |
| 3 – off | 6 – off  | Inversão da entrada desativada.  |
| 3 – on | 6 – on   | Inversão da entrada ativada.   |

# Princípio de funcionamento  

A fonte de alimentação de emergência, no modo de funcionamento normal, alimenta os atuadores (mecanismos de elevação) 24V e carrega ou mantém carregadas as baterias, que fornecerão energia em caso de falha de alimentação.  O seletor AUTO/MANUAL determina o modo de funcionamento do dispositivo.  

**Modo MANUAL** permite o controlo direto dos atuadores (mecanismos de elevação) através do botão rotativo no painel do dispositivo.  

**Modo AUTO** – modo de funcionamento principal, transmite o sinal de controlo da entrada para a saída, efetuando o processamento adequado em função das definições do seletor «S1» e monitoriza o nível do sinal de entrada.  Caso seja detetada uma irregularidade numa determinada entrada, o dispositivo aplica à sua saída o sinal do botão rotativo no painel frontal.  O relé de alarme atua nos seguintes casos:  •sinal de entrada demasiado baixo (Uin < 1,5V) – seletor «S1» 1-off, 4-off,  •curto-circuito do sinal de saída à massa ou a 24V,  •ausência de tensão de alimentação,  •curto-circuito da tensão 24V.

## Utilização 

O utilizador seleciona o modo MANUAL com o seletor e, com o botão rotativo, o grau de abertura das entradas de ar adequado aos requisitos – os atuadores funcionam de acordo com a indicação do botão rotativo. Após concluir a regulação das entradas de ar, seleciona-se o modo AUTO com o seletor e deixa-se o dispositivo a funcionar – as entradas de ar posicionam-se no nível exigido pelo controlador de ventilação. Numa situação de emergência, as entradas de ar posicionam-se de acordo com a indicação do botão rotativo.  

## Painel frontal 

| MENU                       | Descrição | 
|:---:                       |:---|
|![Ligação](./img/paneldcw50.png) |**Indicador luminoso POWER** – indica a presença de alimentação e o carregamento das baterias.  1.**Indicador luminoso CHECK** – permanece aceso no modo automático quando o sinal do controlador é transmitido à saída; pisca quando o sinal do botão rotativo é aplicado à saída.  2.**OUT 1** – indica irregularidades no canal 1.  3.**OUT 2** – indica irregularidades no canal 2.  4.**AUTO** – modo de funcionamento automático.  5.**MANUAL** – modo de funcionamento manual.  6.**Botão rotativo 0%-100%** - seleção do grau de abertura das entradas de ar.| 

# Mensagens de erro e avisos

As mensagens de erro destinam-se a informar o utilizador sobre irregularidades no funcionamento do dispositivo. As possíveis mensagens de erro são apresentadas abaixo:
 -  Indicador luminoso POWER – não acende a verde – ausência de alimentação da rede elétrica.
 -  Indicador luminoso CHECK – pisca a amarelo – o sinal do potenciómetro foi aplicado às saídas.
 -  Indicador luminoso OUT 1 – acende a vermelho - deteção de irregularidades (ausência de sinal de controlo, curto-circuito na saída ou curto-circuito no barramento 24VDC) no primeiro canal.
 -  Indicador luminoso OUT 2 – acende a vermelho - deteção de irregularidades (ausência de sinal de controlo, curto-circuito na saída ou curto-circuito no barramento 24VDC) no segundo canal.

# Observações e avisos  

:::danger 
Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão presente em alguns componentes representa um perigo para a vida e a saúde. Recomenda-se que a instalação seja confiada a uma pessoa qualificada.
:::

 - Para evitar problemas na utilização do dispositivo, é obrigatório ler o manual antes de proceder à instalação e à utilização. Não é permitido alterar a construção do dispositivo nem efetuar reparações por iniciativa própria. Isto aplica-se, em particular, à alteração de elementos e componentes.
 - As operações de manutenção ou assistência técnica devem ser efetuadas por pessoal autorizado (instalador ou serviço de assistência do fabricante). Nos edifícios de criação animal com ventilação forçada, é obrigatório um sistema de alarme. 
 - O fabricante do dispositivo não se responsabiliza por danos causados por instalação incorreta, programação incorreta das funções, consequências de acontecimentos fortuitos ou fatores externos. O dispositivo exige a configuração dos parâmetros de acordo com as condições existentes no espaço de criação animal.Estas definições são individuais e dependem da decisão do criador. 
 - O fabricante do dispositivo reserva-se o direito de efetuar alterações na construção do dispositivo e no software.
O dispositivo inclui um banco de baterias; não se deve permitir a sua descarga excessiva, pois tal pode danificar as baterias. 
Um curto-circuito entre os polos das baterias pode provocar um incêndio.  


:::caution
![alt](./img/trash.svg) No final da vida útil do produto, este não deve ser eliminado juntamente com resíduos urbanos indiferenciados, mas sim eliminado de acordo com a legislação em vigor (diretivas WEEE da União Europeia 2012/19/UE).  O produto foi fabricado de acordo com os requisitos RoHS (diretiva da União Europeia 2011/65/UE).
:::

<!-- \newpage -->
# Dados técnicos do controlador  

|Parâmetro                        |	DESCRIÇÃO      |
|:-----------                    |:---------- |
|Tensão de alimentação alternada|	85~264VAC 47~63Hz|
|Tensão de alimentação contínua|	120~370VDC|
|Tensão de saída|	27,6VDC|
|Corrente máxima de saída|	1,8A|
|Rendimento|	85%|
|Corrente máxima das saídas de controlo 0-10V|	30mA|
|Corrente máxima da saída (contacto) ALARM|	3A|
|Proteção contra sobretensões das entradas e saídas|	SIM|
|Proteção contra curto-circuitos|	Automática |
|Banco de baterias|	4Ah 24V|
|Intervalo de temperaturas de funcionamento|	-10 +40oC|
|Dimensões do dispositivo|	20x15x8 cm|
|Grau de proteção do invólucro|	IP65|

:::info
O controlador IC-AC inclui no conjunto:
 - buchas de expansão - 	4 unid., 
 - baterias 12V 4Ah - 	2 unid., 
 - bucim PG13,5 -	1 unid.,
 - bucim PG11 -	3 unid., 
 - bucim PG9 -	3 unid.
:::

