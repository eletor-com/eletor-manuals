---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Perguntas mais frequentes sobre seleção, configuração, diagnóstico e
  assistência técnica dos dispositivos ELETOR.
keywords:
- ELETOR
- FAQ
- controladores de ventilação
- reguladores
- ventiladores
- atuadores
- alarmes
- inversores de frequência
- assistência técnica
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Perguntas frequentes

O FAQ foi elaborado com base em uma análise anonimizada de conversas reais com utilizadores e clientes ELETOR. As respostas foram generalizadas para ajudar em casos típicos e não contêm dados de pessoas ou instalações específicas.

:::note Ambito do FAQ

As respostas referem-se a casos típicos. As designações dos terminais, as funções e a forma de ligação podem diferir entre modelos e versões de dispositivos. Em caso de dúvida, utilize a documentação adequada ao produto específico.

:::

:::warning Segurança

Execute os trabalhos na instalação elétrica em conformidade com a documentação do dispositivo e com as regras de segurança aplicáveis. Os trabalhos em tensão de rede devem ser realizados por uma pessoa com as qualificações adequadas.

:::

## Seleção do controlador e da potência

### Como selecionar o controlador para ventiladores?

A base da seleção é, прежде de tudo, a corrente total dos ventiladores, e não apenas a sua quantidade.

:::tip Prepare os dados antes da seleção

Quanto mais precisos forem os dados sobre os motores e sobre o modo de funcionamento da instalação, mais segura será a seleção do controlador.

:::

Antes da seleção, vale a pena preparar:

- o número de ventiladores,
- a tensão de alimentação,
- a potência ou a corrente nominal de cada ventilador,
- a informação se todos os ventiladores devem funcionar com regulação contínua,
- a informação se os ventiladores podem ser divididos em grupos,
- informações sobre dispositivos adicionais, por exemplo aquecedores ou entradas de ar.

O controlador não deve ser selecionado exatamente “no limite”. Deve ser mantida uma margem adequada em relação à carga máxima.

### Basta somar a potência dos ventiladores em watts?

A potência pode ser utilizada para uma estimativa preliminar, mas a seleção final deve basear-se na corrente nominal dos dispositivos e no caráter da carga.

Durante o arranque, o motor pode consumir mais corrente do que durante o funcionamento normal. Por esse motivo, dois conjuntos de ventiladores com potência nominal semelhante nem sempre representam uma carga equivalente para o controlador.

### Tenho vários ventiladores pequenos. Posso ligá-los em paralelo a uma única saída?

Sim, se:

- forem destinados a esse tipo de controlo,
- tiverem de funcionar em conjunto,
- a soma das cargas não exceder a corrente admissível da saída,
- o método de ligação estiver em conformidade com a documentação do controlador.

No caso de um número maior de ventiladores, vale a pena considerar a divisão em grupos ou a utilização de uma expansão de potência.

### Quando é necessária uma expansão de potência?

A expansão de potência é utilizada quando a carga excede a capacidade da saída do controlador ou quando a instalação deve ser ampliada com um maior número de ventiladores.

Nesse caso, o controlador fornece o sinal de controlo, enquanto a carga propriamente dita é tratada por um módulo adicional.

### A instalação pode ser posteriormente ampliada com ventiladores adicionais?

Em muitas instalações, sim. O mais frequente é utilizar:

- uma expansão de potência adicional,
- um grupo de ventilação adicional,
- um contactor para ligar o grupo seguinte,
- um inversor de frequência no caso de motores trifásicos.

É melhor prever a ampliação planeada já durante a primeira seleção do controlador.

### Todos os ventiladores têm de funcionar com regulação contínua?

Não. Duas soluções típicas são:

1. todos os ventiladores funcionam com regulação contínua,
2. o primeiro grupo funciona com regulação contínua, e os grupos seguintes são ligados gradualmente, por exemplo por meio de contactores.

A segunda solução permite operar uma instalação maior sem regulação contínua de cada ventilador.

### Tenho 10 ventiladores. Preciso de um controlador muito grande?

Nem sempre. Podem ser aplicados vários métodos de controlo:

- divisão em grupos,
- expansões de potência,
- contactores,
- inversor de frequência.

