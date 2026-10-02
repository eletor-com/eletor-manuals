---
id: faq
title: FAQ
sidebar_label: FAQ
slug: /faq
description: Most common questions regarding the selection, configuration, diagnostics,
  and service of ELETOR devices.
keywords:
- ELETOR
- FAQ
- ventilation controllers
- regulators
- fans
- actuators
- alarms
- frequency inverters
- service
toc_min_heading_level: 2
toc_max_heading_level: 3
---

# Frequently Asked Questions

The FAQ was created on the basis of an anonymized analysis of real conversations with users and customers of ELETOR. The answers have been generalized so that they help in typical cases and do not contain data of specific persons or installations.

:::note FAQ scope

The answers concern typical cases. Terminal designations, functions, and connection methods may differ between device models and versions. In case of doubt, use the documentation applicable to the specific product.

:::

:::warning Safety

Perform work on the electrical installation in accordance with the device documentation and applicable safety rules. Work involving mains voltage should be carried out by a person with appropriate qualifications.

:::

## Controller selection and power rating

### How should a controller be selected for fans?

The basis for selection is primarily the total current of the fans, not only their number.

:::tip Prepare the data before selection

The more accurate the data about the motors and the operating method of the installation, the more reliable the controller selection.

:::

Before selection, it is worth preparing:

- the number of fans,
- the supply voltage,
- the rated power or current of each fan,
- information on whether all fans are to operate continuously with smooth control,
- information on whether the fans can be divided into groups,
- information about additional devices, e.g. heaters or air inlets.

The controller should not be selected exactly at the limit. An appropriate margin relative to the maximum load must be maintained.

### Is it enough to sum the fan power in watts?

Power can be used for a preliminary estimate, but the final selection should be based on the rated current of the devices and the nature of the load.

During startup, a motor may draw more current than during normal operation. For this reason, two sets of fans with similar rated power are not always an equivalent load for the controller.

### I have several small fans. Can I connect them in parallel to one output?

Yes, if:

- they are intended for this method of control,
- they are to operate together,
- the sum of the loads does not exceed the permissible output current,
- the connection method is in accordance with the controller documentation.

With a larger number of fans, it is worth considering division into groups or the use of a power extension.

### When is a power extension required?

A power extension is used when the load exceeds the capability of the controller output or when the installation is to be expanded with a larger number of fans.

The controller then provides the control signal, while the actual load is handled by an additional module.

### Can the installation later be expanded with additional fans?

In many installations, yes. The following are most commonly used:

- an additional power extension,
- an additional ventilation group,
- a contactor that switches on another group,
- a frequency inverter in the case of three-phase motors.

It is best to plan the intended expansion already during the initial controller selection.

### Do all fans have to operate with smooth control?

No. Two typical solutions are:

1. all fans operate with smooth control,
2. the first group operates with smooth control, and subsequent groups are connected step by step, e.g. via contactors.

The second solution makes it possible to handle a larger installation without smooth control of every fan.

### I have 10 fans. Do I need a very large controller?

Not always. Several control methods can be used:

- division into groups,
- power extensions,
- contactors,
- a frequency inverter.

The final selection depends on the electrical parameters of the fans and on whether all of them are to change speed simultaneously.

### Do controller 6 A and 12 A differ only in permissible load?

It should not be assumed that the only difference is the current value. Individual device versions and generations may differ in equipment or design.

When replacing a device, the exact model and current documentation must be checked.


## Fans and ventilation control

### Does the controller regulate fans smoothly?

In controllers intended for smooth ventilation control, fan speed is changed depending on demand resulting, among other things, from temperature.

However, it should be verified whether a given motor type is suitable for the applied control method.

### What does set temperature mean?

The set temperature is the value against which the controller compares the current temperature measurement.

On this basis, the controller increases or decreases ventilation intensity in accordance with the other settings, e.g. the control band and the minimum and maximum levels.

### What does the minimum ventilation level mean?

This is the minimum fan control value during automatic operation.

The setting prevents operation below the level at which the fan could operate unstably or provide insufficient air exchange.

