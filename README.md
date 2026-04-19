# 📊 Sentiment Analysis on “AI Replacing Jobs” Tweets

---

## 📌 Objective
The objective of this assignment is to perform sentiment analysis on tweets related to the topic **“AI replacing jobs”** using machine learning techniques. The aim is to classify tweets into positive, negative, or neutral sentiments and evaluate model performance using precision and recall.

---

## 📌 Introduction
The topic chosen for this assignment is **“AI replacing jobs”**, which is highly relevant in today’s technological era. With the rapid growth of artificial intelligence, there is increasing debate about its impact on employment. Some people believe AI will create new opportunities, while others fear job losses, making it a suitable topic for sentiment analysis.

---

## 📂 Dataset
- Total Tweets: **100**
- Source: Manually created dataset inspired by real-world discussions
- Type: Text data (tweets)
- Labels:
  - Positive
  - Negative
  - Neutral

---

## 🔧 Data Collection & Preprocessing

### 🔹 Data Collection
A total of 100 tweets were manually created and curated to reflect realistic opinions about AI replacing jobs.

### 🔹 Preprocessing Steps
- Converted text to lowercase
- Removed punctuation, numbers, and special characters
- Cleaned unnecessary spaces

### 🔹 Data Labeling
Each tweet was manually labeled as:
- **Positive** → Supports or highlights benefits of AI  
- **Negative** → Expresses concern about job loss  
- **Neutral** → Balanced or unclear opinion  

---

## 🔀 Data Splitting
The dataset was divided into:
- **80% Training Data (80 tweets)**
- **20% Testing Data (20 tweets)**

This split ensures sufficient data for training while maintaining a separate dataset for unbiased evaluation.

---

## 🤖 Model Training & Classification

### 🔹 Classifiers Used
- Naïve Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  

### 🔹 Methodology
- Text data was converted into numerical format using **CountVectorizer**
- Models were trained using the training dataset
- Predictions were made on the testing dataset

### 🔹 Hyperparameters
- Logistic Regression: `max_iter = 200`
- Naïve Bayes & SVM: Default parameters

---

## 📊 Model Evaluation

### 🔹 Performance Metrics
- Precision
- Recall
- F1-score
- Accuracy

### 🔹 Results Summary

| Classifier            | Accuracy | Macro Avg Precision | Macro Avg Recall |
|----------------------|----------|--------------------|------------------|
| Naïve Bayes          | 0.75     | 0.79               | 0.69             |
| Logistic Regression  | 0.60     | 0.64               | 0.51             |
| SVM                  | 0.60     | 0.64               | 0.51             |

---

## 📈 Results & Observations

The results of the sentiment analysis show that:

- **Naïve Bayes performed the best**, achieving the highest accuracy of **75%**, along with better precision and recall compared to other models.
- **Logistic Regression and SVM performed similarly**, both achieving an accuracy of **60%**, but with lower recall values.
- The models performed well in predicting **positive sentiments**, but struggled more with **neutral and negative classifications**, which is common in small datasets.

Overall, Naïve Bayes proved to be the most effective classifier for this dataset due to its efficiency in handling text data.

The dataset reflects mixed public opinion about AI replacing jobs, with both positive and negative sentiments present.

---

## 📊 Visualizations

### 📌 Dataset Preview
<img width="1470" height="956" alt="dataset" src="https://github.com/user-attachments/assets/81a606bc-d23d-40c9-939e-604e00af5f4e" />


---

### 📌 Model Results (Precision, Recall, F1-score)
<img width="1118" height="1793" alt="results" src="https://github.com/user-attachments/assets/7d2f00cb-3f0d-417b-bf20-aa499e968135" />


---

## ⚠️ Limitations

- Dataset size is limited to 100 tweets
- Data is manually created and may not fully represent real-world diversity
- Contextual understanding (sarcasm, tone) is limited

---

## 🚀 Future Improvements

- Use real-time Twitter API for data collection
- Increase dataset size
- Apply TF-IDF or word embeddings
- Use advanced models like LSTM or BERT
- Perform hyperparameter tuning

---

## 🤖 AI Ethics & Responsible Usage Declaration

I hereby declare that:

- The dataset used in this assignment is ethically created and used.
- No personal or sensitive data is included in the dataset.
- The analysis was conducted responsibly for academic purposes only.
- AI tools were used only for guidance and learning support.

---

### Dataset Details:
- Source: Manually created dataset (inspired by public discussions)
- Type of Data: Text (tweets)
- Contains Personal/Sensitive Data? No

---

### Identified Bias:
The dataset may contain bias as it is manually created and may not fully represent real-world opinions.

---

### Responsible Usage Statement:
This project is intended for educational purposes only. The results should not be used for real-world decision-making.

---

## 📁 Repository Structure

```tree
sentiment-analysis/
├── tweets.csv
├── sentiment_analysis.ipynb
├── dataset.png
├── results.png
└── README.md
```
---

## 💻 Tools & Technologies Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- CountVectorizer

---

## 👨‍💻 Author

- Name: Mohmmed Aqeeb Pathan
- UIN: 242A003
- Course: TE-AI&DS
- Subject: Data Analytics and Visualization
- Date: -- -- --
