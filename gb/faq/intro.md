---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Frequently asked questions about the selection, configuration, diagnostics
  and servicing of ELETOR devices.
keywords:
- ELETOR
- FAQ
- ventilation controllers
- regulators
- fans
- actuators
- alarms
- variable frequency drives
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Frequently Asked Questions

This FAQ was prepared based on an anonymized analysis of actual conversations with users and customers of ELETOR. The answers have been generalized to address typical situations and do not contain data relating to specific individuals or installations.

:::note Scope of the FAQ

The answers address typical situations. Terminal designations, functions and connection methods may differ between device models and versions. If in doubt, consult the documentation for the specific product.

:::

:::warning Safety

Perform electrical installation work in accordance with the device documentation and applicable safety rules. Work involving mains voltage should be performed by a suitably qualified person.

:::

## Controller Selection and Power Rating

### How should a controller be selected for fans?

Selection is based primarily on the total current drawn by the fans, not solely on their number.

:::tip Prepare the data before selection

The more accurate the data on the motors and the installation's operating conditions, the more reliable the controller selection.

:::

Before selection, it is advisable to prepare:

- the number of fans,
- the supply voltage,
- the rated power or current of each fan,
- information on whether all fans require continuously variable speed control,
- information on whether the fans can be divided into groups,
- information on additional devices, e.g. heaters or air inlets.

The controller should not be selected to operate exactly at its limit. An appropriate margin relative to the maximum load must be maintained.

### Is adding up the fan power ratings in watts sufficient?

Power ratings can be used for an initial estimate, but final selection should be based on the rated current of the devices and the nature of the load.

A motor may draw more current during startup than during normal operation. For this reason, two sets of fans with similar rated power do not always represent equivalent loads for the controller.

### I have several small fans. Can I connect them in parallel to one output?

Yes, provided that:

- they are designed for this control method,
- they are intended to operate together,
- the total load does not exceed the permissible output current,
- the connection method complies with the controller documentation.

For a larger number of fans, consider dividing them into groups or using a power expansion module.

### When is a power expansion module needed?

A power expansion module is used when the load exceeds the capacity of the controller output or when the installation is to be expanded with more fans.

The controller then provides the control signal, while the actual load is handled by an additional module.

### Can additional fans be added to the installation later?

In many installations, yes. The most commonly used solutions are:

- an additional power expansion module,
- an additional ventilation group,
- a contactor to switch on another group,
- a variable frequency drive for three-phase motors.

It is best to allow for planned expansion when initially selecting the controller.

### Do all fans require continuously variable speed control?

No. There are two typical solutions:

1. all fans operate with continuously variable speed control,
2. the first group operates with continuously variable speed control, while subsequent groups are switched on in stages, e.g. using contactors.

The second solution allows a larger installation to be controlled without continuously variable speed control of every fan.

### I have 10 fans. Do I need a very large controller?

Not always. Several control methods can be used:

- division into groups,
- power expansion modules,
- contactors,
- a variable frequency drive.

Final selection depends on the electrical parameters of the fans and on whether all of them need to change speed simultaneously.

### Do the 6 A and 12 A controllers differ only in their permissible load?

Do not assume that the current rating is the only difference. Individual device versions and generations may differ in their equipment or construction.

When replacing a device, check the exact model and current documentation.


## Fans and Ventilation Control

### Does the controller provide continuously variable fan speed control?

In controllers designed for continuously variable ventilation control, fan speed is adjusted according to demand arising from factors including temperature.

However, check whether the motor type is suitable for the control method used.

### What does the temperature setpoint mean?

The temperature setpoint is the value against which the controller compares the current temperature measurement.

Based on this value, the controller increases or decreases ventilation intensity in accordance with the other settings, e.g. the control band and the minimum and maximum levels.

### What does the minimum ventilation level mean?

This is the minimum fan control value during automatic operation.

This setting prevents operation below a level at which the fan could operate unstably or provide insufficient air exchange.

### What does the maximum ventilation level mean?

This is the upper limit of the ventilation control value.

