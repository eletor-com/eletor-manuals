---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Preguntas más frecuentes sobre la selección, configuración, diagnóstico
  y servicio técnico de los dispositivos ELETOR.
keywords:
- ELETOR
- FAQ
- controladores de ventilación
- reguladores
- ventiladores
- actuadores
- alarmas
- variadores de frecuencia
- servicio técnico
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Preguntas frecuentes

Estas preguntas frecuentes se han elaborado a partir de un análisis anonimizado de conversaciones reales con usuarios y clientes de ELETOR. Las respuestas se han generalizado para ayudar en los casos habituales y no contienen datos de personas ni de instalaciones concretas.

:::note Alcance de las preguntas frecuentes

Las respuestas se refieren a casos habituales. Las designaciones de los bornes, las funciones y el modo de conexión pueden variar entre modelos y versiones de los dispositivos. En caso de duda, consulte la documentación correspondiente al producto concreto.

:::

:::warning Seguridad

Realice los trabajos en la instalación eléctrica de acuerdo con la documentación del dispositivo y las normas de seguridad vigentes. Los trabajos con tensión de red deben ser realizados por una persona con las cualificaciones adecuadas.

:::

## Selección del controlador y de la potencia

### ¿Cómo seleccionar un controlador para los ventiladores?

La selección se basa principalmente en la corriente total de los ventiladores, y no únicamente en su número.

:::tip Prepare los datos antes de la selección

Cuanto más precisos sean los datos sobre los motores y el funcionamiento de la instalación, más fiable será la selección del controlador.

:::

Antes de la selección, conviene preparar:

- el número de ventiladores,
- la tensión de alimentación,
- la potencia o la corriente nominal de cada ventilador,
- información sobre si todos los ventiladores deben funcionar con regulación continua,
- información sobre si los ventiladores pueden dividirse en grupos,
- información sobre los dispositivos adicionales, por ejemplo, calefactores o entradas de aire.

No debe seleccionarse un controlador cuya capacidad se ajuste exactamente a la carga. Debe mantenerse un margen adecuado respecto a la carga máxima.

### ¿Basta con sumar la potencia de los ventiladores en vatios?

La potencia puede utilizarse para una estimación preliminar, pero la selección definitiva debe basarse en la corriente nominal de los dispositivos y en la naturaleza de la carga.

Durante el arranque, un motor puede consumir más corriente que durante el funcionamiento normal. Por este motivo, dos conjuntos de ventiladores con una potencia nominal similar no siempre constituyen una carga equivalente para el controlador.

### Tengo varios ventiladores pequeños. ¿Puedo conectarlos en paralelo a una sola salida?

Sí, siempre que:

- estén diseñados para este modo de control,
- deban funcionar juntos,
- la suma de las cargas no supere la corriente admisible de la salida,
- el modo de conexión sea conforme con la documentación del controlador.

Si el número de ventiladores es mayor, conviene considerar su división en grupos o el uso de una ampliación de potencia.

### ¿Cuándo se necesita una ampliación de potencia?

Se utiliza una ampliación de potencia cuando la carga supera la capacidad de la salida del controlador o cuando se prevé ampliar la instalación con un mayor número de ventiladores.

En ese caso, el controlador transmite la señal de control, mientras que un módulo adicional se encarga de la carga propiamente dicha.

### ¿Se puede ampliar posteriormente la instalación con ventiladores adicionales?

En muchas instalaciones, sí. Las soluciones más habituales son:

- una ampliación de potencia adicional,
- un grupo de ventilación adicional,
- un contactor que conecte otro grupo,
- un variador de frecuencia en el caso de motores trifásicos.

Lo mejor es prever la ampliación prevista al seleccionar el controlador por primera vez.

### ¿Todos los ventiladores deben funcionar con regulación continua?

No. Hay dos soluciones habituales:

1. todos los ventiladores funcionan con regulación continua,
2. el primer grupo funciona con regulación continua y los grupos siguientes se conectan por etapas, por ejemplo, mediante contactores.

La segunda solución permite controlar una instalación mayor sin regular de forma continua cada ventilador.

### Tengo 10 ventiladores. ¿Necesito un controlador de gran capacidad?

No siempre. Se pueden utilizar varios modos de control:

- división en grupos,
- ampliaciones de potencia,
- contactores,
- un variador de frecuencia.

La selección definitiva depende de los parámetros eléctricos de los ventiladores y de si todos deben cambiar de velocidad de giro simultáneamente.

