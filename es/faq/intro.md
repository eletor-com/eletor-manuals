---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Preguntas más frecuentes sobre la selección, la configuración, el diagnóstico
  y el servicio técnico de los dispositivos ELETOR.
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

Las preguntas frecuentes se elaboraron a partir de un análisis anonimizado de conversaciones reales con usuarios y clientes de ELETOR. Las respuestas se han generalizado para ayudar en casos típicos y no contienen datos de personas ni de instalaciones concretas.

:::note Alcance de las preguntas frecuentes

Las respuestas se refieren a casos típicos. Las designaciones de bornes, las funciones y la forma de conexión pueden variar entre modelos y versiones de los dispositivos. En caso de duda, utilice la documentación correspondiente al producto concreto.

:::

:::warning Seguridad

Realice los trabajos en la instalación eléctrica de acuerdo con la documentación del dispositivo y las normas de seguridad vigentes. Los trabajos con tensión de red deben ser realizados por una persona con las cualificaciones adecuadas.

:::

## Selección del controlador y de la potencia

### ¿Cómo seleccionar un controlador para ventiladores?

La base de la selección es, ante todo, la corriente total de los ventiladores, y no únicamente su número.

:::tip Prepare los datos antes de la selección

Cuanto más precisos sean los datos sobre los motores y el modo de funcionamiento de la instalación, más segura será la selección del controlador.

:::

Antes de la selección conviene preparar:

- el número de ventiladores,
- la tensión de alimentación,
- la potencia o la corriente nominal de cada ventilador,
- información sobre si todos los ventiladores deben funcionar de forma continua y regulable,
- información sobre si los ventiladores pueden dividirse en grupos,
- información sobre dispositivos adicionales, por ejemplo, calefactores o entradas de aire.

El controlador no debe seleccionarse exactamente “al límite”. Debe mantenerse un margen adecuado con respecto a la carga máxima.

### ¿Basta con sumar la potencia de los ventiladores en vatios?

Para una estimación preliminar se puede utilizar la potencia, pero la selección final debe basarse en la corriente nominal de los dispositivos y en el carácter de la carga.

Durante el arranque, el motor puede consumir más corriente que durante el funcionamiento normal. Por este motivo, dos conjuntos de ventiladores con una potencia nominal similar no siempre constituyen una carga equivalente para el controlador.

### Tengo varios ventiladores pequeños. ¿Puedo conectarlos en paralelo a una sola salida?

Sí, si:

- están destinados a este modo de control,
- deben funcionar juntos,
- la suma de las cargas no supera la corriente admisible de la salida,
- el método de conexión es conforme con la documentación del controlador.

Con un mayor número de ventiladores, conviene considerar la división en grupos o el uso de una ampliación de potencia.

### ¿Cuándo se necesita una ampliación de potencia?

La ampliación de potencia se utiliza cuando la carga supera las capacidades de la salida del controlador o cuando la instalación debe ampliarse con un mayor número de ventiladores.

En ese caso, el controlador transmite la señal de control, mientras que la carga real es gestionada por un módulo adicional.

### ¿Puede ampliarse más adelante la instalación con ventiladores adicionales?

En muchas instalaciones, sí. Lo más habitual es utilizar:

- una ampliación de potencia adicional,
- un grupo de ventilación adicional,
- un contactor que conecte otro grupo,
- un variador de frecuencia en el caso de motores trifásicos.

Lo mejor es prever la ampliación planificada ya durante la primera selección del controlador.

### ¿Deben funcionar todos los ventiladores con regulación continua?

No. Son típicas dos soluciones:

1. todos los ventiladores funcionan con regulación continua,
2. el primer grupo funciona con regulación continua y los grupos siguientes se conectan gradualmente, por ejemplo, mediante contactores.

La segunda solución permite gestionar una instalación más grande sin regulación continua de cada ventilador.

### Tengo 10 ventiladores. ¿Necesito un controlador muy grande?

No siempre. Se pueden aplicar varios métodos de control:

- división en grupos,
- ampliaciones de potencia,
- contactores,
- variador de frecuencia.

La selección final depende de los parámetros eléctricos de los ventiladores y de si todos deben cambiar de velocidad al mismo tiempo.

### ¿El controlador 6 A y 12 A se diferencian solo en la carga admisible?

