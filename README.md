# ⚡ 5V-to-3.3V LDO Regulator PCB

**A compact, reliable voltage regulator board that converts USB 5V to stable 3.3V output** 🔥

Perfect for powering ESP32, Arduino, sensors, or any 3.3V microcontroller/project from a standard USB power source! 

---

## 📸 Visuals

![Schematic Diagram](Regulator Schematic.png)
**Schematic** – Clean & simple linear regulation

![PCB Layout](PCB layout design.png)
**PCB Layout** – Compact 2-layer design with clear labeling

![3D View Front](3D view.png)
**3D Render (Front)** – Professional look with components placed

![3D View Back](https://github.com/Awad235/5V-to-3.3V-LDO-Regulator-PCB/blob/105e766f723e5859e9febe2f0bbbf1fbc27d35e7/3D%20view/3D%20view%20back.png)
**3D Render (Back)** – Clean ground plane & mounting holes

---

## 🛠️ Bill of Materials (BOM)

| Id | Designator | Quantity | Component                  | Footprint                  | Part Number (Manufacturer)          | Digi-Key P/N         | LCSC P/N    |
|----|------------|----------|----------------------------|----------------------------|-------------------------------------|----------------------|-------------|
| 1  | J1         | 1        | USB Micro-B Connector      | USB_Micro-B_Molex          | MOLEX 47346-0001                    | WM17141CT-ND         | C132560     |
| 2  | U1         | 1        | 3.3V LDO Regulator         | TO-252-3                   | AMS1117CD-3.3 (Advanced Monolithic) | 4518-AMS1117CD-3.3CT-ND | C841796 |
| 3  | C1, C3     | 2        | 100nF Ceramic Capacitor    | 0402 (1005 Metric)         | YAGEO CC0402KRX7R5BB104             | 311-1701-1-ND        | C541406     |
| 4  | C2, C4, C5 | 3        | 22µF Electrolytic Capacitor| 6.3×7.7mm                  | 22µF 10V (standard electrolytic)    | —                    | —           |
| 5  | J2         | 1        | 2-Pin Screw Terminal       | Phoenix MKDS-3-2-5.08      | XINLAIYA XYEEK500-5.08-2P           | A126305CT-ND         | C557689     |

> 💡 All parts are easily available on Digi-Key, LCSC, or AliExpress. Total BOM cost ≈ $2–3 USD in small quantities!

---

## 🔧 How It Works

1. **5V Input** → Comes from **J1 (USB Micro-B)**. VBUS pin carries raw 5V.
2. **Filtering** → C4 (22µF) + C3 (100nF) clean the input.
3. **Regulation** → **U1 (AMS1117-3.3)** LDO drops 5V → stable **3.3V** with low dropout (~1.2V).
4. **Output Filtering** → C1 (100nF) + C2 & C5 (22µF) ensure ripple-free 3.3V.
5. **Output** → Available on **J2 (Screw Terminal)** – easy to connect wires or headers.

**Max current**: ~800mA (limited by AMS1117 & USB).  
**Dropout voltage**: Very low – works even when input is 4.5V+.

**Simple, efficient, and bulletproof** – no switching noise, perfect for analog/sensor projects! ⚙️

---

## 📌 Features & Specs

- ✅ Input: 5V USB Micro-B (VBUS)
- ✅ Output: Clean 3.3V @ up to 800mA
- ✅ Ultra-compact size (~50×20mm)
- ✅ Through-hole + SMD mix for easy hand soldering
- ✅ Mounting holes on all corners
- ✅ Clear silkscreen labels
- ✅ ESD protection on USB lines

---

## 🧑‍💻 Author

**Awad Zuhair** 👨‍💻

- **GitHub**: [https://github.com/Awad235](https://github.com/Awad235)
- **LinkedIn**: [www.linkedin.com/in/awadzuhair](https://www.linkedin.com/in/awadzuhair)

Made with ❤️ in Bengaluru. Feel free to fork, improve, or use this in your projects!

---

**Star ⭐ this repo if you found it useful!**  
Questions? Open an issue or DM me on LinkedIn.
