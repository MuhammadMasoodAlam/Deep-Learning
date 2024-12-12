# Deep Learning Projects - PGD NED Data Science

Welcome to the **Deep Learning Projects** repository! This repository contains a collection of projects developed during the Postgraduate Diploma (PGD) program at NED University. These projects focus on various deep learning techniques and applications, showcasing hands-on learning and real-world implementations.

---

## Projects Overview

### 1. **Sequence Processing (1D)**
- **Description**: This project explores sequence processing techniques using 1D data. Applications include natural language processing, time-series analysis, and sequential data modeling.
- **Dataset**: Reddit data on Israel-Palestine War:
  - `/kaggle/input/Redditors opinion on Israel-Palestine War/posts.csv`
  - `/kaggle/input/Redditors opinion on Israel-Palestine War/reddit_comments_clean`
- **Key Features**:
  - Preprocessing and handling sequential data.
  - Implementation of models like RNNs, LSTMs, or GRUs.
  - Performance evaluation and insights.

### 2. **Sequence Processing (2D)**
- **Description**: This project extends sequence processing to 2D data, focusing on spatial-temporal data analysis, such as video frame sequences or spatiotemporal sensor readings.
- **Dataset**: Jena Climate Data.
- **Key Features**:
  - 2D sequential data handling and transformation.
  - Advanced deep learning architectures like ConvLSTMs.
  - Use cases in video processing and dynamic systems.

### 3. **Detecting Bike Helmets Using YOLOv11**
- **Description**: A real-time object detection project focusing on identifying bike riders with or without helmets to promote road safety. The YOLOv11 model is trained and evaluated for accuracy and speed.
- **Key Features**:
  - Data preprocessing and conversion to YOLO format.
  - Training YOLOv11 on custom helmet detection datasets.
  - Real-time inference on images and videos.
  - Metrics analysis to assess model performance.

---

## Requirements

To run these projects, ensure you have the following installed:

- Python 3.8 or higher
- Libraries:
  - `TensorFlow`
  - `PyTorch`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `opencv-python`
  - `ultralytics` (for YOLO)

Use the following command to install the dependencies:
```bash
pip install -r requirements.txt
```

---

## How to Run

### For Sequence Processing (1D or 2D):
1. Navigate to the respective project folder.
2. Run the notebook or Python script provided in the folder.
3. Follow instructions for input data and model training/inference.

### For Helmet Detection:
1. Ensure the dataset is properly organized as described in the project.
2. Train the YOLOv11 model using the provided script or notebook.
3. Use the trained model for inference on test images/videos.

---

## Contribution

Feel free to fork this repository and contribute to the projects. Suggestions for improvement or additional features are always welcome.

---

## Acknowledgments

Special thanks to **NED University** for providing an excellent learning environment and the opportunity to work on practical deep learning projects. These projects are part of the curriculum for the Postgraduate Diploma in Artificial Intelligence.

---

## License

This repository is licensed under the MIT License. Feel free to use and adapt the code for your own projects.
