# 3-Button Mini LED Keychain PCB Project 🚀

Welcome to my very first hardware development project! This is a compact, stylish, and fully functional 3-button interactive LED keychain designed from scratch in EasyEDA. 

As a **15-year-old computer technician and electronics enthusiast**, I spent exactly **12 hours straight** learning the software and completing this design on my very first day in PCB layout design.

---

## 👤 About the Designer
* **Name:** Abdullah Özdemir
* **Role:** Hardware & Computer Technician
* **Aspiration:** Founder of "Özdemir Teknik Bilgisayar" 
* **Experience:** Certified in computer hardware, assembly, and troubleshooting. Actively leveling up in custom PCB layout engineering and embedded electronics hardware prototyping.

---

## 🛠️ Project Specifications & Design
The board is carefully engineered to serve as a premium, robust, and highly pocketable interactive electronic keychain.

* **Dimensions:** Ultra-compact form factor (`43mm x 29mm`)
* **Layer Count:** 2 Layers (Double-Sided)
* **Surface Aesthetics:** Premium blue solder mask combined with ENIG (Gold) plating finish for optimal corrosion resistance and a sleek cyberpunk look.
* **Mechanical Features:** Built-in dual keychain ring mounting holes on corners for seamless chain integration.
* **Component Mounting Type:** Through-Hole Technology (THT) for core components, ensuring rugged durability during daily carry.

---

## ⚡ Circuit Topology & How It Works
The system follows a fully customized parallel interactive configuration where each line operates independently to optimize current draw and dramatically extend battery longevity.

1. **Power Source:** Powered by a single **3V CR2032 Coin Cell Battery** (`B1`), housed in a heavy-duty bacaklı (THT) cell retainer.
2. **Control Switches:** Features 3 independent tactile push-buttons (`SW1, SW2, SW3`) labeled with `HT 26 / HT A 26` standards. They operate in a *momentary (anlık)* fashion, meaning the circuit triggers strictly while pressed.
3. **Current Limiting:** Armed with 3 independent **220 Ohm / 120 Ohm AXIAL-0.3** standard resistors (`R1, R2, R3`) to strictly regulate current and completely eliminate any risk of burning the semiconductors.
4. **Output Indication:** 3 distinct indicator LEDs (`LED1, LED2, LED3`) that light up vividly to indicate corresponding track execution.

Since the tracks are isolated per switch, a user only triggers one LED at a time during normal interaction. This smart parallel mechanism keeps the overall current loop well under the chemical limits of the CR2032 cell, preventing immediate voltage sags.

---

## 📂 Repository Contents
* `/Gerber_Files/` : Contains the complete industrial manufacturing `.zip` package (Tested and verified for production lines like Robotistan PCB / JLCPCB).
* `/Schematics/` : Source design sheets from EasyEDA.
* `README.md` : Project documentation.

---

## 🖼️ Visual Showcase

### 3D Production Render (Front)
![3D Front View](images/3d-front.png)

### 3D Production Render (Back & Gold Traces)
![3D Back View](images/3d-back.png)

### EasyEDA Layout Mapping
![PCB Layout Grid](images/pcb-layout.png)

---

## 🔧 Assembly and Fabrication Note
The PCB structure is manufactured with thick copper pouring and distinct clearance paths, specifically optimized for seamless manual hand-soldering using a standard 60W soldering iron. It is perfectly tailored for beginner workshops and custom boutique tech merchandising.

*Designed with passion by Abdullah Özdemir © 2026*
