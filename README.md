# Computer-Vision Real-Time Object Detection 

## Overview
This project demonstrates the seamless integration of YOLOv8, a state-of-the-art object detection algorithm, with Streamlit, a Python framework for building interactive web applications. The goal is to provide a user-friendly interface for real-time object detection and tracking on video streams, images, and online sources such as RTSP, UDP, and YouTube URLs.

## Why Choose This Project?
While object detection is not a new concept, this project serves as a practical implementation of combining multiple technologies to create an interactive and adaptable machine learning application. It is an ideal choice for those looking to:
- Understand how to integrate deep learning models into a web-based interface.
- Explore real-time inference capabilities using pre-trained models.
- Learn about handling various video sources, including live streams and pre-recorded files.
- Gain insights into deploying computer vision models with Streamlit.

## Features
- **Real-time Object Detection:** Supports live video feeds, static images, and YouTube video links.
- **Customizable Model Settings:** Users can adjust confidence thresholds and choose between object detection and segmentation tasks.
- **User-Friendly Interface:** Streamlit-powered UI ensures ease of use for both developers and non-technical users.
- **Multiple Source Options:** Supports RTSP, UDP, YouTube URLs, video files, and images.
- **Download Results:** Allows users to download processed images with detected objects.

## Installation
### Prerequisites
- Python 3.6 or higher
- YOLOv8
- Streamlit

## Usage
### Running the Application
Start the Streamlit application using the following command:
```bash
streamlit run app.py
```
This will launch the web application in a browser where users can upload images, video files, or provide URLs for real-time object detection.

### Configuring the ML Model
1. Select the task (Object Detection / Segmentation).
2. Adjust the confidence threshold using the slider.
3. Choose a data source (image, video, RTSP stream, or YouTube URL).

### Object Detection on Images
- Upload an image.
- Click "Detect Objects" to process the image.
- Download the output if needed.

### Object Detection on Videos
- Store video files in the `videos` folder.
- Modify `settings.py` to reference video file names.
- Select the video from the web app interface and start detection.

### Object Detection on Live Streams (RTSP / YouTube)
- Provide the RTSP stream URL or YouTube video link.
- Click "Detect Objects" to start real-time inference.

## Learning Outcomes
By working on this project, users will:
- Gain hands-on experience with deploying deep learning models in web applications.
- Understand the workflow of real-time object detection.
- Learn how to integrate computer vision models with interactive user interfaces.
- Explore the challenges and optimizations required for running deep learning models in a lightweight web app.

## Disclaimer
This project is for educational and demonstration purposes only. It is not optimized for production use and should be used for learning and experimentation.

## Acknowledgments
This application leverages:
- **YOLOv8** for object detection
- **Streamlit** for the web interface
- **OpenCV** for image processing

If you find this project useful, consider starring the repository on GitHub!

Let the graph be growing !

- Ayush Kumar

