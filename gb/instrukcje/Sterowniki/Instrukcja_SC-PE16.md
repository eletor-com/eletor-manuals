---
id: sc-pe16
title: SC-PE16 — operating manual
sidebar_label: SC-PE16
sidebar_position: 5
description: SC-PE16 power expansion module manual — mounting, connection, startup,
  menus and protection.
slug: /sc-pe16
toc_min_heading_level: 2
toc_max_heading_level: 3
---


The SC-PE16 power expansion module is used to control fans when the load exceeds the capacity of the master controller. The device regulates the voltage supplied to the fans based on an analog signal or a manual setting. The maximum total output current is 16 A.

![Power expansion module ELETOR SC-PE16](./img/sc-pe16/sc-pe16.jpg)

## Parameters and features

- AUTO and MANUAL modes and device sleep mode;
- graphic display and touch keypad;
- analog control 2–10 V or 4–20 mA;
- programmable activation threshold for ventilation group 2;
- byPASS at a steady level of 100%;
- thermal protection of the power circuit;
- safeRUN: adjustable emergency operation level;
- calibration of the minimum ventilation level;
- ventilation, relay and alarm tests;
- keypad lock and cleaning lock;
- Polish, English or Ukrainian language;
- power supply 230 V AC, 50 Hz; enclosure IP65.

:::info Software version

The functional description applies to the supplied software **ver. 2.1**. The availability of functions must be checked against the version installed in the device.

:::

## Controller installation

:::danger Disconnect the power supply

The electrical power supply must be disconnected when installing the device, as the voltage present on some components poses a danger to life and health. It is recommended that installation be entrusted to a qualified person.

:::

### Selecting the installation location

Install the device in a location accessible to operators, out of reach of children and animals, and away from direct sunlight. The ambient temperature range is −10°C to +40°C. Ensure free airflow around the enclosure and heat sink. Do not cover the heat sink or install the device near heat sources.

### Mounting

Secure the bottom section of the enclosure to a flat wall using four wall plugs and the mounting holes outside the sealed compartment. Fit the cover using the hinge supplied in the kit. Check the condition and position of the gasket before closing.

Use cables with a circular outer cross-section, sized to fit the cable glands. Tighten the cable glands so that they seal and secure the cable. Seal unused cable entries. Tighten all cover screws. Sealing depends on correct installation of the enclosure and cable entries.

### Preparing the connections

Carry out all work inside the enclosure only after disconnecting the power supply and verifying the absence of voltage. If removing the panel requires disconnecting the ribbon cable, disconnect it carefully and reconnect it securely before closing the enclosure. Do not connect or disconnect the ribbon cable while the power supply is on.

Route INPUT and ENABLE signal cables separately from power supply and output cables. Follow the terminal markings on the specific device. The signal input ground and the PE protective terminal perform different functions and are not interchangeable.

## Electrical connection

:::danger Disconnect the power supply

Before connecting the system, make sure that the power supply is switched off!

:::

![Power supply, fan, GR 2, ENABLE, CAN and INPUT terminals](./img/sc-pe16/zaciski.png)

| TERMINAL | FUNCTION |
| --- | --- |
| L, N, PE — power supply | Power supply 230 V AC, 50 Hz: L — line, N — neutral conductor, PE — protective conductor. The original documentation specifies B20 protection; the selection of protective devices and cables should take the installation and load into account. |
| U, N, PE — fans | U — regulated line output; N and PE — the corresponding common terminals of the device. The total fan current must not exceed 16 A. Each fan requires separate protection. Use motors approved for voltage control. |
| GR 2: C, NO | Isolated relay contact for group 2. It closes when the ventilation setpoint is equal to or above the “Ventilation group 2” threshold. Maximum contact current according to the supplied manual: 6 A. For direct load control, the documentation specifies external B6 protection. |
| INPUT: V, ground | Voltage input. Select “Control type → V input”. In the software under review, the control range is 2–10 V. Do not connect mains voltage or the regulated fan power supply output to this input. |
| INPUT: I, ground | Current input 4–20 mA. Select “Control type → I input”. Connect the signal according to the markings on the source and receiver. |