For example, setting a value below 100% may limit the maximum fan speed if the installation requires this.

### What does the ventilation band mean?

The ventilation band defines the temperature range over which the controller transitions from the minimum to the maximum ventilation level.

The narrower the band, the more rapidly the control responds to a temperature change by increasing ventilation capacity.

### After startup, the fan first reaches 100% and only then slows down. Why?

A startup function may be active, intended to briefly start the motor at a higher power level.

Depending on the controller version, check the settings relating to:

- the Soft Start function,
- the acceleration time,
- the operating time at 100%,
- the deceleration time.

If the function is not needed in the installation, the relevant parameters can be changed in accordance with the device manual.

### Why might a fan briefly run at full power during startup?

This startup method may help ensure reliable fan starting and may be useful in installations where mechanical components offer greater resistance during startup.

However, it is not necessary in every installation.

### What do acceleration time and deceleration time mean?

**Acceleration time** defines how the control value increases during fan startup.

**Deceleration time** defines how the speed decreases.

Both parameters help limit abrupt changes in speed and installation operation.

### Why can two identical controllers start fans differently?

The most common cause is different settings.

In particular, compare:

- the temperature setpoint,
- the ventilation band,
- the minimum and maximum levels,
- the Soft Start settings,
- the acceleration and deceleration times,
- the ventilation group configuration.

### Can the controller periodically start ventilation independently of temperature?

Depending on the model, a periodic ventilation function is available.

It can run ventilation for a specified duration at set intervals, even when temperature control does not require increased ventilation.

### What are ventilation groups used for?

Groups allow the installation's capacity to be increased in stages.

For example:

- group 1 operates with continuously variable speed control,
- group 2 starts additional fans,
- the next group starts when demand increases further.

This allows a large number of fans to be controlled without continuously variable speed control of each one.

### Can an additional group of fans be switched on using a contactor?

Yes. The controller's relay output can control the coil of a suitably selected contactor.

In this case, the fan load should not be routed directly through the small control contact.

### What does the fan symbol or yellow indicator on the controller mean?

Depending on the model, indicators show the current state of outputs and functions.

A yellow indication may mean that an operating function is active, e.g. ventilation, heating or another group.

Check the manual for the specific model for the exact meaning.

### What does the manual mode symbol mean?

Manual mode means that the control value has been overridden by the user and is not currently calculated automatically based on temperature.

After testing, ensure that the controller has been returned to the appropriate automatic mode.


## Air Inlets and Actuators

### Can the controller control air inlets?

Yes, selected controllers support air inlet drives.

The connection method depends on the actuator type and its control method.

### What types of actuators can be used for air inlets?

Two solutions appeared most frequently in the technical conversations:

- an actuator controlled by an analog signal of 0–10 V or 2–10 V,
- a reversible open/close actuator with a feedback signal, e.g. from a potentiometer.

Before purchase, check the compatibility of the specific model with the existing controller.

### Does an actuator supply voltage of 24 V or 230 V affect the 0–10 V signal?

The control signal and the actuator power supply are separate parameters.

The actuator may be powered by a voltage different from the control signal voltage. Both parameters must comply with the actuator and controller documentation.

### What does 0–10 V control mean?

The controller sends an analog voltage signal representing the required position or control level.

In a typical application, a lower value means a smaller opening and a higher value means a larger opening, but the actual characteristic must be checked in the actuator documentation.

### How does 0–10 V differ from 2–10 V?

In both cases, the position is commanded by an analog signal.

In the 2–10 V standard, the lower end of the range is offset and may allow the device to distinguish a control signal from its absence.

The controller and actuator must support a compatible range.

### How should an actuator be selected for the number of air inlets?

Do not select an actuator solely on the basis of the number of flaps.

Consider:

- the required force or torque,
- the length and routing of the mechanism,
- the resistance of the flaps,
- the stroke length,
- the operating speed,
- the supply voltage,
- the control type,
- the required feedback.

### Can one actuator operate multiple flaps?

