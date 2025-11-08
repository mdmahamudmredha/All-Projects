# 🧠 Data Science & Machine Learning Project Portfolio – Md Mahamud Mredha

Welcome to my personal project repository, where I showcase a curated collection of my end-to-end projects across various domains including Exploratory Data Analysis (EDA), Machine Learning (ML), SQL, Data Visualization, Statistical Inference, and  more.

This portfolio acts as a central hub for both technical and non-technical audiences to explore my problem-solving abilities, applied concepts, and storytelling skills through data. Whether you're a recruiter, collaborator, or curious learner — you'll find categorized, well-documented projects that reflect my journey and expertise in the field of Data Science & Machine Learning.

<p align="center">
  <img src="https://github.com/mdmahamudmredha/All-Projects/blob/main/image.png" width="1000"/>
</p>

---


## Student Exam Analytics Project using SQL, Power BI & Machine Learning  **![SQL](https://img.shields.io/badge/-SQL-blue)** **![Power BI](https://img.shields.io/badge/-Power%20BI-yellow)** **![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-brightgreen)** **![KMeans](https://img.shields.io/badge/-KMeans-orange)** **![EDA](https://img.shields.io/badge/-EDA-teal)** **![Clustering](https://img.shields.io/badge/-Clustering-purple)** **![Student Analytics](https://img.shields.io/badge/-Student%20Analytics-0057e7)** **![DAX](https://img.shields.io/badge/-DAX-black)**

