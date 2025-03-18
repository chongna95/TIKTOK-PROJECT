## [TIKTOK PROJECT](https://github.com/chongna95/Google-Advanced-Data-Analytics-/tree/main/TikTok%20Project)

# 📊 TikTok Data Analytics & Engagement Prediction Project  

## 📌 Project Overview  
This project analyzes **TikTok data** to uncover **trending content patterns, user engagement metrics, and audience growth strategies**. Additionally, it includes a **Machine Learning model to predict engagement rates** based on video attributes. The goal is to provide **data-driven insights** into what makes content go viral on TikTok.  

## 🛠️ Technologies Used  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Data Visualization**: Tableau, Matplotlib, Seaborn  
- **Machine Learning**: Regression & Classification Models for Engagement Prediction  
- **SQL**: Querying structured TikTok datasets  


## 📊 Key Analysis & Insights  

### **1️⃣ Trend Analysis: Most Popular Hashtags**  
- Identified top **hashtags** associated with high engagement.  
- Used **word clouds** and **bar charts** to visualize frequently used hashtags.  

📌 **Example Visualization: Hashtag Frequency**  
```python
from wordcloud import WordCloud
import matplotlib.pyplot as plt

wordcloud = WordCloud(width=800, height=400, background_color="white").generate(" ".join(df['hashtags']))
plt.figure(figsize=(10,5))
plt.imshow(wordcloud, interpolation="bilinear")
plt.axis("off")
plt.title("Most Popular TikTok Hashtags")
plt.show()
```
🖼️ This visualization helps identify the most used hashtags in viral videos.


### **2️⃣ Engagement Metrics: Likes, Shares & Comments Analysis**
- **Calculated engagement rates** based on likes, comments, and shares.
- Identified patterns of **high-performing videos vs. low-performing videos**.
📌 **Example Visualization: Engagement Rate by Video Category**