A seleção final depende dos parâmetros elétricos dos ventiladores e do facto de todos terem de variar a rotação ao mesmo tempo.

### O controlador 6 A e 12 A diferem apenas na carga admissível?

Não se deve presumir que a única diferença é o valor da corrente. As diferentes versões e gerações de dispositivos podem diferir em termos de equipamento ou de forma de execução.

Ao substituir um dispositivo, é necessário verificar o modelo exato e a documentação atual.


## Ventiladores e controlo da ventilação

### O controlador regula os ventiladores de forma contínua?

Nos controladores destinados à regulação contínua da ventilação, a velocidade dos ventiladores é alterada em função da necessidade resultante, entre outros fatores, da temperatura.

No entanto, é necessário verificar se o tipo de motor em causa é adequado ao método de regulação utilizado.

### O que significa temperatura de referência?

A temperatura de referência é o valor ao qual o controlador relaciona a medição atual da temperatura.

Com base nela, o controlador aumenta ou diminui a intensidade da ventilação de acordo com as restantes definições, por exemplo banda de regulação, nível mínimo e máximo.

### O que significa nível mínimo de ventilação?

É o valor mínimo de controlo do ventilador durante o funcionamento automático.

Esta definição impede o funcionamento abaixo do nível em que o ventilador poderia operar de forma instável ou assegurar uma renovação de ar demasiado baixa.

### O que significa nível máximo de ventilação?

É o limite superior do valor de controlo da ventilação.

Por exemplo, a definição de um valor inferior a 100% pode limitar a rotação máxima do ventilador, se a instalação assim o exigir.

### O que significa banda de ventilação?

A banda de ventilação define a gama de temperaturas em que o controlador passa do nível mínimo para o nível máximo de ventilação.

Quanto menor for a banda, mais rapidamente o controlo reage ao aumento da temperatura com o aumento do desempenho.

### Após o arranque, o ventilador vai primeiro para 100% e só depois desacelera. Porquê?

A função de arranque pode estar ativa, cuja finalidade é pôr momentaneamente o motor em funcionamento com maior potência.

Consoante a versão do controlador, devem ser verificadas as definições relacionadas com:

- a função Soft Start,
- o tempo de aceleração,
- o tempo de funcionamento em 100%,
- o tempo de desaceleração.

Se a função não for necessária na instalação em questão, os parâmetros adequados podem ser alterados de acordo com o manual do dispositivo.

### Para que serve o facto de o ventilador poder ser momentaneamente arrancado com potência total?

Esse arranque pode ajudar a garantir o acionamento do ventilador e é útil em instalações em que os elementos mecânicos podem oferecer maior resistência durante o arranque.

No entanto, isso não é necessário em todas as instalações.

### O que significam tempo de aceleração e tempo de desaceleração?

**Tempo de aceleração** define a forma de aumento do controlo durante o arranque do ventilador.

**Tempo de desaceleração** define a forma de redução da velocidade.

Ambos os parâmetros permitem limitar mudanças bruscas na rotação e no funcionamento da instalação.

### Por que dois controladores idênticos podem arrancar os ventiladores de forma diferente?

A causa mais frequente são definições diferentes.

Vale a pena comparar прежде de tudo:

- a temperatura de referência,
- a banda de ventilação,
- o mínimo e o máximo,
- as definições do Soft Start,
- os tempos de aceleração e desaceleração,
- a configuração dos grupos de ventilação.

### O controlador pode acionar periodicamente a ventilação independentemente da temperatura?

Consoante o modelo, está disponível a função de ventilação periódica.

Ela pode acionar a ventilação durante um tempo definido em intervalos estabelecidos, mesmo quando a regulação de temperatura não exige aumento da ventilação.

### Para que servem os grupos de ventilação?

Os grupos permitem aumentar gradualmente o desempenho da instalação.

Por exemplo:

- o grupo 1 funciona com regulação contínua,
- o grupo 2 aciona os ventiladores seguintes,
- o grupo seguinte é acionado com uma necessidade ainda maior.

Isto permite controlar um grande número de ventiladores sem regulação contínua de cada um deles.

### Um grupo adicional de ventiladores pode ser ligado através de um contactor?