No debe suponerse que la única diferencia es el valor de la corriente. Las distintas versiones y generaciones de dispositivos pueden diferir en el equipamiento o en la forma de construcción.

Al sustituir un dispositivo, debe comprobarse el modelo exacto y la documentación vigente.


## Ventiladores y control de la ventilación

### ¿El controlador regula los ventiladores de forma continua?

En los controladores destinados a la regulación continua de la ventilación, la velocidad de los ventiladores se modifica en función de la demanda resultante, entre otros factores, de la temperatura.

No obstante, debe comprobarse si el tipo de motor dado es adecuado para el método de regulación utilizado.

### ¿Qué significa temperatura de consigna?

La temperatura de consigna es el valor con respecto al cual el controlador compara la medición actual de temperatura.

Sobre esta base, el controlador aumenta o disminuye la intensidad de la ventilación de acuerdo con los demás ajustes, por ejemplo, la banda de regulación, el nivel mínimo y el máximo.

### ¿Qué significa nivel mínimo de ventilación?

Es el valor mínimo de control del ventilador durante el funcionamiento automático.

Este ajuste evita el funcionamiento por debajo del nivel en el que el ventilador podría funcionar de forma inestable o proporcionar un intercambio de aire insuficiente.

### ¿Qué significa nivel máximo de ventilación?

Es la limitación superior del valor de control de la ventilación.

Por ejemplo, ajustar un valor inferior a 100% puede limitar las revoluciones máximas del ventilador, si la instalación así lo requiere.

### ¿Qué significa banda de ventilación?

La banda de ventilación define el intervalo de temperatura en el que el controlador pasa del nivel mínimo al nivel máximo de ventilación.

Cuanto menor sea la banda, más rápidamente reaccionará el control con un aumento del rendimiento ante un cambio de temperatura.

### El ventilador, al ponerse en marcha, primero sube a 100% y solo después reduce la velocidad. ¿Por qué?

Puede estar activa una función de arranque cuyo propósito es poner en marcha momentáneamente el motor con mayor potencia.

Según la versión del controlador, deben comprobarse los ajustes relacionados con:

- la función Soft Start,
- el tiempo de aceleración,
- el tiempo de funcionamiento a 100%,
- el tiempo de desaceleración.

Si la función no es necesaria en una instalación determinada, los parámetros correspondientes pueden modificarse de acuerdo con el manual del dispositivo.

### ¿Por qué el ventilador puede arrancar momentáneamente a plena potencia?

Este tipo de arranque puede ayudar a garantizar una puesta en marcha fiable del ventilador, así como en instalaciones en las que los elementos mecánicos pueden ofrecer mayor resistencia durante el arranque.

No obstante, no es necesario en todas las instalaciones.

### ¿Qué significan el tiempo de aceleración y el tiempo de desaceleración?

**El tiempo de aceleración** define la forma en que aumenta la señal de control durante el arranque del ventilador.

**El tiempo de desaceleración** define la forma en que disminuye la velocidad.

Ambos parámetros permiten limitar los cambios bruscos de revoluciones y del funcionamiento de la instalación.

### ¿Por qué dos controladores idénticos pueden arrancar los ventiladores de forma diferente?

La causa más frecuente son ajustes distintos.

Conviene comparar sobre todo:

- la temperatura de consigna,
- la banda de ventilación,
- el mínimo y el máximo,
- los ajustes de Soft Start,
- los tiempos de aceleración y desaceleración,
- la configuración de los grupos de ventilación.

### ¿Puede el controlador poner en marcha periódicamente la ventilación independientemente de la temperatura?

Según el modelo, está disponible una función de ventilación periódica.

Puede poner en marcha la ventilación durante un tiempo determinado a intervalos definidos, incluso cuando la regulación por temperatura no requiera aumentar la ventilación.

### ¿Para qué sirven los grupos de ventilación?

Los grupos permiten aumentar gradualmente el rendimiento de la instalación.

Por ejemplo:

- el grupo 1 funciona con regulación continua,
- el grupo 2 pone en marcha ventiladores adicionales,
- el siguiente grupo se activa cuando la demanda es aún mayor.

Esto permite controlar un gran número de ventiladores sin regulación continua de cada uno de ellos.

### ¿Se puede conectar un grupo adicional de ventiladores mediante un contactor?

Sí. La salida de relé del controlador puede controlar la bobina de un contactor correctamente seleccionado.

