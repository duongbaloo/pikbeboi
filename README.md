# PikBeBoi 🏓

A mobile-first pickleball technique analyzer. Open `index.html` in Chrome or Edge — no install required.

## Features
- **Live camera** or **video upload** (landscape & portrait)
- **AI pose tracking** via TensorFlow.js MoveNet (runs fully in-browser)
- **Multi-person detection** — tap any player on screen to track them
- **Portrait video support** — vertical phone recordings display correctly
- **Rewatch mode** — replay sessions with shot markers on a scrubber timeline
- Detects 9 shot types: Dink, Volley, Smash, Reset, Drop, Drive, Lob, Block, Flick
- **Star rating (1–5★)** per shot based on technique quality
- **Real-time feedback** on form + targeted drills after each shot
- **Session report** with shot distribution, tips, and recommended drills

## Usage
1. Open `index.html` in Chrome / Edge / Safari
2. Select dominant hand
3. Tap **📷 Camera** or **📁 Upload Video**
4. If multiple people are in frame, tap the player you want to track
5. Play — shots are detected and rated automatically
6. Tap **📊 Report** for session summary
7. Tap **▶ Rewatch** to replay the session with shot markers

## Tips
- Stand **6–8 ft** from camera, side-on for best skeleton tracking
- Good lighting improves detection accuracy
- Portrait (vertical) phone videos are supported and displayed correctly
- First load downloads the AI model (~8s on mobile)
- Camera sessions are recorded for rewatch automatically
