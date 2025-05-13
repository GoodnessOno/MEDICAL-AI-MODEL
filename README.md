# 🧠 Medical Diagnosis AI Model

This project is a machine learning-based medical diagnosis system designed to predict diseases based on symptoms using a Random Forest Classifier. The model was developed using real-world datasets during a volunteer project at a hospital to assist in early-stage diagnosis and triage support for low-resource clinical settings.

---

## 📊 Dataset

- **Source**: Structured CSV file with 17 symptom columns and one disease label.
- **Format**: Each row represents a patient case.
- **Target**: `Disease`
- **Features**: `Symptom_1` through `Symptom_17` (text values)

---

## 🔧 Features

- Converts raw symptom text into a binary feature matrix
- Trains a `RandomForestClassifier` on encoded features
- Outputs disease predictions with accuracy and detailed classification report
- Saves model, encoders, and feature transformers for deployment or future use

---

## 🧪 Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- MultiLabelBinarizer, LabelEncoder
- Jupyter Notebook / Google Colab

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/GoodnessOno/MEDICAL-AI-MODEL
cd medical-diagnosis-ai
pip install -r requirements.txt