### ¿Los controladores 6 A y 12 A se diferencian únicamente en la carga admisible?

No debe suponerse que la única diferencia es el valor de la corriente. Las distintas versiones y generaciones de dispositivos pueden diferir en su equipamiento o en su construcción.

Al sustituir un dispositivo, debe comprobarse el modelo exacto y la documentación vigente.


## Ventiladores y control de la ventilación

### ¿El controlador regula los ventiladores de forma continua?

En los controladores destinados a la regulación continua de la ventilación, la velocidad de los ventiladores cambia en función de la demanda derivada, entre otros factores, de la temperatura.

No obstante, debe comprobarse si el tipo de motor en cuestión es adecuado para el modo de regulación utilizado.

### ¿Qué significa la temperatura de consigna?

La temperatura de consigna es el valor con el que el controlador compara la medición actual de temperatura.

A partir de ella, el controlador aumenta o disminuye la intensidad de la ventilación de acuerdo con los demás ajustes, por ejemplo, la banda de regulación y los niveles mínimo y máximo.

### ¿Qué significa el nivel mínimo de ventilación?

Es el valor mínimo de control del ventilador durante el funcionamiento automático.

Este ajuste evita el funcionamiento por debajo de un nivel en el que el ventilador podría funcionar de manera inestable o proporcionar una renovación de aire insuficiente.

### ¿Qué significa el nivel máximo de ventilación?

Es el límite superior del valor de control de la ventilación.

Por ejemplo, ajustar un valor inferior a 100% puede limitar la velocidad máxima de giro del ventilador si la instalación lo requiere.

### ¿Qué significa la banda de ventilación?

La banda de ventilación define el intervalo de temperaturas en el que el controlador pasa del nivel mínimo al nivel máximo de ventilación.

Cuanto menor sea la banda, más rápidamente responderá el control a un cambio de temperatura aumentando el caudal.

### Al arrancar, el ventilador primero alcanza 100% y solo después reduce la velocidad. ¿Por qué?

Puede estar activa una función de arranque cuya finalidad sea arrancar brevemente el motor con una potencia mayor.

Según la versión del controlador, deben comprobarse los ajustes relacionados con:

- la función Soft Start,
- el tiempo de aceleración,
- el tiempo de funcionamiento a 100%,
- el tiempo de deceleración.

Si la función no es necesaria en la instalación en cuestión, los parámetros correspondientes pueden modificarse de acuerdo con el manual del dispositivo.

### ¿Por qué puede arrancarse brevemente el ventilador a plena potencia?

Este tipo de arranque puede ayudar a garantizar el arranque del ventilador, así como en instalaciones cuyos elementos mecánicos pueden ofrecer una mayor resistencia durante el arranque.

Sin embargo, no es necesario en todas las instalaciones.

### ¿Qué significan el tiempo de aceleración y el tiempo de deceleración?

**El tiempo de aceleración** define cómo aumenta el valor de control durante el arranque del ventilador.

**El tiempo de deceleración** define cómo disminuye la velocidad.

Ambos parámetros permiten limitar los cambios bruscos de velocidad de giro y de funcionamiento de la instalación.

### ¿Por qué dos controladores idénticos pueden arrancar los ventiladores de forma diferente?

La causa más habitual es que tengan ajustes diferentes.

Conviene comparar, sobre todo:

- la temperatura de consigna,
- la banda de ventilación,
- el mínimo y el máximo,
- los ajustes de Soft Start,
- los tiempos de aceleración y deceleración,
- la configuración de los grupos de ventilación.

### ¿Puede el controlador activar periódicamente la ventilación con independencia de la temperatura?

Según el modelo, existe una función de ventilación periódica.

Esta puede activar la ventilación durante un tiempo determinado a intervalos establecidos, incluso cuando la regulación de temperatura no requiere aumentar la ventilación.

### ¿Para qué sirven los grupos de ventilación?

Los grupos permiten aumentar por etapas el caudal de la instalación.

Por ejemplo:

- el grupo 1 funciona con regulación continua,
- el grupo 2 activa otros ventiladores,
- el siguiente grupo se activa cuando la demanda es aún mayor.

Esto permite controlar un gran número de ventiladores sin regular de forma continua cada uno de ellos.

### ¿Se puede conectar un grupo adicional de ventiladores mediante un contactor?