Use the selected V or I input for control. SC-PE16 requires its own mains power supply; the analog input transmits only the control value.

## ENABLE input and communication

### ENABLE: E and ground

The input works with a potential-free contact. Terminals E and ground may only be shorted together or left open; do not apply an external voltage. A closed contact permits operation; an open contact sets the level to 0%. Stopping is subject to the “Ramp-down time” setting.

ENABLE support is activated separately for AUTO and MANUAL in the “Advanced → Fan” menu. Both functions are disabled by default, so no jumper is required in this state. Opening ENABLE is not the same as sleep mode: the panel remains active. In AUTO, when the ENABLE interlock is active, the software skips reading the control signal and does not activate safeRUN.

### CAN and Wi-Fi

The “CAN input” and “WiFi input” items are present in the menu, but in software ver. 2.1 they do not provide control: both functions return a level of 0%. To operate the device with this software, select the V or I input. Do not configure the installation to rely on CAN or Wi-Fi without confirming support in the installed software version.

## Operating principle

SC-PE16 is a power regulator that executes commands from the master controller or the operator. It does not measure room temperature and has no settings of its own for temperature, airing, supplementary heating or air inlet dampers. The percentage ventilation level represents a control value, not a measurement of the actual motor speed.

| NOMINAL SIGNAL | VENTILATION SETPOINT |
| --- | --- |
| 2 V / 4 mA | 0% |
| 6 V / 12 mA | 50% |
| 10 V / 20 mA | 100% |

Between the limit values, the software calculates the level linearly and rounds it to whole percentages. For the V input, the increase starts when the reading exceeds 2,04 V, and for the I input — 4,04 mA. The final output state also depends on ENABLE, startup and thermal protection.

## Emergency operation and protection

### safeRUN — loss of input signal

In AUTO mode, the “Input” alarm appears when the voltage reading is below 1,50 V or the current reading is below 2,00 mA, depending on the selected input. The software then sets the “Emergency operation” level within the range 0–100%; the default is 30%. When the signal returns to or above the detection threshold, the input alarm clears and the device returns to analog control.

The ranges 1,50–2,04 V and 2,00–4,04 mA produce a level of 0% without an input alarm. In this version, a signal of 0 V is not a normal stop command — it activates emergency operation. A master controller with an 0–10 V output must be configured for the 2–10 V range without cutting off to 0 V. In MANUAL, the analog signal does not control ventilation, and the input alarm is cleared.

### Thermal protection

The “Overheating” alarm is set when the heat sink temperature reading exceeds 87°C. It clears when the reading falls below 80°C. During the alarm, the software changes the setpoint: for values of at least 50%, it sets 100%, and for values below 50%, it sets 0%. The output change is subject to the startup and ramp-down algorithm. The protection does not guarantee continuous ventilation operation in every situation.

The state of the GR 2 relay is determined before thermal correction: its state depends on the level before 0% or 100% is forced. The emergency operation level is also subject to thermal correction. In the event of overheating, check the cooling conditions, heat sink contamination and load; work inside the enclosure must be entrusted to an authorized person.

### byPASS and soft start

At a steady output level of 100%, the software activates the phase-control circuit bypass relay. Startup may include ramping up to 100%, holding at 100% and transitioning to the setpoint. The “Soft Start” parameters also affect how quickly the output responds to a change in demand.

## Initial controller startup

:::warning Fan calibration

Warning! During the initial startup of the device, the prohibited motor operating band must be set.

:::

1. With the power supply disconnected, check the power supply, PE, fan and analog signal connections. Confirm that the motors are approved for voltage control and that the total current does not exceed 16 A.
2. Switch on the power supply. If prompted to select a language, press OK and select the language. Unlock the keypad using the button with the padlock symbol.
3. Under “Control type”, select “V input” or “I input”. Set the “Emergency operation” level and the “Ventilation group 2” threshold. If necessary, activate ENABLE separately for the relevant mode.
4. Go to “Advanced → Fan → Prohibited band”. In this menu item, the software forces a level of 1%, and changing the parameter immediately affects the output. The range is −20 to 200, with a default of 0. A positive value increases the minimum control level; a negative value decreases it.
5. Adjust the value so that all fans rotate steadily, without stopping or excessive heating. Observe each fan, preferably with the assistance of another person. A damper lifting alone is not a substitute for checking correct motor operation. Confirm with OK; ESC restores the previous setting.
6. Check the output at several levels, including 0%, a low level and 100%. Repeat calibration after replacing fans or changing their configuration.
7. In AUTO, check the response to the minimum and maximum signal. Then check signal interruption and the transition to emergency operation, as well as the return after the signal is restored. If ENABLE is active, also check its operation.
8. Check GR 2 and the alarm indication in the “Testing” menu. After completing the tests, exit this menu item and select the intended operating mode.

