---
sidebar_position: 4
title: Manual IC-AC
description: Controlador IC-AC de entradas de ar para instalações pecuárias com corrente
  de saída admissível de até 2A
keywords:
- eletor IC-AC
- controlador de entradas de ar
- controlador de clima
- controlador de ventilação de instalações de suínos
- controlador de microclima
- controlador para instalações de suínos
- ventilação de instalações de suínos
- controlador para instalações de recria
---


# Controlador IC-AC

  Controlador de atuadores e guinchos de entradas de ar baseados em motores AC com rotação direita/esquerda e potenciômetro para leitura da posição atual. O controlador funciona como conversor do sinal 0-10V para o nível de abertura das entradas de ar e permite também o controle manual.

## Parâmetros e características:  
- Modos de funcionamento:
  - MANUAL – controle manual por meio dos botões “+”, “-”;
  - AUTO – funcionamento automático no intervalo calibrado, proporcional ao sinal 0-10V;
  - EMERGÊNCIA – em caso de perda do sinal de controle, as entradas de ar abrem até o nível definido em porcentagem; 
- Saída de relé (direita/esquerda) 2A;
- Sinal de controle: 0-10V;
- Possibilidade de inversão do sinal de controle;
- Medição da posição por meio de potenciômetro 1-100kΩ;
- Histerese e tempo de cálculo da média das leituras programáveis; 
- Invólucro hermético IP56;
- Tensão de alimentação 230VAC 50Hz;
- Menu nos idiomas: 
  - polonês
  - inglês
  - ucraniano
  - russo

# Instalação do controlador  
:::danger 
Durante a instalação do dispositivo, a alimentação elétrica deve ser obrigatoriamente desligada, pois a tensão em alguns componentes representa perigo para a vida e a saúde. Recomenda-se que a instalação seja realizada por uma pessoa qualificada.
:::

## Escolha do local de montagem  

  O local de montagem deve ser escolhido de forma criteriosa, considerando a facilidade de acesso ao dispositivo por pessoas autorizadas e a impossibilidade de acesso por animais e crianças. Devem também ser consideradas as condições climáticas, ou seja, o dispositivo deve funcionar no intervalo de temperaturas de -10°C a 40 °C, em um local sem exposição ao sol.

# Montagem

O dispositivo pode funcionar em condições climáticas agressivas. Quando corretamente montado, o dispositivo é resistente aos efeitos nocivos do ambiente. 

  Durante a montagem, deve-se prestar atenção aos seguintes pontos: 
- a tampa deve ser apertada com todos os parafusos,
- os cabos utilizados para conectar o dispositivo devem ter seção transversal circular,
- após conectar o cabo, os prensa-cabos devem ser apertados de modo a vedar e imobilizar o cabo; recomenda-se o uso de silicone,
- as passagens não utilizadas (prensa-cabos) devem ser tampadas,
- a parte inferior do invólucro deve ser fixada a uma parede plana com 4 buchas de expansão.


# Conexão elétrica  

:::danger 
Antes de conectar o sistema, certifique-se de que a alimentação esteja desligada!
:::

  Após desapertar os parafusos do dispositivo, o painel frontal deve ser removido. Para isso, retire o cabo plano do conector identificado como P1. Passe os cabos pelos prensa-cabos de borracha e, em seguida, efetue as conexões. A conexão deve ser realizada de acordo com a descrição. Os terminais do controlador são apresentados na figura abaixo.

![Conexão](./img/ic-acpołącz.png)

## A alimentação 230V AC proveniente do quadro de distribuição deve ser conectada aos terminais:  
 - **Conector L** terminal de fase. É obrigatório utilizar um disjuntor de sobrecorrente (tipo “S” B3) e dispositivos de proteção contra surtos.  
 - **Conector N** terminal de neutro.  
 - **Conector PE** terminal de proteção.

