# ⚽ AI/ML Football Analysis System

A computer vision-based football analytics pipeline using YOLO, KMeans clustering, Optical Flow, and Perspective Transformation to detect, track, and analyze players, referees, and the football from match footage. This system generates performance insights like ball possession, player speed, and distance covered — making football analytics accessible and scalable for everyone.

---

## 📌 Features

- 🎯 **Player, Referee, and Ball Detection** using YOLOv5/YOLOv8  
- 🎽 **Team Classification** via KMeans clustering on jersey colors  
- 🧠 **Ball Possession Analysis** by tracking which team controls the ball  
- 📷 **Camera Motion Compensation** using Optical Flow  
- 📐 **Perspective Transformation** for real-world measurement (in meters)  
- 🚀 **Player Metrics** like speed, distance covered, and movement paths  
- 📊 Data export in CSV or visualization using Matplotlib/Seaborn  

---

## 🛠 Technologies Used

- Python 3.x  
- [Ultralytics YOLO](https://github.com/ultralytics/ultralytics)  
- OpenCV  
- NumPy, Pandas, Matplotlib  
- KMeans (from Scikit-learn)  
- Optical Flow (Lucas-Kanade or Farnebäck method)  
- Perspective Transformation (Homography Matrix)  

---

## 📁 Dataset

- Training and test data obtained from [Roboflow](https://roboflow.com/).  
- Includes annotations for players, referees, and footballs.  
- Custom training performed on YOLOv5/YOLOv8 format.

---