:::warning Actual activation of outputs

Testing and calibration control the actual outputs. They may start the fans, and the ventilation test forces a level independently of normal control. Ensure safe test conditions and continuous supervision.

:::

## Controller programming

### Front panel — indicators and buttons

| ELEMENT | OPERATION |
| --- | --- |
| Power / sleep | The button with the power symbol displays a sleep confirmation prompt; confirm with OK. Pressing it again wakes the device. Sleep mode sets the outputs to the off state; it does not disconnect the mains voltage. |
| Padlock | Enables or disables the keypad lock. When unlocked, the indicator next to the padlock is lit. On the main screen, the lock is reactivated after approximately 30 s of inactivity. |
| A — AUTO | Selects analog input control after confirmation with OK. Indicator A shows the selected mode. |
| M — MANUAL | Selects manual control after confirmation with OK. On the main screen, the + and − keys change the setting within 0–100%. Indicator M shows the selected mode. |
| +, −, OK, ESC | OK opens the menu, enters an item and confirms a value. + and − select an item or change a value. ESC returns to the previous level or cancels editing. |
| Alarm and group 2 | The red indicator signals an alarm. The indicator next to the “2” fan symbol indicates activation of the GR 2 relay. |
| Display | In AUTO, it shows the ventilation setpoint, the reading of the selected input, a bar graph and alarms. When ENABLE is active, it also shows its status. In MANUAL, the main value represents the manual setting; the protective functions may change the output. |

### Saving settings

Menu parameters are saved in non-volatile memory after confirmation with OK. Changes to the MANUAL level take effect immediately and are saved after a short period of inactivity. After a power failure, the saved settings are restored, including the AUTO/MANUAL mode, manual level and sleep state. Do not switch off the power supply immediately after changing the manual setting.

If the checksum is incorrect or a value is out of range, the software restores the factory defaults. All settings must then be checked again, particularly fan calibration, the control input and emergency operation.

## Basic menu functions

| MENU | RANGE / DEFAULT | DESCRIPTION |
| --- | --- | --- |
| Control type | V input | Selection of V, I, CAN or Wi-Fi. For the version under review, use V (2–10 V) or I (4–20 mA). CAN and Wi-Fi do not provide control. |
| Ventilation group 2 | 1–100% / 100% | Activation threshold for the GR 2 contact. The contact is closed at a level equal to or above the threshold and open below the threshold. The software does not define separate hysteresis. |
| Emergency operation | 0–100% / 30% | Level set when the selected analog signal is lost in AUTO. A value of 0% means stopping in the event of signal loss. |
| Cleaning lock | 60 s | Locks key operation for 60 seconds and displays a countdown. Ventilation control continues to operate. The function is intended for wiping the panel, not for electrical work or washing the interior. |
| Advanced | Submenu | Access to tests, language, fan calibration, ENABLE, Soft Start, alarm sound, factory settings and software information. |

## Advanced menu functions