### What does the maximum ventilation level mean?

This is the upper limit of the ventilation control value.

For example, setting a value below 100% may limit the maximum fan speed, if required by the installation.

### What does the ventilation band mean?

The ventilation band defines the temperature range in which the controller moves from the minimum to the maximum ventilation level.

The smaller the band, the faster the control reacts with increased capacity to a change in temperature.

### After startup, the fan first goes to 100% and only then slows down. Why?

The startup function may be active, whose task is to start the motor temporarily at higher power.

Depending on the controller version, settings related to the following should be checked:

- the Soft Start function,
- acceleration time,
- time of operation at 100%,
- deceleration time.

If the function is not needed in a given installation, the relevant parameters can be changed in accordance with the device manual.

### Why can the fan be started temporarily at full power during startup?

Such startup may help ensure reliable fan start-up and may help in installations where mechanical elements can offer greater resistance during start.

However, this is not necessary in every installation.

### What do acceleration time and deceleration time mean?

**Acceleration time** defines how the control ramps up when the fan is started.

**Deceleration time** defines how the speed is reduced.

Both parameters help limit abrupt changes in rotational speed and installation operation.

### Why can two identical controllers start fans differently?

The most common cause is different settings.

It is worth comparing above all:

- the set temperature,
- the ventilation band,
- minimum and maximum,
- Soft Start settings,
- acceleration and deceleration times,
- the configuration of ventilation groups.

### Can the controller start ventilation periodically regardless of temperature?

Depending on the model, a periodic ventilation function is available.

It can start ventilation for a specified time at specified intervals, even when temperature control does not require increased ventilation.

### What are ventilation groups used for?

Groups make it possible to increase installation capacity gradually.

For example:

- group 1 operates with smooth control,
- group 2 starts additional fans,
- the next group starts at even higher demand.

This makes it possible to control a large number of fans without smooth regulation of each of them.

### Can an additional fan group be switched on via a contactor?

Yes. The controller relay output can control the coil of a suitably selected contactor.

The fan load should then not be carried directly through a small control contact.

### What does the fan symbol or yellow indicator on the controller mean?

Depending on the model, the indicators show the current state of outputs and functions.

A yellow indication may mean an active operating function, e.g. ventilation, heating, or the next group in operation.

The exact meaning should be checked in the manual for the specific model.

### What does the manual mode symbol mean?

Manual mode means that the control value has been forced by the user and is not currently calculated automatically on the basis of temperature.

After testing, it should be ensured that the controller has been returned to the correct automatic mode.


## Air inlets and actuators

### Can the controller control air inlets?

Yes, selected controllers can work with air inlet actuators.

The connection method depends on the actuator type and its control method.

### What types of actuators can be used for inlets?

In technical discussions, the following two solutions appeared most often:

- an actuator controlled by an analog signal 0–10 V or 2–10 V,
- a reversing open/close actuator with a feedback signal, e.g. from a potentiometer.

Before purchase, the compatibility of the specific model with the controller in use should be verified.

### Does the actuator supply voltage 24 V or 230 V matter for the 0–10 V signal?

The control signal and the actuator power supply are separate parameters.

An actuator may be supplied with a voltage different from the control signal voltage. Both parameters must comply with the actuator and controller documentation.

### What does 0–10 V control mean?

The controller sends an analog voltage signal representing the required position or control level.

In a typical application, a lower value means a smaller opening and a higher value a larger one, but the actual characteristic should be checked in the actuator documentation.

### What is the difference between 0–10 V and 2–10 V?

In both cases, the position is set by an analog signal.

In the 2–10 V standard, the lower part of the range is shifted and may allow the device to distinguish the control signal from its absence.

The controller and actuator must support a compatible range.

### How should an actuator be selected for the number of inlets?

An actuator should not be selected solely on the basis of the number of dampers.

The following must be taken into account:

- the required force or torque,
- the length and routing of the mechanism,
- damper resistance,
- stroke length,
- operating speed,
- supply voltage,
- control type,
- required feedback.

### Can one actuator operate multiple dampers?