Sim. A saída a relé do controlador pode comandar a bobina de um contactor adequadamente selecionado.

Nesse caso, a carga dos ventiladores não deve ser conduzida diretamente através do pequeno contacto de comando.

### O que significa o símbolo do ventilador ou o indicador amarelo no controlador?

Consoante o modelo, os indicadores informam sobre o estado atual das saídas e das funções.

A sinalização amarela pode significar uma função de trabalho ativa, por exemplo funcionamento da ventilação, aquecimento ou do grupo seguinte.

O significado exato deve ser verificado no manual do modelo em questão.

### O que significa o símbolo do modo manual?

O modo manual significa que o valor de controlo foi forçado pelo utilizador e, naquele momento, não é calculado automaticamente com base na temperatura.

Após a conclusão dos testes, é necessário certificar-se de que o controlador foi reposto no modo automático correto.


## Entradas de ar e atuadores

### O controlador pode controlar entradas de ar?

Sim, determinados controladores permitem a cooperação com acionamentos de entradas de ar.

O método de ligação depende do tipo de atuador e da forma do seu controlo.

### Que tipos de atuadores podem ser utilizados para entradas?

Nas conversas técnicas, surgiram com maior frequência duas soluções:

- atuador controlado por sinal analógico 0–10 V ou 2–10 V,
- atuador reversível abrir/fechar com sinal de realimentação, por exemplo de um potenciómetro.

Antes da compra, deve ser verificada a compatibilidade do modelo específico com o controlador disponível.

### A tensão de alimentação do atuador 24 V ou 230 V é importante para o sinal 0–10 V?

O sinal de controlo e a alimentação do atuador são parâmetros distintos.

O atuador pode ser alimentado com uma tensão diferente da tensão do sinal de controlo. Ambos os parâmetros devem estar em conformidade com a documentação do atuador e do controlador.

### O que significa controlo 0–10 V?

O controlador envia um sinal analógico de tensão que representa a posição desejada ou o nível de controlo.

Numa aplicação típica, um valor mais baixo significa menor abertura e um valor mais alto maior abertura, mas a característica real deve ser verificada na documentação do atuador.

### Em que difere 0–10 V de 2–10 V?

Em ambos os casos, a posição é definida por um sinal analógico.

No padrão 2–10 V, a parte inferior da gama é deslocada e pode permitir ao dispositivo distinguir o sinal de controlo da sua ausência.

O controlador e o atuador devem suportar uma gama compatível.

### Como selecionar o atuador em função do número de entradas?

O atuador não deve ser selecionado apenas com base no número de comportas.

É necessário ter em conta:

- a força ou o binário exigidos,
- o comprimento e a forma de condução do mecanismo,
- as resistências das comportas,
- o comprimento do curso,
- a velocidade de atuação,
- a tensão de alimentação,
- o tipo de controlo,
- a realimentação exigida.

### Um único atuador pode operar várias comportas?

Sim, se a mecânica da instalação permitir unir as comportas por um sistema comum e se o binário ou a força exigidos não excederem a capacidade do atuador.

Na prática, a seleção é determinada pelas resistências de todo o mecanismo, e não apenas pelo número de comportas.

### Vários atuadores podem ser ligados em paralelo e controlados por um único sinal?

Em alguns sistemas isso é possível, mas é necessário verificar a documentação dos atuadores e a carga admissível da saída de controlo.

No caso de acionamentos reversíveis sem realimentação independente, também pode ocorrer uma desincronização gradual das posições dos atuadores individuais.

### Por que vários atuadores podem, com o tempo, posicionar-se em posições diferentes?

Mesmo motores idênticos podem operar com velocidades ligeiramente diferentes devido a:

- carga diferente,
- resistências mecânicas,
- tolerância dos parâmetros do motor,
- diferenças da transmissão.

Por isso, quando é necessária sincronização precisa, é indispensável a realimentação adequada ou o controlo individual da posição.

### As entradas podem ser controladas proporcionalmente à ventilação?

Sim. Em sistemas corretamente configurados, a posição das entradas pode ser associada ao nível atual de ventilação.

Dessa forma, à medida que o desempenho dos ventiladores aumenta, a abertura das entradas também é aumentada.

### O atuador 24 V requer uma fonte de alimentação separada?

