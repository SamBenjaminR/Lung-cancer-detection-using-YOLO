# Sybil-Integrated YOLO Model for Deep Learning-Based Lung Cancer Prediction

This repository contains the implementation of a hybrid deep learning model that combines Sybil and YOLO frameworks for early and accurate lung cancer detection using CT scan data from the LUNA16 dataset.

## 📌 Project Highlights
- **YOLO** for nodule detection in CT images.
- **Sybil model** for lung cancer risk prediction.
- Combines image-based and clinical data for improved accuracy.

## 📂 Folder Structure
- `data/`: Contains CT scans, annotations, and clinical metadata.
- `models/`: YOLO, Sybil, and integrated model code.
- `preprocessing/`: Data cleaning, labeling, and preprocessing scripts.
- `notebooks/`: Jupyter notebooks for EDA and visualization.
- `results/`: Output predictions and evaluation metrics.
- `utils/`: Helper functions for data loading, plotting, etc.

## 🛠️ Installation

```bash
git clone https://github.com/your-username/Sybil-YOLO-LungCancer.git
cd Sybil-YOLO-LungCancer
pip install -r requirements.txt
