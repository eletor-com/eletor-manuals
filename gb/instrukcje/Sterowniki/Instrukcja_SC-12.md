---
sidebar_position: 3
title: Manual SC-12
description: Climate controller for livestock rooms with a permissible output current
  of up to 12A
keywords:
- eletor sc-12
- ventilation controller
- climate controller
- pig house ventilation controller
- microclimate controller
- controller for pig houses
- pig house ventilation
- controller for rearing rooms
---

# Controller SC-12

Microprocessor-based climate controller belonging to the SPEED CONTROL series. The versatility of the device is ensured by its extensive range of inputs/outputs and intuitive software in Polish and English. In addition to basic settings for temperature, periodic ventilation, supplementary heating, min./max. ventilation levels and alarms, the controller software allows testing and saving calibration settings for actuators working with the controller.

**Parameters and features:** 
- Group I ventilation: 
  - max. current of the continuously variable control output 12A,
  - thermal protection of the circuit, 
  - soft start of ventilation,
  - bypass relay at full output, 
  - minimum speed calibration, 
  - energy-saving program with a system of dampers opened in advance.
- Group II ventilation, isolated contact rated up to 6A.
- Supplementary heating, isolated contact rated up to 6A
- Alarm outputs NO and NC: 
  - power failure indication,
  - indication of temperature below the min. or above the max. threshold,
  - built-in audible indicator.
- Independent 3 outputs 0..10V:
  - operation with expansion modules,
  - damper system control, 
  - variable-capacity heating control.**
- Two analog inputs for temperature measurement.
- Digital port for temperature measurement (up to 4 sensors).
- Two selectable-function relay outputs:
  - operation with linear actuators, 
  - III and IV ventilation groups
- Two analog inputs 0-10V.
- DC power supply for the potentiometer 10V.
- Auxiliary DC power supply 12V.
- Capability of operation with a computer up to 1200m.
- Sealed enclosure IP65.
- Supply voltage 230VAC 50Hz.
- Power consumed by the circuit < 10V

# Controller installation
:::danger 
 The electrical power supply must be disconnected when installing the device, as the voltage present on certain components poses a danger to life and health. Installation by a qualified person is recommended.  This action is dangerous
:::

## Selecting the installation location
The installation location must be selected carefully, ensuring easy access to the device for authorized persons while keeping it inaccessible to animals and children. Climatic conditions must also be taken into account, i.e. the device should operate within a temperature range of -10°C to 40 °C, in a location not exposed to sunlight. Air must be able to flow freely around the device. A temperature sensor is included with the device.  

### Several rules apply to temperature sensor installation:
 - the sensor should not be installed in a location without air circulation or exposed to direct sunlight,
 - the sensor should not be installed on a load-bearing (external) wall of the building,
 - avoid proximity to heat-emitting equipment, such as heaters and lamps,
 - do not place the sensor directly beside doors or ventilation openings,
 - do not place the sensor in locations accessible to animals,
 - it is recommended to route the sensor connection cable away from power cables.

# Installation
The device can operate in harsh climatic conditions. When correctly installed, the controller and temperature sensor are resistant to harmful environmental effects.  

### During installation, pay attention to the following:
 - check the cover gasket before fastening the screws,
 - the cover must be secured with all screws,
 - cables used to connect the controller should be round,
 - after connecting the cable, tighten the cable glands so that the cable is sealed and secured; the use of silicone is recommended,
 - unused cable entries (glands) must be plugged,
 - secure the controller (the bottom part of the enclosure) to a flat wall using 4 wall plugs.

# Electrical connection
:::danger 
 Before connecting the circuit, make sure that the power supply is switched off!
This action is dangerous
:::

Before connecting the controller, unscrew and remove the cover. Feed the cables through the rubber cable glands and then proceed with their connection. The controller terminals are shown in the figure below.

![Connection ](./img/sc-12.png)

**Connect the AC 230V** connector to the power supply (distribution board). An 1P-B6 overcurrent circuit breaker and type T1 T2 surge protective devices are required. When connecting several devices, it is good practice to group the controllers on different “phases” (L1, L2, L3) to distribute the load evenly across the supply line.

