# 📧 Spam Email Classification System

A machine learning-powered web application that predicts whether an email is **Spam** or **Not Spam**. This system utilizes natural language processing (NLP) techniques and a trained model to help detect spam messages in real-time.

## 🚀 Features

- 🧠 Trained ML model using TF-IDF and Naive Bayes.
- 🗃️ Cleaned and preprocessed email text using NLP techniques.
- 🌐 Interactive Web Interface built with **Streamlit**.
- 📈 Displays prediction with probability confidence.
- 💾 Option to save and view prediction history.

---

## ⚙️ Technologies Used

- Python
- Scikit-learn
- Pandas, NumPy
- Natural Language Toolkit (NLTK)
- Streamlit(for frontend)
---

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/spam-email-classifier.git
cd spam-email-classifier
```
2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the app**

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
spam-email-classifier/
│
├── app.py                  # Streamlit 
├── model/
│   └── spam_model.pkl      # Trained ML model
│
├── data/                   # Sample CSV/email dataset
├── README.md
└── screenshots/
    └── spam_classifier_ui.png
```

---

## 🔍 Sample Prediction

| Email Content                                 | Prediction | Confidence |
|----------------------------------------------|------------|------------|
| "Win a free iPhone today. Claim now!"         | Spam       | 98.6%      |
| "Your project meeting is scheduled tomorrow." | Not Spam   | 96.2%      |

---

## 🙋‍♂️ Author

- **Soumya Ranjan Mohanty** – [@Smohanty834](https://github.com/Smohanty834)
