---
sidebar_position: 2
title: Manual SC-S
description: Controlador climático para alojamentos pecuários com corrente de saída
  admissível até 5A
keywords:
- eletor sc-s
- controlador de ventilação
- controlador climático
- controlador de ventilação de pocilgas
- controlador de microclima
- controlador para pocilgas
- ventilação de pocilgas
- controlador para instalações de recria
---


# Controlador SC-S

Controlador climático com microprocessador pertencente à família SPEED CONTROL. Controlador fiável, de instalação e utilização simples, com software em polaco, inglês, russo e alemão. O programa do controlador permite definir intuitivamente os parâmetros: temperaturas, renovação do ar, aquecimento suplementar, níveis mín./máx. de ventilação e alarmes.

**Parâmetros e características:**  
- Ventilação do grupo I:
  - corrente máx. da saída de regulação contínua 6A,
  - proteção térmica do circuito,
  - arranque suave da ventilação,
  - calibração da velocidade mínima de rotação
- Ventilação do grupo II, contacto isolado até 3A (1 opcional)
- Aquecimento suplementar, contacto isolado até 3A (1 opcional)
- Saídas de alarme NO e NC:
  - sinalização de falha de alimentação,
  - sinalização de ultrapassagem do limiar de temperatura mín. ou máx.
- 1 entrada analógica para medição da temperatura
- 2 saídas 0-10V
- Potência consumida pelo circuito < 3W
- Caixa hermética IP56
- Tensão de alimentação 230VAC 50Hz

## Instalação do controlador  
:::danger 
Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão presente em alguns componentes representa um perigo para a vida e a saúde.  
Recomenda-se que a instalação seja confiada a uma pessoa qualificada.
:::

### Escolha do local de montagem  

O local de montagem deve ser escolhido de forma criteriosa, tendo em conta a facilidade de acesso ao aparelho por pessoas autorizadas e a sua inacessibilidade a animais e crianças. Devem também ser consideradas as condições climáticas, ou seja, o dispositivo deve funcionar num intervalo de temperaturas de -10°C a 40°C, num local não exposto à luz solar direta. Deve existir livre circulação de ar à volta do dispositivo. O dispositivo inclui um sensor de temperatura. Aplicam-se as seguintes regras à montagem do sensor de temperatura:  
- o sensor não deve ser montado num local sem circulação de ar ou exposto à luz solar direta
- o sensor não deve ser montado numa parede estrutural (exterior) do edifício,
- evitar a proximidade de dispositivos que emitam calor, como aquecedores e lâmpadas,
- não colocar o sensor diretamente junto de portas e aberturas de ventilação,
- não colocar o sensor em locais acessíveis aos animais,
- recomenda-se que o cabo de ligação do sensor seja instalado longe dos cabos de alimentação.

### Montagem  

O dispositivo pode funcionar em condições climáticas adversas. Quando corretamente montados, o controlador e o sensor de temperatura são resistentes à ação do ambiente.
Durante a montagem, deve prestar-se atenção aos seguintes aspetos:  
- antes de apertar os parafusos, verificar a junta da tampa,
- a tampa deve ser apertada com todos os parafusos,
- os cabos utilizados para ligar o controlador devem ser redondos,
- após ligar o cabo, apertar os bucins de modo a vedar e imobilizar o cabo; recomenda-se a utilização de silicone,
- as passagens não utilizadas (bucins) devem ser obturadas,
- fixar o controlador (a parte inferior da caixa) a uma parede plana com 4 buchas de expansão.

## Ligação elétrica  

:::danger 
Antes de ligar o circuito, certificar-se de que a alimentação está desligada!
:::

Antes de proceder à ligação do controlador, desapertar os parafusos e retirar a tampa. Introduzir os cabos pelos bucins de borracha e proceder à sua ligação. Os terminais do controlador são apresentados na figura abaixo.

![Ligação](./img/Sc-s2.png)

