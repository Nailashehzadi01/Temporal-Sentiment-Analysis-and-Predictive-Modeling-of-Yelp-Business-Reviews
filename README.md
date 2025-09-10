# Temporal Sentiment Analysis and Predictive Modeling of Yelp Business Reviews  

## 📌 Overview  
This project analyzes **50,000 Yelp reviews (2005–2023)** to uncover temporal sentiment trends, predict business decline, and classify user behavior.  
By combining **NLP techniques** with **machine learning models**, it demonstrates how review data can provide **early warning systems** for businesses and deeper insights into evolving customer behavior.  

---

## 🎯 Key Features  
- **Temporal Sentiment Analysis** → Track how review sentiment changes over time  
- **User Behavior Classification** → Identify long-term reviewer patterns and behavioral shifts  
- **Business Decline Prediction** → Forecast early signs of business decline with high accuracy  
- **Hidden Sentiment Detection** → Found that **14% of 5⭐ reviews contained hidden negative sentiment**  
- **Impact of External Events** → Showed how **COVID-19 shifted focus to safety and delivery**  

---

## 🛠️ Technologies & Methods  

### 📂 Data  
- Yelp Academic Dataset (50,000 reviews, 2005–2023)  

### 🧠 NLP Techniques  
- **Sentiment Scoring**: VADER, TextBlob  
- **Topic Modeling**: TF-IDF, LDA  

### 🤖 Machine Learning Models  
- Random Forest  
- XGBoost  

### 📏 Evaluation Metrics  
- Accuracy  
- F1-score  
- ROC AUC  

### 📊 Visualization  
- Sentiment distribution  
- Temporal trends  
- PCA (dimensionality reduction)  
- Feature importance charts  

---

## 📊 Results  
- **Business decline prediction accuracy**: ~87%  
- **User behavior classification accuracy**: ~82%  

### 🔑 Key Findings  
- Sentiment decline occurs **6–9 months before rating drops**  
- **23% of active users became more critical post-2020**  
- Urban businesses dominate the dataset → **urban bias detected**  

---

## 📂 Repository Contents  
- `Complete Project code.ipynb` → Full analysis and modeling pipeline  
- `Project Documentation.docx` → Detailed methodology, findings, and references  
- `Presentation.pptx` → Project summary with visuals for quick understanding  

---

## 🚀 Future Work  
- Integrate external data (macroeconomic indicators, COVID-19 restrictions)  
- Apply advanced models (BERT, RoBERTa) for aspect-based sentiment analysis  
- Develop real-time dashboards (Streamlit / Plotly)  
- Cross-platform validation with TripAdvisor & Google Reviews  

---