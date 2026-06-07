# Country Development Clustering 🌍

## What is this project about?
Every year, international organizations like the UN spend billions 
in foreign aid — but how do they decide which countries need help 
the most? This project uses machine learning to answer that question 
by grouping 165 countries based on their health, income, and economic 
indicators — with zero manual labeling.

## Dataset
Kaggle — Country Data (165 countries, 9 features)
Features include child mortality, income, GDP per capita, 
life expectancy, trade, inflation, and fertility rate.

## My Approach
1. Explored and cleaned the data
2. Scaled features using StandardScaler
3. Applied PCA to compress 9 features into 6 components 
   (retained 97% of information)
4. Used Elbow method to find the optimal number of clusters
5. Applied K-Means clustering
6. Visualized results using t-SNE
7. Analyzed each cluster to draw real world conclusions

## What I Found
After clustering, three distinct groups emerged:

- 🔴 Cluster 2 — Underdeveloped Countries
  High child mortality (~95), very low income ($3,539), 
  low life expectancy (59 years). These countries need aid urgently.

- 🟡 Cluster 0 — Developing Countries
  Moderate indicators across the board. Moving in the right 
  direction but still need support.

- 🟢 Cluster 1 — Developed Countries
  Low child mortality (~5), high income ($45,672), 
  high life expectancy (80 years). Stable and self sufficient.

## Why PCA?
With 9 features, there was risk of noise affecting clustering. 
PCA reduced this to 6 components while keeping 97% of the 
meaningful information — making K-Means more accurate.

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib

## What I learned
Choosing the right algorithm matters as much as the code itself. 
This project taught me when to use PCA, how to interpret 
clustering results, and most importantly — how to turn numbers 
into real world decisions.
