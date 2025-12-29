---

 MCU Data Logger with Built-in EEPROM & RTC

A compact, low-power **embedded data logger** based on the **ATmega328P**, featuring **on-board EEPROM storage** and a **battery-backed real-time clock** for reliable, time-stamped data logging without an SD card.

---

 📌 Key Features

 🧠 Core MCU

* **ATmega328P-AU** (TQFP package)
* 8-bit AVR microcontroller
* Arduino-compatible ecosystem
* Stable and widely supported for embedded applications

 💾 On-Board Memory

* **2 × 24LC1025 I²C EEPROM**
* Total storage: **512 kbit (64 KB)**
* Non-volatile memory for secure data retention
* Ideal for structured and time-stamped logging

 ⏱️ Real-Time Clock

* **DS1337 RTC**
* I²C interface
* Backup battery support
* Maintains accurate date and time during power loss

 🔋 Power System

* Battery input supported
* On-board voltage regulation
* Low-power design for continuous operation
* LED indicators for power and status

 🔌 I/O & Expansion

* I²C bus shared between EEPROM and RTC
* GPIO headers for external sensors
* UART pins available for debugging and data readout
* Flexible for future firmware expansion

---

 📂 Repository Structure

```
MCU-Data-Logger/
│
├── README.md              # Project documentation
├── LICENSE                # MIT License
│

│── Schematic/             # KiCad schematic files
│── PCB/                   # KiCad PCB layout
│── Gerber/                # Manufacturing-ready Gerber files
│
└── Images/                # PCB renders, photos, diagrams
```

---

 🛠️ Hardware Overview

 Memory & RTC

* **24LC1025 EEPROMs** connected via I²C
* **DS1337 RTC** on the same I²C bus
* Required I²C pull-up resistors included

 Power Path

* External power or battery supply
* Regulated voltage for MCU and peripherals
* RTC backup battery for uninterrupted timekeeping

 PCB Design

Understood. Below is the **corrected and updated text**, rewritten to **accurately reflect a FOUR-LAYER PCB design**.
You can **directly replace the existing “PCB Design” section** in your README with this.

---

 🛠️ Hardware Overview

 PCB Design

* **Four-layer PCB architecture**
* Dedicated internal planes for **GND and Power**
* Improved signal integrity and reduced noise
* Better thermal performance and EMI control
* Copper mounting holes for mechanical stability
* Optimized for reliable manufacturing and assembly

---

 🚀 Firmware Overview

* Supports **custom AVR firmware** or **Arduino-based development**
* Capable of:

  * Time-stamped data logging
  * Periodic or event-driven storage
  * UART-based data extraction
* EEPROM addressing handled in firmware for extended memory usage

---

 📄 Manufacturing

The `Hardware/Gerber/` folder includes:

* Top & Bottom Copper
* Solder mask
* Silkscreen
* Drill files
* Board outline

Compatible with popular PCB manufacturers:

* JLCPCB
* PCBWay
* OSH Park

---

---

 📸 Images & Diagrams

Board renders, four-layer PCB photos, and pin-mapping diagrams for the **MCU Data Logger with Built-in EEPROM & RTC** are available here:

 **[Images](./IMAGES)**
 
 📜 License

This project is open-source and released under the **MIT License**.

The MIT License was chosen because it:

* Allows free use, modification, and commercial manufacturing
* Is simple and widely accepted for hardware and PCB projects
* Encourages learning, reuse, and community contributions
* Protects the author from liability

See the `LICENSE` file for full details.

---

 🙌 Contributions

Contributions, improvements, and documentation updates are welcome.
Feel free to open **Issues** or submit **Pull Requests**.

---

 🎯 Best Suited For

* Embedded systems learners
* Data logging applications
* Academic and research projects
* Industrial monitoring prototypes
* Low-power sensor data acquisition systems

---
