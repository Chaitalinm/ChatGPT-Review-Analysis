# ChatGPT-Review-Analysis
## Project Overview
This project analyzes **customer reviews of ChatGPT** to gain insights into user satisfaction and feedback trends.  
The analysis applies **Natural Language Processing (NLP)** for sentiment scoring and keyword/bigram extraction, combined with visualizations to highlight overall sentiment, rating patterns, and review themes.  

---

## Objectives
- Understand the **general sentiment** (positive, neutral, negative) expressed in reviews.  
- Measure the **strength of sentiments** using polarity scores.  
- Identify **frequently mentioned keywords** and **bigrams (two-word phrases)** to uncover praised or criticized features.  
- Explore **review trends over time** (monthly distribution).  

---

## Tools & Libraries
- **Python** (Pandas, NumPy)  
- **TextBlob** (Sentiment Analysis)  
- **NLTK** (Stopwords & Text Processing)  
- **Matplotlib & Seaborn** (Visualizations)  

---

## Project Workflow

### 1. Data Preparation
- Loaded dataset (`chatgpt_reviews.csv`) into Pandas.  
- Standardized column names for consistency.  
- Handled missing values (blank reviews).  
- Converted `review_date` to datetime (if available).  
- Ensured `ratings` were numeric.  

### 2. Sentiment Analysis
- Used **TextBlob** to compute **polarity scores**:  
  - `+1` → highly positive  
  - `-1` → highly negative  
- Categorized reviews into **Positive, Neutral, Negative**.  
- Visualized distributions:  
  - Sentiment count distribution.  
  - Ratings histogram.  
  - Polarity distribution.  

### 3. Text Analysis
- Tokenized reviews into words (excluding stopwords).  
- Extracted **top 20 frequent words (unigrams)**.  
- Extracted **top 20 frequent bigrams (two-word phrases)**.  
- Visualized results with bar plots.  

### 4. Time Trend Analysis
- If review dates available:  
  - Tracked monthly review volume trends.  
  - Displayed number of reviews per month.  

---

## Key Visuals
- Sentiment Distribution (Positive / Neutral / Negative).  
- Ratings Distribution.  
- Polarity Distribution.  
- Top Keywords (Unigrams).  
- Top Phrases (Bigrams).  
- Monthly Review Trends.  

---

## Results & Insights
- Majority of reviews are **positive**, showing high user satisfaction.  
- Common keywords highlight recurring themes (e.g., *useful, tool, great*).  
- Frequent bigrams capture feedback context (e.g., *great tool*, *slow response*).  
- Monthly trend analysis reveals review activity patterns over time.  

---

## Files in Repository
- `chatgpt_review_analysis.py` → main Python script.  
- `chatgpt_reviews.csv` → dataset (not included for privacy).  
- `README.md` → project documentation.  

---

## How to Run
1. Clone repository.  
2. Install requirements:  
   ```bash
   pip install pandas numpy matplotlib seaborn textblob nltk
   ```
3. Download NLTK stopwords:  
   ```python
   import nltk
   nltk.download('stopwords')
   ```
4. Run the script in Jupyter Notebook or Google Colab.  

---

## Key Skills Demonstrated
- Data Cleaning & Preprocessing  
- Sentiment Analysis (TextBlob)  
- NLP Tokenization & Stopword Removal  
- Keyword & Bigram Extraction  
- Data Visualization (Seaborn, Matplotlib)  
- Trend Analysis over Time  

---

## Author
Developed as part of a ChatGPT Review Analysis Project by [Chaitali More]
