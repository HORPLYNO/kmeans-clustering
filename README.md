# kmeans-clustering
Customer segmentation project using K-Means clustering to group users based on income, spending habits, loyalty score, and purchase frequency. Developed as part of the FlexiSAF Generative AI and Data Science Internship. 
🗂️ Dataset
Source: Kaggle 

Features used:

age

annual_income

purchase_amount

loyalty_score

purchase_frequency

🧪 Project Workflow
Data Preprocessing

Checked for missing and duplicate values

Scaled numerical features using StandardScaler

K-Means Clustering

Chose optimal number of clusters using the Elbow Method

Clustered customers into 3 distinct groups

Evaluation

Used Silhouette Score to evaluate clustering performance

Score: 0.56 indicating moderately good clustering

Visualization

Plotted clusters to understand customer groupings

Interpreted relationships between features like age and frequency

📈 Key Insights
Cluster 0: Low income, low loyalty, and low spending

Cluster 1: High income, high loyalty, and high spending

Cluster 2: Moderate behavior across features

✅ Tools & Libraries
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

📌 Objective
To help businesses understand customer segments and enable more personalized marketing strategies.
 
