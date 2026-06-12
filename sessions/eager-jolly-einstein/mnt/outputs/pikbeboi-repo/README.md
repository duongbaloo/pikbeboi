# PikBeBoi 🏓

A browser-based pickleball technique analyzer. Open `index.html` in Chrome or Edge — no install required.

## Features
- **Live camera** or **video upload** analysis
- **AI pose tracking** via TensorFlow.js MoveNet (runs fully in-browser)
- Detects 9 shot types: Dink, Volley, Smash, Reset, Drop, Drive, Lob, Block, Flick
- **Star rating** (1–5★) per shot based on technique quality
- **Real-time feedback** on form after each shot
- **Targeted drills** to improve weak areas
- **Session report** with shot distribution and technique tips

## Usage
1. Open `index.html` in a modern browser
2. Select your dominant hand
3. Click **📷 Live Camera** or **📁 Upload Video**
4. Hit shots — PikBeBoi detects and rates them automatically
5. Click **📊 Report** for a session summary

## Tips
- Stand **6–8 ft** from the camera, side-on for best skeleton tracking
- Good lighting improves detection accuracy
- First load downloads the AI model (~5s)
