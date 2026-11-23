# Satellite Engineering Portfolio Website

**Professional portfolio showcasing satellite engineering projects for spacecraft avionics and power systems careers.**

🌐 **Live Site:** https://dvvansia.github.io/project-portfolio-/

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/dvvansia/project-portfolio-.git
cd project-portfolio-
```

### 2. Deploy to GitHub Pages
```bash
# Enable GitHub Pages in repository settings
# Settings > Pages > Source: main branch > Save

# Push changes
git push origin main
```

### 3. Access Website
Navigate to: `https://dvvansia.github.io/project-portfolio-/`

---

## 📁 Project Structure

```
project-portfolio-/
├── index.html              # Main portfolio page (single-file, inline CSS)
└── README.md               # This file
```

**Note:** Version 2.0 uses inline CSS for simplified deployment (no external dependencies).

---

## 🛰️ Featured Projects (8 Total)

### Flagship Projects

#### 1. CubeSat OBC Power Distribution Unit ⭐
**Latest & Featured** — KiCAD 9.0 • 4-Layer PCB • INA199 Current Sensing

Flight-grade power distribution system for 1U CubeSat OBC with 4 regulated rails, comprehensive protection (reverse polarity, overcurrent, thermal), and telemetry feedback via INA199 high-side current sense amplifiers.

**Key Features:**
- 8-sheet hierarchical KiCAD schematic (ERC passed: 0 errors)
- LM5050-1 ideal diode ORing + TVS protection
- REF5033 precision reference for analog rail (3.3 µVrms noise)
- 16-pin OBC backplane connector with fail-safe boot pull-downs
- Full telemetry: 4× current monitors + battery voltage divider

