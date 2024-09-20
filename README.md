# Description

Fine-tuned a YOLOv8 pose estimation model to detect and label keypoints on horses . The project involved organizing a dataset for training and validation, converting labeled keypoint annotations into YOLO format, and training a deep learning model to recognize horse landmarks.

# Key features of the project include:

- Data Preparation: Converted keypoints and bounding boxes from JSON format into the YOLO keypoint format using a custom Python script.
- Model Training: Trained a YOLOv8-based model on a horse keypoint dataset, with 50 epochs, using specific data augmentation techniques such as mosaics and flipping.
- Model Validation: Performed validation on the model with performance metrics, and visualized the detected keypoints and bounding boxes on sample validation images.
- Visualization: Designed a function to display keypoints on images using color-coded markers and bounding boxes to highlight detected horse poses.