Yes, if the mechanics of the installation allow the dampers to be connected by a common mechanism and the required torque or force does not exceed the actuator capability.

In practice, selection is determined by the resistance of the entire mechanism, not by the number of dampers alone.

### Can several actuators be connected in parallel and controlled by one signal?

In some systems this is possible, but the actuator documentation and the permissible load of the control output must be verified.

In the case of reversing drives without independent feedback, gradual position drift between individual actuators may also occur.

### Why can several actuators gradually move to different positions over time?

Even identical motors may operate at slightly different speeds due to:

- different load,
- mechanical resistance,
- motor parameter tolerance,
- gear differences.

Therefore, where precise synchronization is required, proper feedback or individual position control is necessary.

### Can the inlets be controlled proportionally to ventilation?

Yes. In appropriately configured systems, the inlet position can be linked to the current ventilation level.

As a result, as fan capacity increases, inlet opening is also increased.

### Does actuator 24 V require a separate power supply?

If the controller does not have a suitable power output with the required power rating, a separate power supply is required.

Its power rating should be selected according to the actuator current consumption and other devices powered from the same source.

### Can an actuator from another manufacturer be used?

Often yes, if its electrical parameters and control method are compatible with the controller outputs.

Before connection, check:

- voltage,
- signal type,
- wiring diagram,
- directions of operation,
- position signal,
- permissible load.


## Temperature and humidity sensors

### Where should the temperature sensor be connected?

The sensor should be connected to the sensor input provided by the manufacturer, the sensor input indicated in the documentation for the given model.

It should not be assumed that terminal designations are identical in all device versions.

### The temperature sensor shows a different value than the reference thermometer. What should be done?

If the controller has a sensor calibration function, the reading can be corrected after comparing it with a reliable reference thermometer.

Before changing the calibration, it is worth making sure that:

- both sensors are located in the same place,
- the measurement has stabilized,
- the sensor is not being heated by the sun or equipment,
- it is not located directly in the stream of cold or hot air.

### The humidity sensor shows an incorrect value. Can it be calibrated?

This depends on the controller version, the sensor, and the software.

In some solutions, correction may require an appropriate software function or a compatible sensor type. If the difference is large and repeatable, the device version should be checked and technical support should be contacted.

### Does an incorrect measurement always mean a damaged sensor?

No.

The cause may also be:

- incorrect sensor location,
- the cable,
- the electrical connection,
- configuration,
- an incorrect sensor type,
- the need for calibration,
- moisture or corrosion.


## Alarms and notifications

### Can a siren be connected directly to the controller alarm output?

This should not be assumed.

The controller alarm output is usually a control output or a relay contact. The siren may require a separate power supply and an alarm control panel.

### What is an alarm control panel used for?

The control panel can:

- receive alarm signals from controllers,
- power the sounder,
- maintain operation during a power failure,
- signal an alarm with sound or light,
- send GSM notifications in versions equipped with this function.

### Can the control panel report a controller power failure?

Yes, if the system has been connected correctly.

The solution may detect not only temperature exceedance, but also loss of signal from the controller caused by loss of its power supply.

### Where are the minimum and maximum alarm temperatures set?

In a typical configuration, the alarm thresholds are set in the controller serving the given chamber or room.

The alarm control panel then receives information that the controller has reported an alarm.

### Does a GSM control panel require a SIM card?

To send calls and messages via the cellular network, an active SIM card or another communication solution provided for in the given model is required.

Without an active connection to the cellular network, telephone and SMS functions will not operate.

### Can the alarm send information about which controller the event comes from?

In a properly configured system, yes.

The control panel inputs can be assigned to specific rooms or controllers, allowing the message to identify the source of the alarm.

### How many controllers can be connected to one alarm control panel?

This depends on the control panel model.

The transcripts included control panels supporting up to eight inputs, however, before performing the installation, the current specification of the specific device should be checked.

### What battery is used in the alarm control panel?

In some of the devices discussed in the conversations, a 12 V 7 Ah battery was used.

