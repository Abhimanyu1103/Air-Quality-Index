<h1 align="center">🌍 Hybrid AQI Detector (Hardware + Software)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-Frontend-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/shadcn-ui-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/IoT-Hardware-green?style=for-the-badge&logo=raspberrypi" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="300px" alt="Air Quality Animation" />
</p>

<p align="center">  
A hybrid project combining <b>IoT hardware sensors</b> with a <b>Next.js frontend dashboard</b> to monitor and visualize <b>Air Quality Index (AQI)</b> in real-time.  
</p>

---

## ✨ Features
✅ Real-time AQI monitoring using IoT sensors  
✅ Interactive dashboard for live AQI visualization  
✅ Sleek UI powered by [shadcn/ui](https://ui.shadcn.com/)  
✅ Hardware + Software integration for seamless data flow  
✅ Responsive design for desktop & mobile  

---

## 🛠 Tech Stack
- *Frontend:* [Next.js](https://nextjs.org/), [shadcn/ui](https://ui.shadcn.com/)  
- *Backend/Data Flow:* API bridge (Node.js or Flask optional)  
- *Hardware:* AQI Sensors (MQ135, DHT11/DHT22, or equivalent)  
- *Communication:* Serial / MQTT  

---

## 📂 Project Structure
```bash
hybrid-aqi-detector/
├── frontend/         # Next.js + shadcn UI dashboard
├── hardware/         # Arduino/Raspberry Pi code for AQI sensors
├── api/              # Optional backend bridge (Node/Flask)
└── README.md
