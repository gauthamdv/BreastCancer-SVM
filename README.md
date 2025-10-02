# 🩺 Breast Cancer Detection with Support Vector Machines (SVM)

## 🚀 Project Overview

This project leverages Support Vector Machines (SVM) to classify breast tumors as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) dataset. The workflow encompasses:

* Data preprocessing
* Model training (baseline and tuned)
* Evaluation using metrics like accuracy, precision, recall, and F1-score
* Hyperparameter tuning with GridSearchCV
* Decision boundary visualization
* Model saving for deployment

---

## 🛠️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/gauthamdv/BreastCancer-SVM.git
cd BreastCancer-SVM
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Data

Run the preprocessing script to clean and prepare the dataset stored in the `datasets/` folder:

```bash
python data-preprocessing.py
```

### 4️⃣ Run the Notebook

Open `svm-classifier.ipynb` to:

* Train baseline and tuned SVM models

* Evaluate performance using accuracy, precision, recall, F1-score, and ROC curve

* Visualize decision boundaries

* Perform hyperparameter tuning with GridSearchCV

* **Data:** `datasets/`

* **Models saved in:** `models/`

* **Plots saved in:** `plots/`

---

## 📁 File Structure

```text
BreastCancer-SVM/
├── datasets/                  # Raw and processed datasets
├── models/                    # Saved models
├── plots/                     # Visualizations and plots
├── .gitignore                 # Git ignore file
├── README.md                  # Project documentation (this file)
├── data-preprocessing.py      # Data preprocessing script
├── svm-classifier.ipynb       # Jupyter notebook for SVM classification
└── requirements.txt           # Python dependencies
```

---

## 📊 Models & Evaluation

* **SVM Classifier:** Trained with linear and RBF kernels.
* **Hyperparameter Tuning:** Utilizes GridSearchCV for optimal parameters.
* **Evaluation Metrics:** Accuracy, precision, recall, F1-score, and ROC curve.
* **Visualization:** Decision boundaries plotted for better understanding of model performance.

---

## ⚡ Usage

1. Prepare the data using `data-preprocessing.py`.
2. Open and run `svm-classifier.ipynb` to train, evaluate, and tune SVM models.
3. Check saved plots and models in their respective folders.

---

## 🤝 Contributions

Contributions are welcome! Feel free to open a pull request or report issues.

---