**Ligar o conector AC 230V** à alimentação (quadro de distribuição). É obrigatória a utilização de um disjuntor de sobrecorrente 1P-B6 e de dispositivos de proteção contra sobretensões do tipo T1 T2. Uma boa prática ao ligar vários dispositivos consiste em agrupar os controladores em diferentes «fases» (L1, L2, L3), para distribuir uniformemente a carga da linha de alimentação.  
**O conector FAN** deve ser ligado diretamente ao ventilador; em caso de controlo de vários ventiladores, a carga total não pode exceder 6A, e cada ventilador deve ser protegido individualmente. Não se devem derivar PE e N da alimentação (quadro de distribuição); é obrigatório ligá-los aos terminais do controlador.  
**Conector FUNCTION** saída de relé isolada, a corrente máxima do contacto é de 6A (é obrigatório um disjuntor de sobrecorrente externo 1P-B6 em caso de controlo direto da carga),
pode ser utilizado como:  
- **Aquecimento suplementar** – o contacto fecha quando a temperatura medida desce abaixo do valor definido.  
- **Ventilação do grupo 2 ou de sistemas de aspersão** – o contacto fecha quando a temperatura medida é superior à soma da temperatura definida e da banda de ventilação.  o contacto fecha quando a temperatura medida é superior à soma da temperatura definida e da banda de ventilação.  

A figura abaixo apresenta o modo de ligação do ventilador do grupo 2 ou do aquecedor de ar.  

![Segundo grupo](./img/2grupa.png)

**O conector ALARM** dispõe de saídas isoladas NC, C e NO destinadas à ligação à central de alarme. O alarme é ativado nos seguintes casos:  
- a temperatura é demasiado baixa ou demasiado alta,
- o controlador ou o sensor de temperatura está danificado,
- ocorreu uma falha da tensão de alimentação do controlador;
- ocorreu um funcionamento incorreto do controlador (por exemplo, sobreaquecimento do controlador)  

![Alarme](./img/alarmsc-s.png)  

**O conector V1 0-10V** destina-se à ligação de módulos de expansão de potência ou de ventiladores com um circuito integrado de regulação da velocidade. A tensão neste terminal é proporcional ao nível de ventilação.  
**O conector V2 0-10V** destina-se à ligação do atuador que abre as comportas de entrada de ar.  
**Ligar o conector SENSOR** ao sensor de temperatura 1 TS3 ou TS5; a polaridade não é relevante.  Uma boa prática consiste em manter os cabos de medição afastados dos cabos de alimentação.  
**O conector RS-485** pode ser utilizado para construir sistemas de ventilação e para comunicação com um computador PC.  

## Princípio de funcionamento  

A principal função do controlador é manter a temperatura no alojamento pecuário ao nível definido pelo criador. Deve ter-se em conta que o controlador é apenas uma ferramenta que ajuda a assegurar condições climáticas ideais no alojamento pecuário. No entanto, o papel principal neste processo cabe ao criador, que deve ajustar as definições do dispositivo às condições climáticas variáveis no exterior e, sobretudo, às necessidades dos animais no edifício pecuário, bem como monitorizar o estado de funcionamento do dispositivo através da central de alarme.  

### Primeira colocação em funcionamento do controlador  

:::danger
Na primeira colocação em funcionamento do controlador, é obrigatório definir a banda proibida de funcionamento do motor.
:::

O controlador funciona com ventiladores equipados com um motor assíncrono monofásico, com um consumo total máximo de corrente de 5A. Após ligar os ventiladores escolhidos, o utilizador deve ajustá-los para funcionarem com o controlador. Por outras palavras, é necessário definir o nível mínimo de funcionamento (velocidade de rotação) do ventilador. Esta função denomina-se **«Banda proibida»** e é definida pelo utilizador uma única vez nas **«Definições avançadas»**. Para executar corretamente esta operação, recomenda-se a ajuda de uma segunda pessoa que possa observar continuamente o comportamento do ventilador enquanto a outra pessoa define o valor da **«Banda proibida»**. A ausência de definição da banda proibida pode provocar um funcionamento incorreto do dispositivo. O valor da **«Banda proibida»** pode ser considerado correto quando a pressão gerada pelo ventilador começar a levantar ligeiramente as comportas da chaminé de ventilação. A operação de definição da **«Banda proibida»** deve ser repetida quando o ventilador ligado ao controlador for substituído.  

### Renovação periódica do ar  

