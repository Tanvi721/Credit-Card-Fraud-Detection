
# Credit Card Transaction Analysis

Output 1:
<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/2ef1610f-a809-402f-ab26-896ac3b6a00f" />
outout 2: 
<img width="1916" height="1015" alt="image" src="https://github.com/user-attachments/assets/c462d531-a27f-49c0-ac23-7a3761b04a59" />
Output 3:
<img width="1903" height="1017" alt="image" src="https://github.com/user-attachments/assets/ca72f6d3-90b4-4e62-999c-b4a07f1777f1" />
Output 4:
<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/a4fcdf23-dbb5-4df0-8534-ca86bea3077e" />
Output 5:
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c8b1c3ec-8f5d-4a4e-8acc-34af8362b4ac" />
# Overview

This project demonstrates how to use MLflow for tracking, managing, and visualizing Machine Learning experiments. With MLflow, you can easily log parameters, metrics, artifacts, and models, enabling reproducibility and efficient model comparison.

https://mlflow.org/img/hero.png

# 🚀 Features

📊 Experiment Tracking – Log metrics, parameters, and artifacts.

📂 Model Registry – Save and manage different versions of models.

🔄 Reproducibility – Ensure experiments can be repeated with the same results.

📈 Visualization – Interactive UI to compare model performance.

🔌 Integration – Works with scikit-learn, TensorFlow, PyTorch, and custom ML code.

#  Tech Stack

Language: Python

ML Library: scikit-learn / TensorFlow / PyTorch (as per your use)

Tracking Tool: MLflow

Data Handling: Pandas, NumPy

# 📦 Installation

Clone the repository
git clone https://github.com/yourusername/your-repo.git cd your-repo

Install dependencies
pip install -r requirements.txt

# ▶️ Usage

Run MLflow UI
mlflow ui

Then, open http://127.0.0.1:5000 in your browser to view experiment logs.

📂 Folder Structure project/ │── data/ # Dataset │── notebooks/ # Jupyter notebooks │── src/ # Source code for training │── mlruns/ # MLflow experiment logs │── requirements.txt │── README.md

# 📊 Example MLflow Output

After training, MLflow logs:

Parameters: learning rate, batch size, etc.

Metrics: accuracy, precision, recall, etc.

Artifacts: model files, plots, confusion matrices.
