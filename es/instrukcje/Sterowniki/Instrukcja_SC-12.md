---
sidebar_position: 3
title: Manual SC-12
description: Controlador de clima para recintos ganaderos con una corriente de salida
  admisible de hasta 12A
keywords:
- eletor sc-12
- controlador de ventilación
- controlador de clima
- controlador de ventilación de porquerizas
- controlador de microclima
- controlador para porquerizas
- ventilación de porquerizas
- controlador para recintos de recría
---

# Controlador SC-12

Controlador de clima con microprocesador perteneciente a la serie SPEED CONTROL. La versatilidad del dispositivo está garantizada por la gran cantidad de entradas/salidas del sistema y por el software intuitivo en polaco e inglés. El programa del controlador, además de los ajustes básicos de temperaturas, aireación, calefacción auxiliar, niveles mín./máx. de ventilación y alarmas, permite realizar pruebas y guardar la calibración de los actuadores que funcionan con el controlador.

**Parámetros y características:** 
- Ventilación del grupo I: 
  - corriente máx. de la salida de regulación continua 12A,
  - protección térmica del sistema, 
  - arranque suave de la ventilación – arranque progresivo,
  - relé de derivación con activación plena, 
  - calibración de la velocidad mínima de giro, 
  - programa de ahorro de energía con sistema de compuertas de apertura anticipada.
- Ventilación del grupo II, contacto aislado hasta 6A.
- Calefacción auxiliar, contacto aislado hasta 6A
- Salidas de alarma NO y NC: 
  - señalización de pérdida de alimentación,
  - señalización de superación del umbral de temperatura mín. o máx.,
  - avisador acústico integrado.
- 3 salidas independientes 0..10V:
  - funcionamiento con módulos de expansión,
  - control del sistema de compuertas, 
  - regulación de calefacción de potencia variable.**
- Dos entradas analógicas para medir la temperatura.
- Puerto digital para medir la temperatura (hasta 4 sensores).
- Dos salidas de relé funcionales (seleccionables):
  - funcionamiento con actuadores lineales, 
  - III y IV grupo de ventilación
- Dos entradas analógicas 0-10V.
- Alimentación para el potenciómetro DC 10V.
- Alimentación adicional DC 12V.
- Posibilidad de funcionamiento con un ordenador hasta 1200m.
- Carcasa hermética IP65.
- Tensión de alimentación 230VAC 50Hz.
- Potencia consumida por el sistema < 10V

# Instalación del controlador
:::danger 
 Durante la instalación del dispositivo es obligatorio desconectar el suministro de energía eléctrica, ya que la tensión presente en algunos componentes es peligrosa para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.  Esta operación es peligrosa
:::

## Selección del lugar de montaje
El lugar de montaje debe elegirse de forma racional, teniendo en cuenta que el equipo debe ser fácilmente accesible para las personas autorizadas e inaccesible para los animales y los niños. También deben tenerse en cuenta las condiciones climáticas, es decir, el dispositivo debe funcionar en un intervalo de temperaturas de -10°C a 40 °C, en un lugar no expuesto a la luz solar. Debe haber una libre circulación de aire alrededor del dispositivo. El dispositivo incluye un sensor de temperatura.  

### Deben respetarse varias normas para el montaje del sensor de temperatura:
 - el sensor no debe montarse en un lugar sin circulación de aire ni expuesto directamente a la luz solar,
 - el sensor no debe montarse en un muro de carga (exterior) del edificio,
 - evitar la proximidad de dispositivos que emitan calor, como radiadores o lámparas,
 - no debe colocarse el sensor directamente junto a puertas ni aberturas de ventilación,
 - no debe colocarse el sensor en lugares accesibles para los animales,
 - se recomienda tender el cable de conexión del sensor lejos de los cables de alimentación.

# Montaje
El dispositivo puede funcionar en condiciones climáticas agresivas. El controlador y el sensor de temperatura, correctamente montados, son resistentes a los efectos perjudiciales del entorno.  

