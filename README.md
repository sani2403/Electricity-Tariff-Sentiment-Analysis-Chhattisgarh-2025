# ⚡ Survey-Based Sentiment Analysis on Increased Electricity Tariffs
The state of Chhattisgarh has announced new electricity tariffs for 2025–26, effective July 1, 2025, raising domestic rates by ₹0.10–0.20 per unit and impacting nearly 60 lakh consumers. Alongside the tariff hike, the state has introduced specific rebates, such as concessions for mobile towers in LWE-affected areas and hospitals in rural regions.

This project analyzes **public sentiment and opinion** regarding the **increase in electricity tariffs** through a **survey-based study** conducted via **Google Forms**.  
The responses were primarily **Likert-scale based (Strongly Agree → Strongly Disagree)**, providing a quantitative measure of sentiment and opinion trends.  

In addition, open-ended feedback was processed using **Natural Language Processing (NLP)** techniques to generate **word clouds** and **heatmaps**, offering a visual interpretation of the most common themes and emotions expressed by participants.

---

## 🎯 Objectives
- Collect survey responses on public perception of electricity tariff hikes.  
- Analyze **Likert-scale sentiment trends** statistically.  
- Apply **basic NLP** for open-text comments to extract key themes.  
- Visualize insights using **heatmaps**, **word clouds**, and **sentiment charts**.  
- Derive actionable insights to understand consumer sentiment toward tariff changes.

---

## 🧩 Features
- 📊 Import survey data directly from Google Forms (CSV/Excel).  
- 🧮 Analyze **Likert-scale responses** using descriptive statistics and visual plots.  
- ☁️ Generate **Word Clouds** from text feedback using NLP tokenization and frequency analysis.  
- 🌡️ Create **Heatmaps** to show sentiment intensity across questions.  
- 📈 Visualize findings through bar charts, pie charts, and correlation matrices.  
- 🧠 Export analyzed data and visuals for reporting or dashboards.

---

## 🧠 Tech Stack
**Languages:** Python (3.10+)  
**Environment:** Jupyter Notebook / Google Colab  

**Libraries:**
- `pandas`, `numpy` – Data cleaning and statistical analysis  
- `matplotlib`, `seaborn`, `wordcloud` – Visualization and heatmaps  
- `nltk` – Text preprocessing for word cloud generation  
- `scikit-learn` – Optional utilities for encoding and scaling  
- `tqdm` – Progress tracking in data operations  

---

<p align="center">
  <img src="visuals/feeling_about_tariff.png" alt="Sentiment Distribution" width="500"/>
</p>

---

### 🔹 Word Cloud

Frequently used terms include **bill, inflation, burden, government, affordability**.  

<p align="center">
  <img src="visuals/wordcloud.png" alt="Word Cloud" width="500"/>
</p>

---

### 🔹 Key Insights

* Tariff hikes are perceived as a **financial burden** by most households.  
* Neutral perspectives consider them a **necessary step** for infrastructure improvement.  
* Very few participants had **positive outlooks**, conditional on **better service delivery**.  

---

## 🔮 Future Scope

* Apply advanced transformer-based models (e.g., BERT, mBERT) for multilingual sentiment analysis.  
* Expand survey coverage across more states and demographics.  
* Develop a **Streamlit dashboard** for real-time visualization.  