La carga de los ventiladores no debe conducirse entonces directamente a través del pequeño contacto de control.

### ¿Qué significa el símbolo del ventilador o el indicador amarillo en el controlador?

Según el modelo, los indicadores informan sobre el estado actual de las salidas y las funciones.

La señalización amarilla puede significar una función de trabajo activa, por ejemplo, funcionamiento de la ventilación, la calefacción o un grupo adicional.

El significado exacto debe comprobarse en el manual del modelo correspondiente.

### ¿Qué significa el símbolo del modo manual?

El modo manual significa que el valor de control ha sido forzado por el usuario y no se está calculando automáticamente en ese momento sobre la base de la temperatura.

Una vez finalizadas las pruebas, debe asegurarse de que el controlador haya vuelto al modo automático correcto.


## Entradas de aire y actuadores

### ¿Puede el controlador controlar las entradas de aire?

Sí, los controladores seleccionados permiten trabajar con accionamientos de entradas de aire.

La forma de conexión depende del tipo de actuador y del modo de control del mismo.

### ¿Qué tipos de actuadores pueden utilizarse para las entradas?

En las conversaciones técnicas aparecieron con mayor frecuencia dos soluciones:

- actuador controlado por señal analógica 0–10 V o 2–10 V,
- actuador reversible abrir/cerrar con señal de realimentación, por ejemplo, desde un potenciómetro.

Antes de la compra, debe comprobarse la compatibilidad del modelo concreto con el controlador disponible.

### ¿La tensión de alimentación del actuador 24 V o 230 V influye en la señal 0–10 V?

La señal de control y la alimentación del actuador son parámetros independientes.

El actuador puede alimentarse con una tensión distinta de la tensión de la señal de control. Ambos parámetros deben ser conformes con la documentación del actuador y del controlador.

### ¿Qué significa control 0–10 V?

El controlador envía una señal analógica de tensión que representa la posición solicitada o el nivel de control.

En una aplicación típica, un valor más bajo significa una apertura menor y un valor más alto una mayor, pero la característica real debe comprobarse en la documentación del actuador.

### ¿En qué se diferencia 0–10 V de 2–10 V?

En ambos casos, la posición se define mediante una señal analógica.

En el estándar 2–10 V la parte inferior del rango está desplazada y puede permitir que el dispositivo distinga la señal de control de su ausencia.

El controlador y el actuador deben admitir un rango compatible.

### ¿Cómo seleccionar un actuador según el número de entradas de aire?

No debe seleccionarse un actuador basándose únicamente en el número de compuertas.

Es necesario tener en cuenta:

- la fuerza o el par requeridos,
- la longitud y el modo de guiado del mecanismo,
- la resistencia de las compuertas,
- la longitud de carrera,
- la velocidad de funcionamiento,
- la tensión de alimentación,
- el tipo de control,
- la realimentación requerida.

### ¿Puede un solo actuador accionar varias compuertas?

Sí, si la mecánica de la instalación permite unir las compuertas mediante un sistema común y el par o la fuerza requeridos no superan la capacidad del actuador.

En la práctica, la selección viene determinada por la resistencia de todo el mecanismo, y no por el mero número de compuertas.

### ¿Pueden conectarse varios actuadores en paralelo y controlarse con una sola señal?

En algunos sistemas es posible, pero debe verificarse la documentación de los actuadores y la carga admisible de la salida de control.

En el caso de accionamientos reversibles sin realimentación independiente, también puede producirse una desincronización gradual de la posición de los distintos actuadores.

### ¿Por qué varios actuadores pueden colocarse con el tiempo en posiciones diferentes?

Incluso motores idénticos pueden funcionar a velocidades ligeramente distintas debido a:

- cargas diferentes,
- resistencias mecánicas,
- tolerancia de los parámetros del motor,
- diferencias en las transmisiones.

Por ello, cuando se requiere una sincronización precisa, es necesaria una realimentación adecuada o un control individual de posición.

### ¿Pueden controlarse las entradas proporcionalmente a la ventilación?

Sí. En sistemas configurados adecuadamente, la posición de las entradas puede vincularse al nivel actual de ventilación.

De este modo, al aumentar el rendimiento de los ventiladores, también aumenta la apertura de las entradas.

### ¿El actuador 24 V requiere una fuente de alimentación independiente?

