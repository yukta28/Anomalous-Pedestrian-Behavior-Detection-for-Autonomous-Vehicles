# Anomalous-Pedestrian-Behavior-Detection-for-Autonomous-Vehicles

🚀 Project Overview

This project focuses on detecting anomalous pedestrian behavior in self-driving car environments using computer vision and deep learning. By leveraging YOLOv8 for pedestrian detection and LSTM Autoencoders for anomaly detection, we analyze pedestrian motion and identify unusual behavior such as sudden stops, erratic movements, and jaywalking.

![image](https://github.com/user-attachments/assets/153afad5-e409-49b7-b812-065d906b65f2)

📌 Features

Pedestrian Detection using YOLOv8 object detection model

Velocity & Acceleration Computation for pedestrian tracking

Anomaly Detection using LSTM Autoencoders

Visualizations including heatmaps, trajectory plots, and scatter plots

Video Processing with bounding boxes overlay for normal and anomalous pedestrians

Web-based Report displaying insights, images, and embedded video

🔧 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/anomalous-pedestrian-detection.git

cd anomalous-pedestrian-detection

2️⃣ Install Dependencies

pip install ultralytics opencv-python torch torchvision numpy pandas matplotlib seaborn flask

3️⃣ Download the Dataset (JAAD Dataset)

Visit JAAD Dataset Website

Download & extract it inside the dataset/ folder

4️⃣ Run YOLOv8 Detection on Video

python process_video.py --input input_video.mp4 --output output_video.mp4

5️⃣ Train LSTM Autoencoder

python train_lstm_autoencoder.py

📊 Results & Visualizations

Below are some key visualizations from the analysis:
✅ Heatmap of pedestrian movement patterns
![image](https://github.com/user-attachments/assets/31f0784e-09e3-436f-b4db-7551536f66a6)

✅ Velocity vs. Acceleration Scatter Plot
![image](https://github.com/user-attachments/assets/5ccb3f08-7554-4a89-b005-f532ef2e9acb)

✅ Pedestrian trajectory tracking
![image](https://github.com/user-attachments/assets/2bb82ae6-e7a3-45a4-b9d2-6529e07c3033)

✅ Frames with anomalies marked in red
![image](https://github.com/user-attachments/assets/9a8c3463-862c-4fb3-9162-40cc1a315bef)


🚀 Future Improvements

✅ Real-time detection with optimized YOLO models

✅ Deploy model on an Edge AI device (Raspberry Pi / Jetson Nano)

✅ Improve dataset diversity by adding different urban traffic scenes

✅ Fine-tune LSTM Autoencoder for higher accuracy


📌 Author: Yukta Dandekar