### Durante el montaje deben tenerse en cuenta los siguientes aspectos:
 - antes de atornillar, debe comprobarse la junta de la tapa,
 - la tapa debe fijarse apretando todos los tornillos,
 - los cables utilizados para conectar el controlador deben ser redondos,
 - después de conectar el cable, deben apretarse los prensaestopas para que el cable quede sellado e inmovilizado; se recomienda utilizar silicona,
 - las entradas no utilizadas (prensaestopas) deben obturarse,
 - el controlador (la parte inferior de la carcasa) se fija a una pared plana con 4 tacos de expansión.

# Conexión eléctrica
:::danger 
 ¡Antes de conectar el sistema, debe comprobarse que la alimentación esté desconectada!
Esta operación es peligrosa
:::

Antes de proceder a la conexión del controlador, debe desatornillarse y retirarse la tapa. Se introducen los cables por los prensaestopas de goma y se puede proceder a conectarlos. Los bornes del controlador se muestran en la siguiente figura.

![Conexión ](./img/sc-12.png)

**El conector AC 230V** se conecta a la alimentación (cuadro de distribución). Es obligatorio utilizar un interruptor automático de protección contra sobreintensidades 1P-B6 y limitadores de sobretensión de tipo T1 T2. Una buena práctica al conectar varios dispositivos consiste en agrupar los controladores en distintas «fases» (L1, L2, L3), para cargar uniformemente la línea de alimentación.

**El conector FAN** debe conectarse directamente al ventilador; si se controlan varios ventiladores, la carga total no puede superar 6A y cada ventilador debe protegerse por separado. No deben tomarse PE ni N de la alimentación (cuadro de distribución); es obligatorio conectarlos a los terminales del controlador.

**El conector FAN 2** puede utilizarse para conectar los ventiladores del grupo 2 o sistemas de aspersión. La salida está aislada y la corriente máxima del contacto es 6A (se requiere un interruptor automático externo de protección contra sobreintensidades de tipo 1P-B6 en caso de control directo de la carga); el contacto se cierra cuando la temperatura medida es superior a la suma de la temperatura de consigna y la banda de ventilación.

**El conector HOT** puede utilizarse para conectar un aerotermo. La salida está aislada y la corriente máxima del contacto es 6A (se requiere un interruptor automático externo de protección contra sobreintensidades 1P-B6 en caso de control directo de la carga); el contacto se cierra cuando la temperatura medida desciende por debajo del valor ajustado.

**El conector ALARM** dispone de salidas aisladas NC, C y NO destinadas a la conexión con la central de alarma. La alarma se activa en los siguientes casos:
    - la temperatura es demasiado baja o demasiado alta,
    - el controlador o el sensor de temperatura ha sufrido una avería,
    - se ha perdido la tensión de alimentación del controlador,
    - se ha producido un funcionamiento anómalo del controlador (p. ej., sobrecalentamiento del controlador)
La siguiente figura muestra cómo conectar el ventilador a la central de alarma.

![Conexión de alarma](./img/alarmsc-s.png)

**El conector FUNC1 y FUNC2** sirve para conectar el mecanismo elevador de apertura de las entradas de aire basado en un motor de giro a derecha/izquierda. El relé FUNC1 conecta la corriente para el actuador y FUNC2 conmuta el sentido de giro del motor. Ejemplo de esquema de conexión del mecanismo elevador (se requiere un interruptor automático externo de protección contra sobreintensidades 1P-B6):
Al desactivar la función del mecanismo elevador, las salidas FUNC1 y FUNC2 funcionan como contactos de los grupos de ventilación 3 y 4, respectivamente.

![Conexión del mecanismo elevador](./img/Sc-12fan.png)

**El conector 12V** está destinado a alimentar sensores externos.

**El conector V1 0-10V** sirve para conectar módulos de expansión de potencia. La tensión en este borne es proporcional al nivel de ventilación.

**El conector V2 0-10V** sirve para conectar el actuador que abre las compuertas de entrada de aire.

