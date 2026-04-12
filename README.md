🌌 SkySketch
Draw in the air. Capture the moment. SkySketch is an AI-powered spatial drawing application that transforms your webcam into a digital canvas.
Using real-time hand tracking, users can paint in 3D space using simple natural gestures.

✨ Features
1] Air Drawing: Use your index finger to draw lines directly in the video feed.

2] Gesture Controls: 
Point your index finger :Draw
Fist: Pause drawing to move your hand
Z-Depth Scaling: Move your hand closer to the camera for thicker strokes; pull back for finer details.
Creative Brushes: Choose between Pen, Glow, Neon, and Watercolor effects.
Capture: Save your masterpiece as a high-quality PNG with one click.
Performance Optimized: Throttled processing to ensure smooth performance on mobile and older laptops.

🚀 Tech Stack
Engine: [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) (on-device ML)
Frontend: HTML5, CSS3 (Glassmorphism UI), Vanilla JavaScript
Rendering: Canvas API with Quadratic Bezier smoothing
Hosting: GitHub Pages

🛠️ How it Works
SkySketch uses a pre-trained machine learning model to detect 21 hand landmarks in real-time. 
1. The Coordinate Mapper translates 3D hand coordinates into 2D canvas pixels using "Letterbox" math to ensure precision across all screen sizes.
2. An Exponential Moving Average (EMA) filter is applied to the tracking data to eliminate jitter.
3. The Bezier Engine draws smooth curves between points to ensure the "ink" looks organic and fluid.

📱 Mobile Tips
Landscape Mode: Rotate your phone for the best drawing experience.
Lighting: Works best in well-lit environments where your hand is clearly visible.
Browser: Use Safari on iOS and Chrome on Android.

Created by VyasJr