| MENU / PARAMETER | RANGE / DEFAULT | DESCRIPTION |
| --- | --- | --- |
| Testing → Ventilation | 0–100% | Temporary override of the regulated output. Changes take effect during editing. Normal control resumes after exiting with OK or ESC. |
| Testing → Vent. stage 2 | No / Yes | Temporary override of the GR 2 contact and its indicator. |
| Testing → Alarm | No / Yes | Temporary test of alarm signaling, including sound, independently of the normal “Alarm signal” setting. |
| Language | Polish | Polish, English and Ukrainian are available. |
| Fan → Prohibited band | −20–200 / 0 | Calibration of the 1% level. During editing, the actual output is forced to 1%. The parameter is not expressed in percent or seconds. |
| Fan → EN activation AUTO | No / Yes; No | Makes AUTO mode dependent on the ENABLE input. |
| Fan → EN activation MANUAL | No / Yes; No | Makes MANUAL mode dependent on the ENABLE input. |
| Soft Start → Ramp-up time | 0–50 / 5 | Rate of level increase during startup to 100%. A higher value means a slower change. A value of 0 skips the ramp-up stage. |
| Soft Start → Time 100% | 0–250 / 100 | Holding the level at 100% during startup. A value of 0 skips the hold stage. Setting both ramp-up and hold to 0 skips the ventilation boost to 100%. |
| Soft Start → Ramp-down time | 0–50 / 5 | Rate of approach to the requested level, including when it changes. A value of 0 means a change without a gradual transition. |
| Alarm signal | No / Yes; No | Enables the audible alarm signal. The No setting does not remove the on-screen message or the indicator signal. |
| Factory settings | No / Yes | Selecting Yes restores and saves the default values, including calibration 0, V input, AUTO, emergency operation 30%, the GR 2 threshold equal to 100% and disabled ENABLE. After this operation, reconfigure and check the device. |
| Software | ver. 2.1 + compilation date | Displays the software version and compilation date. This description was prepared on the basis of the supplied SC_PX16_v02 sources. |

The Soft Start parameters are dimensionless software counter settings, not times specified in seconds. At 50 Hz, a single step corresponds approximately to (setting + 1) × 20 ms: for ramp-up and ramp-down, this is the time for a change of 1 percentage point; for “Time 100%” — the hold time. The value 0 has the meaning described in the table. Actual times depend on the algorithm phase.

## Error and warning messages

| MESSAGE | MEANING AND ACTION |
| --- | --- |
| Input | The selected signal reading is too low in AUTO. The device sets emergency operation. Check the signal source, cables, common ground and V/I selection. |
| Overheating | Heat sink reading &gt;87°C; clearing &lt;80°C. Ventilation is set to 0% or 100%, as described under thermal protection. Check cooling and load. |
| Power supply | Disturbance in power circuit synchronization with the mains. Check the power supply and installation. In the event of a complete power failure, the display does not operate. |
| Memory CRC | Checksum or range error in the saved settings. The software restores the default values. Check the configuration and repeat calibration; if the error recurs, contact the service department. |

## Notes and warnings

:::danger Disconnect the power supply

The electrical power supply must be disconnected when installing the device, as the voltage present on some components poses a danger to life and health. It is recommended that installation be entrusted to a qualified person.

:::

Read the manual before installation and use. Entrust repairs and work inside the device to authorized personnel. Sleep mode, the keypad lock, ENABLE and the 0% setting do not disconnect the power supply and do not ensure safe conditions for electrical work.

Select ventilation and emergency operation settings according to the needs of the animals and the installation. Regularly check the actual operation of all fans. SC-PE16 signaling is not a substitute for independent monitoring of conditions in the building and power failure. The terminal strip shown has no separate ALARM contact for an alarm control panel.

:::note Device disposal

At the end of its service life, the product must not be discarded with unsorted municipal waste, but must be disposed of in accordance with the applicable regulations (European Union WEEE Directives 2012/19/EU).

:::

The product has been manufactured in accordance with RoHS requirements (European Union Directive 2011/65/EU).

## Controller technical specifications

| PARAMETER | VALUE |
| --- | --- |
| Power supply / internal power consumption | 230 V AC, 50 Hz / &lt;10 W |
| Maximum total U output current | 16 A |
| Maximum GR 2 contact current | 6 A; C–NO contact, isolated |
| V input / I input | 2–10 V / 4–20 mA, selected in the menu |
| Signal loss threshold (software reading) | V &lt;1,50 V / I &lt;2,00 mA |
| ENABLE | Potential-free E–ground contact; activated separately for AUTO/MANUAL |
| Thermal protection (heat sink reading) | Alarm &gt;87°C; reset &lt;80°C |
| Ambient temperature / enclosure | −10°C to +40°C / IP65 |
| Dimensions / surge withstand capability | 34 × 29 × 12 cm / 210 J |
| Menu languages | Polish, English, Ukrainian |