Sí. La salida de relé del controlador puede controlar la bobina de un contactor seleccionado adecuadamente.

En ese caso, la corriente de carga de los ventiladores no debe pasar directamente por el pequeño contacto de control.

### ¿Qué significa el símbolo del ventilador o el indicador amarillo del controlador?

Según el modelo, los indicadores informan del estado actual de las salidas y las funciones.

Una indicación amarilla puede señalar una función operativa activa, por ejemplo, el funcionamiento de la ventilación, la calefacción u otro grupo.

El significado exacto debe consultarse en el manual del modelo en cuestión.

### ¿Qué significa el símbolo del modo manual?

El modo manual significa que el usuario ha forzado el valor de control y que, en ese momento, este no se calcula automáticamente a partir de la temperatura.

Una vez finalizadas las pruebas, debe asegurarse de que el controlador se haya restablecido al modo automático adecuado.


## Entradas de aire y actuadores

### ¿Puede el controlador controlar las entradas de aire?

Sí, determinados controladores permiten trabajar con accionamientos de entradas de aire.

El modo de conexión depende del tipo de actuador y de su modo de control.

### ¿Qué tipos de actuadores pueden utilizarse para las entradas de aire?

En las conversaciones técnicas aparecieron con mayor frecuencia dos soluciones:

- un actuador controlado mediante una señal analógica 0–10 V o 2–10 V,
- un actuador reversible de apertura/cierre con señal de realimentación, por ejemplo, de un potenciómetro.

Antes de la compra, debe comprobarse la compatibilidad del modelo concreto con el controlador disponible.

### ¿La tensión de alimentación del actuador 24 V o 230 V influye en la señal 0–10 V?

La señal de control y la alimentación del actuador son parámetros independientes.

El actuador puede alimentarse con una tensión diferente de la tensión de la señal de control. Ambos parámetros deben ser conformes con la documentación del actuador y del controlador.

### ¿Qué significa el control 0–10 V?

El controlador envía una señal analógica de tensión que representa la posición o el nivel de control deseados.

En una aplicación típica, un valor menor significa una apertura menor y un valor mayor, una apertura mayor, pero la característica real debe comprobarse en la documentación del actuador.

### ¿En qué se diferencia 0–10 V de 2–10 V?

En ambos casos, la posición se establece mediante una señal analógica.

En el estándar 2–10 V, la parte inferior del intervalo está desplazada y puede permitir que el dispositivo distinga la señal de control de su ausencia.

El controlador y el actuador deben admitir un intervalo compatible.

### ¿Cómo seleccionar un actuador según el número de entradas de aire?

No debe seleccionarse un actuador únicamente en función del número de compuertas.

Deben tenerse en cuenta:

- la fuerza o el par requeridos,
- la longitud y el recorrido del mecanismo,
- la resistencia de las compuertas,
- la longitud de la carrera,
- la velocidad de actuación,
- la tensión de alimentación,
- el tipo de control,
- la realimentación requerida.

### ¿Puede un solo actuador accionar varias compuertas?

Sí, siempre que la mecánica de la instalación permita unir las compuertas mediante un sistema común y que el par o la fuerza requeridos no superen la capacidad del actuador.

En la práctica, la selección depende de la resistencia de todo el mecanismo, y no únicamente del número de compuertas.

### ¿Se pueden conectar varios actuadores en paralelo y controlarlos con una sola señal?

En algunos sistemas es posible, pero debe verificarse la documentación de los actuadores y la carga admisible de la salida de control.

En el caso de accionamientos reversibles sin realimentación independiente, también puede producirse una divergencia gradual entre las posiciones de los distintos actuadores.

### ¿Por qué varios actuadores pueden situarse en posiciones diferentes con el paso del tiempo?

Incluso motores idénticos pueden funcionar a velocidades ligeramente diferentes debido a:

- cargas distintas,
- resistencias mecánicas,
- tolerancias de los parámetros del motor,
- diferencias en los mecanismos de transmisión.

Por ello, cuando se requiere una sincronización precisa, es necesaria una realimentación adecuada o un control individual de la posición.

### ¿Se pueden controlar las entradas de aire proporcionalmente a la ventilación?

Sí. En sistemas configurados adecuadamente, la posición de las entradas de aire puede vincularse al nivel actual de ventilación.

De este modo, a medida que aumenta el caudal de los ventiladores, también aumenta la apertura de las entradas de aire.