Se o controlador não dispuser de uma saída de alimentação adequada com a potência exigida, é necessária uma fonte de alimentação separada.

A sua potência deve ser selecionada de acordo com o consumo de corrente do atuador e dos outros dispositivos alimentados pela mesma fonte.

### É possível utilizar um atuador de outra marca?

Muitas vezes, sim, se os seus parâmetros elétricos e o método de controlo forem compatíveis com as saídas do controlador.

Antes da ligação, é necessário verificar:

- a tensão,
- o tipo de sinal,
- o esquema dos condutores,
- os sentidos de funcionamento,
- o sinal de posição,
- a carga admissível.


## Sensores de temperatura e humidade

### Onde ligar o sensor de temperatura?

O sensor deve ser ligado à entrada de sensor prevista pelo fabricante, à entrada de sensor indicada na documentação do modelo em questão.

Não se deve presumir que as designações dos terminais sejam idênticas em todas as versões dos dispositivos.

### O sensor de temperatura mostra um valor diferente do termómetro de referência. O que fazer?

Se o controlador possuir a função de calibração do sensor, a indicação pode ser corrigida após comparação com um termómetro de referência fiável.

Antes de alterar a calibração, vale a pena certificar-se de que:

- ambos os sensores se encontram no mesmo local,
- a medição estabilizou,
- o sensor não é aquecido pelo sol ou por dispositivos,
- ele não está diretamente no fluxo de ar frio ou quente.

### O sensor de humidade mostra um valor incorreto. É possível calibrá-lo?

Depende da versão do controlador, do sensor e do software.

Em algumas soluções, a correção pode exigir uma função de software adequada ou um tipo de sensor compatível. Se a diferença for grande e repetitiva, deve ser verificada a versão do dispositivo e deve ser contactado o suporte técnico.

### Uma medição incorreta significa sempre que o sensor está avariado?

Não.

A causa também pode ser:

- a localização incorreta do sensor,
- o cabo,
- a ligação elétrica,
- a configuração,
- um tipo incorreto de sensor,
- a necessidade de calibração,
- humidade ou corrosão.


## Alarmes e notificações

### Pode-se ligar diretamente uma sirene à saída de alarme do controlador?

Não se deve presumir isso.

A saída de alarme do controlador é geralmente uma saída de comando ou um contacto de relé. A sirene pode exigir uma alimentação separada e uma central de alarme.

### Para que se utiliza uma central de alarme?

A central pode:

- receber sinais de alarme dos controladores,
- alimentar o sinalizador,
- manter o funcionamento durante a falha de alimentação,
- sinalizar o alarme por som ou luz,
- enviar notificações GSM nas versões que dispõem dessa função.

### A central pode alarmar sobre a falha de alimentação do controlador?

Sim, se o sistema tiver sido ligado corretamente.

A solução pode detetar não apenas a ultrapassagem da temperatura, mas também a perda do sinal do controlador causada pela falha da sua alimentação.

### Onde se definem as temperaturas mínima e máxima de alarme?

Numa configuração típica, os limiares de alarme são definidos no controlador que atende a determinada câmara ou compartimento.

A central de alarme recebe então a informação de que o controlador sinalizou um alarme.

### A central GSM necessita de um cartão SIM?

Para enviar chamadas e mensagens pela rede móvel, é necessário um cartão SIM ativo ou outra solução de comunicação prevista no modelo em questão.

Sem uma ligação ativa à rede móvel, as funções telefónicas e SMS não funcionarão.

### O alarme pode enviar a informação de qual controlador originou o evento?

Num sistema devidamente configurado, sim.

As entradas da central podem ser atribuídas a compartimentos ou controladores específicos, pelo que a mensagem permite determinar a origem do alarme.

### Quantos controladores podem ser ligados a uma única central de alarme?

Isso depende do modelo da central.

Nas transcrições apareceram centrais que suportavam até oito entradas; contudo, antes de executar a instalação, deve ser verificada a especificação atual do dispositivo concreto.

### Que bateria é utilizada na central de alarme?

Em parte dos dispositivos discutidos nas conversas, era utilizada uma bateria 12 V 7 Ah.

