# HANDCONNECT — ULTRA ENGINE V3

**HandConnect** is a cutting-edge, browser-based Augmented Reality (AR) experience powered by MediaPipe. It translates hand gestures into digital interactions in real-time, allowing users to paint in the air, trigger visual effects, and interact with a futuristic HUD using only their webcam.

![Screenshot of HandConnect](https://raw.githubusercontent.com/username/HandConnect/main/screenshot.png) *(Placeholder for your screenshot)*

## 🚀 Key Features

- **Real-time Hand Tracking**: Powered by MediaPipe Hands for high-precision, low-latency detection.
- **Air Paint**: Pinch your fingers to draw in 3D space directly over your camera feed.
- **Gesture Recognition**:
  - **Pinch**: Start drawing/interacting.
  - **Fist**: Trigger a gravity burst effect.
  - **Spread**: Release a wave pulse.
  - **Point**: Interaction mode.
- **Visual Stylization**: Multiple themes including Cyberpunk, Electric, Toxic, Deep Space, and Solar Flare.
- **Motion Blur & Depth Scaling**: Advanced visual options for a premium feel.
- **Interactive HUD**: Real-time feedback on detection, FPS, and detected gestures.

## 🛠️ Technology Stack

- **Core**: HTML5, Vanilla JavaScript.
- **Vision Engine**: [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands).
- **Styling**: Vanilla CSS3 with custom glassmorphism effects.
- **Audio**: Web Audio API for immersive spatial hums and interaction sound effects.

## 🚦 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/HandConnect.git
   ```
2. **Open `index.html`**:
   Simply open the `index.html` file in any modern web browser (Chrome or Edge recommended).
   *Note: For camera access, you must run this via a local server (e.g., Live Server in VS Code) or on `localhost`.*

## 📜 Usage Instructions

- Click **Initialize Core** to start the engine.
- Grant camera permissions when prompted.
- Use the **Controls** panel (bottom right) to clear the canvas or toggle effects.
- Use the **Theme Swatches** to change the visual aesthetic.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