### ¿El actuador 24 V requiere una fuente de alimentación independiente?

Si el controlador no dispone de una salida de alimentación adecuada con la potencia requerida, es necesaria una fuente de alimentación independiente.

Su potencia debe seleccionarse en función del consumo de corriente del actuador y de los demás dispositivos alimentados desde la misma fuente.

### ¿Se puede utilizar un actuador de otro fabricante?

A menudo sí, siempre que sus parámetros eléctricos y su modo de control sean compatibles con las salidas del controlador.

Antes de conectarlo, debe comprobarse:

- la tensión,
- el tipo de señal,
- el esquema de cableado,
- los sentidos de funcionamiento,
- la señal de posición,
- la carga admisible.


## Sensores de temperatura y humedad

### ¿Dónde conectar el sensor de temperatura?

El sensor debe conectarse a la entrada de sensor prevista por el fabricante, la entrada de sensor indicada en la documentación del modelo en cuestión.

No debe suponerse que las designaciones de los bornes son idénticas en todas las versiones de los dispositivos.

### El sensor de temperatura indica un valor diferente al del termómetro de referencia. ¿Qué hacer?

Si el controlador dispone de una función de calibración del sensor, puede corregirse la lectura tras compararla con un termómetro de referencia fiable.

Antes de modificar la calibración, conviene asegurarse de que:

- ambos sensores se encuentran en el mismo lugar,
- la medición se ha estabilizado,
- el sensor no recibe calor del sol ni de otros dispositivos,
- no se encuentra directamente en una corriente de aire frío o caliente.

### El sensor de humedad indica un valor incorrecto. ¿Se puede calibrar?

Depende de la versión del controlador, del sensor y del software.

En algunas soluciones, la corrección puede requerir una función de software específica o un tipo de sensor compatible. Si la diferencia es grande y se repite, debe comprobarse la versión del dispositivo y ponerse en contacto con el soporte técnico.

### ¿Una medición incorrecta significa siempre que el sensor está averiado?

No.

La causa también puede ser:

- una ubicación inadecuada del sensor,
- el cable,
- la conexión eléctrica,
- la configuración,
- un tipo de sensor inadecuado,
- la necesidad de calibración,
- humedad o corrosión.


## Alarmas y notificaciones

### ¿Se puede conectar una sirena directamente a la salida de alarma del controlador?

No debe darse por supuesto.

La salida de alarma del controlador suele ser una salida de control o un contacto de relé. La sirena puede requerir una alimentación independiente y una central de alarma.

### ¿Para qué se utiliza una central de alarma?

La central puede:

- recibir señales de alarma de los controladores,
- alimentar el avisador,
- mantener el funcionamiento durante un corte de alimentación,
- señalizar la alarma mediante sonido o luz,
- enviar notificaciones GSM en las versiones que disponen de esta función.

### ¿Puede la central avisar de un corte de alimentación del controlador?

Sí, si el sistema se ha conectado adecuadamente.

La solución puede detectar no solo que se ha superado la temperatura, sino también la pérdida de señal del controlador causada por un corte de su alimentación.

### ¿Dónde se ajustan las temperaturas mínima y máxima de alarma?

En una configuración típica, los umbrales de alarma se ajustan en el controlador que gestiona la cámara o el recinto en cuestión.

La central de alarma recibe después la información de que el controlador ha notificado una alarma.

### ¿La central GSM requiere una tarjeta SIM?

Para realizar llamadas y enviar mensajes a través de la red móvil, se necesita una tarjeta SIM activa u otra solución de comunicación prevista en el modelo en cuestión.

Sin una conexión activa a la red móvil, las funciones de telefonía y SMS no funcionarán.

### ¿Puede la alarma enviar información sobre el controlador del que procede el evento?

Sí, en un sistema configurado adecuadamente.

Las entradas de la central pueden asignarse a recintos o controladores concretos, de modo que el mensaje permita identificar el origen de la alarma.

### ¿Cuántos controladores pueden conectarse a una sola central de alarma?

Depende del modelo de la central.

En las transcripciones aparecieron centrales que admitían hasta ocho entradas; no obstante, antes de realizar la instalación debe comprobarse la especificación vigente del dispositivo concreto.

### ¿Qué batería se utiliza en la central de alarma?

En algunos de los dispositivos tratados en las conversaciones se utilizaba una batería 12 V 7 Ah.