Antes de adquirir um substituto, deve ser verificada a designação na bateria existente e a especificação da central, porque outras versões de dispositivos podem exigir uma bateria diferente.

### A central envia mensagens de baixa tensão. O que verificar?

Em primeiro lugar, deve ser verificado:

- o estado da bateria,
- a sua idade,
- as ligações da bateria,
- a presença de alimentação da rede,
- o funcionamento do carregador ou da fonte de alimentação da central.

Uma bateria desgastada pode provocar mensagens cíclicas de baixa tensão.

### Com que frequência se deve substituir a bateria na central de alarme?

Não existe um valor único adequado para todas as condições.

A bateria deve ser testada periodicamente, especialmente em instalações em que o alarme durante a falha de alimentação tem importância crítica. Com o tempo, a sua capacidade real diminui.

### Apenas a sirene é suficiente como proteção?

A sirene só funciona quando alguém a pode ouvir.

Em instalações que permanecem temporariamente sem supervisão, vale a pena utilizar também notificação remota e alimentação de reserva por bateria.


## Inversores de frequência

### Como selecionar um inversor de frequência para ventiladores?

É necessário conhecer:

- a tensão de alimentação,
- o número de fases,
- a potência e a corrente de todos os motores,
- a forma da sua ligação,
- as condições de funcionamento,
- o método de controlo exigido.

O inversor de frequência deve ter uma margem adequada em relação à carga, especialmente quando vários motores trabalham em paralelo.

### O inversor de frequência deve ter exatamente a mesma potência que a soma das potências dos motores?

O inversor de frequência não deve ser selecionado apenas com base na simples soma das potências nem se deve escolher um dispositivo que trabalhe exatamente no limite dos parâmetros.

É necessário ter em conta as correntes nominais, o caráter da carga e as recomendações do fabricante do inversor de frequência.

### O inversor de frequência parou os ventiladores e exibiu um erro. O que fazer?

O mais importante é registar o código completo do erro antes do reset.

:::tip Tire uma fotografia do ecrã

Se a situação o permitir, antes do reset tire uma fotografia do visor. O código completo do erro facilita significativamente o diagnóstico.

:::

Só o início da mensagem muitas vezes não basta para determinar a causa. O código completo permite distinguir, entre outros:

- sobrecarga,
- excesso de corrente,
- sobreaquecimento,
- tensão incorreta,
- outros erros do acionamento.

### É possível simplesmente fazer reset ao erro do inversor de frequência?

O reset pode restabelecer o funcionamento, mas não elimina a causa do alarme.

Após o evento, deve ser verificado o código do erro e determinada a causa antes de voltar a colocar a instalação em funcionamento prolongado.

### O inversor de frequência funciona num compartimento com poeira. É necessário limpá-lo?

Sim.

Poeira e depósitos no dissipador de calor ou no ventilador de arrefecimento podem piorar a dissipação de calor e levar ao sobreaquecimento do inversor de frequência.

A limpeza deve ser realizada de acordo com as instruções do fabricante, após desligar a alimentação em segurança.

### O que pode causar o sobreaquecimento do inversor de frequência?

As causas mais frequentes são:

- elementos de arrefecimento sujos,
- fluxo de ar obstruído,
- temperatura ambiente demasiado elevada,
- sobrecarga,
- avaria do ventilador de arrefecimento,
- montagem incorreta.

### A tensão elevada da rede pode provocar um alarme do inversor de frequência?

Sim. Os inversores de frequência monitorizam a tensão do circuito de alimentação e podem sinalizar erro após a ultrapassagem do nível admissível.

Se o problema se repetir, a instalação e a qualidade da alimentação devem ser verificadas.


## Avarias e diagnóstico

### O controlador funciona, mas o visor não mostra nada. Qual pode ser a causa?

As causas possíveis incluem, entre outras:

- avaria do visor,
- problema com a regulação do contraste em soluções mais antigas,
- avaria da ligação,
- corrosão,
- avaria da placa principal.

Se o dispositivo não tiver sido utilizado durante muito tempo ou tiver funcionado num ambiente húmido, vale a pena verificar também o estado da placa.

### Após vários anos sem utilização, o controlador apresenta problema no visor. Porquê?

Uma paragem prolongada num ambiente húmido ou agressivo pode levar a:

