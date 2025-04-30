# Universal-bootloader-burner-circuit
Universal bootloader burner circuit board for DIP microcontrollers, simplifying bootloader flashing using Arduino UNO.


🔥 Universal Bootloader Burner Circuit for DIP ICs

A compact and reusable hardware tool for burning bootloaders into popular DIP microcontrollers like ATmega328P, ATtiny84, ATtiny85, and ATtiny2313A — using Arduino as ISP.

📌 Project Overview

This PCB simplifies the bootloading process by providing individual IC sockets and pre-wired ISP connections. No more breadboard or jumper mess — just plug in the IC and burn the bootloader! 

🔧 Features

- Supports ATmega328P, ATtiny84, ATtiny85, ATtiny2313A
- 4 dedicated IC beds
- Status LEDs (Power, Programming, Error)
- Crystal oscillator for external clock setup
- Works with Arduino UNO as ISP

  
📂 Folder Contents

| Folder | Description |
|--------|-------------|
| `hardware/` | PCB layout, schematic, and Gerber files |
| `arduino-code/` | Arduino ISP sketch |
| `docs/` | Final report in PDF & DOCX |
| `images/` | Photos of PCB and circuit |

🧠 Tools Used

- Altium Designer Professional/ EasyEDA (best for beginners)
- Arduino IDE

💸 Approximate Cost

| Component | Cost (INR) |
|-----------|------------|
| ATmega328P-PU | ₹290 |
| IC Beds (x4) | ₹20 |
| Arduino UNO | ₹450 |
| PCB Fabrication | ₹320 |
| Miscellaneous | ₹40 |
| **Total** | **₹1120** |

🚀 How to Use

1. Insert IC in its socket
2. Connect Arduino UNO via ISP
3. Upload `ArduinoISP` sketch to Arduino
4. Select target board in Arduino IDE
5. Go to `Tools > Burn Bootloader`

📘 License

This project is open-source, you can use this schematics and pcb design in your projects :)
