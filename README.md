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

## 🎥 Sample Video Files

Due to GitHub's file size limitations, sample video files are not stored directly in this repository.

However, i have provided google drive links to the input and the output videos below:

- [Input Match Video From kaggle (Google Drive)](https://drive.google.com/file/d/1T494RwIvKLf-40zrFO5jv97uSbgN4AhH/view?usp=sharing)
- [Output Video "Generated Video #v1 (Google Drive)](https://drive.google.com/file/d/1-vsEsRc_1zQaucXH7UX8YEFjMrsv0ddG/view?usp=sharing)
- [Output Video "Generated Video #v2 (Google Drive)](https://drive.google.com/file/d/1FzeQ2Vr2R4VD6GBlxcOZ96KeWKiCjv29/view?usp=sharing)

