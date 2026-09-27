# 🧠 Parkinson's Disease Detection & Hand Tremor Analysis

A Graduation Project focused on **Parkinson's Disease detection and hand tremor analysis** using Machine Learning, Deep Learning, sensor data, and real-time signal processing.

The project contains multiple Machine Learning and Deep Learning models for analyzing tremor-related data and classifying different groups, including **Control, Parkinson's, and Voluntary** groups.

---

## 📌 Project Overview

The main goal of this project is to analyze hand movement and tremor signals and use Artificial Intelligence techniques to identify patterns that can help distinguish between different subject groups.

The project combines:

* 📊 Sensor Data Processing
* 🔬 Signal Processing
* 🤖 Machine Learning
* 🧠 Deep Learning
* 📈 Model Evaluation
* ⚡ Real-Time Prediction
* 📚 Medical Research
* 📉 Data Visualization

---

## 🏗️ Project Structure

```text
AI_Graduation_Project/
│
├── Abdelatef Osama Final New Model.ipynb
├── Abdelatef Osama Real Time Random Forest.ipynb
├── Abdelatef Osama Real Time SVM.ipynb
├── Abdelatef_Osama_Copy_of_Parkinson’s_Model (3).ipynb
│
├── ML/
│   ├── CatBoost/
│   ├── GB/
│   ├── KNN/
│   ├── LightGBM/
│   ├── RF/
│   ├── SVM/
│   └── XgBoost/
│
├── DL/
│   ├── CNN+LSTM/
│   ├── LSTM/
│   ├── MLP/
│   └── TabNet/
│
├── Results/
│   ├── DP/
│   └── ML/
│
├── Sensor Data/
│
├── Virtualization/
│
├── pklfilesnew/
│
├── scaler/
│
├── test/
│   ├── Control/
│   ├── Parkinson/
│   └── Voluntary/
│
├── Medical Researches/
├── Researches/
├── stablization/
│
├── requirements.txt
└── Colab Link.txt
```

---

## 🤖 Machine Learning Models

The project includes several Machine Learning algorithms:

* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Gradient Boosting
* XGBoost
* LightGBM
* CatBoost

These models are used for classification and evaluation of the collected and processed data.

---

## 🧠 Deep Learning Models

The project also contains Deep Learning approaches, including:

* LSTM
* CNN + LSTM
* MLP
* TabNet

These models are used to learn complex patterns from the processed sensor and tremor data.

---

## 📊 Dataset

The project works with sensor-based data related to hand movement and tremor analysis.

The available data is organized into different groups:

```text
Control
Parkinson
Voluntary
```

The repository also contains test datasets and processed sensor data.

> **Note:** The datasets included in this repository are intended for research and graduation-project purposes.

---

## ⚙️ Signal & Data Processing

The project uses several preprocessing and signal-processing techniques before training the models.

The Python implementation includes tools such as:

* Butterworth filtering
* Signal interpolation
* Data normalization
* Feature processing
* Feature selection
* SMOTE for handling class imbalance
* Train/Test splitting
* Group K-Fold Cross Validation

---

## 📦 Requirements

The main Python dependencies are listed in:

```text
requirements.txt
```

Install them using:

```bash
pip install -r requirements.txt
```

### Main Libraries

```text
NumPy
Pandas
SciPy
Scikit-learn
imbalanced-learn
Matplotlib
Seaborn
SHAP
Joblib

LightGBM
XGBoost
CatBoost

TensorFlow
PyTorch
PyTorch-TabNet
```

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AbdelatefOsama/AI_Graduation_Project.git
```

### 2. Navigate to the Project

```bash
cd AI_Graduation_Project
```

### 3. Create a Virtual Environment

Windows:

```bash
python -m venv .venv
```

Activate it:

```bash
.venv\Scripts\activate
```

Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Most of the project experiments are provided as Jupyter Notebook files.

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open one of the available notebooks, for example:

```text
Abdelatef Osama Final New Model.ipynb
```

or one of the real-time models:

```text
Abdelatef Osama Real Time Random Forest.ipynb
```

```text
Abdelatef Osama Real Time SVM.ipynb
```

---

## ⚡ Real-Time Prediction

The project includes notebooks for real-time prediction using trained Machine Learning models.

The available implementations include:

* Random Forest Real-Time Model
* SVM Real-Time Model

These notebooks are intended to demonstrate how the trained models can be used with incoming data for prediction.

---

## 💾 Trained Models

Pre-trained model files are stored in:

```text
pklfilesnew/
```

The directory contains trained models such as:

```text
best_cat.pkl
best_gb.pkl
best_knn.pkl
best_lgb.pkl
best_lstm.pkl
best_mlp.pkl
best_rf.pkl
best_tabnet.pkl
best_xgb.pkl
```

Deep Learning model files are also included.

---

## 📏 Model Evaluation

The project uses several evaluation metrics and visualization techniques, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Log Loss
* Average Precision
* Confusion Matrix
* ROC Curve
* Precision-Recall Curve

Results and visualizations are available inside:

```text
Results/
```

---

## 📈 Visualization

The repository contains generated plots and visualizations for the different Machine Learning and Deep Learning models.

These results can be found under:

```text
Results/ML/
Results/DP/
Virtualization/
```

---

## 🔬 Research

The project includes supporting medical and technical research papers related to:

* Parkinson's Disease
* Hand Tremor
* Tremor Detection
* Smart Gloves
* Machine Learning
* Deep Learning
* Signal Processing

Research materials are organized in:

```text
Medical Researches/
Researches/
```

---

## 🛠️ Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Main programming language |
| NumPy            | Numerical computing       |
| Pandas           | Data processing           |
| SciPy            | Signal processing         |
| Scikit-learn     | Machine Learning          |
| TensorFlow       | Deep Learning             |
| PyTorch          | Deep Learning             |
| XGBoost          | Machine Learning          |
| LightGBM         | Machine Learning          |
| CatBoost         | Machine Learning          |
| Matplotlib       | Visualization             |
| Seaborn          | Visualization             |
| SHAP             | Model explainability      |
| Jupyter Notebook | Experimentation           |

---

## 📂 Important Files

### Main Notebooks

```text
Abdelatef Osama Final New Model.ipynb
Abdelatef Osama Real Time Random Forest.ipynb
Abdelatef Osama Real Time SVM.ipynb
```

### Requirements

```text
requirements.txt
```

### Dataset

```text
Sensor Data/
test/
```

### Trained Models

```text
pklfilesnew/
scaler/
```

---

## ⚠️ Disclaimer

This project is developed for **academic and research purposes** as part of a graduation project.

The models and results presented in this repository should **not be considered a medical diagnosis or a replacement for professional medical advice**.

---

## 👨‍💻 Author

**Abdelatef Osama**

Cybersecurity | Penetration Tester | System Administrator | Bug Bounty Hunter | Backend Django  

GitHub:

https://github.com/AbdelatefOsama

---

## 📄 License

This project is intended primarily for educational and research purposes.

Please contact the author before redistributing or using the project commercially.