Si el controlador no dispone de una salida de alimentación adecuada con la potencia requerida, se necesita una fuente de alimentación independiente.

Su potencia debe seleccionarse en función del consumo de corriente del actuador y de otros dispositivos alimentados desde la misma fuente.

### ¿Se puede utilizar un actuador de otro fabricante?

A menudo sí, si sus parámetros eléctricos y el modo de control son compatibles con las salidas del controlador.

Antes de la conexión, debe comprobarse:

- la tensión,
- el tipo de señal,
- el esquema de cableado,
- los sentidos de funcionamiento,
- la señal de posición,
- la carga admisible.


## Sensores de temperatura y humedad

### ¿Dónde conectar el sensor de temperatura?

El sensor debe conectarse a la entrada de sensor prevista por el fabricante, a la entrada de sensor indicada en la documentación del modelo correspondiente.

No debe suponerse que las designaciones de los bornes son idénticas en todas las versiones de los dispositivos.

### El sensor de temperatura muestra un valor distinto al de un termómetro de referencia. ¿Qué hacer?

Si el controlador dispone de una función de calibración del sensor, la indicación puede corregirse tras compararla con un termómetro de referencia fiable.

Antes de modificar la calibración, conviene asegurarse de que:

- ambos sensores estén en el mismo lugar,
- la medición se haya estabilizado,
- el sensor no esté calentado por el sol o por dispositivos,
- no esté situado directamente en la corriente de aire frío o caliente.

### El sensor de humedad muestra un valor incorrecto. ¿Puede calibrarse?

Depende de la versión del controlador, del sensor y del software.

En algunas soluciones, la corrección puede requerir una función de software adecuada o un tipo de sensor compatible. Si la diferencia es grande y repetible, debe comprobarse la versión del dispositivo y ponerse en contacto con el soporte técnico.

### ¿Una medición incorrecta significa siempre que el sensor está dañado?

No.

La causa también puede ser:

- ubicación incorrecta del sensor,
- el cable,
- la conexión eléctrica,
- la configuración,
- tipo de sensor incorrecto,
- necesidad de calibración,
- humedad o corrosión.


## Alarmas y notificaciones

### ¿Se puede conectar directamente una sirena a la salida de alarma del controlador?

No debe suponerse así.

La salida de alarma del controlador suele ser una salida de control o un contacto de relé. La sirena puede requerir alimentación independiente y una central de alarma.

### ¿Para qué se utiliza una central de alarma?

La central puede:

- recibir señales de alarma de los controladores,
- alimentar el avisador,
- mantener el funcionamiento durante un corte de alimentación,
- señalizar la alarma con sonido o luz,
- enviar notificaciones GSM en las versiones que dispongan de esta función.

### ¿Puede la central avisar sobre la pérdida de alimentación del controlador?

Sí, si el sistema se ha conectado adecuadamente.

La solución puede detectar no solo el exceso de temperatura, sino también la pérdida de señal del controlador provocada por la pérdida de su alimentación.

### ¿Dónde se ajusta la temperatura mínima y máxima de alarma?

En una configuración típica, los umbrales de alarma se ajustan en el controlador que gestiona la cámara o sala correspondiente.

A continuación, la central de alarma recibe la información de que el controlador ha señalado una alarma.

### ¿La central GSM requiere una tarjeta SIM?

Para enviar llamadas y mensajes a través de la red celular se necesita una tarjeta SIM activa u otra solución de comunicación prevista en el modelo correspondiente.

Sin una conexión activa a la red celular, las funciones telefónicas y SMS no funcionarán.

### ¿Puede la alarma enviar información sobre de qué controlador procede el evento?

Sí, en un sistema configurado adecuadamente.

Las entradas de la central pueden asignarse a salas o controladores concretos, de modo que el mensaje permita determinar el origen de la alarma.

### ¿Cuántos controladores pueden conectarse a una sola central de alarma?

Depende del modelo de la central.

En las transcripciones aparecían centrales que admitían hasta ocho entradas; no obstante, antes de realizar la instalación debe comprobarse la especificación vigente del dispositivo concreto.

### ¿Qué batería se utiliza en la central de alarma?

En parte de los dispositivos tratados en las conversaciones se utilizaba una batería 12 V 7 Ah.

