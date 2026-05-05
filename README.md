# Virtual-_lab_simple-pendulum
Virtualization of simple pendulum experiment for determining acceleration due to gravity, amplitude effect and dumping effect through visualization 

# Virtual Physics Lab - Simple Pendulum

## Meru University of Science and Technology

### Experiment A-2: Simple Pendulum

---

## 📋 Overview

This is an interactive web-based virtual physics laboratory for conducting the **Simple Pendulum** experiment. The application allows students to:

- Select different experimental parameters (pendulum length, initial angle)
- Watch real experiment videos corresponding to each parameter combination
- Record measurements in structured data tables
- Analyze damping effects with interactive graphs
- Answer laboratory questions directly in the interface

---

## 👨‍🔬 Author

**Okwara Brian**  
BSc Mathematics & Physics Student  
SC201/108185/21  
Meru University of Science and Technology

**Contact:**  
Email: brianokwara02@gmail.com  
Phone: 0704031227, 0114205073

---

## 🎯 Experiment Parts

### Part A: Determine g (Vary Length)
- Investigate the relationship between pendulum length and period
- Calculate acceleration due to gravity (g)
- Lengths: 50cm, 60cm, 70cm, 80cm, 90cm, 100cm
- Fixed small angle: 10°

### Part B: Effect of Amplitude
- Study how initial angle affects period
- Fixed length: 70cm
- Angles: 10° to 70° (in 5° increments)

### Part C: Damping Effect
- Observe amplitude decay over time
- Fixed length: 70cm
- Initial angle: 20°
- Includes interactive damping graph

---

## 🛠️ Technical Features

### Core Functionality

| Feature | Description |
|---------|-------------|
| **Video Database** | 25+ unique experiment videos for different parameter combinations |
| **Dynamic UI** | Real-time updates of experiment parameters and video content |
| **Data Tables** | Three interactive tables for recording measurements |
| **Damping Graph** | Click-to-view amplitude decay graph with toggle functionality |
| **Apparatus Modal** | Pop-up view of experimental setup and components |
| **Manual Download** | PDF experiment manual available for download |

### Technologies Used

- HTML5
- CSS3 (with responsive design)
- Vanilla JavaScript
- YouTube Embedded Player API
- Font Awesome Icons
- Google Fonts (Inter)

---

## 📊 Data Tables Structure

### Table 1: Length Variation
| Column | Description |
|--------|-------------|
| Length (m) | Pendulum length in meters |
| Time for 50 Oscillations (s) | Measured time for 50 complete swings |
| Average Time (s) | Mean of multiple measurements |
| Period T (s) | Time for one oscillation |
| T² (s²) | Period squared for graphing |

### Table 2: Angle Variation
| Column | Description |
|--------|-------------|
| Amplitude θ (°) | Initial release angle |
| Time for 50 Oscillations (s) | Measured time data |
| Average Time (s) | Mean time |
| Period T (s) | Time per oscillation |
| Correction Factor | Small angle approximation factor |

### Table 3: Damping Study
| Column | Description |
|--------|-------------|
| Cycle Number (n) | Oscillation count |
| Amplitude Aₙ (°) | Peak angle for each cycle |
| Time for 10 cycles (s) | Time measurement |
| Period T (s) | Oscillation period |
| Logarithmic Decrement (Λ) | Damping factor calculation |

---

## 🖥️ Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for YouTube videos)

### Local Installation

1. **Download the HTML file** - Save the complete HTML document as `index.html`

2. **Create folder structure:**
   ```
   project-folder/
   ├── index.html
   ├── images/
   │   └── LOGO.jpeg
   ├── images2/
   │   └── image2.png
   └── simple/
       └── Simple Pendulum.pdf
   ```

3. **Required assets (optional - fallbacks included):**
   - `images/LOGO.jpeg` - University logo
   - `images2/image2.png` - Apparatus diagram
   - `simple/Simple Pendulum.pdf` - Experiment manual