**El conector V3 0-10V** sirve para conectar un sistema de calefacción de potencia regulable de forma continua. La tensión en esta salida aumenta proporcionalmente al descenso de la temperatura a partir de la temperatura de calefacción auxiliar.

**El conector 10V** sirve para alimentar el potenciómetro del mecanismo elevador u otros sistemas de tipo 0-10V.

**El conector SENS1 (SENS2)** se conecta al sensor de temperatura 1 TS3 o TS5; la polaridad no importa. Si se conectan 2 sensores simultáneamente, se calcula el promedio de las temperaturas medidas. Una buena práctica consiste en mantener los cables de medición alejados de los cables de alimentación.

**El conector 1-WIRE** puede utilizarse para conectar un mayor número de sensores digitales de temperatura, hasta un máximo de 4, conectados en paralelo (debe respetarse la polaridad correcta). La longitud máxima del cable que conecta los sensores es 150m (la longitud no influye en la medición de la temperatura); se recomienda utilizar un cable apantallado.

**El conector RS-485** puede utilizarse para crear sistemas de ventilación y para la comunicación con un PC.

**El conector IN1 0-10** sirve para introducir la señal de realimentación del sistema de entradas de aire, que determina la posición actual de las entradas.

**El conector IN2 0-10** sirve para conectar el controlador a otros sensores, p. ej., de humedad, CO2, o para el funcionamiento del controlador como expansión de potencia.

# Principio de funcionamiento
La tarea principal del controlador consiste en mantener la temperatura del recinto de cría al nivel establecido por el ganadero. Debe recordarse que el controlador es únicamente una herramienta destinada a ayudar a garantizar unas condiciones climáticas óptimas en el recinto de cría. No obstante, el papel principal en este proceso corresponde al ganadero, que debe adaptar los ajustes del dispositivo a las condiciones climáticas cambiantes del exterior y, sobre todo, a las necesidades de los animales en el edificio ganadero, así como supervisar el estado de funcionamiento del dispositivo mediante la central de alarma.

## Primera puesta en marcha del controlador
:::danger 
 En la primera puesta en marcha del controlador es obligatorio ajustar la banda prohibida de funcionamiento del motor.

:::
El controlador funciona con ventiladores basados en un motor asíncrono monofásico con un consumo máximo total de corriente de 12A. Tras conectar los ventiladores elegidos, el usuario debe adaptarlos para que funcionen con el controlador. En otras palabras, es necesario ajustar el nivel mínimo de funcionamiento (velocidad de giro) del ventilador. Esta función se denomina «Banda prohibida» y el usuario la ajusta una sola vez desde los «Ajustes avanzados». Para realizar esta operación correctamente, se recomienda contar con la ayuda de una segunda persona que pueda observar continuamente el comportamiento del ventilador mientras la otra persona ajusta el valor de la «Banda prohibida» (el valor de fábrica es 0). La falta de ajuste de la banda prohibida puede provocar un funcionamiento incorrecto del dispositivo. El valor de la «Banda prohibida» puede considerarse correcto cuando la presión generada por el ventilador empieza a levantar mínimamente las compuertas de la chimenea de ventilación. El ajuste de la «Banda prohibida» debe repetirse cuando se cambie el ventilador conectado al controlador.

## Aireación periódica
La aireación es una función realizada por el controlador que se activa cuando la temperatura del recinto desciende por debajo de la temperatura de consigna. Esta función proporciona a los animales un suministro cíclico de aire fresco. En el menú Aireación se encuentran 3 parámetros:
- **«Tiempo de funcionamiento»** - determina durante cuántos minutos debe conectarse el ventilador;
- **«Tiempo de pausa»** - determina el tiempo de parada del ventilador;
- **«Nivel de aireación»** - determina la potencia de ventilación durante el «Tiempo de funcionamiento».

Todos los parámetros indicados anteriormente son ajustados por el usuario. 

