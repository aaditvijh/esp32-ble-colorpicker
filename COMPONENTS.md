# COMPONENTS

This document outlines the components used in the RGB LED color picker project, detailing their specifications and purposes.

## Components List

1. **RGB LED**  
   - **Type:** Common Cathode / Common Anode  
   - **Voltage:** 2.0 - 3.2V (Red), 3.0 - 3.8V (Green), 3.0 - 3.8V (Blue)  
   - **Current:** 20mA  
   - **Description:** The RGB LED will be the primary output device, mixing Red, Green, and Blue light to create a variety of colors.

2. **Microcontroller**  
   - **Type:** ESP32  
   - **CPU:** Dual-core 240MHz  
   - **Flash Memory:** 4MB  
   - **WiFi:** 802.11 b/g/n  
   - **Bluetooth:** BLE  
   - **Description:** The ESP32 will control the RGB LED and handle Bluetooth communication for user interaction.

3. **Resistors**  
   - **Value:** 220 ohm (for current limiting on LED)  
   - **Description:** Resistors are used to limit the current flowing through the LED to prevent damage.

4. **Breadboard**  
   - **Size:** 400 tie points  
   - **Description:** A breadboard will be used for prototyping the circuit before final assembly.

5. **Connecting Wires**  
   - **Type:** Male-to-male jumper wires  
   - **Description:** These wires will connect the components on the breadboard.

6. **Power Supply**  
   - **Type:** USB power adapter or battery  
   - **Voltage:** 5V  
   - **Description:** The power supply will provide power to the microcontroller and the LED.

## Specifications

- Ensure all components are rated for the respective voltages and currents to prevent damage.
- Utilize appropriate wiring techniques to maintain a stable and functional prototype.

## Notes

- Keep in mind that the brightness of the LED can be controlled via PWM signals from the microcontroller.
- Testing should be performed to ensure proper color mixing and functionality of components.
