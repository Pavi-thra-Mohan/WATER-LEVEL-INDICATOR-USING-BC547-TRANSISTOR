# Water Level Indicator Using BC547 Transistor

A simple, low-cost electronics project designed to monitor and display four water levels in a tank using NPN transistors, LEDs, and an alert buzzer for full-level detection.

## Components Required
* **NPN Transistors:** 4× BC547
* **LED Indicators:** 4× LEDs
* **Resistors:** 4× 10kΩ (Base resistors), 4× 1kΩ (Current limiting resistors)
* **Buzzer:** 1× 9V Buzzer
* **Power Source:** 9V Battery
* **Miscellaneous:** Breadboard, connecting wires, sensing probes

## Circuit Description & Working
1. **No Water:** All transistors remain in cutoff mode (OFF); all LEDs and buzzer stay OFF.
2. **Levels 1–3:** Water touches successive level probes, completing the base circuit for each corresponding BC547 transistor and lighting up its LED.
3. **Level 4 (Max Level):** The final probe triggers the fourth transistor, lighting the last LED and sounding the buzzer to signal full capacity and prevent overflow.

## Repository Contents
* `MICROPROJECT_REPORT_AC_FINAL.pdf`: Full microproject report submitted by Pavithra Mohan, Pooja A, and Rohit Anush Nair (Department of Electronics & Communication Engineering, Mar Athanasius College of Engineering).

## How to Recreate
1. Assemble the components on a breadboard following the circuit layout in the documentation.
2. Place four insulated copper wires at varying heights inside the water container as level probes.
3. Connect the common positive probe to the bottom of the container.
4. Power with a 9V battery and fill with water to test sequential LED illumination and the full-tank alert.
