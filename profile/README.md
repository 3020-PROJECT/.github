# 3020-Project

> **Note:** This is an example setup — you don’t actually need a TL-MR3020 to explore the projects. Feel free to adapt the code to any hardware you already have! 😄


The **3020-Project** is an open-source initiative dedicated to unlocking the potential of the **TL-MR3020 router**. Through a series of experiments and projects, we transform this small, affordable device into a flexible mini-computer that can interface with Arduino Nanos, ESP32 displays, and keyboards — proving that curiosity and creativity can breathe new life into old hardware.

---

## Projects

### 🔌 3020-NANO
A lightweight **Arduino Nano firmware** that listens for **serial commands** from the TL-MR3020.  
Allows remote execution of I/O operations such as reading/writing digital or analog pins and controlling an LCD display.  

**Features:**
- Serial command protocol for Nano control  
- Digital & analog I/O support (`read`, `write`, `aread`, `awrite`, `pinmode`)  
- LCD support via I²C  
- Human-readable responses (`OK`, `KO`)  

[Learn more →](https://github.com/3020-PROJECT/3020-NANO)

---

### ⌨️ 3020-Keyboard
A **keyboard bridge program** that forwards keypresses to both the Arduino Nano and an **ESP-VGA-Displayer** over TCP/IP.  
Enables live text input on the VGA screen while simultaneously controlling the Nano.

**Features:**
- Dual output: serial + network  
- Live text mirroring on VGA  
- Modular, simple design for integration with other hardware  

[Learn more →](https://github.com/3020-PROJECT/3020-Keyboard)

---

### 🖥️ ESP-VGA-Displayer
An **ESP32 project** that drives a VGA display using a simple TCP/IP text protocol.  
Other devices on the same network can send text commands in real time, turning the ESP32 into a versatile display server.

**Features:**
- VGA output powered directly by the ESP32  
- TCP-based text protocol  
- Color control and live updates  

[Learn more →](https://github.com/3020-PROJECT/esp-VGA-Displayer/)

---

## Contributing
Pull requests, feature suggestions, and bug reports are welcome!  
Please document any changes or additions clearly to help the community build on this work.

---

## License
MIT License — free to use, modify, and share.
