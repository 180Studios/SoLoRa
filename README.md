Board Features:

1. Low-cost components 

2. Easy (ish) Assembly. 
    a. Uses QFP package processor and 0603 Rs and Cs 
    b. Can be soldered by hand by most people using standard soldering iron 
    c. One exception is the accelerometer, which can be soldered using a reflow heat gun and a little training

3. Arduino compatible 
    a. Uses the same device as the Arduino Zero - can use Arduino bootloader. 

4. FeatherWing compatible 
    a. Can use with Adafruit’s featherwing expansion boards or use the header for a protoboard mezzanine 

5. Multiple power options to targeting wider IoT applications, particular field applications 
    a. Solar 
        i. Has a CR123 battery clip for a LiFePo4 battery used as a power reservoir. (400mAh) 
        ii. On-board regulator charges LiFePo4 to constant voltage. Solar cell size constrains max charge current. 
    b. Rechargeable Li-Po or external battery pack 
        i. For standard indoor applications 
        ii. On-board USB micro connector and charger IC 
    c. Lithium (primary cell) 
        i. Battery clip will also house a standard CR123 3V Lithium, which has ~1000mAH capacity 
    d. USB 5V for desktop development (or use with a USB battery bank?) 
    e. On- board adjustable regulator 
        i. Change Resistor values to adjust VDD 
            1. To drop Li-Po, external battery pack output voltage and USB 5V to safe level 
            2. LiFePo4 charge voltage. 
        ii. Regulator is used with Lithium primary battery 

6. Small size: 2.3 x 2 inches 
    a. Has mounting holes to match a inexpensive water tight enclosure 
    b. All components mount on one-size only. Bottom is free to increase mounting versatility. 
    c. 2-layer board, cheaper to fabricate. 

7. ARM Cortex M0 (SAMD20G18A) 

    a. Low power, high speed capable, 256K Flash 

8. Optional on-board sensors, indicators 
    a. 3-Axis Accelerometer 
    b. Temperature 
    c. Programmable Red LED 

9. Development Options 
    a. Arduino IDE (use as an Arduino Zero) 
    b. Atmel Studio 
        i. Atmel Studio has Arduino templates to program like Arduino, or: 
        ii. Use standard C form 
        iii. Full debugging capability (breakpoints, watch variables) 
            1. $20 JTAG debugger hardware required for this feature   


