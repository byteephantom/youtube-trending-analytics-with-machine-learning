# YouTube Trending Videos Analytics (500 mb Dataset) – End-to-End Data Analysis + ML

> This project analyzes of YouTube Trending data to uncover what makes videos viral using advanced EDA, NLP, visualization, SEO insights, and ML models.

---

**📌 Project Highlights**

- Cleaned & analyzed a massive 500 mb of Indian dataset
- Removed duplicates, converted Hindi → Hinglish titles
- Extracted keywords, bigrams, trigrams, clickbait patterns
- Built feature engineering: title_length, tags_count, publish_hour
- Category-wise & channel-wise insights
- Viral vs non-viral video comparison
- Built ML model to predict video views (R² ≈ 0.30)
- Extracted feature importances to understand what drives virality
- Created multiple visualizations for storytelling

---

**📊 Key Questions Answered**

- What type of videos become viral?
- Which categories dominate trending?
- Who are the most consistent creators?
- What upload time gives maximum views?
- What keywords/titles perform best?
- What factors (title, tags, time) influence video views?

---

**🔧 Tech Stack**

`Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, WordCloud, NLP, tqdm`

---

**🧠 Machine Learning Model**

- RandomForestRegressor
- Predicts video views using metadata
- Performance:
    * Test R²: ~0.30
    * Strong predictors:
      * Description length
      * Title length
      * Tags count
      * Upload hour
      * Category
      * Tags count
     
---

**📈 Visualizations**

- Category performance
- Channel ranking
- Keyword clouds
- Title pattern analysis
- Upload-hour heatmaps
- Trending duration visualization
- Feature importance chart
