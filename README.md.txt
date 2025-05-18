# 📘 Plagiarism Checker AI

This project uses machine learning to detect potential plagiarism between pairs of texts. It is built using Python and scikit-learn, and is trained on the **MIT Plagiarism Detection Dataset**.

---

## 📂 Project Structure

Plagiarism-Checker-AI/
│
├── train_snli.txt # Dataset file 
├── Plagiarism_Checker.ipynb # Main Jupyter Notebook with full pipeline
├── README.md # Project documentation
├── requirements.txt # List of required libraries
└── .gitignore # Files to ignore in the repo

---

## 📊 Dataset

- **Source:** [Kaggle - MIT Plagiarism Detection Dataset](https://www.kaggle.com/datasets)
- The dataset contains pairs of text samples and labels indicating whether the second text is plagiarized from the first.

---

## 🧪 Features

- Preprocessing of text data
- Vectorization using TF-IDF
- Model training using:
  - Logistic Regression
  - Support Vector Machine (SVM)
- Evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and classification report

---

## 🚀 How to Run

1. Clone the repository or download the files.
2. Open `Plagiarism_Detector.ipynb` using **Jupyter Notebook**.
3. Run the cells step-by-step:
   - Load and preprocess the dataset
   - Vectorize text
   - Train models
   - Evaluate accuracy
4. You can view model accuracy and predictions at the end.

---

## ✅ Results

- **Logistic Regression Accuracy:** 71.31%
- **SVM Accuracy:** 72.73%
- The SVM model performed better on the test set.

---

## 🛠️ Requirements

Install required Python libraries using:

```bash
pip install -r requirements.txt
