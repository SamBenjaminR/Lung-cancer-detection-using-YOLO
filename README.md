# Lung-cancer-detection-using-YOLO
Sybil-YOLO-LungCancer/
│
├── data/
│   ├── CT_Scans/              # LUNA16 CT scan data
│   ├── Annotations/           # YOLO formatted annotations
│   └── Clinical_Data.csv      # Metadata (age, gender, etc.)
│
├── models/
│   ├── sybil_model.py         # Sybil implementation code
│   ├── yolo_model.py          # YOLO model code
│   └── combined_model.py      # Code to integrate YOLO and Sybil
│
├── preprocessing/
│   ├── preprocess_scans.py    # Preprocessing CT scans
│   ├── data_split.py          # Splitting training/validation sets
│   └── label_converter.py     # Convert annotations if needed
│
├── notebooks/
│   └── EDA_and_Visualization.ipynb # For visualizing scans and annotations
│
├── results/
│   ├── predictions/           # Model outputs
│   └── evaluation_metrics.md  # Accuracy, Precision, Recall, etc.
│
├── utils/
│   └── helpers.py             # Common utility functions
│
├── requirements.txt           # Dependencies
├── README.md                  # Project overview
└── LICENSE                    # (Optional) Licensing info
