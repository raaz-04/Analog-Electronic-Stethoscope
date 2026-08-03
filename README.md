<div align="center">

# 🩺 Analog Electronic Stethoscope

### A Fully Analog Heart & Lung Sound Amplification System

Designed and built using **NE5532 operational amplifiers**, **BD139 output stage**, and a **±12 V analog power supply**.

<p align="center">
  <img src="images/WhatsApp Image 2026-07-12 at 11.06.53.jpeg" width="900">
</p>

![Status](https://img.shields.io/badge/Status-Completed-success)
![Analog](https://img.shields.io/badge/Signal%20Processing-100%25%20Analog-blue)
![PCB](https://img.shields.io/badge/PCB-Altium%20Designer-red)
![CAD](https://img.shields.io/badge/CAD-SolidWorks-orange)
![Power](https://img.shields.io/badge/Power-%C2%B112V-green)

</div>

---

# 📖 Overview

This project is a **fully analog electronic stethoscope** developed as part of the **Electronic Circuit Design (EN2111)** module.

Unlike conventional digital stethoscopes that rely on microcontrollers and digital signal processing, this design performs the entire signal conditioning chain using analog electronics.

Weak heart and lung sounds are captured by an electret microphone, amplified using low-noise operational amplifiers, filtered through active analog filters, and finally amplified by a discrete output stage to drive a speaker.

The project covers the complete hardware design workflow from concept to a fully functional prototype.

---

# ✨ Features

- 🩺 Fully analog signal processing
- 🎧 Low-noise microphone preamplifier
- 🎚 Active analog filtering
- 🔊 Speaker output stage
- ⚡ Dual-rail ±12V power supply
- 💻 PCB designed in Altium Designer
- 📦 Enclosure designed in SolidWorks
- 🔧 Hand-assembled and tested hardware prototype

---

# 🛠 Hardware

| Component | Description |
|-----------|-------------|
| NE5532 | Dual low-noise operational amplifier |
| BD139 | Speaker output driver |
| Electret Microphone | Audio sensor |
| Speaker | Audio output |
| Passive Components | Gain and filter network |
| ±12V Supply | Analog power supply |

---

# 💻 Software & Design Tools

- Altium Designer
- LTSpice / Multisim
- SolidWorks

---

# ⚙ System Architecture

```text
        Chest Piece
             │
             ▼
   Electret Microphone
             │
             ▼
    Low Noise Pre-Amplifier
          (NE5532)
             │
             ▼
    Active Band-Pass Filter
          (NE5532)
             │
             ▼
      Output Driver
          (BD139)
             │
             ▼
          Speaker
```

---

# 📷 Project Gallery

## Prototype Setup

The complete analog electronic stethoscope prototype showing the assembled PCB connected to the stethoscope chest piece and speaker.

<p align="center">
<img src="images/WhatsApp Image 2026-07-12 at 11.06.53.jpeg" width="850">
</p>

---

## Assembled PCB

Angled view of the fabricated PCB after soldering and hardware assembly.

<p align="center">
<img src="images/WhatsApp Image 2026-07-12 at 11.06.54.jpeg" width="700">
</p>

---

## PCB Top View

Top view of the completed PCB highlighting the component placement and analog circuitry.

<p align="center">
<img src="images/WhatsApp Image 2026-07-12 at 11.06.55.jpeg" width="600">
</p>

---

# 🚀 Development Workflow

```text
Research
    │
    ▼
Circuit Design
    │
    ▼
Simulation
    │
    ▼
Schematic Design
    │
    ▼
PCB Layout
    │
    ▼
PCB Fabrication
    │
    ▼
Component Assembly
    │
    ▼
Testing & Debugging
    │
    ▼
Working Prototype
```

---

# 📚 What I Learned

This project provided valuable experience in real-world analog electronics, including:

- Low-noise amplifier design
- Active filter design
- PCB layout techniques
- Grounding strategies
- Power supply decoupling
- Noise reduction
- Signal integrity
- Analog circuit debugging
- Component tolerances
- Hardware testing and validation

One of the biggest lessons was understanding the difference between simulation and real hardware. Designing, assembling, and debugging a fully analog system required careful analysis of every stage in the signal chain, reinforcing practical engineering skills beyond what simulation alone can provide.

---

# 📁 Repository Structure

```
Analog-Electronic-Stethoscope
│
├── README.md
├── LICENSE
├── images
│   ├── WhatsApp Image 2026-07-12 at 11.06.53.jpeg
│   ├── WhatsApp Image 2026-07-12 at 11.06.54.jpeg
│   └── WhatsApp Image 2026-07-12 at 11.06.55.jpeg
│
├── pcb
│
├── simulation
│
├── enclosure
│
└── docs
```

---

# 🔮 Future Improvements

- Portable battery-powered design
- Adjustable volume control
- Headphone output
- Improved acoustic chamber
- Rechargeable power supply
- Digital recording interface
- Bluetooth connectivity
- Enhanced enclosure design

---

# 🤝 Acknowledgements

This project was completed as part of the **Electronic Circuit Design (EN2111)** module.

Special thanks to my teammates for their collaboration, dedication, and support throughout the project.

---

# 📄 License

This project is licensed under the MIT License.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a star!

**Designed • Simulated • Built • Tested**

🩺 **100% Analog Electronics**

</div>
