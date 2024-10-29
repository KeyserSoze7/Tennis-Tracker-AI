
# Tennis Court Object Detection Project

This project demonstrates object detection on a tennis court, specifically identifying players and tennis balls. It uses a fine-tuned YOLOv8 model trained on a tennis-specific dataset to perform accurate object detection in video files.

## Overview

The goal of this project was to develop an object detection system capable of recognizing key objects on a tennis court, specifically players and the tennis ball, in real-time video footage. The trained model, fine-tuned using YOLOv8, allows accurate and efficient detection in various tennis scenarios.

## Features

- **Object Detection on Video**: Detects players and tennis balls in real-time from video files.
- **YOLOv8 Fine-Tuning**: Fine-tuned using a custom tennis dataset for improved accuracy.
- **Roboflow Integration**: Utilized Roboflow to save and manage the model state, aiding in streamlined model deployment and version control.
- **ByteTrack Tracking**: Incorporates ByteTrack for enhanced object tracking, maintaining continuity of objects across video frames.
- **Supervision for Labeling and Annotation**: Used for supervised learning to improve model accuracy and reliability.

## Tools & Technologies

- **Python**: Core language for developing the detection model and scripts.
- **YOLOv8**: Backbone model for object detection, fine-tuned on a tennis dataset.
- **Roboflow**: Used to organize the dataset, annotate images, and save the model state.
- **Supervision**: Assisted with annotating and labeling the dataset.
- **ByteTrack**: Enabled real-time object tracking across frames.

## Setup & Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/KeyserSoze7/Tennis-Tracker-AI.git
   cd Court-Tracker.ipynb

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

3. **Load the Model**:
   ```bash
   # Example code snippet
   from roboflow import Roboflow
   rf = Roboflow(api_key="YOUR_API_KEY")
   project = rf.workspace().project("YOUR_PROJECT_NAME")
   model = project.version("YOUR_VERSION").model

4. **Run the Detection on Video**:
   ```bash
   python detect.py --source path/to/video/file

  # Result  

The model performed well in detecting and tracking both players and the tennis ball across frames. ByteTrack allows for maintaining object identity through frames, enhancing the continuity of the object detection process.

  ## Sample Output (Compressed) 
Here's the output video downloaded in "court-tracker.ipynb" : 


https://github.com/user-attachments/assets/045b2571-9cc8-489d-a59e-5d74d613a60e

# Future Improvements

- Calculating distance covered and speed of the player. 
- Enhancing the model to handle different camera angles.
- Improving detection under varying lighting conditions.
  







    
