# 📊 Campus Event Feedback Review – Internship Project (Data Science & Analytics)

An analytical project to explore student feedback, uncover satisfaction trends, and identify actionable suggestions from survey responses.  

---

## 🎯 Aim of the Project  
This internship task focuses on evaluating opinions shared by students about various campus events to:  

- Measure overall satisfaction levels  
- Detect positive, neutral, and negative sentiment in comments  
- Present feedback trends visually  
- Suggest improvements for upcoming events  

---

## 🗂️ Data Overview  
- **Source:** Responses collected through Google Forms  
- **Export Format:** CSV file  
- **Fields Included:**  
  - Event Title  
  - Event Date  
  - Rating Scale (1 to 5)  
  - Favorite aspects of the event (text)  
  - Areas that need improvement (text)  
  - Willingness to attend again (Yes/No)  
  - Additional remarks  

---

## 🛠️ Tools & Technologies Used  
- **Python** – data processing and analysis  
- **Pandas** – data handling  
- **Matplotlib & Seaborn** – charts & graphs  
- **TextBlob** – sentiment classification  
- **WordCloud** – visualizing text highlights  
- **Google Colab / Jupyter Notebook / VS Code** – coding environment  

---

## 🚀 Process Flow  

### 1. Data Preparation  
- Remove incomplete entries  
- Eliminate empty feedback rows  

### 2. Sentiment Analysis  
- Check text polarity scores  
- Categorize as Positive, Negative, or Neutral  

### 3. Visualization  
- Plot rating distribution  
- Show sentiment breakdown  
- Generate WordCloud for favorite points  
- Generate WordCloud for improvement suggestions  

### 4. Insights  
- Calculate average rating per event  
- Identify recurring positive themes  
- Highlight top improvement requests  

---

## 📈 Key Outcomes (Sample)  
- **Average rating:** 4.2/5  
- **Positive sentiment:** 72%  
- **Frequent suggestions:** Better scheduling, wider variety of activities, improved audio setup  

---

## 📝 How to Execute  

**Step 1 – Install Required Packages:**  
```bash
pip install pandas seaborn matplotlib textblob wordcloud
python -m textblob.download_corpora
```

**Step 2 – Run the Notebook or Script:**  
- **Jupyter / Colab:** `main.ipynb`  
- **Python Script:** `main.py`  

**Step 3 – Place CSV Data:**  
Put your file at:  
```
/data/feedback.csv
```

---

## 📚 Skills Acquired  
- Data cleaning & preprocessing  
- Sentiment analysis using TextBlob  
- Basic NLP techniques  
- Data visualization (Matplotlib, Seaborn, WordCloud)  
- Survey-based analytics  

---

## 🙌 Credits  
Internship by **FUTURE INTERNS**  
Completed under **Data Science & Analytics Internship Program**  