Antes de comprar un repuesto, debe comprobarse la designación de la batería existente y la especificación de la central, ya que otras versiones de los dispositivos pueden requerir una batería diferente.

### La central envía mensajes de baja tensión. ¿Qué debe comprobarse?

En primer lugar, debe comprobarse:

- el estado de la batería,
- su antigüedad,
- las conexiones de la batería,
- la presencia de alimentación de red,
- el funcionamiento del cargador o de la fuente de alimentación de la central.

Una batería desgastada puede provocar mensajes cíclicos de baja tensión.

### ¿Con qué frecuencia debe sustituirse la batería de la central de alarma?

No existe un valor único adecuado para todas las condiciones.

La batería debe probarse periódicamente, especialmente en instalaciones en las que la alarma durante una pérdida de alimentación tiene una importancia crítica. Con el paso del tiempo, su capacidad real disminuye.

### ¿Basta la sirena sola como protección?

La sirena solo actúa cuando alguien puede oírla.

En instalaciones que permanecen temporalmente sin supervisión, conviene utilizar también una notificación remota y respaldo mediante batería.


## Variadores de frecuencia

### ¿Cómo seleccionar un variador de frecuencia para ventiladores?

Es necesario conocer:

- la tensión de alimentación,
- el número de fases,
- la potencia y la corriente de todos los motores,
- la forma de su conexión,
- las condiciones de funcionamiento,
- el método de control requerido.

El variador de frecuencia debe disponer de un margen adecuado con respecto a la carga, especialmente cuando varios motores funcionan en paralelo.

### ¿Debe el variador de frecuencia tener exactamente la misma potencia que la suma de las potencias de los motores?

No debe seleccionarse un variador de frecuencia únicamente sobre la base de una simple suma de potencias ni elegir un dispositivo que funcione exactamente en el límite de sus parámetros.

Deben tenerse en cuenta las corrientes nominales, el carácter de la carga y las recomendaciones del fabricante del variador de frecuencia.

### El variador de frecuencia detuvo los ventiladores y mostró un error. ¿Qué hacer?

Lo más importante es anotar el código de error completo antes de reiniciar.

:::tip Tome una foto de la pantalla

Si la situación lo permite, antes de reiniciar haga una foto de la pantalla. El código de error completo facilita considerablemente el diagnóstico.

:::

A menudo, el inicio del mensaje no basta para determinar la causa. El código completo permite distinguir, entre otros:

- sobrecarga,
- exceso de corriente,
- sobrecalentamiento,
- tensión incorrecta,
- otros errores del accionamiento.

### ¿Se puede simplemente reiniciar el error del variador de frecuencia?

El reinicio puede restablecer el funcionamiento, pero no elimina la causa de la alarma.

Después del evento, debe comprobarse el código de error y determinar la causa antes de volver a poner la instalación en funcionamiento prolongado.

### El variador de frecuencia funciona en una sala con polvo. ¿Es necesario limpiarlo?

Sí.

El polvo y los depósitos en el disipador o en el ventilador de refrigeración pueden empeorar la disipación térmica y provocar el sobrecalentamiento del variador de frecuencia.

La limpieza debe realizarse de acuerdo con el manual del fabricante, tras desconectar la alimentación de forma segura.

### ¿Qué puede causar el sobrecalentamiento del variador de frecuencia?

Las causas más frecuentes son:

- elementos de refrigeración sucios,
- flujo de aire obstruido,
- temperatura ambiente demasiado alta,
- sobrecarga,
- avería del ventilador de refrigeración,
- montaje incorrecto.

### ¿Puede una tensión de red elevada provocar una alarma del variador de frecuencia?

Sí. Los variadores de frecuencia supervisan la tensión del circuito de alimentación y pueden señalar un error al superarse el nivel admisible.

Si el problema se repite, debe revisarse la instalación y la calidad de la alimentación.


## Averías y diagnóstico

### El controlador funciona, pero la pantalla no muestra nada. ¿Cuál puede ser la causa?

Las posibles causas incluyen, entre otras:

- avería de la pantalla,
- problema con el ajuste de contraste en soluciones antiguas,
- avería de la conexión,
- corrosión,
- avería de la placa principal.

Si el dispositivo no se ha utilizado durante mucho tiempo o ha funcionado en un entorno húmedo, conviene comprobar también el estado de la placa.