**The FAN** connector must be connected directly to the fan; when controlling several fans, the total load must not exceed 6A, and each fan must be protected separately. Do not run PE and N from the power supply (distribution board); they must be connected to the controller terminals.

**The FAN 2** connector can be used to connect group 2 fans or sprinkler systems. The output is isolated, and the maximum contact current is 6A (an external type 1P-B6 overcurrent circuit breaker is required when controlling the load directly); the contact closes when the measured temperature is higher than the sum of the setpoint temperature and the ventilation band.

**The HOT** connector can be used to connect a heater. The output is isolated, and the maximum contact current is 6A (an external 1P-B6 overcurrent circuit breaker is required when controlling the load directly); the contact closes when the measured temperature falls below the setting.

**The ALARM** connector has isolated outputs NC, C and NO for connection to an alarm control panel. The alarm is activated in the following cases:
    - the temperature is too low or too high,
    - the controller or temperature sensor has failed,
    - the controller supply voltage has been lost,
    - the controller has malfunctioned (e.g. controller overheating)
The figure below shows how to connect the fan to the alarm control panel.

![Alarm connection](./img/alarmsc-s.png)

**The FUNC1 and FUNC2** connectors are used to connect an air inlet winch based on a reversible motor. Relay FUNC1 switches on the power to the actuator, and FUNC2 switches the motor direction of rotation. Example winch wiring diagram (an external 1P-B6 overcurrent circuit breaker is required):
When the winch function is deactivated, outputs FUNC1 and FUNC2 operate as contacts for ventilation groups 3 and 4, respectively.

![Winch connection](./img/Sc-12fan.png)

**The 12V** connector is intended to supply power to external sensors.

**The V1 0-10V** connector is used to connect power expansion modules. The voltage at this terminal is proportional to the ventilation level.

**The V2 0-10V** connector is used to connect the actuator that opens the air inlet dampers.

**The V3 0-10V** connector is used to connect a heating system with continuously variable capacity. The voltage at this output increases proportionally to the temperature drop, starting from the supplementary heating temperature.

**The 10V** connector is used to supply power to the winch potentiometer or other 0-10V type circuits.

**Connect the SENS1 (SENS2)** connector to the 1 temperature sensor TS3 or TS5; polarity is irrelevant. When 2 sensors are connected simultaneously, the measured temperatures are averaged. It is good practice to keep measurement cables away from power cables.

**The 1-WIRE** connector can be used to connect a larger number of digital temperature sensors, up to 4, connected in parallel (correct polarity must be maintained). The maximum length of the cable connecting the sensors is 150m (the length does not affect temperature measurement); the use of a shielded cable is recommended.

**The RS-485** connector can be used to build ventilation systems and communicate with a PC.

**The IN1 0-10** connector is used to input a feedback signal from the air inlet system – it determines the current position of the inlets.

**The IN2 0-10** connector is used to connect the controller to other sensors, e.g. humidity, CO2, or to operate the controller as a power expansion module.

# Operating principle
The main task of the controller is to maintain the temperature in the livestock room at the level set by the livestock keeper. Remember that the controller is only a tool intended to help ensure optimal climatic conditions in the livestock room. The primary role in this process, however, belongs to the livestock keeper, who should adjust the device settings to changing outdoor climatic conditions and, above all, to the requirements of the animals in the livestock building, and monitor the operating status of the device using an alarm control panel.

## Initial controller start-up
:::danger 
 At initial controller start-up, the prohibited motor operating band must be set.

:::
The controller works with fans based on a single-phase asynchronous motor with a maximum total current consumption of 12A. After connecting the selected fans, the user must adapt them to operation with the controller. In other words, the minimum fan operating level (speed) must be set. This function is called “Prohibited Band” and is set once by the user in “Advanced Settings”. To perform this procedure correctly, assistance from a second person is recommended, so that one person can continuously observe the fan behavior while the other adjusts the “Prohibited Band” value (the factory value is 0). Failure to set the prohibited band may lead to incorrect device operation. The “Prohibited Band” value can be considered correct when the pressure generated by the fan begins to lift the ventilation shaft dampers slightly. The “Prohibited Band” setting procedure must be repeated whenever the fan connected to the controller is replaced.

