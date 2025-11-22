#  Instagram Performance Analysis  
*Exploratory analysis of Instagram post metrics*

This project provides a structured exploratory data analysis (EDA) workflow for understanding how different Instagram content features influence reach, impressions, and engagement.  
The analysis covers data cleaning, feature engineering, visual analytics, and performance insights.

---

##  1. Files Included

- **insta_analysis_.ipynb** — Main notebook containing all analysis steps  
- **Instagram data.csv** — Dataset used in the notebook  

---

##  2. Data Preparation

### **Loading & Preview**
- The dataset is loaded using pandas and previewed using `.head()`.

### **Data Cleaning**
- Removal of duplicates  
- Missing values check  
- Text cleanup and formatting  
- Conversion of numeric fields  

### **Feature Engineering**
- **caption_length** — Character count of each caption  
- **hashtags_count** — Number of hashtags used  
- Additional engagement-related features  

---

##  3. Visual Analytics

### **1) Distribution of Key Metrics**
Histograms for:
- Impressions  
- Likes  
- Comments  
- Saves  
- Shares  

---

### **2) Correlation Matrix Analysis**
Heatmap showing relationships between:
- Engagement metrics  
- Caption length  
- Hashtag count  
- Traffic sources  

---

### **3) Engagement vs Content Features**
Scatter plots analyzing:
- Caption length vs Engagement  
- Hashtag count vs Engagement  
- Hashtag count vs Impressions  

---

### **4) Performance by Traffic Source**
Analysis of sources such as:
- Home  
- Explore  
- Other  

Evaluating their effect on engagement and impressions.

---

### **5) Trend Analysis by Post Order**
Line charts showing how impressions and engagement evolve across posts.

---

### **6) Conversion Rates Analysis**
Visualizations for:
- Profile Visits / Impressions  
- Engagement Rate  

---

### **7) Top Performing Posts**
Highlights the highest‑engagement posts with comparisons across:
- Likes  
- Comments  
- Engagement  

---

##  4. How to Run

1. Open **insta_analysis_.ipynb**  
2. Ensure **Instagram data.csv** is in the same directory  
3. Run the notebook cells sequentially  
4. Adjust paths or column names if using different data  

---

## 5. Technologies Used

- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly.express  
- wordcloud  