### Al ajustar los parámetros de aireación deben recordarse varias normas:
- la aireación se activa única y exclusivamente cuando la temperatura de la porqueriza desciende por debajo de la temperatura de consigna,
- la función básica de la aireación es proporcionar a los animales un suministro cíclico de aire fresco, no mantener la temperatura de consigna en el recinto,
- se recomienda airear los recintos durante periodos breves, pero frecuentes,
- deben evitarse los periodos largos de aireación, ya que pueden provocar fluctuaciones excesivas de temperatura,
- es obligatorio adaptar los parámetros ajustados al comportamiento de los animales y a las condiciones existentes tanto dentro como fuera del recinto.

## Modo de funcionamiento del dispositivo
El controlador regula de forma continua la ventilación desde **«Mín.1» hasta «Máx.1»** en el intervalo comprendido entre **«Temperatura de consigna»** y la suma de **«Temperatura de consigna»** y **«Banda de ventilación 1gr.»**. Por encima de este intervalo se conecta el grupo de ventilación 2, y el grupo 1 cambia su nivel a **«Mín.2»**; si la temperatura sigue aumentando, la ventilación aumentará hasta **«Máx.2»**, al final del intervalo de **«Banda de ventilación 2 gr.»**. Si **«Banda de ventilación 2 gr.»** está ajustada a cero y la ventilación funciona a **«Máx.1»**, se conecta el grupo de ventilación 2 y un aumento adicional de la temperatura ya no produce cambios en la ventilación (parte punteada de la gráfica). Si la temperatura del recinto desciende por debajo de **«Temperatura de consigna»**, el controlador airea periódicamente el recinto; si sigue descendiendo, se conecta la calefacción auxiliar. Todo depende de los ajustes introducidos por el usuario. El programa del controlador también contempla el funcionamiento con una central de alarma, que puede activarse cuando la temperatura de la porqueriza se aparta de los parámetros establecidos. 

![Ventilación](./img/Sc-12wentyl.png)  

## Programación del controlador
El controlador dispone de un conjunto de ajustes predeterminados que se escriben en la memoria no volátil en dos casos:
1. Primera puesta en marcha del dispositivo,
2. Error en la memoria de datos.
En caso de ausencia o pérdida de alimentación, el controlador no pierde los ajustes del usuario introducidos y guardados anteriormente.

## Panel frontal – indicadores, botones y pantalla
![Panel](./img/SC-12panel.png)  
    1. Indicador rojo que señala que se ha superado la temperatura máxima admisible.
    2. Indicador rojo que señala que se ha rebasado el límite de temperatura mínima admisible.
    3. Indicador amarillo que señala la calefacción auxiliar.
    4. Indicador amarillo que señala la ventilación del grupo 2.
    5. Indicador verde que señala el ajuste manual del nivel de ventilación.
    6. Indicador verde que señala el funcionamiento de la comunicación RS485.
    7. Pantalla del menú; en el estado de funcionamiento normal muestra la temperatura.
    8. Indicador de barras que señala el nivel de ventilación.
    9. Tecla para desplazarse hacia arriba en el menú o cambiar el valor de un parámetro.
    10. Tecla ESC - salir del menú o de un parámetro sin guardar el valor.
    11. Tecla OK - acceder al menú o confirmar (guardar) un parámetro.
    12. Tecla para desplazarse hacia abajo en el menú o cambiar el valor de un parámetro.

## Uso del menú
El controlador está equipado con diversas funciones que permiten adaptarlo a una aplicación determinada. Estas funciones están agrupadas en un menú al que se accede pulsando una de las teclas **(«+», «-» u «OK»)**. Las teclas **«+»** y **«-»** sirven para seleccionar funciones, mientras que la edición, el guardado de datos o el acceso a un nivel inferior se realizan mediante la tecla **«OK»**. Pulse la tecla **«Esc»** para volver al menú superior o cancelar el guardado de un parámetro.

## Funciones del menú básico