## Periodic ventilation
Periodic ventilation is a function performed by the controller that starts when the room temperature falls below the setpoint temperature. This function provides the animals with a cyclical supply of fresh air. The Periodic Ventilation menu contains 3 parameters:
- **“Operating Time”** - specifies how many minutes the fan is to be switched on;
- **“Pause Time”** - specifies the fan standstill time;
- **“Periodic Ventilation Level”** - specifies the ventilation output during the “Operating Time”.

All the parameters listed above are set by the user. 

### Several rules must be kept in mind when setting periodic ventilation parameters:
- periodic ventilation is activated only when the temperature in the pig house falls below the setpoint temperature,
- the primary function of periodic ventilation is to provide the animals with a cyclical supply of fresh air, not to maintain the setpoint temperature in the room,
- it is recommended to ventilate rooms briefly but frequently,
- long periodic ventilation intervals should be avoided, as they may lead to excessive temperature fluctuations,
- the settings must always be adapted to the animals' behavior and the conditions both inside and outside the room.

## Device operation
The controller continuously varies ventilation from **“Min.1” to “Max.1”** within the range from **“Setpoint Temperature”** to the sum of **“Setpoint Temperature”** and **“Ventilation Band 1gr.”**. Above this range, ventilation group 2 is switched on, and group 1 changes its level to **“Min.2”**; as the temperature rises further, ventilation increases to **“Max.2”** at the end of the **“Ventilation Band 2 gr.”** range. If **“Ventilation Band 2 gr.”** is set to zero and ventilation operates at **“Max.1”**, ventilation group 2 switches on, and a further temperature rise causes no further changes in ventilation (dotted part of the graph). If the room temperature falls below **“Setpoint Temperature”**, the controller ventilates the room periodically; with a further decrease, supplementary heating is switched on. Everything depends on the settings entered by the user. The controller software also supports operation with an alarm control panel, which can be activated if the temperature in the pig house deviates from the set parameters. 

![Ventilation](./img/Sc-12wentyl.png)  

## Programming the controller
The controller has a set of default settings that are written to non-volatile memory in two cases:
1. Initial device start-up,
2. Data memory error.
In the event of an absent or interrupted power supply, the controller does not lose previously entered and saved user settings.

## Front panel – indicators, buttons and display
![Panel](./img/SC-12panel.png)  
    1. Red indicator light indicating that the maximum permissible temperature has been exceeded.
    2. Red indicator light indicating that the temperature has fallen below the minimum permissible temperature.
    3. Yellow indicator light indicating supplementary heating.
    4. Yellow indicator light indicating group 2 ventilation.
    5. Green indicator light indicating manual ventilation level setting.
    6. Green indicator light indicating RS485 communication activity.
    7. Menu display; during normal operation, it shows the temperature.
    8. Bar graph indicating the ventilation level.
    9. Key for moving up in the menu or changing a parameter value.
    10. ESC key - exits the menu or a parameter without saving the value.
    11. OK key - enters the menu or confirms (saves) a parameter.
    12. Key for moving down in the menu or changing a parameter value.

## Using the menu
The controller is equipped with a range of functions that allow it to be adapted to a specific application. These functions are grouped in a menu accessed by pressing one of the keys **(“+”, “-” or “OK”)**. The **“+”** and **“-”** keys are used to select functions, while editing, saving data or entering a further submenu is performed using the **“OK”** key. Press the **“Esc”** key to return to the parent menu or cancel saving a parameter.

## Basic menu functions

