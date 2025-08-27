# 📊 ChatGPT Review Analysis

This project analyzes **customer reviews of ChatGPT** to understand user sentiment, extract key feedback, and visualize review trends.  
The analysis was implemented in **Google Colab** using `numpy`, `pandas`, `matplotlib`, `seaborn`, and `plotly`.

---

## 🚀 Project Objectives
- Analyze general **sentiment distribution** of reviews.  
- Compare **ratings vs. sentiment categories**.  
- Extract and visualize the **most common keywords** in reviews.  
- Identify **review trends over time** (monthly analysis).  

---

## 🛠️ Tech Stack
- **Python** (Data Analysis & Processing)
- **Libraries Used**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `plotly.express`
  - `collections.Counter`
  - `re` (Regex)

---

## 📂 Project Workflow

### 1️⃣ Data Preparation
- Load dataset (`chatgpt_reviews.csv`)  
- Standardize column names  
- Handle missing values in `review` column  
- Convert `review_date` to datetime  
- Ensure `ratings` column is numeric  

### 2️⃣ Sentiment Mapping
Reviews were categorized into:
- **Positive** → Ratings ≥ 4  
- **Neutral** → Rating = 3  
- **Negative** → Ratings ≤ 2  

### 3️⃣ Visualizations
- 📊 **Sentiment Distribution** (Seaborn & Plotly interactive)  
- ⭐ **Ratings Distribution** (Histogram)  
- 🔑 **Top 20 Frequent Keywords** (Bar plot using regex & Counter)  
- 📈 **Monthly Review Trend** (Line chart over time)  

---

## 📸 Sample Visualizations
1. Sentiment Distribution (Seaborn & Plotly)  
2. Ratings Histogram  
3. Top Keywords in Reviews  
4. Monthly Review Trends  

---

## ▶️ How to Run
1. Upload the dataset (`chatgpt_reviews.csv`) into Google Colab.  
2. Run the Jupyter Notebook / Python script step by step.  
3. Visualizations will be displayed inline & interactively (Plotly).  

---

## 📌 Insights
- **Most reviews are Positive** (ratings ≥ 4 dominate).  
- **Frequent keywords** reveal what users discuss most (both positive & critical).  
- **Trends over months** show how review volume changes with time.  

---

## 👤 Author
Developed as part of a **ChatGPT Review Analysis Project**
by *[Chaitali More]* ✨  
