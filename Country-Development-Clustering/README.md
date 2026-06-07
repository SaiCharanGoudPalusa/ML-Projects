# Country Development Clustering 🌍

## What's this about?
Which countries need humanitarian aid the most? 
This project answers that using unsupervised machine learning 
— no labels, no guessing, just data.

## Dataset
Kaggle — Country Data (165 countries, 9 features)
Child mortality, income, GDP, life expectancy and more.

## What I did
- Scaled features, applied PCA (6 components, 97% variance)
- Used Elbow method to find optimal K
- Applied K-Means clustering
- Visualized using t-SNE

## What I found
3 clear groups emerged:

- 🔴 Cluster 2 → Underdeveloped — child mortality 95, income $3.5k
- 🟡 Cluster 0 → Developing — moderate across all indicators
- 🟢 Cluster 1 → Developed — life expectancy 80, income $45k

## Tools
Python, Pandas, Scikit-learn, Matplotlib

## What I learned
Choosing the right algorithm matters as much as the code itself. 
This project taught me when to use PCA, how to interpret 
clustering results, and most importantly — how to turn numbers 
into real world decisions.
