# 📊 Income Predictor with EDA & Machine Learning

This project uses the `adult.csv` dataset to explore demographic factors and predict whether an individual's income exceeds $50K annually. It combines **exploratory data analysis (EDA)** and **machine learning (Random Forest Classifier)** for classification.

---

## 🔍 Dataset

- Source: UCI Machine Learning Repository
- 32,000+ samples with features like age, education, workclass, marital status, and occupation

---

## 🧪 EDA Tools

- `pandas`, `numpy`
- `matplotlib`, `seaborn`

**Highlights:**
- Age group binning (e.g. Youth, Adult, Senior)
- Correlation heatmap
- Feature importance analysis
- Income distribution & categorical analysis

---

## 🤖 Machine Learning

- Model: **Random Forest Classifier**
- Pipeline: Label encoding → train-test split → fitting model
- Metrics: Accuracy, Precision, Recall, Confusion Matrix

---

## 📁 Project Structure

data/
├── adult.csv # Original dataset

eda/
├── eda_analysis.ipynb # EDA notebook

model/
├── model_training.ipynb # ML notebook
├── income_model.pkl # Trained model

images/
├── charts and visualizations

---

## 📝 How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run eda.ipynb for data exploration

Run model_training.ipynb to train the model and save it

📸 Sample Output
Confusion Matrix

Classification Report

Feature Importance Bar Chart

👨‍💻 Author
Syed Muhammad Waiz Rizvi – AI Student @ UMT
📫 Contact: dragoXtrme666@gmail.com

---

### ✅ requirements.txt Example

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
