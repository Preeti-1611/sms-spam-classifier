#  Spam Email Classifier using TF-IDF & Naive Bayes

---

##  Project Description

This project is a Machine Learning based SMS/Email Spam Classifier built using:

- TF-IDF Vectorization
- Multinomial Naive Bayes
- Streamlit for deployment

The model achieved **97% test accuracy** and was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

---

##  Dataset

- SMS Spam Collection Dataset
- Total samples: 5169 (after cleaning)
- Imbalanced dataset (~12% spam)

---

##  Model Used

- TF-IDF (max_features=3000)
- Multinomial Naive Bayes
- Cross-validation performed

---

##  How to Run Locally

## 1️. Clone the Repository

```bash
git clone https://github.com/Preeti-1611/sms-spam-classifier.git
cd sms-spam-classifier

2. Create Virtual Environment
python -m venv venv
venv\Scripts\activate


3️. Install Dependencies
pip install -r requirements.txt

4️. Run the App
streamlit run app.py


## Model Performance

Train Accuracy: ~97.8%

Test Accuracy: ~97%

High precision for spam detection

 Tech Stack

Python

Scikit-learn

Pandas

Numpy

NLTK

Streamlit

 Author

Preeti Nagarale