| MENU                          | Description       | 
|:-----------                   |:---------- |
| Temperature 20,8o C W16% A    | **Information mode** - normal operation. The display shows the current temperature and, when the fan is running, the ventilation level. Meaning of additional symbols:A-indicates an active alarm,D  - indicates heating is on, W - indicates additional ventilation| 
|   Setpoint temp.   20,0o C      |**“Setpoint Temperature”** – Specifies the temperature at which continuously variable ventilation begins. Select an appropriate value according to the type of livestock.| 
| Periodic ventilation     | **Periodic ventilation** – two time values are set.    1.**Operating time** Specifies the number of minutes of ventilation operation.    2.**Pause time** Specifies the number of minutes of ventilation standstill between successive operating cycles.    3.**Periodic ventilation level** - Specifies the ventilation intensity during periodic ventilation operation.| 
| Alarm |  1.**Alarm active Yes** - Activation/Deactivation of the alarm contact; to prevent the controller from issuing an alarm signal at the output (to the alarm control panel), select “NO” in the menu.  2. **Temp. Min. 15,0o C** - Specifies the absolute minimum temperature at which the alarm is activated.  3.**Temp. Max. 25,0o C** - Specifies the absolute maximum temperature at which the alarm is activated.  4.**Audible alarm Yes** - Activation/Deactivation of the audible signal inside the controller. | 
|    Ventilation        |  1.**Vent. band 1 5,0o C**   - Specifies the controller response rate (changes in ventilation level from minimum 1 to maximum 1) to rising temperature.  2.**Min. level 1 1 %** - Specifies the ventilation level corresponding to the setpoint temperature.  3.**Max. level 1 100 %**-Specifies the constant ventilation level for a temperature exceeding the continuously variable control range when “Vent. band 2gr.” = 0; otherwise, the maximum controlled ventilation level for a temperature equal to the sum of the setpoint temperature and the group 1 band.  4.**Vent. band 2 0,0o C**-Specifies the controller response rate (changes in ventilation level from minimum 2 to maximum 2) to rising temperature for group 2. The function is inactive when the band equals zero.  5.**Min. level 2 1 %**-Specifies the minimum ventilation level of group 1 at the point when the contacts of group 2 close.  6.**Max. level 2 100 %**-Specifies the constant ventilation level for a temperature exceeding the continuously variable control range when group 2 is switched on.  7.**Group 3  5,0o C**-Specifies the constant ventilation level for a temperature exceeding the continuously variable control range when group 2 is switched on.  8.**Group 4 7,0o C**-Specifies the temperature, relative to the setpoint temperature, at which ventilation group 4 switches on (the winch function must be deactivated).| 
|    Supplementary heating  |  1.**Suppl. heating temp. 15,0o C**-Specifies the temperature at which supplementary heating switches on.  2.**Suppl. heating band 5,0o C** -Specifies the proportion of supplementary heating system output (at output V3 0-10V) depending on temperature. | 

## Advanced menu functions
The advanced menu is intended mainly for installers; it allows the controller to be adapted to the installation and the fan, circuits to be tested, and the menu language to be selected. To access advanced settings, press and hold two menu keys for approximately 10s. 

