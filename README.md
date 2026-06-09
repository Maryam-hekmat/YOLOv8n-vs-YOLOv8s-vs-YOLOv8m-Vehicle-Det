# YOLOv8n-vs-YOLOv8s-vs-YOLOv8m-Vehicle-Det
Real-world detection results of YOLOv8 model on a Tehran city street, Iran
# 🚗 YOLOv8 Vehicle Detection - Tehran Street

Real-world detection results of YOLOv8 model on a Tehran city street, Iran.

## 📌 Project Overview

This project trains and compares **YOLOv8n, YOLOv8s, and YOLOv8m** models for vehicle detection.  
Dataset includes **5 vehicle classes**:
- 🚑 Ambulance
- 🚌 Bus
- 🚗 Car
- 🏍️ Motorcycle
- 🚛 Truck

---

## 📊 Results (30 Epochs)

| Model | mAP50 | Precision | Recall |
|-------|-------|-----------|--------|
| YOLOv8n | 0.2361 | **0.4217** | 0.2570 |
| YOLOv8s | 0.2536 | 0.2492 | 0.2671 |
| **YOLOv8m** | **0.2724** | 0.2473 | **0.2979** |

> ✅ **Best mAP:** YOLOv8m  
> ✅ **Best Precision:** YOLOv8n  
> ✅ **Best Recall:** YOLOv8m

---

## 🛠️ Tools & Libraries

- Python 🐍
- Ultralytics YOLOv8
- OpenCV
- Matplotlib / Seaborn
- Kaggle Notebooks

---

├── README.md
├── yolov8n-vs-yolov8s-vs-yolov8m-vehicle-det (1).ipynb
└── (images)


---

## 🎯 Conclusion

- **YOLOv8m** → Best for maximum accuracy (mAP & Recall)
- **YOLOv8n** → Best for speed & precision-critical tasks
- **YOLOv8s** → Balanced trade-off

---
## 🗂️ Dataset Source

This project uses the **VehicleDetection-YOLOv8** dataset, which is perfectly structured for YOLOv8.

- **Dataset Link:** [VehicleDetection-YOLOv8 on Kaggle](https://www.kaggle.com/datasets/alkanerturan/vehicledetection/data)
- **Author:** Alkan Erturan (Updated 2 years ago)
- **Dataset Size:** ~65.45 MB (2,510 files) + a separate test video
- **Classes (5):** Car, Bike, Ambulance, Truck, Motorcycle
- **Format:** YOLOv8 ready (includes `data.yaml` and train/val/test splits)
- **License:** Other (specified in the dataset description)
- **Note:** The dataset is sourced from Roboflow and is excellent for practicing object detection algorithms.

> The dataset is already structured in YOLOv8 format, making it easy to use for training, validation, and testing.
## 👩‍💻 Author

**Maryam Hekmat**  
[GitHub Profile](https://github.com/Maryam-hekmat)

## 📁 Repository Structure