A renovação do ar é uma função executada pelo controlador que é ativada quando a temperatura no alojamento desce abaixo da temperatura definida. Esta função assegura aos animais um fornecimento cíclico de ar fresco. A renovação do ar é definida por 3 parâmetros:
- **«Tempo de funcionamento»** - determina durante quantos segundos o ventilador deve permanecer ligado,
- **«Tempo de pausa»** - determina o tempo, em segundos, durante o qual o ventilador permanece parado,
- **«Nível de renovação do ar»** - determina a potência de ventilação durante o «Tempo de funcionamento».  

Uma definição exemplificativa de **60s/120s** significa que o ventilador é ligado durante 60s, com uma pausa de 120s entre ligações sucessivas. 

Todos os parâmetros acima mencionados são definidos pelo utilizador. Ao definir os parâmetros de renovação do ar, devem observar-se algumas regras:
- a renovação do ar é ativada exclusivamente quando a temperatura na pocilga desce abaixo da temperatura definida,
- a função principal da renovação do ar é assegurar aos animais um fornecimento cíclico de ar fresco, e não manter a temperatura definida no alojamento,
- recomenda-se renovar o ar dos alojamentos durante períodos curtos, mas frequentes,
- devem evitar-se períodos prolongados de renovação do ar, pois podem provocar variações de temperatura excessivas,
- é obrigatório ajustar os parâmetros definidos ao comportamento dos animais e às condições existentes tanto no interior como no exterior do alojamento,
- é possível desativar a função de renovação do ar; nesta situação, tanto no modo percentual como no modo temporizado, devem definir-se valores nulos no campo correspondente ao tempo de renovação do ar, por exemplo: 0/120s  

### Ventilação de regulação contínua  

O controlador regula continuamente a ventilação desde a «Velocidade mínima de rotação» até à **«Velocidade máxima de rotação»** no intervalo entre a **«Temperatura definida»** e a soma da **«Temperatura definida»** e da **«Banda de ventilação»**. Acima deste intervalo, é ativado o grupo 2 de ventilação.  

![ventilação](./img/wentylacjia.png)  

Acima deste intervalo, é ativado o grupo 2 de ventilação, Se a temperatura no alojamento descer abaixo da **«Temperatura definida»**, o controlador renova periodicamente o ar do alojamento; se a temperatura continuar a descer, é ativado o aquecimento suplementar. Tudo depende das definições introduzidas pelo utilizador. O programa do controlador também contempla o funcionamento com uma central de alarme, que pode ser ativada quando a temperatura na pocilga se desvia dos parâmetros definidos.  

## Programação do controlador  

O controlador dispõe de um conjunto de definições predefinidas, que são gravadas na memória não volátil em dois casos:  
1. Primeira colocação em funcionamento do dispositivo,  
2. Erro na memória de dados.  
Em caso de ausência ou falha de alimentação, o controlador não perde as definições do utilizador anteriormente introduzidas e guardadas.  

### Utilização do menu  

O controlador está equipado com várias funções que permitem adaptá-lo à aplicação em questão. Estas funções estão agrupadas num menu, ao qual se acede premindo uma das teclas **(« Seta para a direita», «Seta para a esquerda»)**. Os parâmetros são alterados através das teclas **«+» e «-»**; o parâmetro editado será automaticamente guardado na memória não volátil após **30s** desde a última pressão de uma tecla.  

### Funções do menu básico  

