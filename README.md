# Drowsiness Detection Using OpenCV

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project implements a drowsiness detection system using OpenCV and Python. The system analyzes video frames from a webcam to detect facial landmarks and identify signs of drowsiness, such as blinking and head position. This can be particularly useful in applications like driver monitoring systems.

## Features
- Real-time drowsiness detection using webcam input
- Utilizes facial landmark detection to monitor eye activity
- Alerts users when drowsiness is detected
- Easy to set up and run

## Technologies Used
- Python
- OpenCV
- dlib
- NumPy

## Installation
To run this project, ensure you have Python installed on your machine. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/2003MADHAV/DrowsinessDetectionUsingOpenCV.git
   cd DrowsinessDetectionUsingOpenCV

2.Install the required packages:
  pip install -r requirements.txt
3. Download the shape predictor model from dlib's model repository and place it in the project directory.
4. type This command :- python drowsiness_detection.py