- oxidação dos conectores,
- corrosão,
- deterioração dos contactos,
- danos em componentes eletrónicos.

Nesse caso, vale a pena realizar uma inspeção completa, em vez de substituir elementos sem diagnóstico prévio.

### O controlador está escurecido por fuligem após uma sobretensão. Isso significa que a placa tem de ser substituída?

Nem sempre.

Um componente de proteção pode sofrer danos e deixar muitos resíduos, embora o restante da placa ainda possa ser reparado.

No entanto, se o laminado estiver carbonizado, queimado ou se as pistas estiverem danificadas, a reparação pode ser antieconómica ou pouco duradoura.

### O que pode danificar vários controladores ao mesmo tempo?

Se muitos dispositivos falharem ao mesmo tempo, a instalação de alimentação deve ser verificada.

Uma das causas possíveis é um problema no condutor neutro que, numa instalação trifásica, pode levar ao aparecimento de tensões incorretas em cargas monofásicas.

Também são possíveis sobretensões provenientes da rede ou de um gerador.

### O que fazer após uma avaria relacionada com sobretensão?

Antes de ligar um controlador reparado ou novo, deve ser determinada a causa do problema.

:::danger Não volte a ligar o dispositivo sem verificar a instalação

Se a causa da avaria tiver sido tensão incorreta, condutor neutro danificado ou sobretensão, o controlador reparado ou novo pode voltar a ser danificado.

:::

### O que é o componente de proteção contra sobretensão na placa?

Em dispositivos eletrónicos são utilizados componentes limitadores de sobretensão, por exemplo varistores.

A sua função é absorver parte da energia da sobretensão e proteger os circuitos subsequentes. Após um evento severo, esse componente pode sofrer dano permanente.

### É possível colocar o dispositivo em funcionamento após remover o componente de proteção queimado?

Isso não deve ser tratado como uma reparação normal.

Após a remoção da proteção, o dispositivo pode perder a proteção contra uma nova sobretensão. Tais ações só podem ser realizadas como procedimento de assistência técnica consciente por uma pessoa com as qualificações adequadas e após a eliminação da causa primária da avaria.

### O controlador foi inundado ou sofreu forte corrosão. Vale a pena repará-lo?

Isso depende do grau dos danos.

Corrosão superficial e danos isolados muitas vezes podem ser removidos. Se a corrosão tiver atingido as pistas, os conectores e muitos componentes, a reparação pode ser morosa, incerta e economicamente injustificada.

### A lavagem do dispositivo com pressão pode danificar o controlador?

Sim.

A eletrónica não deve ser exposta diretamente à água nem a agente de limpeza, se o invólucro e o método de montagem não forem destinados a isso.

A humidade que penetra no interior pode levar à corrosão e a falhas posteriores difíceis de diagnosticar.

### Por que as falhas após inundação podem voltar após a reparação?

A corrosão pode progredir também em locais não visíveis durante a primeira inspeção.

Vias, pistas e ligações danificadas podem funcionar durante o teste e, mais tarde, voltar a perder contacto.

Por isso, no caso de uma placa fortemente corroída, a assistência técnica pode recomendar a substituição em vez de novas reparações.

### O dispositivo às vezes funciona e às vezes não. Por onde começar?

Vale a pena reunir, antes do contacto com a assistência técnica:

- o modelo exato,
- a descrição do sintoma,
- o momento da ocorrência,
- os valores mostrados no ecrã,
- o código de alarme ou erro,
- informações sobre as últimas alterações na instalação,
- uma fotografia do interior e dos terminais, se puder ser tirada em segurança.

Quanto mais precisa for a descrição, mais fácil será o diagnóstico.


## Assistência técnica e reparações

### O que enviar para a assistência técnica, se o controlador estiver avariado?

O ideal é enviar um conjunto que permita reproduzir o problema.

Deve ser anexada à remessa uma breve descrição:

- do que não funciona,
- de quando o problema aparece,
- se a avaria é permanente ou periódica,
- se antes da avaria ocorreu sobretensão, inundação ou outro evento,
- os dados necessários para contacto e devolução do dispositivo.

:::note Dados para o pedido de assistência técnica

