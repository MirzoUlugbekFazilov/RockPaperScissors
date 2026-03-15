AI Rock–Paper–Scissors 🤖✊📄✂️

Real-time hand gesture recognition game powered by computer vision and browser-based AI.

This project uses webcam input and machine learning-based hand tracking to detect a player's hand gestures and play Rock–Paper–Scissors against an AI robot in real time. The system runs entirely in the browser, combining computer vision, gesture classification, and an interactive animated UI.

Demo

Live Demo: https://your-demo-link.com

Features

Real-time hand tracking using MediaPipe Hands

Gesture classification for rock, paper, and scissors

AI opponent with animated robot interface

Interactive browser-based gameplay

Smooth gesture recognition using frame history smoothing

Webcam-based computer vision processing

Fully client-side AI inference

Technologies Used

JavaScript

HTML5 / CSS

MediaPipe Hands

Canvas API

WebRTC camera streaming

Libraries

@mediapipe/hands

@mediapipe/camera_utils

@mediapipe/drawing_utils

How It Works

Webcam Input
The browser accesses the user's webcam using WebRTC to capture live video frames.

Hand Detection
MediaPipe Hands detects and tracks 21 hand landmarks in real time.

Gesture Recognition
A custom classification algorithm analyzes landmark distances to determine whether the user shows:

Rock

Paper

Scissors
Temporal smoothing across frames improves stability.

Game Logic
The system compares the player's gesture with the AI's move and determines:

Win

Lose

Tie

Interactive Visualization
The game renders the interface using HTML5 Canvas, including:

Real-time hand overlay

Animated AI robot

Score tracking

Game feedback

Project Structure
project
│
├── index.html
├── styles.css
├── script.js
└── README.md

(Adjust if your structure differs)

Running the Project

Clone the repository:

git clone https://github.com/yourusername/ai-rock-paper-scissors.git

Open the project:

cd ai-rock-paper-scissors

Run locally:
Simply open index.html in a browser with webcam permissions enabled.

Future Improvements

Train a custom gesture classification model

Implement AI strategy prediction instead of random moves

Add multiplayer mode

Improve gesture recognition with deep learning

Deploy as a web application

Learning Outcomes

This project demonstrates:

Real-time computer vision

Browser-based AI applications

Gesture recognition systems

Human-computer interaction

Interactive visualization with Canvas

Author

Mirzo-Ulugbek Fazilov
Computer Science & AI student interested in:

Artificial Intelligence

Computer Vision

AI-driven applications
