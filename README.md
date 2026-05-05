# Virtual-_lab_simple-pendulum
Virtualization of simple pendulum experiment for determining acceleration due to gravity, amplitude effect and dumping effect through visualization 

This code is for a **Virtual Physics Lab** web application, specifically designed for a **Simple Pendulum Experiment** at Meru University of Science and Technology.

It is built using **HTML5** and **CSS3** and is designed to be fully responsive (working on mobile, tablets, and desktops).

---

## ### **Core Components of the Code**

### **1. Branding and Identity**
*   **University Theme:** The application uses a custom color palette defined in CSS variables:
    *   `--mu-primary`: A deep green (#006633).
    *   `--mu-secondary`: A bright yellow/gold (#FFCC00).
*   **Creator Credit:** There is a specific section highlighted in yellow to credit the developer/creator.
*   **Logo Container:** A styled box designed to hold the university logo with a professional border and shadow.

### **2. Laboratory Dashboard**
The interface is split into two main functional areas:

*   **The Control Panel (Left Side):**
    *   **Experiment Parts:** Allows users to switch between different sections of the experiment (e.g., Part A, B, or C).
    *   **Parameter Selector:** Interactive buttons for users to choose variables like the **length of the string** or **mass of the bob**.
    *   **Setup Card:** A real-time readout displaying the currently selected experiment parameters.

*   **The Video/Simulation Panel (Right Side):**
    *   **Video Player:** An embedded area (using a 16:9 aspect ratio) intended to show the pendulum simulation or recorded experiment footage.
    *   **Status Indicator:** Shows which experiment is currently active within the viewer.

### **3. Data Collection System**
*   **Interactive Data Table:** A robust table where students can manually input their observations.
*   **Tabbed Navigation:** Users can switch between different data sheets for different parts of the lab.
*   **Mobile Optimized:** The table is wrapped in a scrollable container to prevent it from breaking the layout on small screens.

---

## ### **Technical Highlights**

| Feature | Implementation |
| :--- | :--- |
| **Responsive Design** | Uses **CSS Grid** and **Flexbox** with extensive `@media` queries for mobile compatibility. |
| **Typography** | Integrates the **Inter** font family via Google Fonts for a modern, clean look. |
| **Iconography** | Uses **FontAwesome 6.4.0** for intuitive visual cues (e.g., download icons, gear icons). |
| **UI Polish** | Features glassmorphism effects (`backdrop-filter`), linear gradients, and smooth transitions for a "premium" feel. |

---

## ### **Missing Elements**
Based on the code provided, this is the **Frontend (UI) only**. To make the lab functional, you would need:
1.  **JavaScript:** To handle the button clicks, update the "Current Setup" text, and change the video source based on selection.
2.  **Video Assets:** The `<iframe>` or `<video>` tags would need specific URLs to play the pendulum simulations.
3.  **PDF/Manual:** The "Download Manual" button is styled but requires a link to an actual file to work.