Before purchasing a replacement, check the marking on the existing battery and the control panel specification, because other device versions may require a different battery.

### The control panel sends low voltage messages. What should be checked?

First of all, check:

- the condition of the battery,
- its age,
- the battery connections,
- the presence of mains power,
- the operation of the control panel charger or power supply.

A worn-out battery may cause cyclic low-voltage messages.

### How often should the battery in the alarm control panel be replaced?

There is no single value suitable for all conditions.

The battery should be tested periodically, especially in installations where an alarm during a power failure is critically important. Its actual capacity decreases with age.

### Is a siren alone sufficient as protection?

A siren works only when someone can hear it.

In facilities that are periodically left unattended, it is worth using remote notification and battery backup as well.


## Frequency inverters

### How should a frequency inverter be selected for fans?

It is necessary to know:

- the supply voltage,
- the number of phases,
- the power and current of all motors,
- their connection method,
- operating conditions,
- the required control method.

The frequency inverter should have an appropriate margin relative to the load, especially when several motors operate in parallel.

### Should the frequency inverter have exactly the same power as the sum of the motor powers?

The frequency inverter should not be selected solely on the basis of a simple sum of power values, and a device operating exactly at the parameter limit should not be chosen.

The rated currents, the nature of the load, and the frequency inverter manufacturer's recommendations must be taken into account.

### A frequency inverter stopped the fans and displayed an error. What should be done?

The most important thing is to record the full error code before reset.

:::tip Take a photo of the screen

If the situation allows, take a photo of the display before reset. The full error code makes diagnosis much easier.

:::

The beginning of the message alone is often not enough to determine the cause. The full code makes it possible to distinguish, among other things:

- overload,
- overcurrent,
- overheating,
- incorrect voltage,
- other drive errors.

### Can a frequency inverter error simply be reset?

A reset may restore operation, but it does not remove the cause of the alarm.

After the event, the error code should be checked and the cause determined before long-term restarting of the installation.

### A frequency inverter operates in a dusty room. Does it need to be cleaned?

Yes.

Dust and deposits on the heatsink or cooling fan may impair heat dissipation and lead to frequency inverter overheating.

Cleaning should be carried out in accordance with the manufacturer's instructions, after safely disconnecting the power supply.

### What can cause frequency inverter overheating?

The most common causes are:

- contaminated cooling components,
- obstructed airflow,
- excessively high ambient temperature,
- overload,
- cooling fan failure,
- incorrect installation.

### Can increased mains voltage trigger a frequency inverter alarm?

Yes. Frequency inverters monitor the supply circuit voltage and may report an error if the permissible level is exceeded.

If the problem repeats, the installation and power quality should be checked.


## Failures and diagnostics

### The controller operates, but the display shows nothing. What could be the cause?

Possible causes include, among others:

- display damage,
- a contrast adjustment problem in older solutions,
- connection damage,
- corrosion,
- main board damage.

If the device has not been used for a long time or has operated in a humid environment, it is also worth checking the board condition.

### After several years of non-use, the controller has a display problem. Why?

Prolonged downtime in a humid or aggressive environment may lead to:

- oxidation of connectors,
- corrosion,
- deterioration of contacts,
- damage to electronic components.

In such a case, it is worth carrying out a full inspection rather than replacing parts without prior diagnosis.

### The controller is blackened after an overvoltage event. Does this mean the board must be replaced?

Not always.

A protective component may be damaged and leave a large amount of residue, even though the rest of the board may be repairable.

However, if the laminate is carbonized, burnt through, or the traces are damaged, repair may be uneconomical or not durable.

### What can damage several controllers at the same time?

If many devices fail at the same time, the power supply installation should be checked.

One possible cause is a problem with the neutral conductor, which in a three-phase installation may lead to the appearance of incorrect voltages on single-phase loads.

Overvoltage events originating from the grid or a generator are also possible.

### What should be done after a failure related to an overvoltage event?

Before connecting a repaired or new controller, the cause of the problem must be determined.

:::danger Do not reconnect the device without checking the installation