Transmita os dados de contacto e de envio diretamente à assistência técnica. Não os publique em pedidos abertos nem em materiais públicos.

:::

### É necessário enviar o controlador completo ou apenas a placa?

Depende da avaria.

Em caso de problemas com o visor, botões, alimentação ou comportamento ambíguo, o melhor é enviar o conjunto completo necessário para reproduzir o sintoma.

No caso de reparação previamente acordada de um módulo específico, a assistência técnica pode solicitar apenas a placa.

### A ELETOR repara os controladores em vez de os substituir imediatamente?

Das transcrições resulta que os dispositivos são primeiro diagnosticados.

Se a reparação for possível e fizer sentido, são substituídos os componentes ou módulos danificados. Em caso de dano grave, a assistência técnica pode propor a substituição da placa ou de todo o dispositivo.

### O que acontece se a placa danificada não puder ser reparada?

É possível substituir o módulo danificado por um novo, desde que a peça adequada esteja disponível e seja compatível com o dispositivo.

Nos dispositivos mais antigos, a assistência técnica deve קודם verificar a compatibilidade da versão.

### Vale a pena comprar imediatamente uma placa nova após uma sobretensão?

Nem sempre.

Se o dano disser respeito ao componente de proteção ou a uma pequena parte do circuito, a reparação pode ser justificada. Vale a pena realizar primeiro o diagnóstico.

### A assistência técnica também pode verificar o visor e os botões?

Sim, se os elementos forem entregues juntamente com o dispositivo ou módulo.

Isto é particularmente útil quando não se sabe se o problema se encontra na placa principal ou no painel do utilizador.

### Vale sempre a pena salvar um controlador fortemente corroído?

Não.

Se o custo do diagnóstico e da reparação aumentar e a fiabilidade após a reparação continuar incerta, a substituição pode ser mais sensata.

Isto aplica-se especialmente a dispositivos dos quais depende a ventilação da instalação.

### Como acelerar o diagnóstico da assistência técnica?

Anexe uma descrição precisa do sintoma em vez da simples afirmação “não funciona”.

Também são úteis:

- fotografias,
- o código do erro,
- a descrição da instalação,
- o tipo de cargas ligadas,
- a informação sobre sobretensão ou falha de alimentação,
- a informação sobre inundação ou lavagem do dispositivo.


## Instalação e cablagem

### Como ligar dispositivos aos terminais de relé C e NO?

C e NO são designações típicas de contacto de relé:

- C — contacto comum,
- NO — contacto normalmente aberto.

A forma de utilização depende do dispositivo e do esquema da instalação. O contacto pode ser utilizado, por exemplo, para comandar a bobina de um contactor, mas os seus parâmetros admissíveis não podem ser excedidos.

:::warning Trabalhos elétricos

As ligações à tensão de rede devem ser realizadas por uma pessoa com as qualificações adequadas, de acordo com o esquema do dispositivo específico.

:::

### A saída de relé pode alimentar diretamente um ventilador grande?

Geralmente, essa não é uma aplicação adequada para uma pequena saída de comando.

Para cargas maiores, utiliza-se um contactor, um relé de potência ou um módulo de atuação dedicado.

### Para que servem os terminais A1 e A2 do contactor?

São os terminais da bobina do contactor.

Ao aplicar a tensão adequada à bobina, o contactor altera o estado dos seus contactos de potência.

A tensão da bobina deve estar em conformidade com o projeto da instalação e com a documentação do contactor.

### É possível montar aparelhos adicionais no interior do invólucro do controlador?

Só quando a construção do invólucro específico o permite e isso não piora:

- o grau de proteção,
- o isolamento,
- o arrefecimento,
- a segurança,
- o acesso para assistência técnica.

Quaisquer novos furos devem ser executados de forma a manter a estanquidade exigida.

### Os interruptores adicionais dos ventiladores são úteis?

Podem facilitar a assistência técnica e permitir a desconexão independente de ventiladores específicos.

No entanto, a forma de execução deve ter em conta as proteções elétricas e não pode provocar estados perigosos do controlador.

### Os cabos de controlo podem ser instalados juntamente com os cabos de potência?

Deve evitar-se a passagem de cabos de sinal sensíveis em paralelo e muito próximos de cabos de grande potência, especialmente em troços longos.

