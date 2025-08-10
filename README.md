# Driver-Drowsiness-Detection-System
Real-time driver drowsiness detection system using TensorFlow and OpenCV. Detects eye closure and yawning from live video feeds with a CNN model (87% accuracy) and provides timely alerts to improve road safety.
A real-time driver drowsiness detection system built with TensorFlow and OpenCV, designed to enhance road safety by monitoring driver behavior through live video feeds. The system detects eye closure and yawning using a custom-trained CNN model with 87% accuracy and provides timely alerts to prevent accidents caused by fatigue.


# 🚀 Features

Real-time Detection – Monitors driver’s facial features via webcam or camera feed.

CNN-based Classification – Identifies states like eye open, eye closed, yawning, and no yawning.

High Accuracy – Achieves around 87% classification accuracy.

Timely Alerts – Triggers notifications upon detecting drowsiness indicators.

Optimized for Speed – Designed to run smoothly in real-time environments.


# 🛠 Tech Stack

Python

TensorFlow / Keras – CNN model for classification

OpenCV – Video capture and image processing

NumPy & Pandas – Data handling and preprocessing


# 📊 Model Training

Dataset contains images of drivers with eyes open/closed and yawning/no yawning.

Preprocessing includes grayscale conversion, face & eye detection, and resizing to CNN input size.

Model architecture: Convolutional + Pooling layers → Dense layers → Softmax output.


# 📸 Sample Output

Demo Video: https://drive.google.com/file/d/1_ttXATCAf0dvCxQBgl_KCqnAww2nY9oT/view?usp=sharing


# 📌 Future Improvements

Add head pose estimation for more robust detection.

Integrate with vehicle alert systems.