| MENU                          | Description       | 
|:-----------                   |:---------- |
|Testing  |This function is used to check the individual controller output circuits; all settings are temporary and apply only while the respective menu item is selected. After pressing “ESC” or “OK”, the output returns to the state determined by controller operation.  1.**Ventilation 0 %**  Allows the ventilation level to be entered manually to check the ventilation system. After confirming the function, the green indicator light (hand) lights up.  2.**Alarm No** Activation switches on 2 red indicator lights, the audible signal and the alarm circuit.  3.**Supplementary heating No** Activation switches on the yellow indicator light (flame) and the supplementary heating circuit.  4.**Vent. stage 2 No** Activation switches on the yellow indicator light (fan) and the group 2 circuit.  5.**Output V1 0,0 V  Output V2  0,0 V Output V3  0,0 V**-Test of outputs 0-10V; the “+” or “-” keys can be used to set the selected voltage for the following systems, respectively: expansion modules, inlet dampers, continuously variable supplementary heating. This function is particularly useful for calibrating inlet damper Output V2.  6.**Winch 0** Allows the inlet damper system to be checked: “+” - opens the inlets, “-” - closes the inlets; the display shows the current actuator position read from the potentiometer.  7.**Group 3 No**  Activation switches on the ventilation group 3 circuit. (the winch function must be deactivated)  8.**Group 4 No**  Activation switches on the ventilation group 4 circuit. (the winch function must be deactivated)|
|Language        | Menu language selection. Polish or English can be selected. | 
|Fan         |  1.**Prohibited Band 0**- Calibration of the minimum speed of fans connected directly to the controller; this parameter corresponds to ventilation level “1%”. A positive parameter value increases the speed, and a negative value decreases it.  2.**Exp. module Min. 1,9 V** -Minimum voltage supplied to the power expansion module (output V1 0-10V).  3.**Exp. module Max. 10,0 V** -Maximum voltage supplied to the power expansion module (output V1 0-10V).  4.**Module cutoff No** - Disconnection of the power expansion module; when “YES” is selected, the voltage at the output controlling the expansion modules (V1 0-10V) drops to 0V rather than the set minimum value when the ventilation level is 0%.  5.**Inversion  No**-Activation reverses the characteristic of output V1. The voltage decreases as the ventilation level increases within the specified min.-max. range. The signal at output V1 is of type 10-0V.| 
| Inlet dampers       |  1.**Advance opening 0,0o C**-Earlier opening of the inlet dampers. The set parameter specifies how far below the “Setpoint Temperature” the inlet dampers should open.  2.**Full closure  No**- Activation causes the voltage at the output controlling the inlet dampers (V2 0-10V) to drop to 0V rather than the set minimum value. This applies when there is no ventilation (ventilation level 0%).  3.**Dampers min.  1,9 V**- Minimum voltage supplied to the inlet dampers (output V2 0-10V).  4.**Dampers max.  10,0 V**- Maximum voltage supplied to the inlet dampers (output V2 0-10V).  5.**Inversion   No**-Activation reverses the characteristic of output V2. The voltage decreases as the ventilation level increases within the specified min.-max. range. The signal at output V2 is of type 10-0V. |  
| Temperature measurement  |  1.**Calibration S1 23,0o C -> 23,5o C**,**Calibration S2 23,0o C -> 23,2o C** - Calibration for analog inputs allows the temperature read from sensors S1 and S2 to be rescaled.  2.**Averaging Time 60 s**- This parameter specifies the time period over which current temperature readings are averaged. The average temperature value is the basic parameter for controller functions. Changes in output states (ventilation, supplementary heating, dampers, subsequent ventilation groups, alarms,...) are closely linked to this parameter and cannot occur more frequently than the time specified here. | 
| Winch      |  1.**Opening Calibration 1024 -> 853**,**Closing Calibration 0 -> 324** -Winch calibration is essential for correct operation of the air inlet system. The “+” key opens the inlets, and the “-” key closes them. While the inlets are opening, the position parameter should increase, and while they are closing, it should decrease; otherwise, check the actuator connection (power supply and potentiometer). For opening calibration, open the inlets fully and confirm the position with the “OK” key. For closing calibration, close the inlets and confirm the position with the “OK” key. The “ESC” key exits the function without saving. The difference between the open and closed positions should be at least 100 units.  2.**Deactivation No**-Deactivation releases contacts FUNC1 and FUNC2 from winch control; these contacts then serve ventilation groups 3 and 4.| 
| Soft Start               | The parameters in this menu group control ventilation start-up. Switching on ventilation in the continuously variable group is preceded by a gradual start-up to 100%, brief operation at 100%  and a decrease to the required ventilation level. This produces a blast of air at ventilation start-up, facilitating the opening of butterfly valves in the ventilation shafts.   Values are expressed in supply voltage cycles at 1% ventilation.  1.**Ramp-up Time 5**- This parameter specifies the rate at which the ventilation speed rises from zero to maximum – soft starting of the fans. A value of 0 disables the soft ramp-up.  2.**Time 100%   100**- This parameter specifies the operating time at start-up at 100% ventilation level. Setting the ramp-up time and 100% to 0 completely disables the blast of air at ventilation start-up.  3.**Ramp-down Time 5**-  This parameter specifies the rate of ventilation level changes. | 
|Supplementary heating              |  1.**Contact inversion No**-Activation reverses the characteristic of the HOT output. The contact opens as the measured temperature decreases.  2.**Hysteresis  0,5o C** - Specifies the temperature hysteresis level for the supplementary heating contact.  3.**Relative operation No**- Activation enables the supplementary heating temperature to be set relative to the setpoint temperature. The basic supplementary heating menu changes so that the difference from the setpoint temperature is entered.  4.**Supplementary heating min. 1,9 V** - Minimum voltage supplied for continuously variable heating control – a heater with variable fan capacity (output V3 0-10V).  5.**Supplementary heating max. 10,0 V** - Maximum voltage supplied for continuously variable heating control – a heater with variable fan capacity (output V3 0-10V).| 
| Program 	|  **ver. 2.4  Apr 13 2018** - 	Displays the software version and compilation date|

