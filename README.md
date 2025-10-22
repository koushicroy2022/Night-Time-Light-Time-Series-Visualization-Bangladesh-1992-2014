# 🌃 Night-Time Light Time-Series Visualization (Bangladesh, 1992–2014)

This project visualizes temporal changes in night-time illumination across Bangladesh using DMSP-OLS data in Google Earth Engine.

The animation highlights the gradual increase in urban brightness, reflecting economic and infrastructural development over time.

---

## 🛰️ Data & Methods
- **Dataset:** NOAA/DMSP-OLS/NIGHTTIME_LIGHTS
- **Region:** Bangladesh (from FAO/GAUL)
- **Years:** 1992–2014
- **Overlay:** Vector boundary and year label (using `users/gena/packages:text`)
- **Visualization:** Animated GIF with hillshade background

---

## ⚙️ Tools Used
- Google Earth Engine (JavaScript API)
- Gena’s `text` package for annotations
- Git & GitHub for version control

---

## 📸 Outputs
| Year | Visualization |
|------|----------------|
| 1992 | ![1992](results/ntl_bangladesh_1992.png) |
| 2014 | ![2014](results/ntl_bangladesh_2014.png) |

Animated GIF:
![GIF](results/ntl_animation.gif)

---

## 🔗 View Code
[View the full GEE script on GitHub](nighttime_light_bangladesh.js)

---

## 💡 Insights
- Noticeable illumination growth around **Dhaka** and **Gazipur** after 2000.
- Rural areas remain relatively dim throughout 1992–2014.
- Night-time light intensity can serve as a proxy for urban expansion and economic activity.