**📁 GitHub Repo**:
[🔗 View Full Project](https://github.com/mdmahamudmredha/Student_Data_Query)
### Power BI Dashboard [Link](https://app.powerbi.com/view?r=eyJrIjoiMmVhZjExNDctOTM4Mi00ZDQ1LTllMTctODZiMjQ2OTRlMjM2IiwidCI6IjgxYmI4MGFlLTcxY2ItNDk4Yi05NGJiLThhNWNjMjljNDEzZCIsImMiOjEwfQ%3D%3D)
### Video Explanation [Click Here](https://drive.google.com/file/d/1WboLO3csXj5o_d6RC992LE1-rLUCYIzs/view?usp=sharing)
**Overview**
A complete end-to-end **Student Exam Analytics** project where performance data is analyzed using **BigQuery SQL**, **visualized with Power BI**, and extended with **clustering via Machine Learning**.

The project begins with deep **SQL-based EDA**, including custom metrics like actual mark calculation, pass/fail classification, performance trend tracking using `LAG()`, and ranking of top performers. It then transitions into **interactive dashboards** in Power BI to visualize attendance trends, performance changes, and pass rate over time.

Finally, the project applies **KMeans clustering** on student behavior (e.g., mark%, time taken) to segment students into groups like fast & accurate, slow but low scorer, etc. These segments offer valuable insights for educators to deliver **personalized feedback** and improve outcomes.

**Tools & Technologies**:
BigQuery SQL, Power BI, Python (Pandas, Scikit-learn), Jupyter Notebook

**Key Concepts**:
Student Performance Analysis, Exam Result Classification, Time-based Performance Trend, Clustering (KMeans), Business Intelligence, DAX Measures

**Techniques Used**:
* SQL Joins, Aggregations, Window Functions (`LAG()`, `RANK()`, `ROW_NUMBER()`)
* Percentage-based mark calculation
* Time duration handling using `TIMESTAMP_DIFF`
* DAX for day-wise, weekly trend visualizations
* KMeans Clustering on performance & behavior metrics
* Insightful labeling of clusters and interpretation

**Visuals in Power BI**:
* Day-wise Exam Attendance (Line Chart)
* Stacked Bar Chart: Daily Attempts by Exam
* Top 5 Students per Exam (Rank + Time)
* Performance Trend (Improved / Declined / Same)
* Decline-heavy Exams (Bar Chart)
* Most Improved in 2nd Attempt (Filtered Table)
* Cluster-based student categorization

**Clustering Insights**:
* Grouped students by speed and accuracy
* Interpreted behavior using average mark %, time taken
* Used results to suggest personalized student feedback

### 1. Day-wise Exam Attendance Trend

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Attendance%20by%20Week%20Days%20and%20Date.png" width="1000"/>
</p>

### 2. Stacked Bar Chart: Daily Attempts by Exam

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Stacked%20Bar%20Chart.png" width="1000"/>
</p>


### 3. Top 5 Students in Each Exam		

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Top%205%20Students.png" width="1000"/>
</p>


### 4. Performance Trend Categories (Improved / Declined / Same)
### 6. In which exams are students most likely to decline in performance?

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Trend%20%26%20Decline%20Analysis.png" width="1000"/>
</p>
				
### 5. Who improved the most in their second attempt?	

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Improve%20Attempts.png" width="1000"/>
</p>

### 7. Is there any correlation between exam date and pass rate over time?

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Pass%20Rtae.png" width="1000"/>
</p>

### Clustering

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/Cluster.png" width="1000"/>
</p>

## Clustering with Machine Learning Algorithm

<p align="center">
  <img src="https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Power%20BI%20Visualization/ML.png" width="1000"/>
</p>

**See All Steps** [Click Here](https://github.com/mdmahamudmredha/Student_Data_Query/blob/main/Machine%20Learning%20Clustering/Student%20Clustering.ipynb)

| Cluster | Student Count | Avg Duration (sec) | Avg Mark | % Mark   |
| ------- | ------------- | ------------------ | -------- | -------- |
| 0       | 82            | 601 (\~10 min)     | 18.17    | 74.88%   |
| 1       | 47            | 967 (\~16 min)     | 5.59     | 23.58%   |
| 2       | 90            | 1062 (\~18 min)    | 14.38    | 57.11%   |
| 3       | 81            | 515 (\~8.6 min)    | 10.37    | 43.01%   |


**Video Walkthroughs**:
* *  **Full SQL + Power BI + ML Concept Walkthrough (For Learners)**[Video Link](https://drive.google.com/file/d/1WboLO3csXj5o_d6RC992LE1-rLUCYIzs/view?usp=sharing)
* *  **Output + Insight Summary (For Recruiters / Business Users)**[Video Link](https://drive.google.com/file/d/1WboLO3csXj5o_d6RC992LE1-rLUCYIzs/view?usp=sharing)

**📁 GitHub Repo**:
[🔗 View Full Project](https://github.com/mdmahamudmredha/Student_Data_Query)

---

## Uber Ride Insights Dashboard
### Problem Statement Link [Click Here](https://github.com/mdmahamudmredha/Uber-Ride-Insights-Dashboard/blob/main/Problem%20Statement.pdf)
### Interactive Dashboard Link [Click Here](https://app.powerbi.com/view?r=eyJrIjoiYzZhMjQ0YmItOWYzMi00OTkwLTk1ZjMtYmI1YTlkZjMxZTBiIiwidCI6IjgxYmI4MGFlLTcxY2ItNDk4Yi05NGJiLThhNWNjMjljNDEzZCIsImMiOjEwfQ%3D%3D)
<p align="center">
  <img src="https://github.com/mdmahamudmredha/Uber-Ride-Insights-Dashboard/blob/main/Uber%20Ride%20Insights%20Dashboard.png" width="1000"/>
</p>

---

## Super store Sales Dashboard
### Power BI Dashboard Link [Click Here](https://app.powerbi.com/groups/me/reports/5d18f8ca-3254-4ad8-8c3b-609050a6910b/a828a5acdc7069096cd9?experience=power-bi)
<p align="center">
  <img src="https://github.com/mdmahamudmredha/Super-store-Sales-Dashboard/blob/main/Dashboad.png" width="1000"/>
</p>

---

##  Packaging Appeal vs. Purchase Behavior: A Data Science-Based Decision-Making Project  **![Data Science](https://img.shields.io/badge/-Data%20Science-004d00)**  **![#Pandas](https://img.shields.io/badge/-Pandas-teal)**  **![#Scipy](https://img.shields.io/badge/-Scipy-blue)**  **![#EDA](https://img.shields.io/badge/-EDA-orange)**  **![#Statistics](https://img.shields.io/badge/-Statistics-green)**  **![#BusinessIntelligence](https://img.shields.io/badge/-Business%20Intelligence-FF6D01?style=flat&color=white)**

**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/Packaging-Uniqueness-vs-Purchase-A-Data-Science-Based-Decision-Making-Project/tree/main)

**Overview**: A hypothesis testing project for a Dog Food company to determine if packaging uniqueness influences purchase decisions.

**Tools & Technologies**: Python, Pandas, Seaborn, Scipy

**Key Concepts**: Chi-Square Test of Independence, Categorical Data Visualization

**Techniques Used**: Cross-tabulation, Heatmaps, Countplots, Statistical Testing

**Video Walkthroughs**:  
-  **Full Code + Concept Explanation (For Learners)**: [Watch Here](https://youtu.be/vqXt1wZuaIk?si=byCFR5mYxtwTQQOV)  
-  **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/link_to_recruiter_friendly_video)

**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/Packaging-Uniqueness-vs-Purchase-A-Data-Science-Based-Decision-Making-Project/tree/main)

---

##  All Hypothesis Tests: A Complete Statistical Decision-Making Project **![#DataScience](https://img.shields.io/badge/-Data%20Science-004d00)** **![#Statistics](https://img.shields.io/badge/-Statistics-green)** **![#HypothesisTesting](https://img.shields.io/badge/-Hypothesis%20Testing-blueviolet)** **![#ParametricTests](https://img.shields.io/badge/-Parametric-orange)** **![#NonParametricTests](https://img.shields.io/badge/-Non--Parametric-teal)** **![#Pandas](https://img.shields.io/badge/-Pandas-150458)** **![#Visualization](https://img.shields.io/badge/-Visualization-0e8a16)**

**📁 GitHub Repo**:
[📂 View Project on GitHub](https://github.com/mdmahamudmredha/All-Hypothesis-Test-Projects/tree/main)

**Overview**:
A complete hypothesis testing project showcasing both parametric and non-parametric tests on numerical and Categorical datasets. This notebook demonstrates the logic, assumptions, and business implications of each test — helping learners and decision-makers understand where, why, and how to apply statistical testing in real-world contexts.

**Tools & Technologies**:
Python, Pandas, Seaborn, Matplotlib, Scipy, Statsmodels

**Key Concepts**:
Parametric vs Non-Parametric Testing, Assumption Checking, Normality Tests, Variance Tests, Central Tendency Tests, Association Tests

**Tests Covered**:

| Category         | Test Name                       | Purpose                                           |
| ---------------- | ------------------------------- | ------------------------------------------------- |
| ✅ Parametric     | Z-Test                          | Compare sample mean with known population mean    |
|                  | One-Sample T-Test               | Compare sample mean to expected mean              |
|                  | Independent T-Test              | Compare means of two independent groups           |
|                  | Paired T-Test                   | Compare means of the same group before vs after   |
|                  | One-Way ANOVA                   | Compare means across 3+ independent groups        |
|                  | Pearson Correlation             | Measure linear relationship between two variables |
| ✅ Non-Parametric | Mann-Whitney U Test             | Non-parametric alternative to independent t-test  |
|                  | Wilcoxon Signed-Rank Test       | Alternative to paired t-test                      |
|                  | Kruskal-Wallis H Test           | Alternative to ANOVA                              |
|                  | Spearman Rank Correlation       | Alternative to Pearson for non-normal data        |
|                  | Chi-Square Test of Independence | Association between two categorical variables     |
|                  | Levene’s Test                   | Test for equal variances between groups           |
|                  | Shapiro-Wilk Test               | Check for normality                               |

**📊 Techniques Used**:

* Distribution Plotting & Skewness Check
* Shapiro-Wilk & Levene's Tests for assumptions
* Grouping & Aggregation for comparisons
* Annotated heatmaps & countplots for categorical patterns
* Step-by-step statistical test applications
* Business-oriented interpretations and recommendations

**🎥 Video Walkthroughs**:

* 🎓 **Full Code + Concept Explanation (For Learners)**: [Watch Here](https://youtu.be/YOUR_MAIN_VIDEO_LINK)
* 🧠 **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/YOUR_SUMMARY_VIDEO_LINK)

**📁 GitHub Repo**:
[📂 View Project on GitHub](https://github.com/mdmahamudmredha/All-Hypothesis-Test-Projects/tree/main)

---

## 💼 RFM Segmentation: SQL-Based Customer Analytics Project **![SQL](https://img.shields.io/badge/-SQL-336791)** **![#EDA](https://img.shields.io/badge/-EDA-orange)** **![#CustomerAnalytics](https://img.shields.io/badge/-Customer%20Analytics-blue)** **![#BusinessIntelligence](https://img.shields.io/badge/-Business%20Intelligence-FF6D01?style=flat\&color=white)** **![#Segmentation](https://img.shields.io/badge/-Segmentation-teal)** **![#MySQL](https://img.shields.io/badge/-Customer%20Retention-green)**

**📁 GitHub Repo**:
[View Project](https://github.com/mdmahamudmredha/RFM-Analysis-with-MySQL/tree/main)

**🔍 Overview**:
A real-world SQL-based marketing analytics project where customers are segmented using the **RFM model** (Recency, Frequency, Monetary). This helps businesses identify champions, loyal users, at-risk customers, and more — using only **MySQL**.

**📌 Tools & Technologies**:
MySQL, SQL Views, Excel-based dataset

**📈 Key Concepts**:
Customer Segmentation, RFM Scoring, SQL Window Functions, Business Intelligence

**📊 Techniques Used**:
Date formatting, Aggregation, NTILE scoring, CASE logic for labeling segments

**🎥 Video Walkthroughs**:

* - 🎓 **Full SQL Script + Concept Explanation (For Learners)**: [Watch Here](https://www.youtube.com/watch?v=MnBbYINMbFc)
* - 🧠 **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/link_to_recruiter_friendly_video)

**📁 GitHub Repo**:
[View Project](https://github.com/mdmahamudmredha/RFM-Analysis-with-MySQL/tree/main)

---

## 🤖 RFM Segmentation using Python & K-Means Clustering Machine Learning Algorithm   **![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)**   **![#KMeans](https://img.shields.io/badge/-KMeans-orange)**   **![#CustomerAnalytics](https://img.shields.io/badge/-Customer%20Analytics-blue)**   **![#EDA](https://img.shields.io/badge/-Exploratory%20Data%20Analysis-yellow)**   **![#DataScience](https://img.shields.io/badge/-Data%20Science-black)**   **![#Segmentation](https://img.shields.io/badge/-Segmentation-teal)**

**GitHub Repo**
[👉 View Full Project on GitHub](https://github.com/mdmahamudmredha/Real-Life-Business-Analytics-Project-RFM-Based-Customer-Segmentation-Using-Machine-Learning)

**Overview**
A real-world **Python-based marketing analytics project** where customers are segmented using the **RFM (Recency, Frequency, Monetary)** model and then clustered using **K-Means**. This enables businesses to target specific groups like Diamond, Gold, Silver Customers, and high-value shoppers based on purchase behavior.

This project demonstrates how RFM and ML clustering can be combined to generate **actionable business insights** from raw transaction data.

**Tools & Technologies**
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (KMeans)
- Jupyter Notebook
- Dataset: Online Retail (CSV)

**Key Concepts**
- Customer Segmentation
- RFM Scoring & Clustering
- Business Intelligence
- Visual Analytics
- Data Preprocessing & Cleaning
- Interpretation of Clusters for Business Strategy

**Techniques Used**
- Handling Missing Values (CustomerID null logic)
- Feature Engineering: Recency (InvoiceDate), Frequency (InvoiceNo), Monetary (Quantity × UnitPrice)
- RFM Scoring (Log-transformed & scaled if needed)
- KMeans Clustering (with optimal k)
- Segment Labelling: Gold, Silver, Diamond using custom logic
- Insightful Features:
  - Revenue contribution by segment
  - Region-wise Diamond/Gold/Silver customers (pie chart)
  - CLV estimation
  - Churn risk detection
  - Monthly sales trend analysis

**Advanced Business Insights Extracted**
> We designed 15+ powerful analytics queries on top of RFM clusters, such as:
- What % of revenue comes from Diamond customers?
- From which regions do Diamond customers come?
- Which segment has the highest AOV?
- Are top 20% customers contributing to 80% of revenue?
- Month-over-month total sales trend

**Visual Snapshots**
- ✅ Region-wise customer pie charts
- ✅ Monthly sales line graph
- ✅ Boxplots by segment
- ✅ Top customer tables

**Video Walkthrough**
- 💡 **Full Concept + Code Explanation**: *Coming soon...*
- 🧠 Non-Technical Output Summary (For Recruiters): Watch Here

**📁 GitHub Repo**
[👉 View Full Project on GitHub](https://github.com/mdmahamudmredha/Real-Life-Business-Analytics-Project-RFM-Based-Customer-Segmentation-Using-Machine-Learning)

---

## People Flow Detection using Object Tracking & Heatmap Visualization  **![Computer Vision](https://img.shields.io/badge/-Computer%20Vision-004d00)**  **![YOLOv8](https://img.shields.io/badge/-YOLOv8-blue)**  **![Object Tracking](https://img.shields.io/badge/-Object%20Tracking-teal)**  **![ByteTrack](https://img.shields.io/badge/-ByteTrack-darkgreen)**  **![OpenCV](https://img.shields.io/badge/-OpenCV-red)**  **![Heatmap](https://img.shields.io/badge/-Heatmap-orange)**  **![Real-time Analytics](https://img.shields.io/badge/-Real--time%20Analytics-purple)**  **![Surveillance](https://img.shields.io/badge/-Surveillance-8B0000)**


**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/People-Flow-Detection-using-Object-Tracking-Heatmap-Visualization)

**Overview**:
A complete end-to-end computer vision solution to detect, track, count, and analyze people flow in a video feed. This project combines object detection (YOLOv8), tracking (ByteTrack), and spatial behavior analytics (heatmap) to support decision-making in areas such as retail analytics, public safety, and smart infrastructure.

**Tools & Technologies**:
Python, YOLOv8 (Ultralytics), ByteTrack, Supervision, OpenCV, NumPy, Matplotlib

**Key Concepts**:
Object Detection, Multi-Object Tracking, IN/OUT Line-Crossing Logic, Heatmap Generation, Video Frame Annotation

**Techniques Used**:

* YOLOv8 for real-time person detection (class 0 only)
* ByteTrack for unique identity tracking across frames
* Custom logic to detect IN and OUT movement across two virtual lines
* Gaussian-based movement heatmap visualization
* Video output with bounding boxes, object IDs, and live counters

**Video Walkthroughs**:

* **Full Code + Concept Explanation (For Learners)**: [Watch Here](https://youtu.be/link_to_your_full_code_video)
* **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/link_to_recruiter_friendly_video)

**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/People-Flow-Detection-using-Object-Tracking-Heatmap-Visualization)

---

##  NewsGuard-AI (FakeNewsDetector)  **![Machine Learning](https://img.shields.io/badge/-Machine%20Learning-004d00)**  **![#Pandas](https://img.shields.io/badge/-Pandas-teal)**  **![#EDA](https://img.shields.io/badge/-EDA-orange)**

**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/NewsGuard-AI/tree/main)

**Overview**: An AI-powered application that detects whether a news article is real or fake using Machine Learning.

**Tools & Technologies**: Python, Pandas, Scikit-learn, Vectorizer

**Video Walkthroughs**:  
-  **Full Code + Concept Explanation (For Learners)**: [Watch Here](https://youtu.be/)  
-  **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/)

**📁 GitHub Repo**: [View Project](https://github.com/mdmahamudmredha/NewsGuard-AI/tree/main)

---




