
# Parkinson's Disease Prediction Using Machine Learning

This project focuses on the early detection of **Parkinson's Disease** using machine learning techniques. It uses a dataset of biomedical voice measurements and trains classification models to distinguish between healthy individuals and those with Parkinson's disease.

---

## Project Structure

- `PD.ipynb` – Jupyter Notebook containing exploratory data analysis, feature selection, model training, and evaluation.
- `Parkinsson disease.csv` – Dataset of voice measurements used for model training.
- `LICENSE` – MIT License file for open-source distribution.
- `README.md` – Project overview and documentation (you are here).

---

## 📊 Dataset

The dataset includes biomedical voice measurements from people with and without Parkinson’s disease.  
It contains features such as:
- Average vocal fundamental frequency
- Jitter and shimmer measures
- Harmonic-to-noise ratio
- Recurrence period density entropy
- Spread, D2, and PPE

**Target Column:** `status`  
- `1` = Parkinson's Disease  
- `0` = Healthy Control

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/parkinsons)

---

## Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting Classifier
- Evaluation with metrics: accuracy, confusion matrix, precision, recall, F1-score

---

## 🚀 How to Run

1. Clone the repository.
2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
3. Open and run `PD.ipynb` in Jupyter Notebook or Google Colab.

---

## 📈 Results

The notebook includes performance comparison of multiple classifiers. It visualizes:
- Feature importance
- Model accuracy
- Confusion matrices for each algorithm

---

## 📌 Features

- 🧪 EDA and correlation heatmap
- 📉 Feature selection based on variance and correlation
- 🤖 Multiple ML classifiers compared
- 📊 Visual evaluation of predictions

---

## ✅ Requirements

- Python 3.7+
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 📚 License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to contribute or share feedback!