If the cause of the failure was incorrect voltage, a damaged neutral conductor, or an overvoltage event, the repaired or new controller may be damaged again.

:::

### What is the surge protection component on the board?

Electronic devices use components that limit overvoltage, e.g. varistors.

Their task is to absorb part of the overvoltage energy and protect the downstream circuits. After a severe event, such a component may be permanently damaged.

### Can the device be started after removing the burnt protective component?

This should not be treated as a normal repair.

After removal of the protection, the device may lose protection against another overvoltage event. Such actions may be performed only as a deliberate service procedure by a person with appropriate qualifications and after elimination of the root cause of the original failure.

### The controller has been flooded or has heavily corroded. Is it worth repairing?

It depends on the extent of the damage.

Superficial corrosion and isolated damage can often be removed. If the corrosion has affected traces, connectors, and many components, the repair may be time-consuming, uncertain, and economically unjustified.

### Can pressure washing the device damage the controller?

Yes.

Electronics should not be exposed to direct action of water or cleaning agent if the enclosure and mounting method are not designed for this purpose.

Moisture entering the interior may lead to corrosion and later faults that are difficult to diagnose.

### Why can faults after flooding reappear after repair?

Corrosion may also progress in places invisible during the first inspection.

Damaged vias, traces, and connections may work during testing and later lose contact again.

Therefore, in the case of a heavily corroded board, service may recommend replacement instead of further repairs.

### Sometimes the device works and sometimes it does not. Where should diagnosis start?

Before contacting service, it is worth collecting:

- the exact model,
- a description of the symptom,
- the moment of occurrence,
- the values shown on the screen,
- the alarm or error code,
- information about recent changes in the installation,
- a photo of the interior and terminals, if it can be taken safely.

The more accurate the description, the easier the diagnosis.


## Service and repairs

### What should be sent to service if the controller is damaged?

It is best to send a complete set that makes it possible to reproduce the problem.

A short description should be attached to the shipment:

- what does not work,
- when the problem occurs,
- whether the failure is permanent or intermittent,
- whether an overvoltage event, flooding, or another incident occurred before the failure,
- the data needed for contact and return of the device.

:::note Data for a service request

Provide contact and shipping details directly to service. Do not publish them in open tickets or public materials.

:::

### Is it necessary to send the entire controller or only the board?

It depends on the fault.

In the case of problems with the display, buttons, power supply, or ambiguous behavior, it is best to send the entire set required to reproduce the symptom.

In the case of a previously agreed repair of a specific module, service may ask for the board only.

### Does ELETOR repair controllers instead of replacing them immediately?

The transcripts indicate that devices are first diagnosed.

If repair is possible and justified, damaged components or modules are replaced. In the event of serious damage, service may propose replacement of the board or the entire device.

### What happens if the damaged board cannot be repaired?

The damaged module may be replaced with a new one, provided that the appropriate part is available and compatible with the device.

In older devices, service should first confirm version compatibility.

### Is it worth buying a new board immediately after an overvoltage event?

Not always.

If the damage concerns a protective component or a small part of the circuit, repair may be justified. It is worth carrying out a diagnosis first.

### Can service also check the display and buttons?

Yes, if the components are supplied together with the device or module.

This is particularly useful when it is not known whether the problem is located on the main board or in the user panel.

### Is a heavily corroded controller always worth saving?

No.

If the cost of diagnosis and repair increases while reliability after repair remains uncertain, replacement may be more reasonable.

This applies in particular to devices on which facility ventilation depends.

### How can service diagnosis be accelerated?

Attach an accurate description of the symptom instead of only stating that it does not work.

The following are also useful:

- photos,
- the error code,
- a description of the installation,
- the type of connected loads,
- information about an overvoltage event or power failure,
- information about flooding or washing of the device.


## Installation and wiring

### How should devices be connected to relay terminals C and NO?

C and NO are typical relay contact designations:

- C — common contact,
- NO — normally open contact.

The method of use depends on the device and the installation diagram. The contact can be used, for example, to control a contactor coil, but its permissible parameters must not be exceeded.

:::warning Electrical work