| MENU                       | Descrição | 
|:---:                       |:---|
|Temperatura  <br />20,8°C W16% A  |**«Modo informativo»** - de funcionamento normal. O visor apresenta a temperatura atual e, quando o ventilador está em funcionamento, o valor do nível de ventilação. Significado dos símbolos adicionais: A-indica alarme ativado, D  - indica aquecimento ativado, W - indica ventilação adicional| 
|Temp. definida  <br />20,0°C        |**«Temperatura definida»** – valor de temperatura que determina o início do processo de ventilação de regulação contínua.   | 
|Renovação do ar  <br />20s / 200s  |**«Renovação do ar»** – são definidos dois valores de tempo 1 «Tempo de funcionamento», 2 «Tempo de pausa» entre ativações cíclicas sucessivas da ventilação.| 
|Nível renov. ar  <br />20%        |**«Nível de renovação do ar»** - nível de ventilação durante o funcionamento da renovação do ar   | 
|Alarme mínimo  <br />12,0°C       |**«Alarme mínimo»** - determina a temperatura mínima absoluta à qual o alarme será ativado. 
|Alarme máximo  <br />28,0°C       |**"Alarme máximo"** - determina a temperatura máxima absoluta à qual o alarme será ativado.  | 
|Aquecimento suplementar  <br />12,0°C         |Consoante a configuração, são executadas as funções: **«Aquecimento suplementar»** - o contacto fecha se a temperatura descer abaixo do valor indicado. | 
|Ventilação do estágio 2  <br />25,0  |**«Ventilação do estágio 2»** - o contacto fecha quando a temperatura medida excede a soma da temperatura definida e da banda de ventilação. | 
|Banda de ventilação  <br />5,0°C     |**«Banda de ventilação»** - determina a rapidez de resposta do controlador (alterações do nível de ventilação desde o mínimo 1 até ao máximo 1) ao aumento da temperatura. | 
|Velocidade mínima de rotação  <br />1%        |**«Velocidade mínima de rotação»** – é um estado no qual o dispositivo permanece por tempo indeterminado, fornecendo à saída uma tensão com o valor definido. Destina-se à calibração do dispositivo com o motor e o mecanismo das comportas.   | 
|Velocidade máxima de rotação  <br />100%      |**«Velocidade máxima de rotação»** – é um estado no qual o dispositivo permanece por tempo indeterminado, fornecendo à saída uma tensão com o valor definido. Destina-se a limitar a potência destinada à ventilação| 

### Menu avançado  

O menu avançado destina-se principalmente aos instaladores e permite adaptar o controlador à instalação e ao ventilador. Para aceder às definições avançadas, premir e manter premidas as duas teclas do menu durante aproximadamente 10s.  

| MENU                                 | Descrição| 
|:---:                                 |:--- |
|Sem definições  <br />avançadas   |Esta mensagem indica que o controlador não foi calibrado com a ventilação e que o seu funcionamento pode ser incorreto É necessário aceder ao menu avançado e definir a «Banda proibida».|
|Definições <br />Avançadas         |Sinalização de acesso às definições avançadas. | 
|Software Ver:  <br />1907       |Informação sobre a versão do software.| 
|Banda proibida  <br />1000 us       |Calibração da velocidade mínima de rotação dos ventiladores ligados diretamente ao controlador; este parâmetro corresponde ao nível de ventilação «1%»|  
|Função dos contactos  <br />Aquecimento suplementar     |Seleção da função dos contactos:  <br />• Aquecimento suplementar (predefinido)<br />• Grupo 2 de ventilação | 
|Renovação do ar  <br />Temporizada         |Seleção do tipo de renovação do ar: <br />• Temporizada (predefinida) <br />• Percentual| 
|Intervalo V1  <br />de 2,0 a 10,0       |Ajuste do intervalo de variação da tensão na saída V1 0÷10V. As definições referem-se aos valores mínimo e máximo da tensão. O ajuste é utilizado para adaptar o controlador à expansão de potência ou ao variador de frequência.| 
|Inversão V1  <br />Não                |A ativação inverte a característica da saída V1. A tensão diminuirá com o aumento do nível de ventilação no intervalo definido por mín.-máx. O sinal na saída V1 será do tipo 10-0V.| 
|Corte V1  <br />Não                |A ativação faz com que seja fornecido à saída  V1 0-10V o nível 0V, em vez do valor mínimo definido, quando o nível de ventilação for 0%.| 
|Intervalo V2  <br />de 2,0 a 10,0       |Ajuste do intervalo de variação da tensão na saída V2 0÷10V. As definições referem-se aos valores mínimo e máximo da tensão. O ajuste é utilizado para calibrar o sistema de comportas.|
|Inversão V2  <br />Não      	       |A ativação inverte a característica da saída V2. A tensão diminuirá com o aumento do nível de ventilação no intervalo definido por mín.-máx. O sinal na saída V2 será do tipo 10-0V.|
|Calibração temp  <br />21,0°C -> 22,0°C|A calibração do sensor de temperatura permite ajustar a escala do valor lido.|
|Arranque suave  <br />50%      	           |Definição do nível de ventilação em cada arranque do ventilador; o ventilador é acelerado até ao valor indicado e depois passa para o nível definido.| 
|Idioma  <br />Polaco    	           |Seleção do idioma do menu: polaco, inglês, alemão, russo|
|Sair                               |Saída do menu avançado através da tecla «+»; as alterações introduzidas serão guardadas na memória não volátil.|