Yes, provided that the mechanical arrangement of the installation allows the flaps to be connected through a common system and the required torque or force does not exceed the actuator's capacity.

In practice, selection is determined by the resistance of the entire mechanism, not simply the number of flaps.

### Can several actuators be connected in parallel and controlled by one signal?

This is possible in some systems, but the actuator documentation and the permissible load of the control output must be verified.

For reversible drives without independent feedback, the positions of individual actuators may also gradually drift apart.

### Why can several actuators move to different positions over time?

Even identical motors may operate at slightly different speeds due to:

- different loads,
- mechanical resistance,
- motor parameter tolerances,
- differences in gearboxes.

Therefore, where precise synchronization is required, appropriate feedback or individual position control is necessary.

### Can air inlets be controlled proportionally to ventilation?

Yes. In appropriately configured systems, the air inlet position can be linked to the current ventilation level.

This increases the air inlet opening as fan capacity increases.

### Does the 24 V actuator require a separate power supply unit?

If the controller does not have a suitable power supply output with the required power rating, a separate power supply unit is needed.

Its power rating must be selected according to the current drawn by the actuator and other devices powered from the same source.

### Can an actuator from another manufacturer be used?

Often yes, provided that its electrical parameters and control method are compatible with the controller outputs.

Before connection, check:

- the voltage,
- the signal type,
- the wiring diagram,
- the operating directions,
- the position signal,
- the permissible load.


## Temperature and Humidity Sensors

### Where should the temperature sensor be connected?

Connect the sensor to the sensor input provided by the manufacturer, the sensor input specified in the documentation for the model concerned.

Do not assume that terminal designations are identical in all device versions.

### The temperature sensor shows a different value from the reference thermometer. What should I do?

If the controller has a sensor calibration function, the reading can be adjusted after comparison with a reliable reference thermometer.

Before changing the calibration, ensure that:

- both sensors are in the same location,
- the measurement has stabilized,
- the sensor is not being heated by sunlight or equipment,
- it is not directly in a stream of cold or hot air.

### The humidity sensor shows an incorrect value. Can it be calibrated?

This depends on the controller, sensor and software versions.

In some solutions, adjustment may require an appropriate software function or a compatible sensor type. If the difference is large and repeatable, check the device version and contact technical support.

### Does an incorrect measurement always mean a faulty sensor?

No.

The cause may also be:

- incorrect sensor placement,
- the cable,
- the electrical connection,
- the configuration,
- an unsuitable sensor type,
- the need for calibration,
- moisture or corrosion.


## Alarms and Notifications

### Can a siren be connected directly to the controller's alarm output?

Do not assume that this is possible.

The controller's alarm output is usually a control output or a relay contact. The siren may require a separate power supply and an alarm control panel.

### Why is an alarm control panel used?

The panel can:

- receive alarm signals from controllers,
- supply power to an alarm signaling device,
- maintain operation during a power outage,
- indicate an alarm using sound or light,
- send GSM notifications in versions equipped with this function.

### Can the panel signal a loss of power to the controller?

Yes, provided that the system has been connected appropriately.

The solution can detect not only a temperature threshold being exceeded, but also the loss of the controller signal caused by a loss of its power supply.

### Where are the minimum and maximum alarm temperatures set?

In a typical configuration, alarm thresholds are set in the controller serving the relevant chamber or room.

The alarm control panel then receives information that the controller has reported an alarm.

### Does a GSM panel require a SIM card?

To make calls and send messages over the cellular network, an active SIM card or another communication solution provided for in the model concerned is required.

Without an active connection to the cellular network, telephone and SMS functions will not operate.

### Can the alarm send information identifying which controller the event came from?

Yes, in an appropriately configured system.

Panel inputs can be assigned to specific rooms or controllers, allowing the message to identify the alarm source.

### How many controllers can be connected to one alarm control panel?

This depends on the panel model.

The transcripts mentioned panels supporting up to eight inputs; however, check the current specifications of the specific device before installing the system.

### What battery is used in the alarm control panel?

Some of the devices discussed in the conversations used an 12 V 7 Ah battery.