🔗 [View Repository](https://github.com/dvvansia/CubeSat_OBC_Power_Distribution)

#### 2. Buck Converter LTSpice
**Power Electronics** — LTSpice • 93% Efficiency • 12V→3.3V

High-efficiency buck converter simulation converting 12V input to 3.3V output at 500mA load. Optimized for satellite power systems.

**Results:**
- 93% efficiency at full load (500mA)
- Output ripple: <50mV peak-to-peak
- Transient response verified
- Complete technical report with waveforms

🔗 [View Repository](https://github.com/dvvansia/buck_convertor_LTSpice)

#### 3. ADC Sensor Interface Proteus
**Embedded Systems** — Proteus 8 • ATmega328P • Multi-Channel Telemetry

Satellite telemetry acquisition system using ATmega328P ADC for multi-sensor data acquisition with CCSDS-style serial output.

**Specifications:**
- 10-bit ADC resolution (0-1023)
- LM35 temperature sensors (0-100°C)
- 2 ADC channels (A0, A1)
- 9600 bps serial telemetry
- 1 Hz sampling rate

🔗 [View Repository](https://github.com/dvvansia/adc_sensor_interface_proteus)

### Core Projects

#### 4. RF Link Budget Calculator
**Communication Systems** — MATLAB • BPSK/QPSK • Eb/N0 Analysis

MATLAB-based satellite RF link budget calculator for LEO, GEO, and CubeSat missions.

**Capabilities:**
- Friis transmission equation
- BER curves for BPSK/QPSK (erfc-based)
- Link margin verification with pass/fail verdict
- 3 test scenarios: LEO (400km), GEO (35,786km), CubeSat UHF

🔗 [View Repository](https://github.com/dvvansia/RF_Link_Budget_Calculator)

#### 5. Satellite Sensor Node Schematic
**Embedded Design** — KiCAD 9.0 • ATmega328P • BMP280 + XBee

Complete schematic for satellite-compatible sensor node with environmental sensing and wireless telemetry.

**Features:**
- KiCAD 9.0 hierarchical schematic (ERC verified)
- AMS1117-3.3 LDO (500mA capacity)
- 11 test points for critical nets
- BMP280 pressure/temperature sensor
- XBee wireless module

🔗 [View Repository](https://github.com/dvvansia/Satelliet_Sensor_Node)

#### 6. PRL WSN Project (ISRO)
**Space Experience** — ATmega128 • Zigbee • Wireless Sensor Networks

Wireless sensor node developed at Physical Research Laboratory, ISRO for space applications.

**Technologies:**
- ATmega128 microcontroller
- Multiple environmental sensors
- I2C and UART communication
- Zigbee wireless protocol
- GUI visualization

🔗 [View Repository](https://github.com/dvvansia/prl-wsn-project)

### Additional Projects

#### 7. NBC Bearings AI Project
**Machine Learning** — Python • OpenCV • CNN

Computer vision system for industrial bearing defect detection using convolutional neural networks.

🔗 [View Repository](https://github.com/dvvansia/nbc-bearings-project)

#### 8. Pothole Detection YOLO
**Computer Vision** — YOLOv4 • Darknet • C

Object detection system for automated pothole identification using YOLOv4 framework.

🔗 [View Repository](https://github.com/dvvansia/Pothole-Detection-usinh-YOLO)

---

## 🛠️ Technical Skills Showcased

| Category | Skills |
|----------|--------|
| **EDA Tools** | KiCAD 9.0, LTSpice, Proteus 8 Professional, MATLAB/Simulink |
| **Embedded Systems** | ATmega328P/128, Arduino, C/C++, FreeRTOS |
| **Power Electronics** | Buck/Boost Converters, LDO Regulators, Current Sensing (INA199), Thermal Management |
| **Communication** | I2C/SPI/UART, Zigbee/XBee, RF Link Budget Analysis, ADC Interfacing |
| **AI & ML** | Python, OpenCV, CNNs, YOLOv8, Data Analysis |
| **Automation** | PLC/SCADA, Sensor Integration, Circuit Design, Signal Processing |

---

## 🎨 Design Features (v2.0)

### Visual Design
- ✅ **Modern dark theme** optimized for space industry
- ✅ **Professional gradient backgrounds** with subtle effects
- ✅ **Responsive layout** (mobile, tablet, desktop)
- ✅ **Smooth animations** and hover effects
- ✅ **Fixed navigation** with blur backdrop

### Technical Improvements
- ✅ **Single-file deployment** (33KB total)
- ✅ **No external dependencies** (inline CSS/JS)
- ✅ **SEO-optimized** meta tags
- ✅ **WCAG AA accessibility** compliant
- ✅ **Fast load time** (<1 second)

### Color Palette
```
Primary: #0066cc (Space Blue)
Secondary: #00a3e0 (Sky Blue)
Dark: #0a0e1a (Near Black)
Light: #f8fafc (Star White)
```

---

## 📊 Portfolio Statistics

| Metric | Value |
|--------|-------|
| Total Projects | 8 |
| Space-Focused | 6 |
| GitHub Repositories | 14 |
| Publications | 3 |
| Industry Experience | ISRO, IBM, NBC |
| Primary Focus | Satellite Avionics & Power Systems |

---

## 📝 Update Instructions

### Add New Project
Edit `index.html` - find the projects grid section and add:

```html
<div class="project-card">
    <div class="project-icon">🚀</div>
    <h3 class="project-title">Project Name</h3>
    <p class="project-description">Brief description...</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
    <div class="project-links">
        <a href="https://github.com/..." target="_blank" class="project-link">
            View Repository →
        </a>
    </div>
</div>
```

### Customize Colors
Edit CSS variables in `<style>` section (lines 17-28):

```css
:root {
    --primary: #0066cc;        /* Main accent */
    --primary-dark: #004c99;   /* Hover state */
    --secondary: #00a3e0;      /* Secondary accent */
    --dark: #0a0e1a;           /* Background */
    --light: #f8fafc;          /* Text */
}
```

### Update Contact Info
Search for contact section (near line 380) and update:
- Email address
- GitHub URL
- LinkedIn URL

---

## 📄 License

MIT License — Free for personal and educational use.

---

## 👨‍💻 Author

**Dhruvrajsinh Vansia**  
MSc Space Sciences and Technologies  
University of Bremen, Germany  

- 🐙 GitHub: https://github.com/dvvansia
- 💼 LinkedIn: https://www.linkedin.com/in/dhruvrajsinh-vansia1805/
- 📧 Email: dhruvrajvansia1805@gmail.com
- 📍 Location: Bremen, Germany

---

## 🎯 Career Focus

**Target Roles:**
- Satellite Avionics Engineer
- Embedded Systems Engineer (Space)
- Power Systems Engineer (CubeSat)
- Flight Software Developer
- Payload Electronics Engineer

**Target Companies:**
- OHB System AG (Bremen)
- Airbus Defence and Space
- DLR (German Aerospace Center)
- ESA (European Space Agency)
- Isar Aerospace (Munich)
- Rocket Factory Augsburg (RFA)
- SpaceX, Blue Origin (US)
- JAXA, ISRO (International)

---

## 📈 Version History

### v2.0 (November 23, 2026) - Current
- Complete redesign with modern dark theme
- Added 3 new projects (ADC Sensor, Buck Converter, PRL WSN)
- Enhanced visual hierarchy
- Single-file deployment (no external CSS)
- Improved mobile responsiveness
- Better recruiter experience

### v1.0 (Previous)
- Initial portfolio release
- Basic project showcase
- External CSS architecture

---

## 🔗 Quick Links

- [Live Portfolio](https://dvvansia.github.io/project-portfolio-/)
- [CubeSat OBC Power Distribution](https://github.com/dvvansia/CubeSat_OBC_Power_Distribution)
- [Buck Converter LTSpice](https://github.com/dvvansia/buck_convertor_LTSpice)
- [ADC Sensor Interface](https://github.com/dvvansia/adc_sensor_interface_proteus)
- [RF Link Budget Calculator](https://github.com/dvvansia/RF_Link_Budget_Calculator)
- [Satellite Sensor Node](https://github.com/dvvansia/Satelliet_Sensor_Node)
- [PRL WSN (ISRO)](https://github.com/dvvansia/prl-wsn-project)

---

*Last Updated: November 23, 2026*  
*Built with HTML, CSS, and passion for space engineering.* 🚀
