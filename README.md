# Pose-Estimation-and-Green-Dot-Detector-app

IT is a Flask-based web application that combines the power of MediaPipe Pose Estimation and dot detection in videos. It allows users to upload video files, choose between two functionalities - Pose Estimation or Dot Detection, and visualize the processed results

## Features

- **Pose Estimation:** Utilizes the MediaPipe Pose module to draw the skeleton of a person in the uploaded video.

- **Dot Detection:** Identifies green dots in the video and draws red dots at their centers.

## Prerequisites

- Python 3.x
- Flask
- OpenCV
- Mediapipe

Install the required dependencies using:

```bash
pip install Flask opencv-python mediapipe
Getting Started
1. Clone the repository:
git clone https://github.com/yourusername/VisualPoseDotInsightAnalyzer.git
cd VisualPoseDotInsightAnalyzer
2. Install dependencies:
pip install -r requirements.txt
3. Run the Flask app:
python app.py