Os requisitos dependem do tipo de sinal e do ambiente eletromagnético.

### Que cabo deve ser utilizado para ligações de rede e dispositivos PoE?

Nas instalações discutidas, era indicado como mínimo cabo de par trançado da categoria 5e.

Se o cabo passar por um ambiente com nível elevado de interferências ou risco de cargas eletrostáticas, pode ser justificável utilizar um cabo devidamente blindado e um sistema de aterramento correto.

### Para PoE é necessário um cabo cruzado?

Em instalações típicas, utiliza-se uma ligação direta padrão.

Contudo, é sempre necessário verificar os requisitos do dispositivo de rede e da fonte de alimentação PoE utilizada.


## Operação e manutenção

### Como reduzir o risco de avaria dos controladores em edifícios agropecuários?

O mais importante é limitar a influência de:

- humidade,
- amónia e ambiente agressivo,
- poeira,
- lavagem direta com água,
- sobretensões,
- alimentação incorreta.

Vale também a pena controlar periodicamente o estado dos cabos, ligações e invólucros.

### Os dispositivos eletrónicos devem ser limpos regularmente?

Sim, especialmente os dispositivos equipados com dissipadores de calor, ventiladores e aberturas de ventilação.

A acumulação de poeira prejudica o arrefecimento.

A limpeza deve ser realizada após desligar a alimentação e de acordo com o manual do dispositivo.

### Após alguns anos de funcionamento, vale a pena fazer uma inspeção do controlador?

Sim, especialmente em condições ambientais difíceis.

A inspeção pode incluir:

- avaliação do estado dos conectores,
- controlo de vestígios de humidade e corrosão,
- verificação dos elementos de arrefecimento,
- verificação do painel e dos botões,
- teste dos sensores,
- controlo das baterias nos sistemas de alarme.

### O que vale a pena registar após a ocorrência de uma avaria?

Os elementos mais úteis são:

- a mensagem completa,
- o código do erro,
- a hora do evento,
- a temperatura,
- o estado da ventilação,
- a informação sobre falha de alimentação,
- a informação sobre funcionamento do gerador,
- uma fotografia do ecrã ou do dispositivo.

Não se deve fazer reset ao dispositivo antes de registar o código, se a situação permitir fazê-lo em segurança.

### Vale a pena ter um alarme independente do controlador de ventilação?

Sim, especialmente onde uma falha da ventilação possa rapidamente levar a condições perigosas.

Uma central independente com a sua própria bateria e notificação remota proporciona uma camada adicional de proteção.

### Que informações preparar antes de contactar o suporte técnico?

O melhor é preparar:

1. o modelo exato do dispositivo,
2. a descrição da instalação,
3. o número e os parâmetros dos dispositivos ligados,
4. as definições atuais relacionadas com o problema,
5. o sintoma exato,
6. o código completo do erro ou do alarme,
7. fotografias do dispositivo e das placas de identificação,
8. a informação sobre as últimas alterações na instalação.

Isto permite encurtar significativamente o diagnóstico.


## Observação importante relativa a dispositivos mais antigos

Os nomes, as designações dos terminais e as funções disponíveis podem diferir entre versões de dispositivos fabricadas em anos diferentes.

Se o dispositivo tiver vários ou uma dezena de anos, antes de utilizar a instrução de um modelo mais recente, deve ser confirmado:

- a designação exata do dispositivo,
- a versão da placa,
- o tipo de visor,
- a versão do software,
- o esquema dos terminais.

:::warning Versões mais antigas de dispositivos

Não presuma plena compatibilidade apenas com base numa aparência semelhante do invólucro. Antes de utilizar um esquema ou manual, confirme o modelo exato e a versão do dispositivo.

:::


## Contacto com o suporte técnico

Se o FAQ não resolver o problema, prepare antes do contacto:

- uma fotografia do controlador,
- uma fotografia da placa de identificação da carga,
- os parâmetros dos motores ou atuadores,
- o esquema de ligações,
- uma descrição exata do modo de funcionamento esperado.

Isso permite que a seleção do dispositivo ou o diagnóstico do problema sejam realizados com base nos parâmetros reais da instalação, e não em suposições.
