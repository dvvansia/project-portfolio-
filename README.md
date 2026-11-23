# Satellite Engineering Portfolio Website

**Personal portfolio showcasing satellite engineering projects for career in spacecraft avionics and power systems.**

🌐 **Live Site:** https://dvvansia.github.io/project-portfolio

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/dvvansia/project-portfolio.git
cd project-portfolio
```

### 2. Deploy to GitHub Pages
```bash
# Enable GitHub Pages in repository settings
# Settings > Pages > Source: main branch > Save

# Or deploy manually
git push origin main
```

### 3. Access Website
Navigate to: `https://dvvansia.github.io/project-portfolio`

---

## 📁 Project Structure

```
project-portfolio/
├── index.html              # Main portfolio page
├── assets/
│   ├── css/
│   │   └── style.css       # Stylesheet
│   └── js/
│       └── script.js       # (Optional) JavaScript
└── README.md               # This file
```

---

## 🛰️ Featured Projects

### 1. CubeSat OBC Power Distribution Unit
**Latest Project** — KiCAD 9.0, 4-layer PCB, INA199 current sensing

Flight-grade power distribution for 1U CubeSat with 4 regulated rails, comprehensive protection, and telemetry feedback.

- 8-sheet hierarchical schematic (ERC: 0 errors)
- LM5050-1 ideal diode ORing + TVS protection
- REF5033 precision reference for analog rail
- 16-pin OBC backplane with fail-safe control

🔗 [View Repository](https://github.com/dvvansia/CubeSat_OBC_Power_Distribution)

### 2. Satellite Sensor Node Schematic
KiCAD 9.0, ATmega328P, BMP280 + XBee

Complete schematic for satellite-compatible sensor node with environmental sensors and wireless telemetry.

- KiCAD hierarchical schematic (ERC verified)
- AMS1117-3.3 LDO (500mA)
- 11 test points for debugging
- Arduino firmware example

🔗 [View Repository](https://github.com/dvvansia/Satelliet_Sensor_Node)

### 3. RF Link Budget Calculator
MATLAB, BPSK/QPSK, Eb/N0 Analysis

MATLAB-based satellite RF link budget calculator with Friis equation, BER curves, and link margin verification.

- Load transient, inrush, short-circuit simulations
- 3 test scenarios: LEO, GEO, CubeSat UHF
- Link margin pass/fail verdict

🔗 [View Repository](https://github.com/dvvansia/RF_Link_Budget_Calculator)

### 4. ADC Sensor Interface (Proteus)
Proteus 8, ATmega328P, Multi-Channel Telemetry

Multi-channel ADC sensor interface simulation mirroring ISRO PRL sensor node experience.

- 4-channel ADC with LM35 sensors
- UART telemetry output
- Calibration routines

🔗 [View Repository](https://github.com/dvvansia/adc_sensor_interface_proteus)

### 5. Buck Converter LTSpice
LTSpice, 93% Efficiency, 12V→3.3V

High-efficiency buck converter simulation with optimized switching and filtering.

- 93% efficiency at 500mA load
- <50mV ripple peak-to-peak
- Transient response verification

🔗 [View Repository](https://github.com/dvvansia/buck_convertor_LTSpice)

---

## 🛠️ Technical Skills Showcased

| Category | Skills |
|----------|--------|
| **EDA Tools** | KiCAD 9.0, LTSpice, Proteus 8, MATLAB |
| **Embedded** | ATmega328P, Arduino, C/C++, FreeRTOS |
| **Power Electronics** | Buck/Boost, LDO, Current Sensing, Thermal Design |
| **Communication** | I2C/SPI/UART, Zigbee/XBee, RF Link Budget |

---

## 🎨 Customization

### Update Personal Information
Edit `index.html`:
- Line 12: Name
- Line 13: University/degree
- Line 14: Tagline/specialization
- Lines 16-17: CTA buttons

### Add New Project
Copy existing project card structure in `index.html` (lines 60-100):
```html
<article class="project-card">
    <h3>Project Name</h3>
    <p class="project-meta">Tools • Technologies</p>
    <p class="project-description">Brief description...</p>
    <ul class="project-features">
        <li>Feature 1</li>
        <li>Feature 2</li>
    </ul>
    <div class="project-links">
        <a href="https://github.com/..." class="btn btn-small">View</a>
    </div>
</article>
```

### Customize Colors
Edit `assets/css/style.css` (lines 9-16):
```css
:root {
    --primary: #2563eb;      /* Main accent color */
    --primary-dark: #1d4ed8; /* Hover state */
    --secondary: #64748b;    /* Text color */
    --dark: #0f172a;         /* Dark background */
    --light: #f8fafc;        /* Light background */
    --accent: #0ea5e9;       /* Highlight color */
}
```

---

## 📄 License

MIT License — Free for personal and educational use.

---

## 👨‍💻 Author

**Dhruvrajsinh Vansia**  
MSc Space Sciences and Technologies, University of Bremen  
GitHub: https://github.com/dvvansia  
Location: Bremen, Germany

---

*Built for satellite engineering career opportunities in Europe.*
