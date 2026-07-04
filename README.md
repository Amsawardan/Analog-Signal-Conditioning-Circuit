# 🔊 Multi-Stage Analog Signal Conditioning Circuit Using BJT and RC Filters

## 📖 Overview

This project was developed as part of the **IE2034 – Analog Electronics** module for the **BSc. (Hons) in Computer System Engineering** program.

The objective was to design, analyze, and implement a **multi-stage analog signal conditioning circuit** capable of filtering unwanted frequencies and amplifying weak analog signals. The circuit consists of three main stages:

- High-Pass RC Filter
- Common Emitter BJT Amplifier
- Low-Pass RC Filter

The complete circuit was designed, tested, and implemented on a **dot board** using discrete electronic components.

---

## 🎯 Project Objectives

- Design a High-Pass RC Filter with a cutoff frequency of **2 kHz**
- Design a Common Emitter BJT Amplifier with a voltage gain greater than **60**
- Design a Low-Pass RC Filter with a cutoff frequency of **12 kHz**
- Build the complete circuit using a **9V DC power supply**
- Verify circuit performance using an oscilloscope

---

# 🏗️ System Architecture

```
Input Signal
      │
      ▼
High-Pass Filter
(Removes frequencies below 2 kHz)
      │
      ▼
Common Emitter BJT Amplifier
(Amplifies weak signals)
      │
      ▼
Low-Pass Filter
(Removes frequencies above 12 kHz)
      │
      ▼
Clean Amplified Output
```

---

# ⚙️ Circuit Specifications

| Parameter | Value |
|-----------|---------|
| Supply Voltage | 9V DC |
| High-Pass Cutoff Frequency | 2 kHz |
| Low-Pass Cutoff Frequency | 12 kHz |
| Amplifier Type | Common Emitter BJT |
| Transistor | 2N3904 |
| Voltage Gain | Approximately 70 |

---

# 🔩 Components Used

| Component | Value |
|------------|--------|
| NPN Transistor | 2N3904 |
| HPF Capacitor | 100 nF |
| HPF Resistor | 820 Ω |
| LPF Capacitor | 1.2 nF |
| LPF Resistor | 11 kΩ |
| Collector Resistor | 4.7 kΩ |
| Emitter Resistor | 1 kΩ |
| Bias Resistors | 82 kΩ, 27 kΩ |
| Coupling Capacitors | 10 µF |
| Emitter Bypass Capacitor | 100 µF |
| Power Supply | 9V |

---

# 📷 Project Photos

## Circuit Diagram

![Circuit Diagram](Photos/Circuit_Diagram.png)

---

## Final Circuit

![Final Circuit](Photos/Final_Circuit.jpg)

---

## Dot Board Implementation

![Dot Board](Photos/Dot_Board.jpg)

---

# 📈 Experimental Results

| Test | Observation |
|------|-------------|
| HPF @ 1 kHz | Signal attenuated |
| HPF @ 10 kHz | Signal passed successfully |
| Amplifier | Voltage gain ≈ 70 |
| LPF @ 20 kHz | High-frequency noise attenuated |
| LPF @ 10 kHz | Signal passed successfully |
| Overall Circuit | Clean amplified output |

---

# 📊 Oscilloscope Outputs

### High-Pass Filter

![HPF](Photos/HPF_Output.jpg)

---

### Amplifier Output

![Amplifier](Photos/Amplifier_Output.jpg)

---

### Low-Pass Filter

![LPF](Photos/LPF_Output.jpg)

---

### Final Output

![Final Output](Photos/Final_Output.jpg)

---

# 💡 Applications

- Analog Signal Conditioning
- AM Radio Receiver Circuits
- Audio Signal Processing
- Sensor Signal Conditioning
- Communication Systems
- Electronics Education

---

# 🚀 Future Improvements

- Replace passive filters with active filters
- Design a PCB for improved reliability
- Use operational amplifiers for higher performance
- Add adjustable gain control
- Improve noise immunity

---

# 🛠️ Tools and Equipment

- Dot Board
- Digital Multimeter
- Oscilloscope
- Function Generator
- DC Power Supply
- Electronic Components
- Soldering Kit

---

# 📁 Repository Structure

```
Analog-Signal-Conditioning-Circuit
│
├── README.md
├── Report
│   └── Final_Report.pdf
│
├── Photos
│   ├── Circuit_Diagram.png
│   ├── Final_Circuit.jpg
│   ├── Dot_Board.jpg
│   ├── HPF_Output.jpg
│   ├── Amplifier_Output.jpg
│   ├── LPF_Output.jpg
│   └── Final_Output.jpg
│
└── Documentation
```

---

# 👨‍💻 Author

**Amsawardan**

BSc. (Hons) in Computer System Engineering

---

# 📚 References

- Sedra & Smith – *Microelectronic Circuits (7th Edition)*
- Boylestad & Nashelsky – *Electronic Devices and Circuit Theory (11th Edition)*

---

## ⭐ If you found this project interesting, feel free to star the repository!
