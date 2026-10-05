# Aero-Foil
"An interactive Python aerodynamic flow simulation using NACA airfoils and Matplotlib, featuring real-time controls for angle of attack, speed, and geometry.


An interactive Python application that simulates fluid air flow around a NACA 4-digit airfoil, calculating aerodynamic forces (Lift and Drag) in real-time using the International System of Units (SI).

This project uses `matplotlib` for dynamic particle visualization and interactive widgets to modify flight parameters.

---

## 🚀 Key Features

* **Real-time fluid visualization:** Smooth particle animation avoiding the airfoil and dynamically adapting to the angle of attack (AoA).
* **Full GUI control (Sliders & Textboxes):**
  * Speed (km/h)
  * Altitude (m)
  * Angle of Attack (degrees)
  * NACA Camber and Thickness (%)
  * Wing Area ($m^2$)
* **Aerodynamic physics calculation:** Estimates air density based on altitude, lift/drag coefficients, and resulting forces in Newtons.
* **Comparative charts:** Dynamic display of output values and a side-by-side force comparison bar chart.

---

## 📦 System Requirements

To run this project, you need Python 3.x installed along with the following libraries:

```bash
pip install numpy matplotlib