## Saída para o atuador: 
 - **Conector L** deve ser ligado por um cabo ao conector C para fornecer tensão aos relés.  
 - **Conector N** terminal de neutro do atuador.  
 - **Conector PE** terminal de proteção do atuador – carcaça.  
 - **Conector NO** terminal do atuador no sentido de abertura das entradas de ar.  
 - **Conector NC** terminal do atuador no sentido de fechamento das entradas de ar.
 - **Conector do potenciômetro** – deve ser conectado de acordo com as indicações no esquema do atuador. A polaridade da alimentação do potenciômetro deve ser selecionada de modo que as unidades de posição aumentem durante a abertura das entradas de ar e diminuam durante o fechamento. Caso contrário, os cabos de alimentação do potenciômetro devem ser invertidos.  
 - **Conector In** – deve ser conectado ao controlador para fornecer o sinal de controle aos sistemas de guinchos.  


# Princípio de funcionamento  

  No modo automático, o controlador converte o sinal de controle no intervalo 0-10V na posição correspondente  do atuador das entradas de ar. É necessário calibrar o atuador nas posições de abertura máxima e de fechamento das entradas de ar. Durante a calibração, deve-se garantir que os cabos  que vão até as entradas de ar permaneçam constantemente tensionados. Durante a calibração, o botão “+” deve abrir as entradas de ar e o botão “-” deve fechá-las. Caso contrário, os cabos nos terminais NO e NC devem ser trocados entre si.
  As posições lidas pelo potenciômetro, para abertura e fechamento, devem apresentar uma diferença superior a 100 unidades. As unidades de posição lidas pelo potenciômetro devem aumentar durante a abertura das entradas de ar e diminuir durante o fechamento. Caso contrário, os cabos de alimentação do potenciômetro devem ser trocados entre si.
  Após a calibração correta, o controlador está pronto para funcionar no modo automático e controlará a posição do atuador. A aplicação de um sinal de controle com nível inferior a 1,5V faz com que as entradas de ar sejam ajustadas para a posição de emergência. 

## Utilização 

  O controlador das entradas de ar pode funcionar em um de dois modos: manual ou automático. O modo de funcionamento selecionado é memorizado e não é afetado pela perda de alimentação – ao restabelecer a alimentação, o controlador retorna ao último modo em que funcionou. O modo de funcionamento atualmente selecionado é indicado no visor:  
   - **MANUAL** - manter pressionado “+” ou “-” por um período prolongado ativa o modo manual. Neste modo, as entradas de ar são controladas manualmente pelos botões: “+” - abertura, “-” - fechamento.           
   - **AUTO**   - manter pressionado “Esc” por um período prolongado ativa o modo automático. Neste modo, as entradas de ar funcionam automaticamente, controladas pelo sinal 0-10V do conector In.

## Funções do menu básico  

