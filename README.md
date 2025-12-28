# Hand Gesture Particle System ✋✨

# Overview
Hand Gesture Particle System is a real-time interactive WebGL project that visualizes 10,000 animated particles and allows users to control them using hand gestures via a webcam. Built with Three.js for 3D rendering and MediaPipe Hands for gesture recognition, this project demonstrates the fusion of computer vision and GPU-accelerated graphics in the browser.

Users can change particle shapes, rotate the scene, and scale formations using natural hand movements—without touching the keyboard or mouse.

# Features
🎥 Real-time hand tracking using MediaPipe Hands

🌐 GPU-accelerated particle rendering with Three.js

🔄 Smooth particle morphing between multiple shapes

✋ Gesture-based controls (finger count & pinch)

🔍 Pinch-to-scale (zoom in/out) interaction

🎨 Glowing particle effects with additive blending

📱 Responsive and full-screen canvas

# Gesture Controls
Gesture	Action
0 fingers	Sphere
1 finger	Heart
2 fingers	Flower / Firework
3 fingers	Saturn
4 fingers	Cube
5 fingers	Galaxy
Thumb + Index Pinch	Scale particles

# Tech Stack
JavaScript (ES6)

Three.js – WebGL-based 3D rendering

MediaPipe Hands – Real-time hand and finger tracking

HTML5 / CSS3

# How It Works
Particles are stored in BufferGeometry using typed arrays for performance.

Each shape defines a target position and color for every particle.

Smooth transitions are achieved using linear interpolation (LERP).

MediaPipe detects hand landmarks to identify gestures and control the scene.


# Use Cases
Creative coding & generative art

Computer vision demos

WebGL learning projects

Portfolio & interview showcase

Touchless UI experiments

# Future Improvements
GPU-based morphing using custom shaders

More advanced gesture recognition

Mobile optimization

Custom gesture training
