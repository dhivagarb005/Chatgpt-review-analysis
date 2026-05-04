# 🤖 ChatGPT Review Analysis using Python

## 📌 Project Overview
This project focuses on analyzing user reviews of ChatGPT using Natural Language Processing (NLP) techniques. The goal is to extract meaningful insights from textual data by performing sentiment analysis, subjectivity analysis, and keyword extraction.

---

## 🎯 Business Objective
To understand user satisfaction and answer:

- What sentiment do users express about ChatGPT?
- How strong or subjective are these opinions?
- What features do users frequently praise or criticize?

---

## 📊 Dataset Description
The dataset includes:

- Review ID  
- User Review (text)  
- Ratings (1–5)  
- Review Date  

Each row represents a user’s feedback along with a rating.

---

## 🧹 Data Preparation
- Standardized column names (lowercase & trimmed)
- Handled missing values (filled empty reviews)
- Converted ratings into numeric format
- Ensured clean and structured dataset

---

## 🧠 Sentiment Analysis
- Used **TextBlob** for NLP processing
- Extracted:
  - **Polarity** → measures positivity/negativity (-1 to 1)
  - **Subjectivity** → measures opinion vs fact (0 to 1)
- Classified reviews into:
  - Positive  
  - Neutral  
  - Negative  

---

## 📈 Exploratory Data Analysis (EDA)

### 🔹 Sentiment Distribution
- Majority of reviews are positive
- Indicates strong user satisfaction

### 🔹 Rating vs Sentiment
- Higher ratings align with positive sentiment
- Confirms consistency between user ratings and text feedback

---

## 📝 Text Analysis
- Extracted frequently used words from positive reviews
- Identified key terms like:
  - good  
  - best  
  - helpful  
  - app  

---

## ☁️ Word Cloud
- Visualized most frequent words in reviews
- Larger words indicate higher importance

---

## 📊 Key Insights
- Most users express **positive sentiment**
- Strong correlation between **ratings and sentiment polarity**
- Users appreciate:
  - Helpfulness  
  - Accuracy  
  - Ease of use  
- Some negative feedback highlights improvement areas

---

## 💡 Business Recommendations
- Focus on improving areas mentioned in negative reviews  
- Enhance features that users frequently appreciate  
- Continuously monitor user feedback for improvements  

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- TextBlob  
- Matplotlib  
- Seaborn  
- WordCloud  

---
## 👤 Author
Dhivagar B

---

## 🚀 Skills Demonstrated
- Data Cleaning  
- Natural Language Processing (NLP)  
- Sentiment Analysis  
- Data Visualization  
- Text Analysis  
- Data Storytelling  

---

⭐ If you found this project useful, consider giving it a star!