## Error and warning messages

Error messages inform the user of irregularities in controller operation. The possible error messages are listed below

|ERROR                            |	DESCRIPTION      |
|:-----------                    |:---------- |
|Overload     Alarm 	     |Overload alarm, activated at 75°C. The device suspends operation until it cools down.|
|Alarm  No sensor|Indicates a missing or damaged sensor or connection cable.|

# Notes and warnings 
:::danger 
 The electrical power supply must be disconnected when installing the device, as the voltage present on certain components poses a danger to life and health. Installation by a qualified person is recommended.

:::
- To avoid problems with device operation, the instructions must be read before installation and use.
- Do not tamper with the construction or carry out repairs yourself. This applies in particular to modifications to parts and components. 
- Maintenance or servicing must be performed by authorized personnel (an installer or the manufacturer's service personnel). An alarm system is required in livestock buildings with forced ventilation. The device manufacturer is not liable for damage caused by incorrect installation, incorrect programming of functions, the consequences of unforeseen events or external factors. 
- The ventilation controller parameters must be set according to the conditions in the livestock room. These settings are individual and depend on the livestock keeper's decisions. The device manufacturer reserves the right to make changes to the device construction and software.

:::caution
<div class="warning-container">
  <p>
    <strong></strong> At the end of its service life, the product must not be discarded with unsorted municipal waste, but disposed of in accordance with applicable regulations (European Union WEEE Directive 2012/19/EU).
The product has been manufactured in accordance with RoHS requirements (European Union Directive 2011/65/EU).
  </p>
</div>
:::
:::tip

## Controller technical data
|Parameter                        |	DESCRIPTION      |
|:-----------                    |:---------- |
|Supply voltage|	230VAC 50Hz|
|Maximum current of the continuously variable control output FAN|	12A|
|Output voltage control range|	70V ÷ 230V|
|Maximum output (contact) current FAN 2|	6A|
|Maximum output (contact) current HOT|	6A|
|Maximum output (contact) current ALARM|	4A|
|Maximum output (contact) current FUNC1 and FUNC2|	4A|
|Operating temperature range|	-10 +40oC|
|Temperature measurement range|	0 +50oC|
|Temperature measurement resolution|	0,1oC|
|Temperature sensor fault detection|	YES|
|Maximum number of analog sensors|	2|
|Temperature measurement accuracy – analog input|	1oC|
|Measurement dependence on cable resistance – analog input|	15,8Ω/oC|
|Maximum number of digital sensors|	4|
|Temperature measurement accuracy – digital input|	0,5oC|
|Measurement dependence on cable resistance – digital input|	None|
|Maximum length of the line connecting digital sensors|	150m|
|Surge withstand capability (max E)|	210J|
|Overload protection|	75oC|
|Device dimensions|	34x29x12 [cm]|
|Enclosure ingress protection rating|	IP56|
:::

:::info
The SPEED CONTROL-12 v2 controller  set includes:
 - 1 temperature sensor,
 - 4 wall plugs,
 - 2 cable glands PG13,5.
 - 3 cable glands PG11,
 - 4 cable glands PG9.
:::















































