Antes de comprar una batería de sustitución, debe comprobarse la designación de la batería existente y la especificación de la central, ya que otras versiones de los dispositivos pueden requerir una batería diferente.

### La central envía mensajes de baja tensión. ¿Qué debe comprobarse?

En primer lugar, debe comprobarse:

- el estado de la batería,
- su antigüedad,
- las conexiones de la batería,
- la presencia de alimentación de red,
- el funcionamiento del cargador o de la fuente de alimentación de la central.

Una batería desgastada puede provocar mensajes periódicos de baja tensión.

### ¿Con qué frecuencia debe sustituirse la batería de la central de alarma?

No existe un único intervalo adecuado para todas las condiciones.

La batería debe probarse periódicamente, especialmente en instalaciones en las que la alarma durante un corte de alimentación sea crítica. Con el tiempo, su capacidad real disminuye.

### ¿Una sirena por sí sola es suficiente como protección?

La sirena solo resulta efectiva si alguien puede oírla.

En instalaciones que permanecen temporalmente sin supervisión, conviene utilizar también notificaciones remotas y alimentación de respaldo mediante batería.


## Variadores de frecuencia

### ¿Cómo seleccionar un variador de frecuencia para los ventiladores?

Es necesario conocer:

- la tensión de alimentación,
- el número de fases,
- la potencia y la corriente de todos los motores,
- su modo de conexión,
- las condiciones de funcionamiento,
- el modo de control requerido.

El variador de frecuencia debe tener un margen adecuado respecto a la carga, especialmente cuando varios motores funcionan en paralelo.

### ¿El variador de frecuencia debe tener exactamente la misma potencia que la suma de las potencias de los motores?

No debe seleccionarse un variador de frecuencia únicamente mediante una simple suma de potencias ni elegirse un dispositivo que funcione exactamente en el límite de sus parámetros.

Deben tenerse en cuenta las corrientes nominales, la naturaleza de la carga y las recomendaciones del fabricante del variador de frecuencia.

### El variador de frecuencia ha detenido los ventiladores y ha mostrado un error. ¿Qué hacer?

Lo más importante es anotar el código de error completo antes de restablecer el dispositivo.

:::tip Fotografíe la pantalla

Si la situación lo permite, fotografíe la pantalla antes de restablecer el dispositivo. El código de error completo facilita considerablemente el diagnóstico.

:::

El principio del mensaje por sí solo a menudo no basta para determinar la causa. El código completo permite distinguir, entre otros:

- sobrecarga,
- sobrecorriente,
- sobrecalentamiento,
- tensión incorrecta,
- otros errores del accionamiento.

### ¿Se puede simplemente restablecer el error del variador de frecuencia?

El restablecimiento puede recuperar el funcionamiento, pero no elimina la causa de la alarma.

Después del evento, debe comprobarse el código de error y determinarse la causa antes de volver a poner la instalación en funcionamiento durante un periodo prolongado.

### El variador de frecuencia funciona en un recinto con polvo. ¿Debe limpiarse?

Sí.

El polvo y los depósitos en el disipador o en el ventilador de refrigeración pueden dificultar la disipación del calor y provocar el sobrecalentamiento del variador de frecuencia.

La limpieza debe realizarse de acuerdo con el manual del fabricante, tras desconectar la alimentación de forma segura.

### ¿Qué puede provocar el sobrecalentamiento del variador de frecuencia?

Las causas más frecuentes son:

- elementos de refrigeración sucios,
- flujo de aire obstruido,
- temperatura ambiente demasiado alta,
- sobrecarga,
- avería del ventilador de refrigeración,
- montaje incorrecto.

### ¿Una tensión de red elevada puede provocar una alarma del variador de frecuencia?

Sí. Los variadores de frecuencia supervisan la tensión del circuito de alimentación y pueden notificar un error cuando se supera el nivel admisible.

Si el problema se repite, debe comprobarse la instalación y la calidad de la alimentación.


## Averías y diagnóstico

### El controlador funciona, pero la pantalla no muestra nada. ¿Cuál puede ser la causa?

Entre las posibles causas se incluyen:

- avería de la pantalla,
- problema con el ajuste del contraste en soluciones antiguas,
- conexión dañada,
- corrosión,
- avería de la placa principal.

Si el dispositivo no se ha utilizado durante mucho tiempo o ha funcionado en un ambiente húmedo, conviene comprobar también el estado de la placa.

### El controlador presenta un problema en la pantalla después de varios años sin uso. ¿Por qué?

