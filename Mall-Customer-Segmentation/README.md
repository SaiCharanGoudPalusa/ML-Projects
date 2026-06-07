# Mall Customer Segmentation 🛒

## What's this about?
A mall has 200 customers but treats everyone the same way. 
This project finds natural customer groups using machine learning 
— so the marketing team can stop guessing and start targeting.

## Dataset
Kaggle — Mall Customers Dataset (200 rows, 5 features)
Age, Income, Spending Score, Gender

## What I did
- Encoded gender, scaled features
- Used Elbow method to find optimal K
- Applied K-Means clustering
- Visualized segments using t-SNE

## What I found
4 distinct customer types emerged:

- 🔴 Cluster 0 → Older Low Spenders — offer loyalty discounts
- 💜 Cluster 1 → High Earners, Low Spenders — target with premium products
- 🟢 Cluster 2 → Young High Spenders — flash sales, new arrivals
- 🔵 Cluster 3 → Young Moderate Spenders — engagement campaigns

## Tools
Python, Pandas, Scikit-learn, Matplotlib

## What I learned
Data never lies — even without labels, patterns exist if you know 
where to look. Building this made me think less like a coder 
and more like someone trying to solve a real business problem.
