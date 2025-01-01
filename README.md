# Touchless-Drawing-Board
This project is a touchless drawing application that uses the MediaPipe Hands library and OpenCV to track hand gestures for a creative and interactive drawing experience. Move your hands in front of your webcam to draw, erase, and even customize brush settings—all without touching a mouse or keyboard!


*Features*

🎨 Draw with Your Hands:
Use your index finger as a virtual brush to draw on the screen.

🖌️ Customize Brush Settings:

Dynamic brush size adjustment using keyboard shortcuts.
Multiple brush colors: Blue, Green, Red, and an Eraser tool.

🤏 Pinch Gesture Toggle:
Switch drawing mode on or off by making a pinching gesture (thumb + index finger).

💾 Save Your Artwork:
Save your creations with a single keypress.

🧹 Clear Canvas:
Start fresh by clearing the canvas instantly.

📋 Easy Controls:

c: Clear the canvas.
s: Save the current canvas as an image (drawing.png).
1-4: Switch brush colors (1: Blue, 2: Green, 3: Red, 4: Eraser).
u/d: Increase or decrease brush size.
Pinch Gesture: Toggle drawing mode.



*Tech Stack*

Python
MediaPipe Hands for hand tracking and gesture detection.
OpenCV for video processing and drawing functionalities.
NumPy for numerical computations.


*How It Works*

Hand Tracking:
The application tracks hand landmarks using MediaPipe Hands.

Gesture Recognition:
Detects the position of your fingers to control drawing and toggle modes (like pinching gestures).

Canvas Blending:
Combines real-time video feed with a drawing layer for an augmented experience.

Custom Gestures and Features:
Switch colors, adjust the brush size, or erase with intuitive gestures and hotkeys.



*How to Run*
Clone this repository:

git clone https://github.com/your-username/touchless-drawing-board.git


Install the required dependencies:

pip install opencv-python mediapipe numpy


Run the script:

python virtual_canvass.py