### Mensagens de erro e de aviso  

As mensagens de erro destinam-se a informar o utilizador sobre irregularidades no funcionamento do controlador. As possíveis mensagens de erro são apresentadas abaixo.  

|ERRO                                    | DESCRIÇÃO |
|:---:                                   |:--- |
|Alarme  <br />de sobrecarga 	         |Alarme de sobrecarga, ativado a 75°C. O dispositivo suspende o funcionamento até arrefecer.|
|SENSOR EM CIRCUITO ABERTO!  <br />Verificar sensor|Sensor em circuito aberto, indica danos no sensor ou no cabo de ligação.|
|SENSOR EM CURTO-CIRCUITO!  <br />Verificar sensor  |Sensor em curto-circuito, indica danos no sensor ou no cabo de ligação.|
|Falha  <br />de alimentação                  |Falha de alimentação, tensão de alimentação demasiado baixa, frequência incorreta ou tensão de alimentação fortemente distorcida.| 

## Observações e avisos  

:::danger 
Durante a instalação do dispositivo, é obrigatório desligar a alimentação elétrica, pois a tensão presente em alguns componentes representa um perigo para a vida e a saúde. Recomenda-se que a instalação seja confiada a uma pessoa qualificada.
:::

- Para evitar problemas na utilização do dispositivo, é obrigatório ler o manual antes de proceder à instalação e utilização.  
- Não é permitido modificar a estrutura nem efetuar reparações por iniciativa própria. Isto aplica-se, em particular, a alterações de elementos e componentes.  
- As operações de manutenção ou assistência devem ser executadas por pessoal autorizado (instalador ou serviço de assistência do fabricante). Nos edifícios pecuários com ventilação forçada, é obrigatório um sistema de alarme. O fabricante do dispositivo não se responsabiliza por danos causados por instalação incorreta, programação incorreta das funções, consequências de acontecimentos fortuitos e fatores externos.  
- O controlador de ventilação exige a definição dos parâmetros de acordo com as condições existentes no alojamento pecuário. Estas definições são individuais e dependem da decisão do criador. O fabricante do dispositivo reserva-se o direito de efetuar alterações à estrutura do dispositivo e ao software.  


:::caution
![texto alternativo](./img/trash.svg) No final da vida útil do produto, este não deve ser eliminado juntamente com resíduos urbanos não triados, mas sim encaminhado para tratamento de acordo com a legislação em vigor (diretivas WEEE da União Europeia 2012/19/UE). <br />O produto foi fabricado de acordo com os requisitos RoHS (diretiva da União Europeia 2011/65/UE).
:::

<!-- \newpage -->
## Dados técnicos do controlador  

|Parâmetro                        |	DESCRIÇÃO      |
|:-----------                    |:---------- |
|Tensão de alimentação|	230VAC 50Hz|
|Corrente máxima da saída de regulação contínua FAN|	6A|
|Intervalo de regulação da tensão de saída|	70V ÷ (Uz-5)V|
|Corrente máxima da saída (contacto) ALARM|	3A|
|Corrente máxima da saída (contacto) FUNCTION|	3A|
|Intervalo de temperatura de funcionamento|	-20 +40oC|
|Intervalo de medição da temperatura|	0 +50°C|
|Resolução da medição da temperatura|	0,1°C|
|Deteção de avarias do sensor de temperatura|	SIM|
|Número máximo de sensores analógicos|	1|
|Precisão da medição da temperatura – entrada analógica|	1°C|
|Dependência da medição em relação à resistência dos cabos – entrada analógica|	15,8Ω/°C|
|Resistência a sobretensões (máx. E)|	210J|
|Proteção contra sobrecarga|	75°C|
|Dimensões do dispositivo|	20x15x8 [cm]|
|Grau de proteção da caixa|	IP56|
  


:::info
O controlador SPEED CONTROL SERVOMOTOR inclui no conjunto:
- 1 sensor de temperatura + acessórios,
- 4 buchas de expansão,
- 1 fusível 10A.
:::

