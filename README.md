# 🌌 AI-Vision-ThreeJS: Interactive Hand-Tracked Particles

A cutting-edge, real-time 3D particle system that responds to your hand gestures. This project bridges the gap between **Computer Vision (AI)** and **Web Graphics (WebGL)** to create an immersive, touchless interactive experience.

---

## 🎮 Live Demo
[https://github.com/Shehbaz-Developer]
*(Example:https://github.com/Shehbaz-Developer/ai-vision-threejs/)*

---

## ✨ Key Features

* **Real-time AI Tracking:** Uses MediaPipe's hand landmark model to track 21 points on your hand at high frequency.
* **Dynamic Particle Physics:** 8,000+ particles rendered using `Three.js` that gravitate toward your index finger.
* **Gesture Recognition:** * **Motion:** Move your hand to stir and pull the particle cloud.
    * **Pinch Interaction:** Touching your thumb and index finger triggers a global color shift using HSL interpolation.
* **High Performance:** Optimized with `BufferGeometry` and `AdditiveBlending` to ensure smooth 60 FPS performance even on mid-range devices.

---

## 🛠️ Technology Stack

* **Three.js:** For high-performance 3D rendering and particle management.
* **MediaPipe Hands:** Google's ML framework for hand landmark detection.
* **JavaScript (ES6):** For core logic and gesture mapping.
* **HTML5/CSS3:** For the UI overlay and camera preview.

---

## 🧠 How It Works

The system follows a three-step pipeline to process your movements:

1.  **Input:** The webcam captures video frames.
2.  **AI Inference:** MediaPipe identifies the (X, Y, Z) coordinates of your hand landmarks.
3.  **Mapping:** The index finger's normalized coordinates are mapped to the Three.js 3D coordinate system to act as a "Magnetic Attractor."



---

## 🚀 Installation & Local Setup

1.  Clone this repository:
    ```bash
   git clone https://github.com/Shehbaz-Developer/ai-vision-threejs.git
    ```
2.  Navigate to the folder and open `index.html` using a **local server** (like VS Code Live Server).
    * *Note: Camera access requires a secure context (HTTPS or Localhost).*

---

## 📜 License
This project is open-source and available under the MIT License.