### El controlador presenta problemas con la pantalla después de varios años sin uso. ¿Por qué?

Una parada prolongada en un entorno húmedo o agresivo puede provocar:

- oxidación de conectores,
- corrosión,
- deterioro de los contactos,
- daños en componentes electrónicos.

En ese caso, conviene realizar una revisión completa y no sustituir componentes sin un diagnóstico previo.

### El controlador está ennegrecido por una sobretensión. ¿Significa eso que la placa debe sustituirse?

No siempre.

Un elemento de protección puede dañarse y dejar muchos residuos, aunque el resto de la placa siga siendo reparable.

Sin embargo, si el laminado está carbonizado, quemado o las pistas están dañadas, la reparación puede no ser rentable o no ser duradera.

### ¿Qué puede dañar varios controladores al mismo tiempo?

Si varios dispositivos fallan al mismo tiempo, debe comprobarse la instalación de alimentación.

Una de las posibles causas es un problema con el conductor neutro que, en una instalación trifásica, puede provocar la aparición de tensiones incorrectas en receptores monofásicos.

También son posibles sobretensiones procedentes de la red o del generador.

### ¿Qué hacer después de una avería relacionada con una sobretensión?

Antes de conectar un controlador reparado o nuevo, debe determinarse la causa del problema.

:::danger No vuelva a conectar el dispositivo sin comprobar la instalación

Si la causa de la avería fue una tensión incorrecta, un conductor neutro dañado o una sobretensión, el controlador reparado o el nuevo puede volver a dañarse.

:::

### ¿Qué es un elemento de protección contra sobretensiones en la placa?

En los dispositivos electrónicos se utilizan componentes limitadores de sobretensiones, por ejemplo, varistores.

Su función es absorber parte de la energía de la sobretensión y proteger los circuitos posteriores. Tras un evento intenso, dicho componente puede sufrir daños permanentes.

### ¿Se puede poner en funcionamiento el dispositivo después de retirar un elemento de protección quemado?

No debe considerarse una reparación normal.

Tras retirar la protección, el dispositivo puede perder la protección frente a una nueva sobretensión. Este tipo de acciones solo pueden llevarse a cabo como un procedimiento de servicio consciente por una persona con las cualificaciones adecuadas y después de eliminar la causa original de la avería.

### El controlador se ha inundado o está muy corroído. ¿Vale la pena repararlo?

Depende del grado de daño.

La corrosión superficial y los daños aislados a menudo pueden eliminarse. Si la corrosión afecta a las pistas, los conectores y muchos componentes, la reparación puede requerir mucho tiempo, ser incierta y no estar justificada económicamente.

### ¿Puede el lavado a presión del dispositivo dañar el controlador?

Sí.

La electrónica no debe exponerse directamente al agua ni al agente de limpieza si la carcasa y la forma de montaje no están diseñadas para ello.

La humedad que penetra en el interior puede provocar corrosión y fallos posteriores difíciles de diagnosticar.

### ¿Por qué las averías después de una inundación pueden reaparecer tras la reparación?

La corrosión puede seguir avanzando también en lugares no visibles durante la primera inspección.

Las vías metalizadas, pistas y conexiones dañadas pueden funcionar durante la prueba y después volver a perder contacto.

Por ello, en una placa fuertemente corroída, el servicio técnico puede recomendar la sustitución en lugar de reparaciones adicionales.

### El dispositivo a veces funciona y a veces no. ¿Por dónde empezar?

Conviene recopilar antes de contactar con el servicio técnico:

- el modelo exacto,
- la descripción del síntoma,
- el momento en que aparece,
- los valores mostrados en la pantalla,
- el código de alarma o de error,
- información sobre los últimos cambios en la instalación,
- una foto del interior y de los bornes, si puede hacerse de forma segura.

Cuanto más precisa sea la descripción, más fácil será el diagnóstico.


## Servicio técnico y reparaciones

### ¿Qué enviar al servicio técnico si el controlador está dañado?

Lo mejor es enviar un conjunto completo que permita reproducir el problema.

En el envío debe incluirse una breve descripción:

- de qué no funciona,
- cuándo aparece el problema,
- si la avería es permanente o periódica,
- si antes de la avería se produjo una sobretensión, inundación u otro evento,
- los datos necesarios para el contacto y la devolución del dispositivo.

:::note Datos para la solicitud de servicio técnico

