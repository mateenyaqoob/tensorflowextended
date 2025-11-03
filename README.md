# 🌟 TensorFlow Extended (TFX) Pipeline — Iris Dataset

## 📘 Overview
This project demonstrates how to build and execute a simple **TFX pipeline** using the Iris dataset.  
The pipeline automates:
- Data ingestion
- Model training
- Evaluation
- Model pushing

This example uses **LocalDagRunner** for local execution.

---

## 🧰 Prerequisites
- Python 3.8+
- TensorFlow 2.15+
- TFX 1.15+
- Pandas, Numpy (optional)

Install dependencies:
```bash
pip install tfx==1.15.0 tensorflow==2.15.0


## How to Run

## Clone the repository:

git clone https://github.com/yourusername/tfx-iris-pipeline.git
cd tfx-iris-pipeline


Prepare the dataset (data/iris.csv).

Run the pipeline:

python tfx_pipeline.py

📂 Project Structure
tfx-iris-pipeline/
│
├── data/
│   └── iris.csv
├── trainer/
│   └── run_fn.py           # Contains TensorFlow model logic
├── tfx_pipeline.py          # Defines the TFX pipeline
└── README.md

📈 Output

Metadata and artifacts are stored in:

./iris_pipeline_output/


Trained model saved in:

./iris_pipeline_output/serving_model/