| MENÚ                          | Descripción       | 
|:-----------                   |:---------- |
| Temperatura 20,8o C W16% A    | **Modo informativo** - de funcionamiento normal. La pantalla muestra la temperatura actual y, cuando el ventilador está en marcha, el valor del nivel de ventilación. Significado de los símbolos adicionales:A-significa alarma activada,D  - significa calefacción conectada, W - significa ventilación adicional| 
|   Temp. de consigna   20,0o C      |**«Temperatura de consigna»** – Determina la temperatura a partir de la cual comienza el proceso de ventilación con regulación continua. Debe elegirse un valor adecuado en función del tipo de animales de cría.| 
| Aireación     | **Aireación** – se ajustan dos valores de tiempo.    1.**Tiempo de funcionamiento** Determina el número de minutos de funcionamiento de la ventilación.    2.**Tiempo de pausa** Determina el número de minutos de parada de la ventilación entre ciclos de funcionamiento consecutivos.    3.**Nivel de aireación** - Determina la intensidad de ventilación durante el funcionamiento de la aireación.| 
| Alarma |  1.**Alarma activa Sí** - Activación/Desactivación del contacto de alarma; para que el controlador no emita una señal de alarma en la salida (hacia la central de alarma), se selecciona «NO» en el menú.  2. **Temp. Mín. 15,0o C** - Determina la temperatura mínima absoluta a la que se activa la alarma.  3.**Temp. Máx. 25,0o C** - Determina la temperatura máxima absoluta a la que se activa la alarma.  4.**Señal de alarma Sí** - Activación/Desactivación de la señal acústica dentro del controlador. | 
|    Ventilación        |  1.**Banda de vent. 1 5,0o C**   - Determina la rapidez de respuesta del controlador (cambio del nivel de ventilación desde el mínimo 1 hasta el máximo 1) ante el aumento de la temperatura.  2.**Nivel mín. 1 1 %** - Determina el nivel de ventilación correspondiente a la temperatura de consigna.  3.**Nivel máx. 1 100 %**-Determina el nivel constante de ventilación para una temperatura que supera el intervalo de regulación continua, cuando «Banda de vent. 2gr.» = 0; en caso contrario, el nivel máximo de ventilación regulada para una temperatura igual a la suma de la T. de consigna y la banda del grupo 1.  4.**Banda de vent. 2 0,0o C**-Determina la rapidez de respuesta del controlador (cambio del nivel de ventilación desde el mínimo 2 hasta el máximo 2) ante el aumento de la temperatura para el grupo 2. Función inactiva cuando la banda es igual a cero.  5.**Nivel mín. 2 1 %**-Determina el nivel mínimo de ventilación del grupo 1 en el punto de cierre de los contactos del grupo 2.  6.**Nivel máx. 2 100 %**-Determina el nivel constante de ventilación para una temperatura que supera el intervalo de regulación continua, cuando el grupo 2 está conectado.  7.**Grupo 3  5,0o C**-Determina el nivel constante de ventilación para una temperatura que supera el intervalo de regulación continua, cuando el grupo 2 está conectado.  8.**Grupo 4 7,0o C**-Determina la temperatura de conexión del grupo de ventilación 4 respecto a la temperatura de consigna (la función del mecanismo elevador debe estar desactivada).| 
|    Calefacción auxiliar  |  1.**Temp. calef. aux. 15,0o C**-Determina la temperatura de conexión de la calefacción auxiliar.  2.**Banda calef. aux. 5,0o C** -Determina la proporción de potencia de los sistemas de calefacción auxiliar (en la salida V3 0-10V) en función de la temperatura. | 

## Funciones del menú avanzado
El menú avanzado está destinado principalmente a los instaladores y permite adaptar el controlador a la instalación y al ventilador, probar los circuitos y seleccionar el idioma del menú. Para acceder a los ajustes avanzados, deben mantenerse pulsadas dos teclas del menú durante aproximadamente 10s. 