Una inactividad prolongada en un ambiente húmedo o agresivo puede provocar:

- oxidación de los conectores,
- corrosión,
- deterioro de los contactos,
- daños en los componentes electrónicos.

En tal caso, conviene realizar una revisión completa en lugar de sustituir componentes sin un diagnóstico previo.

### El controlador presenta hollín tras una sobretensión. ¿Significa esto que debe sustituirse la placa?

No siempre.

Un componente de protección puede dañarse y dejar muchos residuos, aunque el resto de la placa pueda repararse.

Sin embargo, si el laminado está carbonizado o quemado, o si las pistas están dañadas, la reparación puede no ser rentable o duradera.

### ¿Qué puede dañar varios controladores al mismo tiempo?

Si varios dispositivos se averían al mismo tiempo, debe comprobarse la instalación de alimentación.

Una de las posibles causas es un problema con el conductor neutro, que en una instalación trifásica puede provocar tensiones incorrectas en los receptores monofásicos.

También pueden producirse sobretensiones procedentes de la red o del grupo electrógeno.

### ¿Qué hacer después de una avería relacionada con una sobretensión?

Antes de conectar un controlador reparado o nuevo, debe determinarse la causa del problema.

:::danger No vuelva a conectar el dispositivo sin comprobar la instalación

Si la causa de la avería fue una tensión incorrecta, un conductor neutro dañado o una sobretensión, el controlador reparado o nuevo puede volver a dañarse.

:::

### ¿Qué es un componente de protección contra sobretensiones en la placa?

En los dispositivos electrónicos se utilizan componentes que limitan las sobretensiones, por ejemplo, varistores.

Su función es absorber parte de la energía de la sobretensión y proteger los circuitos posteriores. Tras un evento intenso, este tipo de componente puede quedar dañado de forma permanente.

### ¿Se puede poner en marcha el dispositivo después de retirar el componente de protección quemado?

Esto no debe considerarse una reparación normal.

Tras retirar la protección, el dispositivo puede perder su protección frente a una nueva sobretensión. Estas actuaciones solo pueden realizarse como un procedimiento de servicio técnico deliberado, por una persona con las cualificaciones adecuadas y después de eliminar la causa de la avería original.

### El dispositivo ha sufrido una entrada de líquido o presenta una corrosión importante. ¿Merece la pena repararlo?

Depende del grado de los daños.

La corrosión superficial y los daños aislados a menudo pueden eliminarse. Si la corrosión afecta a las pistas, los conectores y numerosos componentes, la reparación puede requerir mucho tiempo, ser poco fiable y no estar justificada económicamente.

### ¿El lavado a presión puede dañar el controlador?

Sí.

La electrónica no debe exponerse directamente al agua ni a productos de limpieza si la carcasa y el modo de montaje no están diseñados para ello.

La humedad que penetra en el interior puede provocar corrosión y averías posteriores difíciles de diagnosticar.

### ¿Por qué pueden reaparecer las averías por entrada de líquido después de la reparación?

La corrosión puede seguir avanzando también en lugares que no sean visibles durante la primera inspección.

Las vías, las pistas y las conexiones dañadas pueden funcionar durante la prueba y perder el contacto de nuevo más adelante.

Por ello, si la placa presenta una corrosión importante, el servicio técnico puede recomendar su sustitución en lugar de continuar con las reparaciones.

### El dispositivo funciona de forma intermitente. ¿Por dónde empezar?

Antes de ponerse en contacto con el servicio técnico, conviene recopilar:

- el modelo exacto,
- una descripción del síntoma,
- el momento en que aparece,
- los valores mostrados en la pantalla,
- el código de alarma o error,
- información sobre los últimos cambios en la instalación,
- una fotografía del interior y de los bornes, si puede tomarse de forma segura.

Cuanto más precisa sea la descripción, más fácil será el diagnóstico.


## Servicio técnico y reparaciones

### ¿Qué debe enviarse al servicio técnico si el controlador está averiado?

Lo mejor es enviar un conjunto que permita reproducir el problema.

Debe adjuntarse al envío una breve descripción de:

- qué no funciona,
- cuándo aparece el problema,
- si la avería es permanente o intermitente,
- si antes de la avería se produjo una sobretensión, una entrada de líquido u otro evento,
- los datos necesarios para el contacto y la devolución del dispositivo.

:::note Datos para la solicitud de servicio técnico

