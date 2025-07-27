# YOLOv5 Object Detection – Final Project

This repository contains a custom YOLOv5 detection script using Ultralytics.

## 📂 Folder Structure

Yolo_Final/
├── my_model/
│   ├── yolo_detect.py    ← main detection script
│   ├── my_model.pt       ← trained weights (ignored by .gitignore)
│   └── train/            ← (optional) your training data
├── Comp_Name/            ← (optional) extra configs
├── .gitignore            ← ignore rules
└── README.md             ← this file

## 🚀 How to Run

```bash
python my_model/yolo_detect.py \
  --model my_model/my_model.pt \
  --source test.jpg \
  --thresh 0.4

python my_model/yolo_detect.py \
  --model my_model/my_model.pt \
  --source 0 \
  --resolution 640x480 \
  --record
```

🛠 Requirements
```bash
pip install ultralytics opencv-python
```

👤 Author
Shubhangam Singh
VIT Vellore