| MENÚ                          | Descripción       | 
|:-----------                   |:---------- |
|Pruebas  |Esta función sirve para comprobar los distintos circuitos de accionamiento del controlador; todos los ajustes son temporales mientras se permanece en la opción correspondiente del menú; después de pulsar «ESC» u «OK», la salida correspondiente vuelve al estado que resulta del funcionamiento del controlador.  1.**Ventilación 0 %**  Permite introducir manualmente el nivel de ventilación para comprobar el sistema de ventilación. Después de confirmar la función, se enciende el indicador verde (mano).  2.**Alarma No** La activación enciende 2 indicadores rojos, la señal acústica y el circuito de alarma.  3.**Calefacción auxiliar No** La activación enciende el indicador amarillo (llama) y el circuito de calefacción auxiliar.  4.**Vent. 2 etapa No** La activación enciende el indicador amarillo (ventilador) y el circuito del grupo 2.  5.**Salida V1 0,0 V  Salida V2  0,0 V Salida V3  0,0 V**-Prueba de las salidas 0-10V; mediante las teclas «+» o «-» puede fijarse la tensión seleccionada para los sistemas, respectivamente: módulos de expansión, compuertas de entrada, calefacción auxiliar de regulación continua. Esta función es especialmente útil para calibrar la Salida V2 de las compuertas de entrada.  6.**Mecanismo elevador 0** Permite comprobar el sistema de compuertas de entrada: «+» - abre las entradas, «-» - cierra las entradas; la pantalla muestra la posición actual del actuador leída del potenciómetro.  7.**Grupo 3 No**  La activación conecta el circuito del grupo de ventilación 3. (la función del mecanismo elevador debe estar desactivada)  8.**Grupo 4 No**  La activación conecta el circuito del grupo de ventilación 4. (la función del mecanismo elevador debe estar desactivada)|
|Idioma        | Selección del idioma del menú. Puede elegirse polaco o inglés. | 
|Ventilador         |  1.**Banda prohibida 0**- Calibración de la velocidad mínima de giro de los ventiladores conectados directamente al controlador; este parámetro corresponde al nivel de ventilación «1%». Un valor positivo del parámetro aumenta la velocidad de giro y uno negativo la reduce.  2.**Módulo exp. Mín. 1,9 V** -Tensión mínima suministrada al módulo de expansión de potencia (salida V1 0-10V).  3.**Módulo exp. Máx. 10,0 V** -Tensión máxima suministrada al módulo de expansión de potencia (salida V1 0-10V).  4.**Desconexión módulo No** - Desconexión del módulo de expansión de potencia; cuando se selecciona «SÍ», la tensión en la salida de control de los módulos de expansión (V1 0-10V) desciende al nivel 0V y no al valor mínimo ajustado, cuando el nivel de ventilación es 0%.  5.**Inversión  No**-La activación invierte la característica de la salida V1. La tensión disminuirá a medida que aumente el nivel de ventilación en el intervalo definido por mín.-máx. La señal en la salida V1 será de tipo 10-0V.| 
| Compuertas de entrada       |  1.**Anticipación 0,0o C**-Apertura anticipada de las compuertas de entrada. El parámetro ajustado determina con qué diferencia de temperatura respecto a la «Temperatura de consigna» deben abrirse anticipadamente las compuertas de entrada.  2.**Cierre completo  No**-La activación hace que la tensión en la salida de control de las compuertas de entrada (V2 0-10V) descienda al nivel 0V y no al valor mínimo ajustado. En caso de ausencia de ventilación (nivel de ventilación 0%).  3.**Compuertas mín.  1,9 V**- Tensión mínima suministrada a las compuertas de entrada (salida V2 0-10V).  4.**Compuertas máx.  10,0 V**- Tensión máxima suministrada a las compuertas de entrada (salida V2 0-10V).  5.**Inversión   No**-La activación invierte la característica de la salida V2. La tensión disminuirá a medida que aumente el nivel de ventilación en el intervalo definido por mín.-máx. La señal en la salida V2 será de tipo 10-0V. |  
| Medición de temperatura  |  1.**Calibración S1 23,0o C -> 23,5o C**,**Calibración S2 23,0o C -> 23,2o C** - La calibración de las entradas analógicas permite reescalar la temperatura leída de los sensores S1 y S2.  2.**Tiempo de promediado 60 s**- Este parámetro define el periodo de tiempo durante el cual se promedian las lecturas actuales de temperatura. El valor de la temperatura media es el parámetro básico de las funciones del controlador. Los cambios de estado de las salidas (ventilación, calefacción auxiliar, compuertas, grupos sucesivos de ventilación, alarmas,...) están estrechamente relacionados con este parámetro y no pueden producirse con una frecuencia superior a la determinada por el tiempo indicado aquí. | 
| Mecanismo elevador      |  1.**Calibración apertura 1024 -> 853**,**Calibración cierre 0 -> 324** -La calibración del mecanismo elevador es indispensable para el funcionamiento correcto del sistema de entradas de aire. La tecla «+» abre las entradas y la tecla «-» las cierra. Al abrir las entradas, el parámetro de posición debe aumentar y, al cerrarlas, disminuir; en caso contrario, debe verificarse la conexión del actuador (alimentación y potenciómetro). En la calibración de apertura, se abren las entradas al máximo y se confirma la posición con la tecla «OK». En la calibración de cierre, se cierran las entradas y se confirma la posición con la tecla «OK». La tecla «ESC» permite salir de la función sin guardar. La diferencia entre la posición de apertura y la de cierre debe ser de al menos 100 unidades.  2.**Desactivación No**-La desactivación libera los contactos FUNC1 y FUNC2 del control del mecanismo elevador; estos contactos pasan entonces a desempeñar la función de ventilación de los grupos 3 y 4.| 
| Arranque suave               | Los parámetros de este grupo del menú controlan el arranque de la ventilación. La conexión de la ventilación en el grupo de regulación continua va precedida de un arranque gradual hasta 100%, un breve funcionamiento a 100%  y un descenso al nivel de ventilación requerido. Esto genera, al arrancar la ventilación, un soplado que facilita la apertura de las válvulas de mariposa de las chimeneas.   Los valores se expresan en periodos de la tensión de alimentación a 1% de ventilación.  1.**Tiempo de aceleración 5**- El parámetro determina la rapidez con la que aumenta la velocidad de giro de la ventilación desde el nivel cero hasta el máximo – conexión suave de los ventiladores. El valor 0 desactiva la aceleración suave.  2.**Tiempo 100%   100**- El parámetro determina el tiempo de funcionamiento al arrancar a 100% del nivel de ventilación. Ajustar el tiempo de aceleración y 100% a 0 desactiva por completo el soplado al arrancar la ventilación.  3.**Tiempo de desaceleración 5**-  El parámetro determina la rapidez de los cambios del nivel de ventilación. | 
|Calefacción auxiliar              |  1.**Inversión del contacto No**-La activación invierte la característica de la salida HOT. El contacto se abrirá al descender la temperatura medida.  2.**Histéresis  0,5o C** - Determina el nivel de histéresis de temperatura para el contacto de calefacción auxiliar.  3.**Funcionamiento relativo No**-La activación permite ajustar la temperatura de calefacción auxiliar de forma relativa respecto a la temperatura de consigna. Se modifica el menú básico de calefacción auxiliar, en el que se introduce la diferencia respecto a la temperatura de consigna.  4.**Calefacción auxiliar mín. 1,9 V** - Tensión mínima suministrada al control continuo de calefacción – aerotermo con caudal variable del ventilador (salida V3 0-10V).  5.**Calefacción auxiliar máx. 10,0 V** - Tensión máxima suministrada al control continuo de calefacción – aerotermo con caudal variable del ventilador (salida V3 0-10V).| 
| Programa 	|  **ver. 2.4  Abr 13 2018** - 	Lectura de la versión del software y de la fecha de compilación|

