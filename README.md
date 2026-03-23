# ⚡ SparkTrack

A progressive web app (PWA) for Walmart Spark Drivers to track trips, log earnings, and monitor gas costs — since the Spark app doesn't have a built-in export feature.

**Live app:** https://dywk8z96r2-hue.github.io/spark-track/

The link auto-detects your device and opens the correct version automatically.

---

## Features

- **Trip tracking** — log each phase of your trip (Accepted → At Store → Delivering → Complete) with a live timer
- **Earnings history** — view all past trips with total earned, avg per trip, and tip rate stats
- **Mileage & gas tracker** — log odometer readings per trip, calculates miles driven and estimated gas cost based on your MPG and current gas price
- **Data export** — export all trip data as a CSV (spreadsheet) or JSON file at any time
- **Export reminder** — a badge appears on the Settings tab after each trip reminding you to export

### What gets exported
Every trip includes: date, store, trip type, stops, time accepted, time at store, time delivering, time completed, transit/shop/delivery time splits, earnings breakdown, odometer readings, miles driven, gas price at time of trip, estimated gas used, estimated gas cost, and notes.

---

## Installation

### iPhone (requires Safari)

1. Open **Safari** on your iPhone — it must be Safari, not Chrome or Firefox
2. Go to: **https://dywk8z96r2-hue.github.io/spark-track/**
3. Tap the **Share button** (the box with an arrow pointing up) at the bottom of the screen
4. Scroll down and tap **Add to Home Screen**
5. Tap **Add** in the top right
6. SparkTrack will appear on your home screen and open fullscreen like a native app

### Android (requires Chrome)

1. Open **Google Chrome** on your Android phone — it must be Chrome
2. Go to: **https://dywk8z96r2-hue.github.io/spark-track/**
3. An **Install SparkTrack** banner will appear at the top of the screen — tap **Install**
4. Tap **Add** when Chrome asks to confirm
5. SparkTrack will appear on your home screen

If you dismissed the install banner, you can still install manually: tap the **three dot menu (⋮)** in Chrome → **Add to Home screen** → **Add**

---

## How your data is stored

All data is saved locally on your phone using your browser's built-in storage (localStorage). Nothing is sent to any server. Your trip history, settings, and mileage log stay on your device until you clear them or uninstall the app.