| MENU                       | Descrição | 
|:---:                       |:---|
|MANUAL  STOP    POT 539  |  **“Modo informativo”** – do funcionamento manual. Informações apresentadas:  - **STOP** – atuador imobilizado;  - **OPEN** – abertura das entradas de ar após pressionar o botão “+”;  - **CLOSE** – fechamento das entradas de ar após pressionar o botão “-”;  - **POT 539** – parâmetro da posição atual do atuador determinado pelo potenciômetro.  •Transição para o modo de funcionamento automático ao manter pressionada a tecla “Esc”| 
|AUTO  20 % = In 3,70 POT 511       |  **“Modo informativo”**  do funcionamento automático. Informações apresentadas:    **20 %**  Valor da posição de abertura definida para as entradas de ar    **“=”**   entradas de ar na posição definida    **“–”**    fechamento das entradas de ar até a posição especificada    **“+”**    abertura das entradas de ar até a posição especificada    **In 3,70**  medição da tensão de controle nos terminais In     **POT 511**  parâmetro da posição atual do atuador determinado pelo potenciômetro.  Transição para o modo de funcionamento manual ao manter pressionada a tecla “+” ou “-” | 
|Aletas em emergência 30 %  |**“Aletas em emergência”** – definição do valor de abertura de emergência das aletas (entradas de ar) em caso de perda do sinal de controle. As entradas de ar abrirão até o nível definido em caso de falha do controlador ou do cabo de sinal.| 
|Calibração Abert 671 -> 311        |**“Calibração da abertura”** – a calibração da abertura das entradas de ar é realizada ajustando a abertura máxima (posição extrema) das entradas de ar por meio dos botões “+” e “-”. O primeiro valor apresentado representa o último ajuste salvo e o segundo valor representa a posição atual do atuador. A tecla “Ok” salva os ajustes introduzidos na memória; “Esc” sai do modo de calibração sem salvar.   | 
|Calibração Fech 281 -> 311      |**“Calibração do fechamento”** – a calibração do fechamento das entradas de ar é realizada ajustando a posição mínima das entradas de ar por meio dos botões “+” e “-”. O primeiro valor apresentado representa o último ajuste salvo e o segundo valor representa a posição atual do atuador. A tecla “Ok” salva os ajustes introduzidos na memória; “Esc” sai do modo de calibração sem salvar.|  
|Tempo de Média 5 s       |**“Tempo de cálculo da média”** – tempo de cálculo da média do sinal de controle do conector In, que protege contra oscilações na entrada de controle.  | 
|Inversão   Não |**“Inversão”** – a ativação desta função adapta o controlador ao sinal de controle 10-0V  | 
|Idioma   Polonês |**“Idioma”** – seleção do idioma do menu  | 
|Histerese Pot  5   | **“Histerese do potenciômetro”** – uma alteração do parâmetro de posição do atuador inferior ao valor definido não é considerada no posicionamento. O parâmetro tem a finalidade de eliminar movimentos muito pequenos do atuador e interferências provenientes do potenciômetro. | 
 

# Observações e advertências  

:::danger 
Durante a instalação do dispositivo, a alimentação elétrica deve ser obrigatoriamente desligada, pois a tensão em alguns componentes representa perigo para a vida e a saúde. Recomenda-se que a instalação seja realizada por uma pessoa qualificada.
:::

- Para evitar problemas na operação do dispositivo, é obrigatório ler as instruções antes de iniciar a instalação e a utilização. Não é permitido alterar a construção do dispositivo nem realizar reparos por conta própria. Isto se aplica especialmente a alterações de elementos e componentes.
- As operações de manutenção ou assistência técnica devem ser realizadas por pessoal autorizado (instalador ou assistência técnica da empresa). Nas instalações pecuárias com ventilação forçada, é obrigatório um sistema de alarme. 
- O fabricante do dispositivo não se responsabiliza por danos causados por instalação incorreta, programação incorreta das funções, consequências de eventos fortuitos ou fatores externos.
- O dispositivo exige que os parâmetros sejam ajustados de acordo com as condições existentes no recinto de criação de animais. Estes ajustes são individuais e dependem da decisão do criador. O fabricante do dispositivo reserva-se o direito de alterar a construção do dispositivo e o software.  


:::caution
![alt](./img/trash.svg) Após o fim da utilização do produto, este não deve ser descartado juntamente com resíduos urbanos não separados, mas sim eliminado de acordo com a legislação em vigor (diretivas WEEE da União Europeia 2012/19/UE).  O produto foi fabricado em conformidade com os requisitos RoHS (diretiva da União Europeia 2011/65/UE).
:::

<!-- \newpage -->
# Dados técnicos do controlador  

|Parâmetro                        |	DESCRIÇÃO      |
|:-----------                    |:---------- |
|Tensão de alimentação alternada|	230VAC 50Hz|
|Corrente máxima de saída|	2A|
|Filtro de supressão de interferências de saída|	RC|
|Impedância de entrada|	100kΩ|
|Proteção contra sobretensões nas entradas e saídas|	SIM|
|Alimentação do potenciômetro|	10VDC|
|Corrente máxima das saídas do potenciômetro|	30mA|
|Intervalo de temperatura de funcionamento|	-10 +40oC|
|Dimensões do dispositivo|	20x15x8 cm |
|Grau de proteção do invólucro|	IP65|

:::info
O controlador IC-AC inclui no conjunto:
- 4 buchas de expansão,
- 2 prensa-cabo PG11,
- 2 prensa-cabo PG9.
:::

