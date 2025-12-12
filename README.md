# **SmartActivityMonitor – Real-Time Human Activity Recognition using CNN + LSTM**

SmartActivityMonitor is an **end-to-end AI system** designed to **recognize human activities from video footage** in real-time.
It combines **Convolutional Neural Networks (CNN)** for spatial feature extraction and **Long Short-Term Memory (LSTM)** networks for temporal modeling, creating a **robust Human Activity Recognition (HAR) pipeline**.

> 🚀 Built for smart monitoring applications like healthcare, elderly care, and surveillance, optimized for production-ready deep learning workflows.

---

## 🌟 **Key Features**

### 🎥 **1. Video-Based Activity Recognition**

* Recognizes activities such as **walking, sitting, running, falling, and more**
* Processes videos frame by frame to capture motion and context
* Designed for **real-time inference**

### 🧠 **2. CNN + LSTM Architecture**

* **CNN layers** extract spatial features from each frame
* **LSTM layers** model temporal dependencies across video sequences
* Accurate detection of **dynamic human actions** over time

### ⚡ **3. End-to-End Pipeline**

* Video preprocessing → frame extraction → normalization
* Feature sequence generation → model training → evaluation
* Deployment-ready inference pipeline for new videos

### 📊 **4. Model Evaluation & Metrics**

* Measures classification performance: **Accuracy, Precision, Recall, F1-Score**
* Confusion matrices to identify challenging activity classes
* Notebook-based visualizations for transparent results

### 🖥️ **5. Real-Time Inference**

* Drop new video clips into `new_videos/` folder
* Run inference notebooks to get activity predictions
* Ready to integrate into **smart monitoring applications**

---

## 🛠️ **Tech Stack**

| Category        | Tools                                |
| --------------- | ------------------------------------ |
| Deep Learning   | TensorFlow / Keras, CNN, LSTM        |
| Computer Vision | OpenCV, NumPy                        |
| Visualization   | Matplotlib, Seaborn                  |
| Environment     | Python, Jupyter Notebook             |
| Deployment      | Flask (it is optional for API integration) |

---

## 📁 **Project Structure**

```
SmartActivityMonitor/
│
├── data/                  # Video datasets (train/test)
├── notebooks/             # EDA, preprocessing, training, evaluation
├── src/                   # Core scripts for model training & inference
├── utils/                 # Helper functions  for preprocessing & evaluation
├── models/                # Saved CNN+LSTM models
├── new_videos/            # Folder for new videos to test its inference
├── docs/                  # Visualizations and documentation
├── requirements.txt
└── README.md
```

---

## 🔄 **Workflow**

```
Raw Video Input
      ↓
Frame Extraction & Preprocessing
      ↓
CNN Feature Extraction
      ↓
LSTM Temporal Modeling
      ↓
Activity Classification
      ↓
Real-Time Inference & Visualization
```

---

## 📊 **Sample Output**

| Video Clip | Predicted Activity | Confidence |
| ---------- | ------------------ | ---------- |
| clip1.mp4  | Walking            | 0.95       |
| clip2.mp4  | Sitting            | 0.91       |
| clip3.mp4  | Falling            | 0.88       |

**Inference Example**

```json
{
    "video_clip": "clip3.mp4",
    "predicted_activity": "Falling",
    "confidence": 0.88
}
```

---

## 🎯 **Benefits**

* Detects human activities accurately in real-time video
* Hybrid deep learning model combines spatial + temporal features
* End-to-end pipeline suitable for **healthcare, smart home, and surveillance applications**
* Production-ready structure for integration into monitoring systems
