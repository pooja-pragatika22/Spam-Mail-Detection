
# 📧 Spam Mail Detection using Machine Learning

A machine learning project that classifies emails as **spam** or **ham (not spam)** using text classification techniques. The project includes preprocessing of raw email text and training different machine learning models using TF-IDF feature extraction.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pooja-pragatika22/Spam-Mail-Detection/blob/main/SPAM_MAIL_DETECTION_ML.ipynb)

---

## 📂 Files in this Project

| File                      | Description                                 |
|---------------------------|---------------------------------------------|
| `SPAM_MAIL_DETECTION_ML.ipynb` | Jupyter Notebook with complete code and explanations |
| `mail_data.csv`                | Dataset containing labeled email messages  |
| `requirements.txt`        | (Optional) List of Python libraries used   |

---

## 🧠 ML Models Used
- Naive Bayes (Multinomial)
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree

---

## 🛠️ Tech Stack / Libraries
- Python 🐍
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- `re` module (for text cleaning)
- `TfidfVectorizer` (from `sklearn.feature_extraction.text`)

---

## 🧪 Project Workflow
1. **Data Loading** – Load `mail_data.csv` dataset
2. **Preprocessing** – Remove special characters, lowercase conversion, clean text
3. **Feature Extraction** – Convert text to numeric using **TF-IDF**
4. **Model Training** – Train and evaluate classifiers
5. **Model Evaluation** – Accuracy, Precision, Recall, F1-score

---

## ✅ Results & Accuracy
- Achieved up to **97%+ accuracy** with **Multinomial Naive Bayes**
- Precision: High, ideal for spam detection scenarios

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/pooja-pragatika22/Spam-Mail-Detection.git
   ```
2. Navigate to the folder:
   ```bash
   cd Spam-Mail-Detection
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook SPAM_MAIL_DETECTION_ML.ipynb
   ```

---

## 📌 Dataset Source
- The `mail_data.csv` file contains SMS or email messages labeled as spam or ham.

---

## 👩‍💻 Author
**Pooja Pragatika Satpathy**  
*B.Tech Computer Engineering, Silicon University*

---

## ⭐️ If you like this project:
Give it a star ⭐ on GitHub to show support!