4. **Open in browser:**
   - Double-click `index.html` or serve via local web server

### Asset Fallbacks
The application includes SVG fallbacks for missing images, so it will work even without the external assets.

---

## 🎮 Usage Guide

### Step 1: Select Experiment Part
Click one of three part buttons at the top of the control panel:
- **Part A** - Length variation study
- **Part B** - Amplitude effect study  
- **Part C** - Damping study

### Step 2: Choose Parameters
- **Part A**: Click a length button (50-100cm)
- **Part B**: Click an angle button (10°-70°)
- **Part C**: Only one option (20° damping)

### Step 3: Watch the Video
- The YouTube video automatically updates
- Use video controls (play, pause, rewind)
- Time 50 oscillations from equilibrium position

### Step 4: Record Data
- Enter measurements in the appropriate data table
- Calculate derived values (period, T², etc.)
- Table tabs switch between three datasets

### Step 5: View Damping Graph (Part C)
- **Tap/Click the graph area** to view the damping graph
- Tap again to hide the graph
- Graph shows exponential amplitude decay

### Step 6: Answer Questions
- Use the text areas in the Questions section
- Save answers locally (browser storage not included)

---

## 🎥 Video Database Reference

### Part A Videos (Length variation, 10° angle)

| Length | Video ID | YouTube Link |
|--------|----------|--------------|
| 50cm | vlLzSGoXGyQ | [Watch](https://youtu.be/vlLzSGoXGyQ) |
| 60cm | EwQ_2Ia8etw | [Watch](https://youtu.be/EwQ_2Ia8etw) |
| 70cm | efrQD6q_LCc | [Watch](https://youtu.be/efrQD6q_LCc) |
| 80cm | GoFWvdnng_k | [Watch](https://youtu.be/GoFWvdnng_k) |
| 90cm | FVDJBEGUEd4 | [Watch](https://youtu.be/FVDJBEGUEd4) |
| 100cm | aW4_WLp_v9k | [Watch](https://youtu.be/aW4_WLp_v9k) |

### Part B Videos (70cm length, varying angles)

| Angle | Video ID | YouTube Link |
|-------|----------|--------------|
| 10° | TWhDMidol3A | [Watch](https://youtu.be/TWhDMidol3A) |
| 15° | CInYg3w5_NQ | [Watch](https://youtu.be/CInYg3w5_NQ) |
| 20° | kCtb3wGq-as | [Watch](https://youtu.be/kCtb3wGq-as) |
| 25° | -7z8Y4HvKqg | [Watch](https://youtu.be/-7z8Y4HvKqg) |
| 30° | 7kZmyIC20Lk | [Watch](https://youtu.be/7kZmyIC20Lk) |
| 35° | durGw4Or6_Q | [Watch](https://youtu.be/durGw4Or6_Q) |
| 40° | vXCrFw_I0Tg | [Watch](https://youtu.be/vXCrFw_I0Tg) |
| 45° | ZpGiPf6I9vo | [Watch](https://youtu.be/ZpGiPf6I9vo) |
| 50° | VvDNEWDWY_0 | [Watch](https://youtu.be/VvDNEWDWY_0) |
| 55° | FuZVD7DQYHE | [Watch](https://youtu.be/FuZVD7DQYHE) |
| 60° | FUwHDwN2uN0 | [Watch](https://youtu.be/FUwHDwN2uN0) |
| 65° | _CVLhHzhImU | [Watch](https://youtu.be/_CVLhHzhImU) |
| 70° | 4x3Y3eJEg40 | [Watch](https://youtu.be/4x3Y3eJEg40) |

### Part C Video (Damping)

| Parameter | Video ID | YouTube Link |
|-----------|----------|--------------|
| 70cm, 20° | uGeP_wdvHL8 | [Watch](https://youtu.be/uGeP_wdvHL8) |

---

## 📐 Theoretical Background

### Simple Pendulum Formula

```
T = 2π √(L/g)
```

Where:
- **T** = Period (seconds)
- **L** = Length (meters)
- **g** = Acceleration due to gravity (9.81 m/s²)

### For calculating g:

```
g = 4π²L / T²
```

### Small Angle Approximation

For angles < 10°, sin θ ≈ θ (in radians), making period independent of amplitude.

### Damping Equation

```
θ(t) = θ₀ e^{-βt} cos(ωt + φ)
```

Where β is the damping coefficient.

---

## 📱 Responsive Design

The application is fully responsive and works on:

| Device | Screen Size | Features |
|--------|-------------|----------|
| Desktop | >1024px | Full layout, side-by-side panels |
| Tablet | 768px-1024px | Adjusted spacing, readable text |
| Mobile | <768px | Stacked layout, touch-friendly buttons |
| Small Mobile | <480px | Optimized padding, smaller fonts |

### Touch Optimizations
- Buttons have touch feedback (scale effect)
- Sufficient tap target sizes (min 44px)
- Clickable graph area for damping visualization

---

## 🔧 Browser Compatibility

| Browser | Minimum Version |
|---------|-----------------|
| Chrome | 60+ |
| Firefox | 55+ |
| Safari | 12+ |
| Edge | 79+ |
| Opera | 47+ |
| Mobile Safari | iOS 12+ |
| Chrome for Android | 60+ |

---

## 📝 Laboratory Questions Included

1. What is the purpose of timing 50 oscillations instead of just one?
2. Why must the amplitude be kept small (<10°)?
3. Compare your experimental g value with the theoretical value (9.81 ms⁻²)
4. Why doesn't the T² vs l graph pass through the origin?
5. What are the assumptions made in the ideal simple pendulum?
6. Error calculation: For pendulum length (0.600 ± 0.002)m and period T = (1.55 ± 0.01)s, calculate the percentage error in g.

---

## 🎨 Color Scheme

| Color | Usage | Hex Code |
|-------|-------|----------|
| Primary Green | Headers, buttons, accents | #006633 |
| Secondary Yellow | Highlights, badges | #FFCC00 |
| Dark Green | Hover states, gradients | #004d26 |
| Light Green | Backgrounds, cards | #F8FCFA |
| Gray | Text, borders | #5D6D7E |

---

## 📁 File Structure

```
virtual-physics-lab/
│
├── index.html                 # Main application file
│
├── images/
│   └── LOGO.jpeg             # University logo (optional)
│
├── images2/
│   └── image2.png            # Apparatus diagram (optional)
│
├── simple/
│   └── Simple Pendulum.pdf   # Experiment manual (optional)
│
└── README.md                 # This file
```

---

## ⚠️ Important Notes

1. **Internet Connection Required** - YouTube videos are streamed, not local
2. **Data Persistence** - Table inputs are temporary; no automatic saving
3. **Image Fallbacks** - SVG placeholders appear if images are missing
4. **Manual Download** - PDF manual must be placed in `simple/` folder
5. **YouTube Terms** - Videos are embedded in compliance with YouTube Terms of Service

---

## 🚀 Future Enhancements

Possible improvements for future versions:

- [ ] Local storage for saving experiment data
- [ ] Export data to CSV/Excel
- [ ] Live graph plotting from user data
- [ ] Built-in calculation tools
- [ ] Virtual ruler and protractor interactions
- [ ] Multi-language support
- [ ] Progress tracking across sessions
- [ ] Audio descriptions for accessibility

---

## 📄 License

This project is created for educational purposes at Meru University of Science and Technology.

---

## 🙏 Acknowledgments

- Meru University Department of Physical Sciences
- YouTube content creators for experiment videos
- Font Awesome for icons
- Google Fonts for Inter typeface

---

## 📞 Support

For technical issues or questions:

**Okwara Brian**  
Email: brianokwara02@gmail.com  
Phone: 0704031227, 0114205073

---

*Last Updated: 2026*  
*Version: 1.0*
