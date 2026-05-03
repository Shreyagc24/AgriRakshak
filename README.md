# 🌿 Crops Disease Detection System

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Model Accuracy](https://img.shields.io/badge/Model%20Accuracy-High-brightgreen)

---

## 📌 Project Overview

This project is a **Deep Learning and Vision transformer-based Crop Disease Detection System** that identifies diseases in crop leaves using image classification techniques. The system helps farmers and agricultural experts detect plant diseases early and improve crop yield using AI models.

---

## 🚀 Features

* Detects crop diseases from leaf images
* Built using Deep Learning (CNN / Vision Transformer models)
* Trained on agricultural image dataset
* Provides classification report and accuracy metrics
* Visual outputs like confusion matrix and ROC curve

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📁 Project Structure

```
Crops_disease_detection/
│
├── Train_plant_disease.ipynb
├── Test_Crops_Disease.ipynb
├── Vit_model.ipynb
├── cnn_crops_trained_model.keras
├── cnn_vit_crops_trained_model.keras
├── crops_trained_model.keras
├── classification_report_ieee.csv
├── confusion_matrix_ieee.png
├── roc_curve_ieee_clean.png
├── training_hist.json
├── train/   (dataset)
├── test/    (dataset)
├── valid/   (dataset)
└── README.md
```

---

## ⚙️ How to Run This Project

### 1️⃣ Clone the repository

```bash
git clone [https://github.com/Shreyagc24/AgriRakshak]
cd crops-disease-detection
```

---

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
```

Activate it:

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Add Dataset

⚠️ Dataset is not included due to large size.

Download dataset from your source and place folders like:

```
train/
test/
valid/
```

---

### 5️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:

* `Train_plant_disease.ipynb`
* `Test_Crops_Disease.ipynb`
* `Vit_model.ipynb`

Run cells step-by-step.

---

## 📊 Model Performance

* Training Accuracy: High (varies by model)
* Evaluation includes:

  * Confusion Matrix
  * ROC Curve
  * Classification Report

---

## 📈 Results

The model successfully classifies crop diseases with strong accuracy and can be used for agricultural decision support systems.

---

## 👨‍💻 Author

* Name: Shreya Garg, Shreya Saxena, Shalvi shrivastava, Ritik Chauhan
* College: Ajay Kumar Garg Engineering College (AKTU University)

---

## 📜 License

This project is for academic and educational purposes only.

---

## 🙌 Acknowledgement

Thanks to open-source datasets and deep learning libraries that made this project possible.
