# Web Heart Rate Monitor

A modern, responsive, open-source Web Bluetooth application for real-time heart rate monitoring, average HR tracking, and RR interval analysis directly in your browser.

## Live use

Use the app directly in your browser without installing anything:  
**[https://hpirila.github.io/web-heart-rate/](https://hpirila.github.io/web-heart-rate/)**

---

## Features

- **Live Heart Rate Display:** Clean, high-visibility large numbers with theme-aware color cycling (click numbers to change color).
- **Average Heart Rate & Workout Timer:** Track session average HR with interactive Start, Stop, and Reset controls.
- **Interactive Dual-Mode View:**
  - **Live Canvas Graph:** Real-time plotting of HR, Average HR, and RR intervals.
  - **Data Table:** Logged metrics table with automatic scroll lock.
  - **Toggle View:** Click anywhere in the bottom graph/table container to switch between Graph and CSV Data Table view.
- **RR Interval Support:** Plots RR intervals on a secondary (right) Y-axis in green. Works automatically with Bluetooth sensors supporting RR interval data.
- **Graph Customization:**
  - Toggle individual lines (**HR**, **Avg HR**, **RR**) via legend checkboxes.
  - Switch X-axis time representation between **Elapsed Seconds** and **Clock Time** by clicking the time indicator in the legend.
- **CSV Data Export:** Tied to the session timer. Download complete session records with timestamps, HR, Avg HR, flags, contact status, and raw hex payload.
- **Web Bluetooth Standard:** Connects seamlessly to standard Bluetooth LE Heart Rate sensors (Polar, Garmin, Wahoo, Apple Watch HR sharing, etc.).
- **Theme Support:** Fully responsive dark/light theme support based on system preferences.

