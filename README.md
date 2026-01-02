
# 🧠 Object Detection 

This project is a real-time computer vision system that detects people and everyday objects, tracks hand interactions, and marks objects as **CONTAMINATED** once they are touched. It is designed for scenarios such as healthcare, hygiene monitoring, and safety analysis.

![1](https://github.com/user-attachments/assets/3485c61d-e991-4261-9bda-e2337b698477)


## 🚀 Features

* Detects **persons (patients)** and common objects (**bottles, cups, glasses**)
* Uses **pose estimation** to locate hand positions
* Identifies **hand–object contact** using IoU-based logic
* Automatically marks touched objects as **CONTAMINATED**
* Real-time visualization with color-coded object status



## 🛠️ Tech Stack

* **YOLOv8** – Object detection
* **YOLOv8-Pose** – Hand and body keypoint detection
* **OpenCV** – Video processing and visualization
* **NumPy** – Numerical computations


## 📦 Installation

Install the required dependencies using pip:

```bash
pip install ultralytics opencv-python numpy
```

> ⚠️ Model weights are downloaded automatically on first run.



## ▶️ Usage

Run the main script:

```bash
python main.py
```

* Press **`q`** to quit the application.


## ⚙️ How It Works

1. **YOLOv8** detects persons and target objects in each video frame
2. **YOLOv8-Pose** identifies hand keypoints
3. An **IoU-based algorithm** checks for hand–object overlap
4. When contact is detected, the object is flagged as **CONTAMINATED**
5. Contaminated objects are highlighted in **RED**



## 📌 Notes

* Designed for **real-time video streams**
* Can be extended to support additional object classes
* Suitable for research, academic projects, and prototype systems


## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**

