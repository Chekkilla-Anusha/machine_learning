🦺 PPE Detection using YOLO (Personal Protective Equipment)
📌 Project Overview

This project focuses on detecting whether individuals are wearing Personal Protective Equipment (PPE) such as helmets, vests, and masks using YOLO (You Only Look Once) object detection.

It is useful for workplace safety monitoring in industries like construction, manufacturing, and mining.

🎯 Objectives
Detect people in images/videos
Identify PPE compliance (Helmet, Vest, Mask)
Improve workplace safety using AI
🧠 Model Used
YOLO (You Only Look Once)
Real-time object detection
High accuracy and speed
Suitable for video surveillance systems
📂 Dataset

The dataset contains labeled images with:

👷 Helmet
🦺 Safety Vest
😷 Mask
❌ No PPE

Annotations are used in YOLO format for training.

⚙️ Technologies Used
Python 🐍
OpenCV
YOLO (v5/v8)
PyTorch
NumPy
Matplotlib
🔄 Project Workflow
Data Collection
PPE images dataset
Data Annotation
Label objects using tools like LabelImg
Data Preprocessing
Convert annotations to YOLO format
Resize and normalize images
Model Training
Train YOLO model on PPE dataset
Model Evaluation
Precision, Recall, mAP
Detection
Real-time detection using webcam/video
📊 Results
Successfully detects PPE in real-time
Good accuracy in identifying safety violations
Can be extended for live CCTV monitoring
▶️ How to Run the Project
Clone the repository:
git clone https://github.com/your-username/ppe-detection-yolo.git
Install dependencies:
pip install -r requirements.txt
Run detection:
python detect.py
📁 Project Structure
├── data/
├── models/
├── runs/
├── detect.py
├── train.py
├── PPE_Detection.ipynb
├── requirements.txt
└── README.md
💡 Future Improvements
Improve detection accuracy with more data
Deploy using Streamlit or Flask
Integrate with CCTV cameras
Add alert system for violations
🙌 Applications
Construction site safety
Factory monitoring
Industrial compliance systems
🤝 Acknowledgements
YOLO by Ultralytics
OpenCV community
Dataset contributors