Before purchasing a replacement, check the designation on the existing battery and the panel specifications, as other device versions may require a different battery.

### The panel sends low-voltage messages. What should I check?

First, check:

- the battery condition,
- its age,
- the battery connections,
- the presence of mains power,
- the operation of the panel's charger or power supply unit.

A worn-out battery may cause recurring low-voltage messages.

### How often should the battery in the alarm control panel be replaced?

There is no single interval suitable for all conditions.

The battery should be tested periodically, especially in installations where alarms during a power outage are critical. Its actual capacity decreases with age.

### Is a siren alone sufficient protection?

A siren is effective only when someone can hear it.

For facilities that are temporarily unattended, it is advisable to also use remote notification and battery backup.


## Variable Frequency Drives

### How should a variable frequency drive be selected for fans?

The following must be known:

- the supply voltage,
- the number of phases,
- the power and current of all motors,
- their connection arrangement,
- the operating conditions,
- the required control method.

The variable frequency drive should have an appropriate margin relative to the load, especially when several motors operate in parallel.

### Should the variable frequency drive have exactly the same power rating as the total motor power?

A variable frequency drive should not be selected solely by adding up the power ratings and choosing a device that operates exactly at its parameter limits.

Rated currents, the nature of the load and the drive manufacturer's recommendations must be taken into account.

### The variable frequency drive stopped the fans and displayed an error. What should I do?

The most important step is to record the full error code before resetting.

:::tip Take a photograph of the screen

If the situation allows, photograph the display before resetting. The full error code greatly facilitates diagnosis.

:::

The beginning of the message alone is often insufficient to determine the cause. The full code helps distinguish between, among other things:

- overload,
- overcurrent,
- overheating,
- incorrect voltage,
- other drive errors.

### Can I simply reset the variable frequency drive error?

A reset may restore operation, but it does not eliminate the cause of the alarm.

After the event, check the error code and determine the cause before restarting the installation for prolonged operation.

### The variable frequency drive operates in a dusty room. Does it need cleaning?

Yes.

Dust and deposits on the heat sink or cooling fan can impair heat dissipation and cause the variable frequency drive to overheat.

Cleaning must be performed in accordance with the manufacturer's instructions, after safely disconnecting the power supply.

### What can cause a variable frequency drive to overheat?

The most common causes are:

- dirty cooling components,
- obstructed airflow,
- excessively high ambient temperature,
- overload,
- cooling fan failure,
- incorrect installation.

### Can elevated mains voltage trigger a variable frequency drive alarm?

Yes. Variable frequency drives monitor the supply circuit voltage and may report an error when the permissible level is exceeded.

If the problem recurs, check the installation and the power supply quality.


## Faults and Diagnostics

### The controller operates, but the display shows nothing. What could be the cause?

Possible causes include:

- display failure,
- a contrast adjustment problem in older designs,
- a damaged connection,
- corrosion,
- main board damage.

If the device has not been used for a long time or has operated in a humid environment, it is also advisable to check the condition of the board.

### The controller has a display problem after several years without use. Why?

Prolonged inactivity in a humid or aggressive environment may lead to:

- connector oxidation,
- corrosion,
- contact deterioration,
- damage to electronic components.

In this case, it is advisable to carry out a full inspection rather than replace components without prior diagnosis.

### The controller is soot-covered after a voltage surge. Does this mean the board must be replaced?

Not always.

A protective component may fail and leave substantial deposits, even though the rest of the board can be repaired.

However, if the board laminate is charred or burned, or the tracks are damaged, repair may be uneconomical or may not provide lasting results.

### What can damage several controllers simultaneously?

If multiple devices fail at the same time, check the power supply installation.

One possible cause is a problem with the neutral conductor, which in a three-phase installation can result in incorrect voltages being applied to single-phase loads.

Voltage surges from the mains or a generator are also possible.

### What should I do after a failure caused by a voltage surge?

Before connecting a repaired or new controller, determine the cause of the problem.

:::danger Do not reconnect the device without checking the installation