Connections to mains voltage should be made by a person with appropriate qualifications, in accordance with the diagram of the specific device.

:::

### Can the relay output directly power a large fan?

Usually this is not an appropriate use of a small control output.

For larger loads, a contactor, power relay, or dedicated output module is used.

### What are terminals A1 and A2 of a contactor used for?

These are the contactor coil terminals.

When the appropriate voltage is applied to the coil, the contactor changes the state of its power contacts.

The coil voltage must comply with the installation design and the contactor documentation.

### Can additional apparatus be installed inside the controller enclosure?

Only if the design of the specific enclosure allows it and if it does not worsen:

- the degree of protection,
- insulation,
- cooling,
- safety,
- service access.

Any new openings should be made in a way that preserves the required sealing.

### Are additional fan switches useful?

They can facilitate service and enable independent disconnection of individual fans.

However, the implementation method must take electrical protection into account and must not cause hazardous controller states.

### Can control cables be routed together with power cables?

Routing sensitive signal cables in parallel and very close to high-power cables should be avoided, especially over long distances.

Requirements depend on the type of signal and the electromagnetic environment.

### What cable should be used for network connections and PoE devices?

In the discussed installations, category 5e twisted pair was indicated as the minimum.

If the cable runs in an environment with an increased level of interference or a risk of electrostatic charges, the use of an appropriately shielded cable and a correct grounding system may be justified.

### Is a crossover cable required for PoE?

Standard straight-through connection is used in typical installations.

However, the requirements of the network device and the applied PoE power supply should always be checked.


## Operation and maintenance

### How can the risk of controller failures in farm buildings be reduced?

The most important thing is to limit the effect of:

- moisture,
- ammonia and an aggressive environment,
- dust,
- direct washing with water,
- overvoltage events,
- incorrect power supply.

It is also worth periodically checking the condition of cables, connections, and enclosures.

### Should electronic devices be cleaned regularly?

Yes, especially devices equipped with heatsinks, fans, and ventilation openings.

Accumulated dust worsens cooling.

Cleaning should be performed after disconnecting the power supply and in accordance with the device instructions.

### After several years of operation, is it worth carrying out an inspection of the controller?

Yes, especially in difficult environmental conditions.

The inspection may include:

- assessment of connector condition,
- checking for signs of moisture and corrosion,
- checking cooling components,
- checking the panel and buttons,
- sensor testing,
- checking batteries in alarm systems.

### What is worth recording after a failure occurs?

The most useful items are:

- the full message,
- the error code,
- the time of the event,
- temperature,
- the ventilation status,
- information about a power failure,
- information about generator operation,
- a photo of the screen or device.

The device should not be reset before the code is recorded, if the situation allows this to be done safely.

### Is it worth having an alarm independent of the ventilation controller?

Yes, especially where a ventilation failure may quickly lead to dangerous conditions.

An independent control panel with its own battery and remote notification provides an additional layer of protection.

### What information should be prepared before contacting technical support?

It is best to prepare:

1. the exact device model,
2. a description of the installation,
3. the number and parameters of connected devices,
4. the current settings related to the problem,
5. the exact symptom,
6. the full error or alarm code,
7. photos of the device and rating plates,
8. information about recent changes in the installation.

This allows diagnosis to be significantly shortened.


## Important note regarding older devices

Names, terminal designations, and available functions may differ between versions of devices manufactured in different years.

If the device is several or more than a dozen years old, before using instructions from a newer model, confirm:

- the exact device designation,
- the board version,
- the display type,
- the software version,
- the terminal diagram.

:::warning Older device versions

Do not assume full compatibility only on the basis of a similar enclosure appearance. Before using a diagram or manual, confirm the exact model and version of the device.

:::


## Contact with technical support

If the FAQ does not solve the problem, prepare before contact:

- a photo of the controller,
- a photo of the load rating plate,
- motor or actuator parameters,
- the wiring diagram,
- an accurate description of the expected method of operation.

This allows device selection or problem diagnosis to be carried out on the basis of actual installation parameters rather than assumptions.
