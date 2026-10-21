---
id: sc-pe16
title: SC-PE16 — manual de instrucciones
sidebar_label: SC-PE16
sidebar_position: 5
description: Manual del módulo de ampliación de potencia SC-PE16 — montaje, conexión,
  puesta en marcha, menú y protecciones.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


El módulo de ampliación de potencia SC-PE16 sirve para controlar ventiladores cuando la carga supera la capacidad del controlador principal. El dispositivo regula la tensión de alimentación de los ventiladores en función de una señal analógica o de un ajuste manual. La corriente total máxima de salida es de 16 A.

![Módulo de ampliación de potencia ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parámetros y características

- modos AUTO y MANUAL y suspensión del dispositivo;
- pantalla gráfica y teclado táctil;
- control analógico 2–10 V o 4–20 mA;
- umbral programable de activación del grupo de ventilación 2;
- byPASS con un nivel estable de 100%;
- protección térmica del circuito de potencia;
- safeRUN: nivel ajustable de funcionamiento de emergencia;
- calibración del nivel mínimo de ventilación;
- prueba de ventilación, relé y alarma;
- bloqueo del teclado y bloqueo para limpieza;
- idioma polaco, inglés o ucraniano;
- alimentación 230 V CA, 50 Hz; carcasa IP65.

:::info Versión del software

La descripción de las funciones se refiere al software suministrado **vers. 2.1**. La disponibilidad de las funciones debe comprobarse en relación con la versión instalada en el dispositivo.

:::

## Instalación del controlador

:::danger Desconecte la alimentación

Durante la instalación del dispositivo es obligatorio desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes es peligrosa para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.

:::

### Elección del lugar de montaje

El dispositivo debe montarse en un lugar accesible para el personal de operación, fuera del alcance de niños y animales y sin exposición directa al sol. El intervalo de temperatura ambiente es de −10°C a +40°C. Debe garantizarse la libre circulación de aire alrededor de la carcasa y del disipador. No cubra el disipador ni monte el dispositivo cerca de fuentes de calor.

### Montaje

Fije la parte inferior de la carcasa a una pared plana con cuatro tacos, utilizando los orificios de montaje situados fuera del compartimento sellado. Monte la tapa con la bisagra incluida en el conjunto. Antes de cerrarla, compruebe el estado y la colocación de la junta.

Utilice cables de sección exterior circular, adecuados para los prensaestopas. Apriete los prensaestopas de forma que sellen e inmovilicen el cable. Obture las entradas de cable no utilizadas. Apriete todos los tornillos de la tapa. La estanqueidad depende del montaje correcto de la carcasa y de las entradas de cable.

### Preparación de las conexiones

Realice todos los trabajos dentro de la carcasa tras desconectar la alimentación y comprobar la ausencia de tensión. Si para retirar el panel es necesario desconectar el cable plano, desconéctelo con cuidado y vuelva a conectarlo antes de cerrar la carcasa. No conecte ni desconecte el cable plano con la alimentación conectada.

Tienda los cables de señal INPUT y ENABLE separados de los cables de alimentación y de salida. Respete las designaciones de los bornes indicadas en el ejemplar concreto del dispositivo. La masa de las entradas de señal y el borne de protección PE cumplen funciones diferentes y no son intercambiables.

## Conexión eléctrica

:::danger Desconecte la alimentación

¡Antes de conectar el sistema, asegúrese de que la alimentación esté desconectada!

:::

![Bornes de alimentación, ventiladores, GR 2, ENABLE, CAN e INPUT](./img/sc-pe16/zaciski.png)

| BORNE | FUNCIÓN |
| --- | --- |
| L, N, PE — alimentación | Alimentación 230 V CA, 50 Hz: L — fase, N — conductor neutro, PE — conductor de protección. En la documentación original se indica una protección B20; la selección de las protecciones y de los cables debe tener en cuenta la instalación y la carga. |
| U, N, PE — ventiladores | U — salida de fase regulada; N y PE — bornes comunes correspondientes del dispositivo. La suma de las corrientes de los ventiladores no puede superar 16 A. Cada ventilador requiere una protección independiente. Utilice motores homologados para regulación por tensión. |
| GR 2: C, NO | Contacto aislado del relé del grupo 2. Se cierra cuando el nivel de ventilación de consigna es igual o superior al umbral «Grupo 2 de ventilación». Corriente máxima del contacto según el manual suministrado: 6 A. Para el control directo de una carga, la documentación indica una protección externa B6. |
| INPUT: V, masa | Entrada de tensión. Seleccione «Tipo de control → Entrada V». En el programa analizado, el intervalo de regulación es 2–10 V. No conecte a esta entrada la tensión de red ni la salida regulada de alimentación de los ventiladores. |
| INPUT: I, masa | Entrada de corriente 4–20 mA. Seleccione «Tipo de control → Entrada I». Conecte la señal de acuerdo con las marcas de la fuente y del receptor. |

Para el control, utilice la entrada seleccionada V o I. SC-PE16 requiere su propia alimentación de red; la entrada analógica transmite únicamente el valor de control.

## Entrada ENABLE y comunicación

### ENABLE: E y masa

La entrada funciona con un contacto libre de potencial. Los bornes E y masa solo pueden cortocircuitarse o dejarse en circuito abierto; no aplique tensión externa. El cierre permite el funcionamiento; la apertura establece el nivel 0%. La parada está sujeta al ajuste «Tiempo de desaceleración».

La función ENABLE se activa por separado para AUTO y MANUAL en el menú «Avanzado → Ventilador». Ambas funciones están desactivadas de fábrica, por lo que en ese caso no se necesita un puente. La apertura de ENABLE no equivale a la suspensión: el panel permanece activo. En AUTO, con el bloqueo ENABLE activo, el programa omite la lectura de la señal de control y no activa safeRUN.

### CAN y Wi-Fi

Las opciones «Entrada CAN» y «Entrada WiFi» figuran en el menú, pero en el software vers. 2.1 no realizan el control: ambas funciones devuelven el nivel 0%. Para poner en marcha el dispositivo con este programa, seleccione la entrada V o I. No configure la instalación basándose en CAN o Wi-Fi sin confirmar su compatibilidad en la versión de software instalada.

## Principio de funcionamiento

SC-PE16 es un regulador de potencia que ejecuta las órdenes del controlador principal o del operador. No mide la temperatura del recinto ni dispone de ajustes propios de temperatura, aireación, calefacción auxiliar o compuertas de entrada de aire. El nivel porcentual de ventilación representa un valor de control, no una medición de la velocidad real del motor.

| SEÑAL NOMINAL | NIVEL DE VENTILACIÓN DE CONSIGNA |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Entre los valores límite, el programa determina el nivel de forma lineal y lo redondea a porcentajes enteros. Para la entrada V, el aumento comienza al superar la lectura 2,04 V y, para la entrada I, 4,04 mA. El estado final de la salida también depende de ENABLE, del arranque y de la protección térmica.

## Funcionamiento de emergencia y protecciones

### safeRUN — pérdida de la señal de entrada

En el modo AUTO, la alarma «Entrada» aparece cuando la lectura de tensión es inferior a 1,50 V o la de corriente es inferior a 2,00 mA, según la entrada seleccionada. El programa establece entonces el nivel «Funcionamiento de emergencia» dentro del intervalo 0–100%; el valor de fábrica es 30%. Cuando la señal vuelve al umbral de detección o lo supera, desaparece la alarma de entrada y el dispositivo vuelve al control analógico.

Los intervalos 1,50–2,04 V y 2,00–4,04 mA proporcionan el nivel 0% sin alarma de entrada. En esta versión, la señal 0 V no es una orden de parada normal: activa el funcionamiento de emergencia. El controlador principal con salida 0–10 V debe configurarse para el intervalo 2–10 V sin corte a 0 V. En MANUAL, la señal analógica no controla la ventilación y la alarma de entrada se borra.

### Protección térmica

La alarma «Sobrecalentamiento» se activa cuando la lectura de temperatura del disipador supera 87°C. Se borra cuando desciende por debajo de 80°C. Durante la alarma, el programa modifica el nivel de consigna: para valores iguales o superiores a 50% establece 100%, y para valores inferiores a 50% establece 0%. La modificación de la salida está sujeta al algoritmo de arranque y desaceleración. La protección no garantiza el funcionamiento continuo de la ventilación en todos los casos.

El estado del relé GR 2 se determina antes de la corrección térmica: depende del nivel anterior a la imposición de 0% o 100%. El nivel de funcionamiento de emergencia también está sujeto a la corrección térmica. En caso de sobrecalentamiento, compruebe las condiciones de refrigeración, la suciedad del disipador y la carga; encargue los trabajos dentro de la carcasa a una persona autorizada.

### byPASS y arranque suave

Con un nivel de salida estable de 100%, el programa activa el relé de derivación del circuito de regulación de fase. El arranque puede incluir un aumento hasta 100%, un mantenimiento en 100% y la transición al nivel de consigna. Los parámetros «Arranque suave» también influyen en la velocidad de respuesta de la salida ante un cambio de la demanda.

## Primera puesta en marcha del controlador

:::warning Calibración de los ventiladores

¡Atención! Durante la primera puesta en marcha del dispositivo es obligatorio ajustar la banda prohibida de funcionamiento del motor.

:::

1. Con la alimentación desconectada, compruebe las conexiones de alimentación, PE, ventiladores y señal analógica. Confirme que los motores sean aptos para regulación por tensión y que la corriente total no supere 16 A.
2. Conecte la alimentación. Si se ofrece la selección de idioma, pulse OK y seleccione el idioma. Desbloquee el teclado con el botón que lleva el símbolo del candado.
3. En «Tipo de control», seleccione «Entrada V» o «Entrada I». Ajuste el nivel «Funcionamiento de emergencia» y el umbral «Grupo 2 de ventilación». Si es necesario, active ENABLE por separado para el modo correspondiente.
4. Acceda a «Avanzado → Ventilador → Banda prohibida». En esta opción, el programa impone el nivel 1% y la modificación del parámetro afecta inmediatamente a la salida. El intervalo es de −20 a 200, con un valor de fábrica de 0. Un valor positivo aumenta el nivel mínimo de control y uno negativo lo reduce.
5. Ajuste el valor de forma que todos los ventiladores giren de manera estable, sin detenerse ni calentarse excesivamente. Observe cada ventilador, preferiblemente con ayuda de otra persona. La simple elevación de la compuerta no sustituye la comprobación del funcionamiento correcto del motor. Confirme con OK; ESC restablece el ajuste anterior.
6. Compruebe la salida a varios niveles, incluidos 0%, un nivel bajo y 100%. Repita la calibración tras sustituir los ventiladores o modificar su configuración.
7. En AUTO, compruebe la respuesta a las señales mínima y máxima. A continuación, compruebe la interrupción de la señal y la transición al funcionamiento de emergencia, así como el retorno tras restablecer la señal. Si ENABLE está activo, compruebe también su funcionamiento.
8. Compruebe GR 2 y la señalización de alarma en el menú «Pruebas». Una vez finalizadas las pruebas, salga de esta opción y seleccione el modo de funcionamiento definitivo.

:::warning Activación real de las salidas

Las pruebas y la calibración controlan las salidas reales. Pueden poner en marcha los ventiladores, y la prueba de ventilación impone un nivel independientemente del control normal. Garantice condiciones de prueba seguras y una supervisión permanente.

:::

## Programación del controlador

### Panel frontal — indicadores y botones

| ELEMENTO | MANEJO |
| --- | --- |
| Alimentación / suspensión | El botón con el símbolo de alimentación muestra una solicitud de confirmación de suspensión; confirme con OK. Al pulsarlo de nuevo, el dispositivo sale de la suspensión. La suspensión establece el estado desactivado de las salidas; no desconecta la tensión de red. |
| Candado | Activa o desactiva el bloqueo del teclado. Tras el desbloqueo, se enciende el indicador junto al candado. En la pantalla principal, el bloqueo se restablece tras aproximadamente 30 s de inactividad. |
| A — AUTO | Selecciona el control desde la entrada analógica tras confirmar con OK. El indicador A muestra el modo seleccionado. |
| M — MANUAL | Selecciona el control manual tras confirmar con OK. En la pantalla principal, las teclas + y − modifican el ajuste 0–100%. El indicador M muestra el modo seleccionado. |
| +, −, OK, ESC | OK abre el menú, accede a una opción y confirma el valor. + y − seleccionan una opción o modifican el valor. ESC vuelve al nivel anterior o cancela la edición. |
| Alarma y grupo 2 | El indicador rojo señala una alarma. El indicador junto al símbolo del ventilador «2» señala la activación del relé GR 2. |
| Pantalla | En AUTO muestra el nivel de ventilación de consigna, la lectura de la entrada seleccionada, el gráfico de barras y las alarmas. Cuando ENABLE está activo, también muestra su estado. En MANUAL, el valor principal representa el ajuste manual; las protecciones pueden modificar la salida. |

### Memorización de los ajustes

Los parámetros del menú se guardan en la memoria no volátil tras confirmar con OK. Las modificaciones del nivel MANUAL surten efecto de inmediato y se guardan tras un breve periodo de inactividad. Tras una interrupción de la alimentación, se restablecen los ajustes guardados, incluidos el modo AUTO/MANUAL, el nivel manual y el estado de suspensión. No desconecte la alimentación inmediatamente después de modificar el ajuste manual.

En caso de suma de comprobación incorrecta o de un valor fuera del intervalo, el programa restablece los valores de fábrica. En ese caso, deben comprobarse de nuevo todos los ajustes, especialmente la calibración de los ventiladores, la entrada de control y el funcionamiento de emergencia.

## Funciones del menú básico

| MENÚ | INTERVALO / VALOR DE FÁBRICA | DESCRIPCIÓN |
| --- | --- | --- |
| Tipo de control | Entrada V | Selección de V, I, CAN o Wi-Fi. Para la versión analizada, utilice V (2–10 V) o I (4–20 mA). CAN y Wi-Fi no realizan el control. |
| Grupo 2 de ventilación | 1–100% / 100% | Umbral de cierre del contacto GR 2. El contacto está cerrado con un nivel igual o superior al umbral y abierto por debajo del umbral. El programa no define una histéresis independiente. |
| Funcionamiento de emergencia | 0–100% / 30% | Nivel establecido cuando se pierde la señal analógica seleccionada en AUTO. El valor 0% representa una parada en caso de pérdida de señal. |
| Bloqueo para limpieza | 60 s | Bloquea el uso de las teclas durante 60 segundos y muestra una cuenta atrás. La regulación de la ventilación continúa funcionando. La función sirve para limpiar la superficie del panel, no para realizar trabajos eléctricos ni lavar el interior. |
| Avanzado | Submenú | Acceso a las pruebas, el idioma, la calibración del ventilador, ENABLE, Arranque suave, el sonido de alarma, los ajustes de fábrica y la información del programa. |

## Funciones del menú avanzado

| MENÚ / PARÁMETRO | INTERVALO / VALOR DE FÁBRICA | DESCRIPCIÓN |
| --- | --- | --- |
| Pruebas → Ventilación | 0–100% | Imposición temporal de la salida regulada. Las modificaciones surten efecto durante la edición. Al salir con OK o ESC, se restablece el control normal. |
| Pruebas → Vent. de etapa 2 | No / Sí | Activación forzada temporal del contacto GR 2 y de su indicador. |
| Pruebas → Alarma | No / Sí | Prueba temporal de la señalización de alarma, incluido el sonido, independientemente del ajuste normal «Señal de alarma». |
| Idioma | Polaco | Se puede seleccionar polaco, inglés o ucraniano. |
| Ventilador → Banda prohibida | −20–200 / 0 | Calibración del nivel 1%. Durante la edición se impone la salida real 1%. El parámetro no se expresa en porcentajes ni en segundos. |
| Ventilador → Activación EN AUTO | No / Sí; No | Activa la dependencia del modo AUTO respecto a la entrada ENABLE. |
| Ventilador → Activación EN MANUAL | No / Sí; No | Activa la dependencia del modo MANUAL respecto a la entrada ENABLE. |
| Arranque suave → Tiempo de aceleración | 0–50 / 5 | Velocidad de aumento del nivel durante el arranque hasta 100%. Un valor mayor representa un cambio más lento. El valor 0 omite la etapa de aumento. |
| Arranque suave → Tiempo 100% | 0–250 / 100 | Mantenimiento del nivel 100% durante el arranque. El valor 0 omite la etapa de mantenimiento. El ajuste conjunto de la aceleración y del mantenimiento a 0 omite el soplado hasta 100%. |
| Arranque suave → Tiempo de desaceleración | 0–50 / 5 | Velocidad de aproximación al nivel solicitado, también cuando este cambia. El valor 0 representa un cambio sin aproximación gradual. |
| Señal de alarma | No / Sí; No | Activa el sonido de señalización de alarma. El ajuste No no elimina el mensaje de la pantalla ni la señalización mediante el indicador. |
| Ajustes de fábrica | No / Sí | Al seleccionar Sí, restablece y guarda los valores predeterminados, incluidos la calibración 0, la entrada V, AUTO, el funcionamiento de emergencia 30%, el umbral GR 2 igual a 100% y ENABLE desactivado. Tras la operación, configure y compruebe de nuevo el dispositivo. |
| Programa | vers. 2.1 + fecha de compilación | Muestra la versión y la fecha de compilación del programa. Esta descripción se ha elaborado a partir de los archivos fuente suministrados SC_PX16_v02. |

Los parámetros de Arranque suave son ajustes adimensionales de los contadores del programa, no tiempos expresados en segundos. Con 50 Hz, un paso corresponde aproximadamente a (ajuste + 1) × 20 ms: para la aceleración y la desaceleración es el tiempo de variación de 1 punto porcentual; para «Tiempo 100%», es el tiempo de mantenimiento. El valor 0 tiene el significado descrito en la tabla. Los tiempos reales dependen de la fase del algoritmo.

## Mensajes de error y advertencia

| MENSAJE | SIGNIFICADO Y ACTUACIÓN |
| --- | --- |
| Entrada | Lectura demasiado baja de la señal seleccionada en AUTO. El dispositivo establece el funcionamiento de emergencia. Compruebe la fuente de señal, los cables, la masa común y la selección de V/I. |
| Sobrecalentamiento | Lectura del disipador &gt;87°C; borrado &lt;80°C. Ventilación establecida en 0% o 100%, según la descripción de la protección térmica. Compruebe la refrigeración y la carga. |
| Alimentación | Alteración de la sincronización del circuito de potencia con la red. Compruebe la alimentación y la instalación. En caso de pérdida total de alimentación, la pantalla no funciona. |
| Memoria CRC | Error de suma de comprobación o de intervalo de los ajustes guardados. El programa restablece los valores predeterminados. Compruebe la configuración y repita la calibración; si el error se repite, póngase en contacto con el servicio técnico. |

## Notas y advertencias

:::danger Desconecte la alimentación

Durante la instalación del dispositivo es obligatorio desconectar la alimentación eléctrica, ya que la tensión presente en algunos componentes es peligrosa para la vida y la salud. Se recomienda encargar la instalación a una persona cualificada.

:::

Antes de la instalación y del uso, lea el manual. Encargue las reparaciones y los trabajos dentro del dispositivo a personal autorizado. La suspensión, el bloqueo del teclado, ENABLE y el ajuste 0% no constituyen una desconexión de la alimentación ni garantizan condiciones seguras para trabajos eléctricos.

Seleccione los ajustes de ventilación y de funcionamiento de emergencia de acuerdo con las necesidades de los animales y de la instalación. Compruebe periódicamente el funcionamiento real de todos los ventiladores. La señalización SC-PE16 no sustituye la supervisión independiente de las condiciones del recinto y de la pérdida de alimentación. La regleta de bornes mostrada no dispone de un contacto ALARM independiente para la central.

:::note Eliminación del dispositivo

Al finalizar su vida útil, el producto no debe desecharse junto con los residuos municipales sin clasificar, sino eliminarse de conformidad con la normativa vigente (directivas WEEE de la Unión Europea 2012/19/UE).

:::

El producto se ha fabricado de conformidad con los requisitos RoHS (Directiva de la Unión Europea 2011/65/UE).

## Datos técnicos del controlador

| PARÁMETRO | VALOR |
| --- | --- |
| Alimentación / consumo propio | 230 V CA, 50 Hz / &lt;10 W |
| Corriente total máxima de la salida U | 16 A |
| Corriente máxima del contacto GR 2 | 6 A; contacto C–NO, aislado |
| Entrada V / entrada I | 2–10 V / 4–20 mA, seleccionables en el menú |
| Umbral de pérdida de señal (lectura del programa) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Contacto libre de potencial E–masa; activación por separado para AUTO/MANUAL |
| Protección térmica (lectura del disipador) | Alarma &gt;87°C; restablecimiento &lt;80°C |
| Temperatura ambiente / carcasa | −10°C a +40°C / IP65 |
| Dimensiones / resistencia a sobretensiones | 34 × 29 × 12 cm / 210 J |
| Idiomas del menú | Polaco, inglés, ucraniano |

Contenido del conjunto según la documentación suministrada: 4 tacos de expansión, 2 prensaestopas PG13,5, 1 prensaestopas PG9 y 1 bisagra.

## Condiciones de garantía

Se ha conservado el contenido de las condiciones de garantía del documento suministrado por el fabricante.

1. El fabricante ELETOR, con sede en Polonia, dirección: Pod Sosno 28, 87-305 Zbiczno (en adelante, el garante), otorga al Comprador una garantía de calidad del producto para el que se ha expedido la presente tarjeta de garantía, siempre que se utilice conforme a su finalidad y a las normas establecidas en el manual de instrucciones entregado al Comprador junto con dicho producto.
2. El periodo de garantía es de 24 meses a partir de la fecha de venta. Las averías o defectos del producto que se manifiesten durante este periodo se subsanarán gratuitamente. Una vez finalizado el periodo de garantía o en caso de pérdida de los derechos de garantía, las averías o defectos se subsanarán con cargo al Comprador.
3. La garantía no cubre:

   - ningún defecto que se haya producido por una manipulación inadecuada del producto (esto incluye la realización de operaciones no descritas en el manual de instrucciones, etc.);

   - ningún defecto resultante de reparaciones, modificaciones, etc., realizadas por una persona distinta del garante;

   - ningún defecto o daño producido durante el transporte o por la caída del producto, si estos hechos tuvieron lugar después de la compra, ni los daños mecánicos derivados de una manipulación incorrecta por parte del usuario;

   - ningún defecto o daño causado por incendios, terremotos, inundaciones, rayos u otras catástrofes naturales, contaminación ambiental, exposición a radiación ionizante externa o a un campo magnético, así como por un suministro eléctrico irregular o con parámetros distintos de los requeridos;

   - ningún defecto derivado de un almacenamiento incorrecto (por ejemplo, almacenamiento del producto fuera del intervalo de temperatura o humedad indicado en las especificaciones, cerca de productos químicos), de un mantenimiento o una limpieza inadecuados, etc.;

   - ningún defecto derivado del agotamiento de las baterías de alimentación, etc.;

   - ningún defecto causado por arena, barro, polvo, agua y otros líquidos, etc., que hayan penetrado en el interior de la carcasa del producto;

   - los daños producidos por el desgaste natural, parcial o total, del producto de acuerdo con sus propiedades o finalidad;

   - las operaciones indicadas en el manual de instrucciones que el usuario está obligado a realizar por su cuenta.

4. El Comprador pierde los derechos de garantía como consecuencia de:

   - cualquier reparación o modificación del producto realizada por una persona distinta del garante;

   - la constatación de la manipulación, deterioro o rotura de cualquiera de los precintos;

   - la constatación del deterioro, manipulación, ocultación o eliminación de los números de serie u otras marcas de identificación del producto.

5. El plazo de reparación es de hasta 21 días laborables a partir de la fecha de notificación del defecto y de entrega del producto completo al centro de servicio técnico del garante. En casos especialmente justificados, relacionados con la necesidad de importar elementos o componentes del extranjero o con un daño especialmente complejo o difícil de reparar o diagnosticar, el plazo de reparación podrá ampliarse por el tiempo necesario para cumplir las obligaciones de garantía.
6. Los derechos del Comprador derivados de la garantía solo podrán ejercerse previa presentación de una tarjeta de garantía válida y debidamente cumplimentada el día de la compra, así como del justificante de compra (factura, recibo, etc.). Las modificaciones no autorizadas de las anotaciones de la tarjeta de garantía (incluidos tachados, borrados, añadidos, etc.) conllevan la pérdida de los derechos de garantía. Una tarjeta de garantía sin el nombre, modelo y número de serie del producto, la fecha y el lugar de compra del producto, así como el sello legible y la firma del Vendedor, no es válida y no constituye una base válida para presentar una reclamación.
7. El Comprador está obligado a entregar el producto por su cuenta en un embalaje adecuado para el equipo que garantice un transporte y almacenamiento seguros y correctos, o a cubrir los gastos de desplazamiento del garante. Si se determina que el producto entregado para su reparación funciona correctamente y está libre de defectos, o que la avería detectada no está cubierta por la garantía, se cobrarán al Comprador los costes de los servicios y del transporte.
8. El Comprador está obligado a recoger el producto reparado en un plazo de 90 días desde la fecha en que el garante le notifique la reparación. Si el comprador no recoge el producto en dicho plazo, asumirá el riesgo de pérdida o daño accidental del producto.
9. El periodo de garantía se amplía por la duración de la reparación, contada desde la fecha de entrega del producto hasta la fecha acordada para su recogida tras la reparación. El garante está obligado a expedir un documento que indique el periodo y el alcance de los defectos subsanados del producto.

10. El Comprador presentará las reclamaciones a través del Vendedor del producto o directamente a la dirección del garante: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Polonia.

11. El garante no se hace responsable:

    - de los ingresos perdidos como consecuencia de la aparición del defecto y del tiempo necesario para subsanarlo;

    - de las pérdidas ocasionadas por la aparición del defecto ni de los daños derivados de una instalación, utilización o programación incorrectas de las funciones del dispositivo.
