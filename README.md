# 📊 User Engagement Analysis for **Restaurant Success**

## 📌 About Yelp  
Yelp is a web and mobile platform that functions as a crowd-sourced local business review site. Users can submit reviews, photos, and tips about businesses, while also browsing ratings and information shared by others.

---

## 🗂️ Agenda  
- Problem Statement  
- Research Objectives  
- Hypothesis  
- Data Overview  
- Analysis and Findings  
- Recommendations

---

## 🔍 Problem Statement  
In a competitive market like the restaurant industry, understanding factors that influence business success is crucial for stakeholders.  
Utilizing the Yelp dataset, this project investigates the relationship between user engagement (reviews, tips, and check-ins) and business success metrics (review count, ratings) for restaurants.

---

## 🎯 Research Objectives  
1. Quantify the correlation between user engagement (reviews, tips, check-ins) and business success indicators (review count, star rating).  
2. Analyze how sentiment influences review count and ratings.  
3. Explore trends in user engagement over time.  
4. Identify regional patterns and user-type differences (elite vs. non-elite).  
5. Determine peak user activity periods for restaurants.

---

## 🧪 Hypotheses  
- Higher levels of user engagement (more reviews, tips, and check-ins) correlate with higher review counts and ratings for restaurants.  
- Positive sentiment expressed in reviews and tips contributes to higher overall ratings and review counts.  
- Consistent engagement over time is positively associated with sustained business success.

---

## 📦 Data Overview  
- Dataset: Subset of Yelp data covering businesses across 8 metropolitan areas in the USA and Canada.  
- Source: Yelp Open Dataset (JSON format)  
- Files:  
  - `business.json`  
  - `review.json`  
  - `user.json`  
  - `tip.json`  
  - `checkin.json`  
- Stored into a SQLite database (`yelp.db`) for efficient querying and analysis.

---

## 📈 Analysis and Findings  

### ✅ General Business Metrics  
- Out of all businesses, ~35,000 are active restaurant businesses.  
- Ratings and review counts are not directly proportional — higher ratings do not guarantee more reviews and vice versa.  
- Review count reflects user engagement, but not necessarily customer satisfaction or performance.

### ⭐ Do higher ratings mean higher engagement?
- Engagement (reviews, check-ins, tips) increases up to 4-star rated restaurants.  
- 5-star businesses show lower engagement — possibly due to fewer but highly satisfied customers or selective clientele.

### 🔄 Correlation between Reviews, Tips, and Check-ins  
- Strong correlation observed between all three — higher activity in one correlates with higher activity in others.  
- Businesses should focus on driving all types of user engagement simultaneously.

### 📊 Engagement Difference: High vs. Low-Rated Businesses  
- Higher-rated restaurants see more reviews, tips, and check-ins.  
- Emphasizes the importance of delivering consistent service and experience.

### 🗺️ Success Metrics Across Cities  
- **Philadelphia** emerges as the top city with the highest success score.  
- Followed by **Tampa**, **Indianapolis**, and **Tucson**.  
- Suggests thriving restaurant cultures in these locations.

### 📅 Time-Based User Engagement Trends  
- Successful businesses show consistent engagement over time.  
- Trend and seasonality analysis reveals periodic spikes in user activity.

### 💬 Sentiment Metrics (Useful, Funny, Cool)  
- These labels reflect user feedback on review quality.  
- Higher counts suggest greater satisfaction and are strong success indicators.

### 🧑‍💼 Elite vs. Non-Elite Users  
- Yelp’s Elite users, though fewer, contribute a large portion of high-quality reviews.  
- Building strong relationships with elite users can foster loyalty and promote repeat visits.

### ⏰ Busiest Hours  
- Peak hours for user engagement: **4 PM to 1 AM**  
- Suggests focus on optimizing operations, staffing, and promotions during evening hours.

---

## ✅ Recommendations  

- Partner with Elite users to boost promotional efforts and reach.  
- Leverage peak hours for special offers and operational efficiency.  
- Less successful restaurants should work on improving review responses, service quality, and user engagement.  
- Consider expansion or strategic investment in top-performing cities.  

---

## 🙏 Thank You  
This project provides a data-driven foundation for understanding and improving restaurant success through user engagement. Feel free to explore the notebooks and insights further in the repository.