Facilite los datos de contacto y de envío directamente al servicio técnico. No los publique en solicitudes abiertas ni en materiales públicos.

:::

### ¿Es necesario enviar todo el controlador o solo la placa?

Depende de la avería.

En caso de problemas con la pantalla, los botones, la alimentación o un comportamiento ambiguo, lo mejor es enviar todo el conjunto necesario para reproducir el síntoma.

Si se ha acordado previamente la reparación de un módulo concreto, el servicio técnico puede solicitar únicamente la placa.

### ¿ELETOR repara los controladores en lugar de sustituirlos directamente?

Las transcripciones indican que los dispositivos se diagnostican primero.

Si la reparación es posible y tiene sentido, se sustituyen los componentes o módulos dañados. En caso de daños graves, el servicio técnico puede proponer la sustitución de la placa o de todo el dispositivo.

### ¿Qué ocurre si no se puede reparar la placa dañada?

Es posible sustituir el módulo dañado por uno nuevo, siempre que la pieza correspondiente esté disponible y sea compatible con el dispositivo.

En dispositivos antiguos, el servicio técnico debe confirmar primero la compatibilidad de las versiones.

### ¿Merece la pena comprar inmediatamente una placa nueva después de una sobretensión?

No siempre.

Si el daño afecta a un componente de protección o a una pequeña parte del circuito, la reparación puede estar justificada. Conviene realizar primero un diagnóstico.

### ¿Puede el servicio técnico comprobar también la pantalla y los botones?

Sí, si los componentes se entregan junto con el dispositivo o el módulo.

Esto resulta especialmente útil cuando no se sabe si el problema se encuentra en la placa principal o en el panel de usuario.

### ¿Siempre merece la pena recuperar un controlador con corrosión importante?

No.

Si el coste del diagnóstico y la reparación aumenta y la fiabilidad tras la reparación sigue siendo incierta, la sustitución puede ser más razonable.

Esto se aplica especialmente a los dispositivos de los que depende la ventilación de la instalación.

### ¿Cómo agilizar el diagnóstico del servicio técnico?

Adjunte una descripción precisa del síntoma en lugar de limitarse a indicar «no funciona».

También resultan útiles:

- fotografías,
- el código de error,
- una descripción de la instalación,
- el tipo de receptores conectados,
- información sobre una sobretensión o un corte de alimentación,
- información sobre una entrada de líquido o el lavado del dispositivo.


## Instalación y cableado

### ¿Cómo conectar dispositivos a los bornes de relé C y NO?

C y NO son designaciones habituales de los contactos de relé:

- C — contacto común,
- NO — contacto normalmente abierto.

El modo de uso depende del dispositivo y del esquema de la instalación. El contacto puede utilizarse, por ejemplo, para controlar la bobina de un contactor, pero no deben superarse sus parámetros admisibles.

:::warning Trabajos eléctricos

Las conexiones a tensión de red deben ser realizadas por una persona con las cualificaciones adecuadas, de acuerdo con el esquema del dispositivo concreto.

:::

### ¿Puede una salida de relé alimentar directamente un ventilador grande?

Por lo general, este no es un uso adecuado de una pequeña salida de control.

Para cargas mayores se utiliza un contactor, un relé de potencia o un módulo de accionamiento específico.

### ¿Para qué sirven los bornes A1 y A2 del contactor?

Son los bornes de la bobina del contactor.

Al aplicar la tensión adecuada a la bobina, el contactor cambia el estado de sus contactos de potencia.

La tensión de la bobina debe ser conforme con el diseño de la instalación y la documentación del contactor.

### ¿Se pueden montar aparatos adicionales dentro de la carcasa del controlador?

Solo si el diseño de la carcasa concreta lo permite y no se perjudica:

- el grado de protección,
- el aislamiento,
- la refrigeración,
- la seguridad,
- el acceso para el mantenimiento.

Cualquier orificio nuevo debe realizarse de forma que se mantenga la estanqueidad requerida.

### ¿Son útiles los interruptores adicionales para los ventiladores?

Pueden facilitar el mantenimiento y permitir la desconexión independiente de cada ventilador.

No obstante, la ejecución debe tener en cuenta las protecciones eléctricas y no debe provocar estados peligrosos del controlador.

### ¿Se pueden tender los cables de control junto con los cables de potencia?

Debe evitarse tender cables de señal sensibles en paralelo y muy cerca de cables de alta potencia, especialmente en tramos largos.

