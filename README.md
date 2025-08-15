# 📊 Campus Event Feedback Insights – Internship Project (Data Science & Analytics)

This project focuses on **analyzing and visualizing feedback from college events** to uncover satisfaction patterns, evaluate engagement, and recommend improvements.  

---

## 🎯 Project Purpose  
As part of my internship, I worked on transforming raw student feedback into meaningful insights by:  

- Measuring overall event satisfaction  
- Identifying sentiment trends (positive, neutral, negative)  
- Visualizing ratings and feedback in a clear format  
- Highlighting areas where future events can improve  

---

## 🗂️ Data Details  
- **Data Source:** Survey responses collected using Google Forms  
- **Format:** CSV export  
- **Included Fields:**  
  - Event Name  
  - Event Date  
  - Overall Rating (1–5 scale)  
  - What students liked most (text)  
  - Suggestions for improvement (text)  
  - Willingness to attend again (Yes/No)  
  - Additional notes or comments  

---

## 🛠 Tools & Technologies  
- **Python** – for analysis and processing  
- **Pandas** – data manipulation and preparation  
- **Matplotlib & Seaborn** – data visualization  
- **TextBlob** – sentiment analysis  
- **WordCloud** – graphical representation of feedback themes  
- **Google Colab / Jupyter Notebook / VS Code** – development environment  

---

## 🚀 Workflow Overview  

### 1. Data Cleaning  
- Removed incomplete or irrelevant responses  
- Filtered out empty text feedback entries  

### 2. Sentiment Processing  
- Calculated polarity for each comment  
- Classified results into Positive, Neutral, and Negative categories  

### 3. Visualization Creation  
- Plotted distribution of ratings  
- Created sentiment breakdown charts  
- Generated WordClouds for likes and improvement suggestions  

### 4. Insights Generation  
- Determined average ratings per event  
- Extracted common positive highlights  
- Pinpointed frequent improvement requests  

---

## 📈 Sample Results  
- **Average Rating:** 4.2/5  
- **Positive Feedback:** 72% of comments  
- **Top Suggestions:** Better scheduling, more event variety, improved sound system  

---

## 📝 How to Run the Project  

**Step 1 – Install Dependencies:**  
```bash
pip install pandas seaborn matplotlib textblob wordcloud
python -m textblob.download_corpora
```

**Step 2 – Open the Notebook or Script:**  
- **Jupyter / Colab:** `main.ipynb`  
- **Python Script:** `main.py`  

**Step 3 – Load the Dataset:**  
Place your survey file here:  
```
/data/feedback.csv
```  

---

## 📚 Skills Gained  
- Data cleaning & transformation techniques  
- Sentiment analysis using NLP (TextBlob)  
- Data visualization for survey data  
- WordCloud-based text analysis  
- Interpreting survey insights for decision-making  

---

## 🙌 Acknowledgements  
Internship completed at **FUTURE INTERNS** as part of the **Data Science & Analytics Internship Program**.  

---
