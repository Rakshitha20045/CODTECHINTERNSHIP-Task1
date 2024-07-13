**Name:** Rakshitha A
**Company:** CODTECH IT SOLUTIONS INTERNSHIP
**ID:** CT08DS1935
**Domain:** Artificial Intelligence
**Duration:** June to July 2024

### Overview of the project
### Object Detection 

### Objective
The primary objective of this project is to implement object detection using the YOLO (You Only Look Once) version 8 model. The project demonstrates object detection on both video and image inputs, highlighting how to use the YOLO model for real-time object recognition and annotation.

### Key Activities
**Loading Class Names**-Read class names from a text file which contains the names of the objects that the YOLO model can detect.
**Generating Random Colors for Classes**-Generate random colors to visually distinguish different object classes in the video frames.
**Loading YOLO Model**-Load the pre-trained YOLOv8 model for object detection.
**Object Detection in Frames**-Save a temporary frame image, run the YOLO model to detect objects, and annotate detected objects with bounding boxes and labels.
**Annotating Frames**-Draw bounding boxes and labels for detected objects on video frames.

### Technologies Used
**Python**: The primary programming language used for the implementation.
**OpenCV**: A computer vision library used for video capture, image processing, and displaying results.
**Ultralytics YOLO**: The YOLO model implementation from the Ultralytics library used for object detection.
**NumPy**: A library for numerical operations, used here to handle the detection data.
**Random**: A module for generating random colors for class annotations.

### Key Insights
**Efficient Object Detection**: YOLOv8 is capable of real-time object detection, making it suitable for applications requiring fast and accurate object recognition.
**Class-Based Color Coding**: Assigning random colors to different classes helps in visually distinguishing between multiple detected objects in the frames.
**Flexibility**: The implementation can be easily adapted to different input sources (e.g., video files, live video streams, images).
**Thresholding**: Using confidence thresholds helps in filtering out less certain detections, improving the reliability of the annotations.
**Temporary Storage**: Saving frames temporarily for processing might be necessary when using certain models or APIs that require file inputs.

### Goal
This project demonstrates the application of the YOLOv8 model for object detection in both video and image inputs. The key activities include data preparation, model loading, frame processing, object detection, and visualization. The use of modern computer vision and machine learning techniques, coupled with robust libraries like OpenCV and Ultralytics YOLO, enables efficient and effective object detection suitable for various real-time applications.
![Screenshot 2024-07-13 210042](https://github.com/user-attachments/assets/826b9209-8194-4296-865b-ff0ccb19ec28)
