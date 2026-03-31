# Human Pose Estimation using Deep Learning

This project implements **Human Pose Estimation** using a pre-trained OpenPose model with OpenCV's DNN module. It detects key human body joints from an image and visualizes them as a skeletal structure.

---

## 📌 Overview

Human Pose Estimation is a computer vision task that identifies and tracks human body keypoints such as head, shoulders, elbows, and knees. This project uses a deep learning-based approach to:

- Detect 15 body keypoints
- Generate probability maps
- Construct a human skeleton
- Visualize joints and connections

---

## 🚀 Features

- Uses pre-trained OpenPose (Caffe model)
- Detects multiple body joints accurately
- Visualizes keypoints and skeleton
- Displays probability maps
- Works on static images

---

## 🛠️ Technologies Used

- Python
- OpenCV (cv2.dnn)
- NumPy
- Matplotlib
- Caffe Model (OpenPose)

---

## 📂 Project Structure

project/
│── model/
│   ├── mpi.prototxt
│   ├── mpi.caffemodel
│── Human_Pose_Estimation_using_Deep_Learning.py
│── Tiger_Woods.jpg
│── README.md

---

## ⚙️ Requirements

Install dependencies:

pip install opencv-python numpy matplotlib

---

## ▶️ How to Run

1. Clone repository:
git clone https://github.com/your-username/human-pose-estimation.git

2. Add input image and update code:
im = cv2.imread("your_image.jpg")

3. Run:
python Human_Pose_Estimation_using_Deep_Learning.py

---

## 📊 Output

- Probability maps
- Keypoints image
- Skeleton image

---

## 🧠 Working

1. Image → Blob
2. Neural network inference
3. Probability maps
4. Keypoint extraction
5. Skeleton drawing

---

## 📌 Applications

- Sports analytics
- Healthcare
- Surveillance
- AR/VR

---

## ⚠️ Limitations

- 2D only
- Sensitive to occlusion

---

## 🔮 Future Work

- Real-time video
- 3D pose estimation

---

## 👤 Author

Anurag Verma