Los requisitos dependen del tipo de señal y del entorno electromagnético.

### ¿Qué cable debe utilizarse para las conexiones de red y los dispositivos PoE?

En las instalaciones tratadas, se indicaba como mínimo un cable de par trenzado de categoría 5e.

Si el cable discurre por un entorno con un nivel elevado de interferencias o riesgo de cargas electrostáticas, puede ser conveniente utilizar un cable con un apantallamiento adecuado y un sistema de puesta a tierra correcto.

### ¿Se necesita un cable cruzado para PoE?

En las instalaciones habituales se utiliza una conexión directa estándar.

No obstante, siempre deben comprobarse los requisitos del dispositivo de red y de la fuente de alimentación PoE utilizada.


## Uso y mantenimiento

### ¿Cómo reducir el riesgo de avería de los controladores en edificios agropecuarios?

Lo más importante es limitar los efectos de:

- la humedad,
- el amoníaco y el ambiente agresivo,
- el polvo,
- el lavado directo con agua,
- las sobretensiones,
- la alimentación incorrecta.

También conviene comprobar periódicamente el estado de los cables, las conexiones y las carcasas.

### ¿Deben limpiarse regularmente los dispositivos electrónicos?

Sí, especialmente los dispositivos equipados con disipadores, ventiladores y aberturas de ventilación.

El polvo acumulado perjudica la refrigeración.

La limpieza debe realizarse tras desconectar la alimentación y de acuerdo con el manual del dispositivo.

### ¿Conviene realizar una revisión del controlador después de varios años de funcionamiento?

Sí, especialmente en condiciones ambientales difíciles.

La revisión puede incluir:

- la evaluación del estado de los conectores,
- la comprobación de indicios de humedad y corrosión,
- la comprobación de los elementos de refrigeración,
- la comprobación del panel y de los botones,
- la prueba de los sensores,
- la comprobación de las baterías de los sistemas de alarma.

### ¿Qué conviene anotar después de una avería?

Los datos más útiles son:

- el mensaje completo,
- el código de error,
- la hora del evento,
- la temperatura,
- el estado de la ventilación,
- información sobre un corte de alimentación,
- información sobre el funcionamiento del grupo electrógeno,
- una fotografía de la pantalla o del dispositivo.

No debe restablecerse el dispositivo antes de anotar el código, si la situación permite hacerlo de forma segura.

### ¿Conviene disponer de una alarma independiente del controlador de ventilación?

Sí, especialmente cuando una avería de la ventilación pueda provocar rápidamente condiciones peligrosas.

Una central independiente con su propia batería y notificaciones remotas proporciona una capa adicional de protección.

### ¿Qué información debe prepararse antes de ponerse en contacto con el soporte técnico?

Lo mejor es preparar:

1. el modelo exacto del dispositivo,
2. una descripción de la instalación,
3. el número y los parámetros de los dispositivos conectados,
4. los ajustes actuales relacionados con el problema,
5. el síntoma exacto,
6. el código completo de error o alarma,
7. fotografías del dispositivo y de las placas de características,
8. información sobre los últimos cambios en la instalación.

Esto permite reducir considerablemente el tiempo de diagnóstico.


## Nota importante sobre los dispositivos antiguos

Los nombres, las designaciones de los bornes y las funciones disponibles pueden variar entre las versiones de los dispositivos fabricados en distintos años.

Si el dispositivo tiene varios años o más de diez años, antes de aplicar las instrucciones de un modelo más reciente debe confirmarse:

- la designación exacta del dispositivo,
- la versión de la placa,
- el tipo de pantalla,
- la versión del software,
- el esquema de bornes.

:::warning Versiones antiguas de los dispositivos

No suponga una compatibilidad total basándose únicamente en un aspecto similar de la carcasa. Antes de utilizar un esquema o un manual, confirme el modelo y la versión exactos del dispositivo.

:::


## Contacto con el soporte técnico

Si estas preguntas frecuentes no resuelven el problema, prepare lo siguiente antes de ponerse en contacto:

- una fotografía del controlador,
- una fotografía de la placa de características del receptor,
- los parámetros de los motores o actuadores,
- el esquema de conexiones,
- una descripción precisa del funcionamiento esperado.

De este modo, la selección del dispositivo o el diagnóstico del problema pueden realizarse a partir de los parámetros reales de la instalación, y no de suposiciones.