Kit contents according to the supplied documentation: 4 wall plugs, 2 cable glands PG13,5, 1 cable gland PG9 and 1 hinge.

## Warranty terms

The content of the warranty terms has been retained from the supplied manufacturer's document.

1. The manufacturer ELETOR, with its registered office in Poland at: Pod Sosno 28, 87-305 Zbiczno (hereinafter referred to as the Warrantor), grants the Purchaser a quality warranty for the goods for which this warranty card has been issued, provided that they are used for their intended purpose and in accordance with the rules specified in the operating manual delivered to the Purchaser with the goods.
2. The warranty period is 24 months from the date of sale. Faults or defects in the goods discovered during this period will be rectified free of charge. After the warranty period expires or if warranty rights are lost, faults or defects will be rectified for a fee.
3. The warranty does not cover:

   - any defects caused by improper handling of the goods (including performing operations not described in the operating manual, etc.);

   - any defects resulting from repairs, modifications, etc. performed by anyone other than the Warrantor;

   - any defects or damage resulting from transporting or dropping the goods, if these events occurred after the purchase of the goods, and mechanical damage caused by improper handling by the user;

   - any defects or damage caused by fire, earthquake, flood, lightning strike or other natural disasters, environmental pollution, exposure to external ionizing radiation or magnetic fields, and irregular power supplies or power with parameters that do not meet the requirements;

   - any defects resulting from improper storage (e.g. storing the goods outside the temperature or humidity range stated in the specifications, near chemicals), improper maintenance or cleaning, etc.;

   - any defects resulting from depleted power supply batteries, etc.;

   - any defects caused by sand, mud, dust, water and other liquids, etc. that have entered the enclosure of the goods;

   - damage resulting from natural, partial or complete wear of the goods in accordance with their properties or intended purpose;

   - activities specified in the operating manual that the user is required to perform independently.

4. The Purchaser loses warranty rights as a result of:

   - any repair or modification of the goods by anyone other than the Warrantor;

   - any seal being found to have been tampered with, damaged or broken;

   - serial numbers or other markings identifying the goods being found to have been damaged, tampered with, covered or removed.

5. The repair period is up to 21 working days from the date the defect is reported and the complete goods are delivered to the Warrantor's service center. In particularly justified cases involving the need to import parts or components from abroad, or damage that is particularly complex or difficult to repair or diagnose, the repair period may be extended by the time necessary to fulfill the warranty obligations.
6. The Purchaser's warranty rights may only be exercised upon presentation of a valid warranty card correctly completed on the date of purchase and proof of purchase (invoice, receipt, etc.). Unauthorized changes to entries on the warranty card (including crossing out, erasures, additions, etc.) result in the loss of warranty rights. A warranty card without the name, model and serial number of the goods, the date and place of purchase, and a legible stamp and signature of the Seller is invalid and does not constitute grounds for a valid warranty claim.
7. The Purchaser is required to deliver the goods at their own expense in packaging appropriate for the equipment that ensures safe and proper transport and storage, or to cover the Warrantor's travel costs. If the goods submitted for repair are found to be technically operational and free from defects, or if the identified fault is not covered by the warranty, the Purchaser will be charged for service and transport costs.
8. The Purchaser is required to collect the repaired goods within 90 days of the Warrantor's notification that the repair has been completed. If the Purchaser does not collect the goods within this period, they bear the risk of accidental loss of or damage to the goods.
9. The warranty period is extended by the duration of the repair, calculated from the date of delivery of the goods to the agreed collection date after repair. The Warrantor is required to issue a document stating the period and scope of the defects rectified in the goods.

10. The Purchaser submits claims through the Seller of the goods or directly to the Warrantor's address: ELETOR, Pod Sosno 28, 87-305 Zbiczno, Poland.

11. The Warrantor is not liable:

    - for lost income resulting from the occurrence of a defect and the time required to rectify it;

    - for losses resulting from the occurrence of a defect or any damage resulting from improper installation, use or programming of the device's functions.
