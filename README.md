# Personal Trainer Application - Automatic Exercise Recognition

This repository contains a Python script designed to recognize and count exercise repetitions using a webcam. It employs MediaPipe for pose detection and OpenCV for real-time video processing. The script can automatically detect, track, and count reps for the following exercises:

1. Bicep Curls
2. Squats
3. Push-Ups

# Features
Automatic Rep Counting: Counts exercise repetitions in real-time.
Exercise Detection: Automatically detects the exercise being performed based on changes in body angles.
Live Angle Display: Displays joint angles on the screen for better exercise form tracking.
Customizable Exercises: Easily extendable for additional exercises by modifying the code.

# Install dependencies: 
Ensure you have Python 3.7+ installed. 
Then install the required Python packages:
pip install opencv-python mediapipe numpy

# Run the application:
python SquatCounter.py

# How It Works
1. Pose Detection: Uses MediaPipe Pose to detect key body landmarks in real time.

2. Angle Calculation: Calculates angles between specific body parts to determine exercise stages (e.g., "up" and "down").

3. Repetition Counting: Tracks changes in angles to count completed repetitions.

4. Exercise Detection: Determines the exercise being performed based on significant changes in joint angles.

# Usage
Run the script to open your webcam.

Perform one of the supported exercises (Bicep Curls, Squats, or Push-Ups).

The application will:

Detect the exercise.
Count the repetitions.
Display the current rep count, stage, and angles on the screen.
Press q to quit the application.