If the failure was caused by incorrect voltage, a damaged neutral conductor or a voltage surge, the repaired or new controller may be damaged again.

:::

### What is a surge protection component on the board?

Electronic devices use components that limit voltage surges, e.g. varistors.

Their purpose is to absorb part of the surge energy and protect downstream circuits. After a severe event, such a component may be permanently damaged.

### Can the device be operated after removing a burned-out protective component?

This should not be regarded as a normal repair.

After removal of the protective component, the device may lose protection against subsequent voltage surges. Such actions may only be performed as a deliberate service procedure by a suitably qualified person and after the cause of the original failure has been eliminated.

### The controller has suffered water ingress or severe corrosion. Is it worth repairing?

This depends on the extent of the damage.

Surface corrosion and isolated damage can often be remedied. If corrosion has affected tracks, connectors and many components, repair may be time-consuming, unreliable and economically unjustified.

### Can pressure washing the device damage the controller?

Yes.

Electronics should not be exposed directly to water or cleaning agents unless the enclosure and installation method are designed for this.

Moisture entering the device can cause corrosion and subsequent faults that are difficult to diagnose.

### Why can faults caused by water ingress recur after repair?

Corrosion may also progress in areas that are not visible during the initial inspection.

Damaged vias, tracks and connections may work during testing and later lose contact again.

For this reason, the service department may recommend replacement rather than further repairs for a heavily corroded board.

### The device works intermittently. Where should I start?

Before contacting the service department, collect:

- the exact model,
- a description of the symptom,
- when it occurs,
- the values shown on the screen,
- the alarm or error code,
- information on recent changes to the installation,
- a photograph of the interior and terminals, if it can be taken safely.

The more detailed the description, the easier the diagnosis.


## Service and Repairs

### What should I send to the service department if the controller is faulty?

It is best to send a complete set that allows the problem to be reproduced.

Include a brief description with the shipment covering:

- what is not working,
- when the problem occurs,
- whether the fault is permanent or intermittent,
- whether a voltage surge, water ingress or another event occurred before the failure,
- the details needed to contact you and return the device.

:::note Details for a service request

Provide contact and shipping details directly to the service department. Do not publish them in open requests or public materials.

:::

### Should I send the entire controller or only the board?

This depends on the fault.

For problems with the display, buttons, power supply or ambiguous behavior, it is best to send the entire set needed to reproduce the symptom.

For a previously agreed repair of a specific module, the service department may request only the board.

### Does ELETOR repair controllers instead of replacing them immediately?

The transcripts indicate that devices are diagnosed first.

If repair is possible and justified, faulty components or modules are replaced. In the event of serious damage, the service department may propose replacing the board or the entire device.

### What happens if the damaged board cannot be repaired?

The damaged module can be replaced with a new one, provided that the appropriate part is available and compatible with the device.

For older devices, the service department should first confirm version compatibility.

### Is it worth buying a new board immediately after a voltage surge?

Not always.

If the damage affects a protective component or a small part of the circuit, repair may be justified. It is advisable to carry out a diagnosis first.

### Can the service department also check the display and buttons?

Yes, provided that the components are supplied with the device or module.

This is particularly useful when it is unclear whether the problem is on the main board or in the user panel.

### Is it always worth saving a heavily corroded controller?

No.

If diagnosis and repair costs increase while reliability after repair remains uncertain, replacement may be more reasonable.

This applies particularly to devices on which the facility's ventilation depends.

### How can I speed up service diagnosis?

Include a detailed description of the symptom rather than simply stating "does not work".

The following are also useful:

- photographs,
- the error code,
- a description of the installation,
- the type of connected loads,
- information on a voltage surge or power outage,
- information on water ingress or washing of the device.


## Installation and Wiring

### How should devices be connected to relay terminals C and NO?

C and NO are typical relay contact designations:

- C — common contact,
- NO — normally open contact.

Their use depends on the device and the installation diagram. The contact can be used, for example, to control a contactor coil, but its permissible ratings must not be exceeded.

:::warning Electrical work

