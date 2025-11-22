# Instagram Performance Analysis  
*A complete exploratory analysis of Instagram post metrics*

This project provides a structured exploratory data analysis (EDA) workflow for understanding how different Instagram content features influence reach, impressions, and engagement.  
The analysis covers data cleaning, feature engineering, visual analytics, and performance insights.

---

## 1. Files Included

- **insta_analysis_.ipynb** — Main notebook containing all analysis steps  
- **Instagram data.csv** — Dataset used in the notebook  

---

## 2. Data Preparation

### **Loading & Preview**
- The dataset is loaded using pandas and previewed with `.head()` for an initial inspection.

### **Data Cleaning**
- Detection and removal of duplicate rows  
- Missing values check  
- Cleanup and formatting of text fields  
- Conversion of numeric columns where needed  

### **Feature Engineering**
- **caption_length**: Length of each caption based on character count  
- **hashtags_count**: Number of hashtags extracted via string operations  
- Additional fields aligned with engagement metrics  

---

## 3. Visual Analytics

### **1) Distribution of Key Metrics**
Histograms are generated for major performance indicators:
- Impressions  
- Likes  
- Comments  
- Saves  
- Shares  

These help visualize the spread and skewness of engagement-related metrics.

---

### **2) Correlation Matrix Analysis**
A correlation heatmap explores relationships between:
- Impressions  
- Likes  
- Comments  
- Profile Visits  
- Follows  
- Caption Length  
- Hashtag Count  

This reveals which metrics move together and which have minimal interaction.

---

### **3) Engagement vs Content Features**
Scatter plots are used to evaluate how content structure affects performance:
- Caption length vs Engagement  
- Hashtag count vs Engagement  
- Hashtag count vs Impressions  

These visualizations help determine whether longer captions or more hashtags lead to better results.

---

### **4) Performance by Traffic Source**
Analyzes the impact of traffic sources such as:
- **From Home**  
- **From Explore**  
- **From Other**

Each is compared against engagement to see how user discovery paths affect reach.

---

### **5) Trend Analysis by Post Order**
Line plots illustrate how impressions and engagement evolve over time based on post index, identifying:
- Growth patterns  
- Performance decline  
- Seasonal or sequential behavior  

---

### **6) Conversion Rates Analysis**
Key conversion metrics are calculated and visualized:
- **Profile Visits / Impressions**  
- **Engagement Rate**  
- Other performance ratios  

Plots assist in understanding how efficiently impressions translate into deeper interactions.

---

### **7) Top Performing Posts**
The notebook identifies the top 10 posts based on overall engagement.  
Visual comparisons include:
- Engagement  
- Likes  
- Comments  

This section highlights the strongest-performing content patterns.

---

## 4. Key Insights

- Posts with higher saves and shares tend to drive significantly more impressions.  
- Engagement shows strong correlation with metrics like likes and shares.  
- Caption and hashtag patterns influence performance but show diminishing returns at higher values.  
- Traffic sources like Explore have a measurable impact on post reach.  

---

## 5. How to Run the Notebook

1. Download and open **insta_analysis_.ipynb**  
2. Ensure **Instagram data.csv** is in the same directory  
3. Run all cells sequentially in Jupyter Notebook or JupyterLab  
4. Modify the dataset path or column names if using different data  

---

## 6. Technologies Used

- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly.express  
- wordcloud  
