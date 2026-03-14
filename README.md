# 🧠 Mental Health & Suicide Detection Using Social Media Posts
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
> An AI-powered system to detect suicidal tendencies and mental health issues from social media text using Machine Learning and Deep Learning.

---

## 👩‍💻 Team Members

| Name | Roll Number |
|------|-------------|
| P. Keerthana | CS23B1071 |
| S. Nagarani | CS23B1060 |

---

## 📌 Problem Statement

In today's digital world, individuals frequently express their emotions and struggles through social media. These posts often contain subtle linguistic cues indicating **mental distress, depression, or suicidal thoughts**. Manually identifying such signals is nearly impossible given the massive volume of unstructured online text.

This project develops an **AI-based system** that automatically detects suicidal tendencies and mental health issues from text posts, assisting in **early detection and prevention**.

---

## 🎯 Scope & Objectives

### Scope
- Analyze and clean social media text data related to mental health
- Apply NLP-based preprocessing and feature extraction
- Train and evaluate models to detect suicidal intent
- Develop a GUI for real-time prediction and user interaction

### Objectives
1. Preprocess and clean text data for accurate sentiment and intent detection
2. Extract linguistic and emotional features using **TF-IDF** and **sentiment scoring**
3. Train and evaluate multiple ML/DL models for classification
4. Integrate the best-performing model into an interactive GUI
5. Promote technology-assisted **mental health monitoring and suicide prevention**

---

## 🛠️ Tech Stack

| Layer | Tools / Libraries |
|-------|-------------------|
| Language | Python 3.8+ |
| NLP & Text Processing | NLTK, spaCy, re |
| Feature Extraction | TF-IDF, VADER Sentiment |
| ML Models | Logistic Regression, SVM, Random Forest, Naive Bayes |
| DL Models | LSTM, BiLSTM, BERT |
| Frameworks | scikit-learn, TensorFlow / Keras |
| GUI | Tkinter / Streamlit |
| Visualization | Matplotlib, Seaborn, WordCloud |

---

## 🗂️ Project Structure

```
mental-health-detection/
│
├── data/
│   ├── raw/                    # Original dataset
│   └── processed/              # Cleaned and preprocessed data
│
├── notebooks/
│   ├── 01_EDA.ipynb            # Exploratory Data Analysis
│   ├── 02_Preprocessing.ipynb  # Text cleaning and feature extraction
│   └── 03_Modelling.ipynb      # Model training and evaluation
│
├── models/
│   └── best_model.pkl          # Saved best-performing model
│
├── src/
│   ├── preprocessing.py        # Text cleaning pipeline
│   ├── features.py             # TF-IDF and sentiment features
│   ├── train.py                # Model training scripts
│   └── predict.py              # Inference logic
│
├── gui/
│   └── app.py                  # GUI application
│
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/mental-health-detection.git
cd mental-health-detection

# 2. Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the GUI application
python gui/app.py
```

---

## 📊 Methodology

```
Raw Text Data
     │
     ▼
Text Preprocessing
(Tokenization → Stopword Removal → Lemmatization → Cleaning)
     │
     ▼
Feature Extraction
(TF-IDF Vectors + VADER Sentiment Scores)
     │
     ▼
Model Training
(ML: Logistic Regression, SVM, Random Forest)
(DL: LSTM, BiLSTM, BERT)
     │
     ▼
Evaluation
(Accuracy | Precision | Recall | F1-Score | ROC-AUC)
     │
     ▼
Best Model → GUI Deployment
```

---

## 📈 Results

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | - | - | - | - |
| Random Forest | - | - | - | - |
| SVM | - | - | - | - |
| LSTM | - | - | - | - |
| BERT | - | - | - | - |

> *(Results will be updated after final evaluation)*

---

## 🖥️ GUI Preview

> *(Add a screenshot of your GUI here)*

```
[ Enter your text below ]
┌─────────────────────────────────────┐
│                                     │
│  Type or paste a social media post  │
│                                     │
└─────────────────────────────────────┘
         [ 🔍 Analyze ]

Result:  ⚠️  Suicidal Intent Detected  /  ✅ No Risk Detected
```

---

## 📁 Dataset

- **Source:** *(e.g., Kaggle - Suicide and Depression Detection dataset)*
- **Classes:** Suicidal / Non-Suicidal
- **Size:** *(mention number of records)*

> Due to the sensitive nature of the data, the dataset is not included in this repository. Please download it from the original source and place it in the `data/raw/` directory.

---

## ⚠️ Disclaimer

This tool is intended solely to **assist** researchers and mental health professionals — it is **not** a substitute for clinical diagnosis or professional mental health care.

**If you or someone you know is in crisis, please reach out immediately:**
- 📞 **iCall (India):** 9152987821
- 📞 **Vandrevala Foundation:** 1860-2662-345 (24/7)
- 🌐 **International Association for Suicide Prevention:** https://www.iasp.info/resources/Crisis_Centres/

---

## 📄 License

This project is for academic purposes only.

---

## 🙏 Acknowledgements

- Dataset providers and open-source NLP community
- Faculty mentors and department of Computer Science
