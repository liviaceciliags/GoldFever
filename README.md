# GoldFever

**Illegal Mining Detection with Embedded Deep Learning on UAVs**

GoldFever is a public repository that provides training notebooks and model weights for detecting illegal mining in the Amazon rainforest using deep learning models embedded in UAV platforms. This project uses the GoldFever dataset, a novel georeferenced dataset built from satellite imagery and drone-simulated views.

## 📂 Contents

This repository includes training notebooks for multiple object detection architectures evaluated on the GoldFever dataset:

- `train_yolov8n.ipynb` — YOLOv8 nano
- `train_yolov10n.ipynb` — YOLOv10 nano
- `train_yolov11n.ipynb` — YOLOv11 nano
- `train_yolov12n.ipynb` — YOLOv12 nano
- `train_rt_detr.ipynb` — RT-DETR Transformer-based model

## 📊 Dataset

The **GoldFever dataset** is composed of manually annotated aerial images categorized into two classes:

- **PA**: Preserved Areas (intact forest and rivers)
- **Mining**: Areas with illegal mining activity

Total images:  
- PA: 996  
- Mining: 1010  

Augmentation techniques expand the training set to approximately 4,000 samples.

🔗 **Access the dataset**:  
[https://www.kaggle.com/datasets/lviacecliagomessilva/illegal-mining-dataset](https://www.kaggle.com/datasets/lviacecliagomessilva/illegal-mining-dataset)