Facilite los datos de contacto y de envío directamente al servicio técnico. No los publique en solicitudes abiertas ni en materiales públicos.

:::

### ¿Es necesario enviar el controlador completo o solo la placa?

Depende de la avería.

En caso de problemas con la pantalla, los botones, la alimentación o un comportamiento ambiguo, lo mejor es enviar el conjunto completo necesario para reproducir el síntoma.

En una reparación previamente acordada de un módulo concreto, el servicio técnico puede solicitar únicamente la placa.

### ¿ELETOR repara los controladores en lugar de sustituirlos inmediatamente?

De las transcripciones se desprende que los dispositivos se diagnostican primero.

Si la reparación es posible y tiene sentido, se sustituyen los componentes o módulos dañados. En caso de daños graves, el servicio técnico puede proponer la sustitución de la placa o del dispositivo completo.

### ¿Qué ocurre si la placa dañada no se puede reparar?

Es posible sustituir el módulo dañado por uno nuevo, siempre que la pieza correspondiente esté disponible y sea compatible con el dispositivo.

En los dispositivos más antiguos, el servicio técnico debe confirmar primero la compatibilidad de la versión.

### ¿Vale la pena comprar inmediatamente una placa nueva después de una sobretensión?

No siempre.

Si el daño afecta al elemento de protección o a una pequeña parte del circuito, la reparación puede estar justificada. Conviene realizar primero un diagnóstico.

### ¿Puede el servicio técnico comprobar también la pantalla y los botones?

Sí, si los elementos se entregan junto con el dispositivo o módulo.

Esto es especialmente útil cuando no se sabe si el problema se encuentra en la placa principal o en el panel de usuario.

### ¿Siempre merece la pena intentar salvar un controlador muy corroído?

No.

Si el coste del diagnóstico y de la reparación aumenta y la fiabilidad después de la reparación sigue siendo incierta, la sustitución puede ser más razonable.

Esto se aplica especialmente a los dispositivos de los que depende la ventilación de la instalación.

### ¿Cómo acelerar el diagnóstico del servicio técnico?

Adjunte una descripción precisa del síntoma en lugar de la simple afirmación “no funciona”.

También son útiles:

- fotos,
- el código de error,
- la descripción de la instalación,
- el tipo de receptores conectados,
- información sobre sobretensión o pérdida de alimentación,
- información sobre inundación o lavado del dispositivo.


## Instalación y cableado

### ¿Cómo conectar los dispositivos a los bornes de relé C y NO?

C y NO son designaciones típicas de un contacto de relé:

- C — contacto común,
- NO — contacto normalmente abierto.

La forma de uso depende del dispositivo y del esquema de la instalación. El contacto puede utilizarse, por ejemplo, para controlar la bobina de un contactor, pero no deben superarse sus parámetros admisibles.

:::warning Trabajos eléctricos

Las conexiones a la tensión de red deben ser realizadas por una persona con las cualificaciones adecuadas, de acuerdo con el esquema del dispositivo concreto.

:::

### ¿Puede una salida de relé alimentar directamente un ventilador grande?

Por lo general, esta no es una aplicación adecuada para una pequeña salida de control.

Para cargas mayores se utiliza un contactor, un relé de potencia o un módulo de potencia dedicado.

### ¿Para qué sirven los bornes A1 y A2 del contactor?

Son los bornes de la bobina del contactor.

Al aplicar la tensión adecuada a la bobina, el contactor cambia el estado de sus contactos de potencia.

La tensión de la bobina debe ser conforme con el diseño de la instalación y con la documentación del contactor.

### ¿Se pueden montar aparatos adicionales dentro de la carcasa del controlador?

Solo si el diseño de la carcasa concreta lo permite y ello no empeora:

- el grado de protección,
- el aislamiento,
- la refrigeración,
- la seguridad,
- el acceso de servicio.

Todos los orificios nuevos deben realizarse de manera que se mantenga la estanqueidad requerida.

### ¿Son útiles los interruptores adicionales para los ventiladores?

Pueden facilitar el servicio técnico y permitir la desconexión independiente de ventiladores concretos.

No obstante, la forma de realización debe tener en cuenta las protecciones eléctricas y no puede provocar estados peligrosos del controlador.

### ¿Pueden tenderse los cables de control junto con los cables de potencia?