## Mensajes de error y advertencia

Los mensajes de error sirven para informar al usuario de las anomalías en el funcionamiento del controlador. A continuación se muestran los posibles mensajes de error

|ERROR                            |	DESCRIPCIÓN      |
|:-----------                    |:---------- |
|Alarma     Sobrecarga 	     |Alarma de sobrecarga, activada a 75°C. El dispositivo suspende el funcionamiento hasta que se enfría.|
|Alarma  Sin sensor|Señala la ausencia o avería del sensor o del cable de conexión.|

# Observaciones y advertencias 
:::danger 
 Durante la instalación del dispositivo es obligatorio desconectar el suministro de energía eléctrica, ya que la tensión presente en algunos componentes es peligrosa para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.

:::
- Para evitar problemas durante el funcionamiento del dispositivo, es obligatorio leer las instrucciones antes de proceder a su instalación y uso.
- No se permite modificar la estructura ni realizar reparaciones por cuenta propia. Esto se aplica especialmente a las modificaciones de elementos y componentes. 
- Las tareas de mantenimiento o servicio deben ser realizadas por personal autorizado (instalador o servicio técnico del fabricante). En los edificios ganaderos con ventilación forzada es obligatorio disponer de un sistema de alarma. El fabricante del dispositivo no se responsabiliza de los daños causados por una instalación incorrecta, una programación incorrecta de las funciones, las consecuencias de sucesos fortuitos o factores externos. 
- El controlador de ventilación requiere el ajuste de los parámetros de acuerdo con las condiciones existentes en el recinto de cría. Estos ajustes son individuales y dependen de la decisión del ganadero. El fabricante del dispositivo se reserva el derecho a realizar cambios en la estructura del dispositivo y en el software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> Al finalizar la vida útil del producto, no debe desecharse junto con los residuos municipales sin clasificar, sino gestionarse de acuerdo con la normativa vigente (directivas WEEE de la Unión Europea 2012/19/UE).
El producto se ha fabricado conforme a los requisitos RoHS (Directiva de la Unión Europea 2011/65/UE).
  </p>
