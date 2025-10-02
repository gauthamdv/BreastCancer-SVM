# 🎗️ Breast-Cancer-Classification-SVM

## 📝 Project Overview

This project classifies breast cancer tumors as **benign** or **malignant** using **Support Vector Machines (SVM)**. The dataset used is the **Breast Cancer Wisconsin (Diagnostic) dataset**.

Key objectives:

* 🧹 Data loading & preprocessing
* ⚡ Baseline and hyperparameter-tuned SVM models
* 📊 Model evaluation: accuracy, confusion matrix, classification report, ROC curves
* 🖼️ Visualization of decision boundaries using PCA
* 💾 Saving trained models for deployment

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/gauthamdv/BreastCancer-SVM.git
cd BreastCancer-SVM
pip install -r requirements.txt
```

---

## 🚀 Usage

### Jupyter Notebook

Run the interactive notebook:

```bash
jupyter notebook BreastCancer_SVM.ipynb
```

### Python Scripts

Run preprocessing and modeling scripts:

```bash
python data_preprocessing.py
```

---

## 📈 Results

Baseline and tuned SVM models test accuracies:

| Model                  | Baseline Accuracy | Tuned Accuracy |
| ---------------------- | ----------------- | -------------- |
| Linear SVM             | 96.50%            | 98.24%         |
| RBF SVM                | 97.36%            | 98.24%         |
| Polynomial SVM (deg=3) | 88.60%            | 93.85%         |

* Confusion matrices and ROC curves available in `plots/`
* PCA 2D projections show decision boundaries for each model

---

## 📂 File Structure

```
BreastCancer-Classifier/
├── datasets/             # CSV dataset files
├── plots/                # Plots: decision boundaries, confusion matrices, ROC curves
├── models/               # Saved trained SVM models
├── svm-classifier.ipynb  # Main notebook
├── requirements.txt      # Python dependencies
└── README.md             # Project description
```

---

**Author:** Gautham DV
**Happy Coding!** 🎉
