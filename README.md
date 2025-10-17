# LoRa-Based 4-Channel Relay Control Board (Altium Designer)

## Overview  
This project presents a **custom PCB design** for a **4-channel relay control system** based on the **ESP32-C3** and **LoRa RA-02** module.  
The board enables **remote control of actuators** over long distances using **LoRa communication**, making it ideal for **IoT and automation applications** such as **smart agriculture, remote monitoring, and industrial control**.

It includes a **battery management and power regulation system** using:  
- **BQ24040DSQR** for **Li-Ion battery charging**  
- **TPS61230DRCR** for **voltage boosting**  
- **TPS7A9201DSKR** for **low-noise voltage regulation**  

Designed entirely with **Altium Designer**, this board offers **robust connectivity**, **efficient power management**, and **multi-channel actuation capability**.

---

## Components Used  
- **Main Controller:** ESP32-C3 Wi-Fi + BLE Module  
- **LoRa Transceiver:** RA-02 (SX1278-based)  
- **Relay Drivers:** 4 × Relay channels with optocoupler isolation  
- **Battery Charger IC:** BQ24040DSQR  
- **Boost Converter:** TPS61230DRCR  
- **LDO Regulator:** TPS7A9201DSKR  
- **Connectors:** JST battery connector, pin headers for external relays and LoRa antenna  
- **Passive Components:** Decoupling capacitors, resistors, and flyback diodes for relay protection  

---

## Features  
- 4 **independent relay outputs** for actuator control  
- **LoRa long-range wireless communication**  
- **ESP32-C3** with integrated Wi-Fi and BLE  
- **Battery-powered** operation with onboard **charging and regulation circuits**  
- **Boost and LDO stages** for stable voltage supply  
- **Compact and manufacturable PCB layout** optimized for IoT use cases  
- **Designed with Altium Designer** (schematic + PCB)  
- Suitable for **smart agriculture**, **home automation**, and **industrial IoT** applications  

---

## Files Included  
- Altium Designer source files (`.SchDoc`, `.PcbDoc`)  
- Gerber files for PCB fabrication  
- Bill of Materials (BOM)  
- PDF schematics and PCB layout drawings  

---

## TOP VIEW  
![TOP View](https://github.com/FaresAmor/LoRa-Based-4-Channel-Relay-Control-Board/blob/main/TOP.png)

## BOTTOM VIEW  
![BOTTOM View](https://github.com/FaresAmor/LoRa-Based-4-Channel-Relay-Control-Board/blob/main/BOTTOM.png)

---

## Demo  
Below is a preview of the PCB design in Altium Designer:

![Demo](https://github.com/FaresAmor/4CH-RELAY-LORA-ESP32C3-PCB/blob/main/demo.gif)

---

## Contribution  
Feel free to **explore, modify, and contribute** to this project!  
If you discover any issues or wish to suggest improvements, don’t hesitate to open a **pull request** or **raise an issue**. 🚀

---

> 💡 **Tip:** This board is perfect for remote control systems, smart irrigation, or any IoT project requiring reliable long-range communication and power autonomy.