</div>
:::
:::tip

## Datos técnicos del controlador
|Parámetro                        |	DESCRIPCIÓN      |
|:-----------                    |:---------- |
|Tensión de alimentación|	230VAC 50Hz|
|Corriente máxima de la salida de regulación continua FAN|	12A|
|Intervalo de regulación de la tensión de salida|	70V ÷ 230V|
|Corriente máxima de la salida (contacto) FAN 2|	6A|
|Corriente máxima de la salida (contacto) HOT|	6A|
|Corriente máxima de la salida (contacto) ALARM|	4A|
|Corriente máxima de la salida (contacto) FUNC1 y FUNC2|	4A|
|Intervalo de temperatura de funcionamiento|	-10 +40oC|
|Intervalo de medición de temperatura|	0 +50oC|
|Resolución de la medición de temperatura|	0,1oC|
|Detección de averías del sensor de temperatura|	SÍ|
|Número máximo de sensores analógicos|	2|
|Precisión de la medición de temperatura – entrada analógica|	1oC|
|Dependencia de la medición respecto a la resistencia de los cables – entrada analógica|	15,8Ω/oC|
|Número máximo de sensores digitales|	4|
|Precisión de la medición de temperatura – entrada digital|	0,5oC|
|Dependencia de la medición respecto a la resistencia de los cables – entrada digital|	Ninguna|
|Longitud máxima de la línea de conexión de los sensores digitales|	150m|
|Resistencia a sobretensiones (máx. E)|	210J|
|Protección contra sobrecargas|	75oC|
|Dimensiones del dispositivo|	34x29x12 [cm]|
|Grado de estanqueidad de la carcasa|	IP56|
:::

:::info
El controlador SPEED CONTROL-12 v2  incluye en el suministro:
 - 1 sensor de temperatura,
 - 4 tacos de expansión,
 - 2 prensaestopas PG13,5.
 - 3 prensaestopas PG11,
 - 4 prensaestopas PG9.
:::















































































