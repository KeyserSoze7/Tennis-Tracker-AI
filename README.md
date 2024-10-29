## Tennis-Tracker-AI

This project demonstrates object detection on a tennis court, specifically identifying players and tennis balls. It uses a fine-tuned YOLOv8 model trained on a tennis-specific dataset to perform accurate object detection in video files.

# Overview

The goal of this project is to develop an object detection system capable of recognizing key objects on a tennis court, specifically players and the tennis ball, in real-time video footage. The trained model, fine-tuned using YOLOv8, allows accurate and efficient detection in various tennis scenarios.

# Features

 Object Detection on Video: Detects players and tennis balls in real-time from video files.
 YOLOv8 Fine-Tuning: Fine-tuned using a custom tennis dataset for improved accuracy.
 Roboflow Integration: Utilized Roboflow to save and manage the model state, aiding in streamlined model deployment and version control.
 ByteTrack Tracking: Incorporates ByteTrack for enhanced object tracking, maintaining continuity of objects across video frames.
 Supervision for Labeling and Annotation: Used for supervised learning to improve model accuracy and reliability.

# Tools & Technologies

Python: Core language for developing the detection model and scripts.
YOLOv8: Backbone model for object detection, fine-tuned on a tennis dataset.
Roboflow: Used to organize the dataset, annotate images, and save the model state.
Supervision: Assisted with annotating and labeling the dataset.
ByteTrack: Enabled real-time object tracking across frames.

  # Result  

The model performed well in detecting and tracking both players and the tennis ball across frames. ByteTrack allows for maintaining object identity through frames, enhancing the continuity of the object detection process.

  # Sample Output 
Here's the output video downloaded in "court-tracker.ipynb" : 



    
