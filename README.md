# 🎈 Air Canvas

A browser-based gesture drawing experience where you draw shapes in the air using hand gestures via your webcam. Completed drawings inflate into soft, 3D balloon-like objects that float in a shared 3D scene.

---

## 🚀 Features

- **Gesture-Based Drawing** – Point your index finger to draw in the air  
- **3D Balloon Inflation** – Completed shapes transform into puffy, floating 3D objects  
- **Real-Time Hand Tracking** – Powered by MediaPipe for responsive detection  
- **Color Palette** – Choose from 10 pastel colors  
- **Interactive Objects** – Poke, grab, rotate, and squish balloons  
- **Draggable Camera Preview** – Move and reposition the tracking preview  
- **Expandable Preview** – Toggle a larger camera view  
- **Mouse & Touch Controls** – Orbit and zoom the 3D environment  

---

## 🆕 Recent Updates

- Draggable camera preview (double-click to reset position)  
- Improved line smoothing with jitter filtering  
- Switched to higher-accuracy hand detection model  
- Dedicated **Clear All** button  
- Expandable camera preview  

---

## ✋ Gesture Controls

| Gesture | Action |
|----------|--------|
| Point (index finger) | Draw in the air |
| Open Palm (hold 0.5s) | Close shape and inflate to 3D |
| Pinch | Grab and move objects |
| Swipe | Remove individual object |

---

## 🎛 UI Controls

| Control | Action |
|----------|--------|
| Clear All button | Remove all objects |
| Color swatches | Change drawing color |
| Camera preview | Drag to move |
| Double-click preview | Reset position |
| Expand button | Toggle larger preview |

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/air-canvas.git

# Navigate into the project folder
cd air-canvas

# Install dependencies
npm install

# Start development server
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

---

## 🧩 Requirements

- Modern browser with WebGL support (Chrome, Firefox, Edge, Safari)  
- Webcam access  
- Good lighting for accurate hand tracking  
- HTTPS connection when deployed online  

---

## 🛠 Tech Stack

- **TypeScript** – Type-safe JavaScript  
- **Vite** – Fast build tool and dev server  
- **Three.js** – 3D rendering and scene management  
- **MediaPipe Hands** – Real-time hand tracking  
- **GSAP** – Smooth animations  
- **PeerJS** – Multiplayer support  

---

## 🖱 Mouse & Touch Controls

- Click + Drag (empty space) → Orbit camera  
- Click + Drag (object) → Rotate object  
- Scroll wheel → Zoom in/out  
- Touch gestures supported on mobile  

---

## 📂 Project Structure

```
src/
├── main.ts
├── handTracking.ts
├── gestureDetector.ts
├── drawingCanvas.ts
├── scene3D.ts
├── objectManager.ts
├── balloonInflator.ts
├── handVisualizer.ts
├── multiplayer.ts
├── constants.ts
└── types.ts
```

---

## 💡 Tips for Best Results

- Use strong lighting so your hand is clearly visible  
- Keep your hand 1–2 feet from the camera  
- Extend only your index finger while drawing  
- Draw slowly and steadily for smoother lines  

---

## 🤝 Contributions

Found a bug or have an idea?

- Open an issue  
- Fork the project  
- Submit a pull request  

---

## 👨‍💻 Credits

Designed & Developed by Jay Thakur  
Contact me if you face any problem
---

## 📜 License

MIT
