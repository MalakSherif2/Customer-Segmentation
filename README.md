📊 Customer Segmentation using Clustering Algorithms
📌 Project Overview

This project focuses on customer segmentation using unsupervised machine learning techniques.
The goal is to group customers based on their Annual Income and Spending Score to better understand purchasing behavior and identify valuable customer segments.

📁 Dataset

The dataset contains customer information including:

Annual Income

Spending Score

These features were used to perform clustering and analyze customer behavior.

🛠 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

📊 Project Workflow
1️⃣ Exploratory Data Analysis (EDA)

Visualized income vs spending behavior

Checked data distribution and relationships

2️⃣ Data Preprocessing

Applied MinMaxScaler to normalize features before clustering

3️⃣ Clustering Algorithms
✅ KMeans

Used Elbow Method to determine optimal number of clusters

Evaluated using Silhouette Score

✅ DBSCAN

Tested multiple eps values

Selected the best value based on highest Silhouette Score

Identified noise and non-linear cluster structures

📈 Model Evaluation

Elbow Method for optimal K selection

Silhouette Score for clustering quality comparison

🔍 Key Insights

Customers can be clearly segmented into groups based on income and spending behavior

High income & high spending customers represent premium target group

High income & low spending customers present marketing opportunities

DBSCAN helped detect outliers and non-spherical clusters

🚀 Conclusion

Clustering techniques successfully revealed meaningful customer segments.
KMeans provided well-separated groups, while DBSCAN offered additional insights by identifying noise points.

This project demonstrates practical application of unsupervised learning in customer analytics.

📌 Future Improvements

Include more customer features

Try hierarchical clustering

Apply dimensionality reduction (PCA)

Perform business-driven cluster profiling

👩‍💻 Author

Malak Sherif
Data Science Student