Connections involving mains voltage should be made by a suitably qualified person, in accordance with the diagram for the specific device.

:::

### Can a relay output directly supply power to a large fan?

This is generally not an appropriate use of a small control output.

For larger loads, use a contactor, power relay or dedicated output module.

### What are contactor terminals A1 and A2 used for?

These are the contactor coil terminals.

When the appropriate voltage is applied to the coil, the contactor changes the state of its power contacts.

The coil voltage must comply with the installation design and the contactor documentation.

### Can additional electrical devices be installed inside the controller enclosure?

Only if the design of the specific enclosure permits this and it does not impair:

- the degree of protection,
- the insulation,
- the cooling,
- the safety,
- the service access.

Any new openings should be made in a way that maintains the required sealing.

### Are additional fan switches useful?

They can facilitate servicing and allow individual fans to be disconnected independently.

However, the implementation must take electrical protection into account and must not cause unsafe controller states.

### Can control cables be routed together with power cables?

Avoid routing sensitive signal cables parallel to and very close to high-power cables, especially over long distances.

Requirements depend on the signal type and the electromagnetic environment.

### What cable should be used for network connections and PoE devices?

In the installations discussed, category 5e twisted-pair cable was specified as the minimum.

If the cable passes through an environment with elevated interference levels or a risk of electrostatic charges, it may be advisable to use appropriately shielded cable and a proper grounding system.

### Is a crossover cable needed for PoE?

Typical installations use a standard straight-through connection.

However, always check the requirements of the network device and the PoE power supply used.


## Operation and Maintenance

### How can the risk of controller failures in agricultural buildings be reduced?

The most important measure is to limit the effects of:

- moisture,
- ammonia and aggressive environments,
- dust,
- direct washing with water,
- voltage surges,
- incorrect power supply.

It is also advisable to periodically check the condition of cables, connections and enclosures.

### Should electronic devices be cleaned regularly?

Yes, especially devices equipped with heat sinks, fans and ventilation openings.

Accumulated dust impairs cooling.

Cleaning must be performed after disconnecting the power supply and in accordance with the device manual.

### Is it worth inspecting the controller after several years of operation?

Yes, especially in harsh environmental conditions.

The inspection may include:

- assessing the condition of connectors,
- checking for signs of moisture and corrosion,
- checking cooling components,
- checking the panel and buttons,
- testing sensors,
- checking batteries in alarm systems.

### What should be recorded after a failure occurs?

The most useful information is:

- the full message,
- the error code,
- the time of the event,
- the temperature,
- the ventilation status,
- information on a power outage,
- information on generator operation,
- a photograph of the screen or device.

Do not reset the device before recording the code if the situation allows this to be done safely.

### Is it worth having an alarm independent of the ventilation controller?

Yes, especially where a ventilation failure can quickly lead to dangerous conditions.

An independent panel with its own battery and remote notification provides an additional layer of protection.

### What information should I prepare before contacting technical support?

It is best to prepare:

1. the exact device model,
2. a description of the installation,
3. the number and parameters of connected devices,
4. the current settings related to the problem,
5. the exact symptom,
6. the full error or alarm code,
7. photographs of the device and rating plates,
8. information on recent changes to the installation.

This can significantly shorten diagnosis.


## Important Note on Older Devices

Names, terminal designations and available functions may differ between device versions manufactured in different years.

If the device is several years old or more than a decade old, confirm the following before applying instructions for a newer model:

- the exact device designation,
- the board version,
- the display type,
- the software version,
- the terminal diagram.

:::warning Older device versions

Do not assume full compatibility solely on the basis of a similar enclosure appearance. Confirm the exact device model and version before using a diagram or manual.

:::


## Contacting Technical Support

If the FAQ does not resolve the problem, prepare the following before making contact:

- a photograph of the controller,
- a photograph of the load's rating plate,
- the motor or actuator parameters,
- the connection diagram,
- a detailed description of the intended operation.

This allows device selection or problem diagnosis to be based on the actual installation parameters rather than assumptions.