Debe evitarse tender cables de señal sensibles en paralelo y muy cerca de cables de alta potencia, especialmente en tramos largos.

Los requisitos dependen del tipo de señal y del entorno electromagnético.

### ¿Qué cable debe utilizarse para conexiones de red y dispositivos PoE?

En las instalaciones tratadas se indicaba como mínimo cable de par trenzado de categoría 5e.

Si el cable discurre en un entorno con un nivel elevado de interferencias o riesgo de cargas electrostáticas, puede ser conveniente utilizar un cable adecuadamente apantallado y un sistema de puesta a tierra correcto.

### ¿Para PoE se necesita un cable cruzado?

En instalaciones típicas se utiliza una conexión recta estándar.

No obstante, siempre deben comprobarse los requisitos del dispositivo de red y de la fuente de alimentación PoE utilizada.


## Explotación y mantenimiento

### ¿Cómo reducir el riesgo de avería de los controladores en edificios ganaderos?

Lo más importante es limitar la influencia de:

- la humedad,
- el amoniaco y el entorno agresivo,
- el polvo,
- el lavado directo con agua,
- las sobretensiones,
- una alimentación incorrecta.

También conviene comprobar periódicamente el estado de los cables, las conexiones y las carcasas.

### ¿Deben limpiarse regularmente los dispositivos electrónicos?

Sí, especialmente los dispositivos equipados con disipadores, ventiladores y orificios de ventilación.

El polvo acumulado empeora la refrigeración.

La limpieza debe realizarse tras desconectar la alimentación y de acuerdo con el manual del dispositivo.

### ¿Conviene realizar una revisión del controlador después de varios años de funcionamiento?

Sí, especialmente en condiciones ambientales difíciles.

La revisión puede incluir:

- evaluación del estado de los conectores,
- control de rastros de humedad y corrosión,
- comprobación de los elementos de refrigeración,
- comprobación del panel y de los botones,
- prueba de sensores,
- control de baterías en sistemas de alarma.

### ¿Qué conviene anotar después de producirse una avería?

Lo más útil es:

- el mensaje completo,
- el código de error,
- la hora del evento,
- la temperatura,
- el estado de la ventilación,
- información sobre pérdida de alimentación,
- información sobre el funcionamiento del generador,
- una foto de la pantalla o del dispositivo.

No debe reiniciarse el dispositivo antes de anotar el código, si la situación permite hacerlo de forma segura.

### ¿Vale la pena disponer de una alarma independiente del controlador de ventilación?

Sí, especialmente donde una avería de la ventilación puede provocar rápidamente condiciones peligrosas.

Una central independiente con su propia batería y notificación remota proporciona una capa adicional de protección.

### ¿Qué información debe prepararse antes de contactar con el soporte técnico?

Lo mejor es preparar:

1. el modelo exacto del dispositivo,
2. la descripción de la instalación,
3. el número y los parámetros de los dispositivos conectados,
4. los ajustes actuales relacionados con el problema,
5. el síntoma exacto,
6. el código completo de error o alarma,
7. fotos del dispositivo y de las placas de características,
8. información sobre los últimos cambios en la instalación.

Esto permite acortar considerablemente el diagnóstico.


## Nota importante sobre dispositivos antiguos

Los nombres, las designaciones de bornes y las funciones disponibles pueden variar entre versiones de dispositivos fabricadas en distintos años.

Si el dispositivo tiene varios o una docena de años, antes de aplicar instrucciones de un modelo más reciente debe confirmarse:

- la designación exacta del dispositivo,
- la versión de la placa,
- el tipo de pantalla,
- la versión del software,
- el esquema de bornes.

:::warning Versiones antiguas de los dispositivos

No suponga una compatibilidad total solo por la apariencia similar de la carcasa. Antes de utilizar un esquema o un manual, confirme el modelo exacto y la versión del dispositivo.

:::


## Contacto con el soporte técnico

Si las preguntas frecuentes no resuelven el problema, prepare antes del contacto:

- una foto del controlador,
- una foto de la placa de características del receptor,
- los parámetros de los motores o actuadores,
- el esquema de conexiones,
- una descripción precisa del modo de funcionamiento esperado.

De este modo, la selección del dispositivo o el diagnóstico del problema puede realizarse sobre la base de los parámetros reales de la instalación, y no de suposiciones.
