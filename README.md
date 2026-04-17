#  PicDetect: A Deep Learning Approach to Object Recognition and Scene Understanding

## Authors
* **Y. Anusha**
* **K. Venkata Sai**
* **P. Sindhu**
* **T. Rakesh**

---

##  Overview 

**PicDetect** is a deep learning-based object recognition and scene analysis system built using **YOLOv8**. It detects objects in images/videos and further analyzes human posture and object interactions to understand the scene.

Beyond simple detection, the system evaluates spatial relationships between persons and objects to identify interactions, proximity, and potential risk scenarios.

It calculates **risk scores (0–100)** based on object type, distance, posture, and context, and generates a fully explainable dashboard with annotated outputs, alerts, and insights.

---

## Implementation

Source Code  
🔗 **https://github.com/ANUSHAYAMPARALA/PicDetect.git**

Description  

The implementation of PicDetect is available in the above GitHub repository, which includes object detection, pose estimation, interaction analysis, and risk scoring modules. The system processes images/videos and produces annotated outputs with explainable results.

---

##  System Architecture


┌─────────────────────────────────────────────────────┐
│ PRESENTATION LAYER (Frontend / UI) │
│ Streamlit / Visualization Dashboard │
│ Matplotlib / Output Display │
└──────────────────────┬──────────────────────────────┘
│ Python Pipeline / API
┌──────────────────────▼──────────────────────────────┐
│ PROCESSING LAYER (Core System) │
│ YOLOv8 Object Detection │
│ YOLOv8 Pose Estimation (17 keypoints) │
│ Interaction Detection Module │
│ Risk Analysis Engine │
└──────────────────────┬──────────────────────────────┘
│ Model Inference
┌──────────────────────▼──────────────────────────────┐
│ MODEL LAYER (AI Models) │
│ YOLOv8 (Object Detection Model) │
│ YOLOv8-Pose (Pose Estimation Model) │
└─────────────────────────────────────────────────────┘


---

##  Key Features

| Feature | Description |
|--------|-------------|
| Object Detection | Detects multiple objects using YOLOv8 |
| Pose Estimation | Extracts 17 human keypoints |
| Interaction Analysis | Finds relationships between objects and persons |
| Risk Scoring | Generates risk score from 0–100 |
| Scene Understanding | Understands context of environment |
| Explainable AI | Provides reasoning for detected risk |

---

##  Problem Statement

Existing object detection systems only identify objects but do not understand:
- Human behavior
- Object interactions
- Scene context
- Risk levels

PicDetect solves this by adding **intelligence, interaction analysis, and explainability**.

---

##  Project Objectives

- Detect objects using YOLOv8  
- Extract human pose keypoints  
- Analyze interactions between objects and persons  
- Compute risk score based on context  
- Generate explainable outputs  

---

##  Tech Stack

### Frontend / Visualization
- Streamlit
- Matplotlib

### Backend
- Python
- OpenCV
- NumPy
- Pillow

### AI Models
- YOLOv8 (Object Detection)
- YOLOv8-Pose (Pose Estimation)

---

##  Methodology

- Input image/video is loaded  
- YOLOv8 detects objects  
- Pose estimation extracts 17 keypoints  
- Interaction analysis between objects/persons  
- Risk scoring based on proximity + posture  
- Context classification of scene  
- Final annotated output generated  

---

##  Inputs

- Image / Video (JPG, PNG, MP4)  
- YOLOv8 pretrained model  
- YOLOv8-Pose model  
- Scene context rules  

---

##  Outputs

- Annotated image/video  
- Bounding boxes and pose skeleton  
- Risk score (0–100)  
- Risk levels:
  - SAFE
  - LOW
  - MEDIUM
  - HIGH
  - CRITICAL  
- Explainable reasoning output  

---

##  Results

- Accurate object detection  
- Effective human pose estimation  
- Interaction-based risk analysis  
- Scene-level understanding  
- Explainable AI output generation  

---

##  Future Enhancements

- Real-time CCTV monitoring  
- Mobile application integration  
- Cloud deployment  
- SMS/Email alert system  
- Video-based temporal risk analysis  
- Improved custom dataset training  

---
