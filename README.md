# customer-segmentation-and-analytics

## Project Overview
This project segments banking customers into groups using K-Means Clustering.  
It helps banks understand customer behavior and target campaigns more effectively.

## Business Context
Banks often run large-scale marketing campaigns.  
Clustering customers allows them to:
- Personalize offers  
- Identify high-value customers  
- Improve campaign success rate  

## Technologies & Libraries
- Python (Pandas, NumPy, Scikit-learn)
- K-Means Clustering
- PCA (Principal Component Analysis)
- Seaborn & Matplotlib for visualization

## Dataset
Dataset: [Bank Marketing Dataset (UCI/Kaggle)](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing)  
- Features used: `age`, `duration`, `campaign`, `pdays`, `previous`  
- Rows: ~40K marketing records  
- Target: Not supervised (unsupervised clustering)

## Steps Implemented
1. Loaded dataset with proper separator (`;`)  
2. Selected numeric behavioral features  
3. Scaled data with StandardScaler  
4. Applied PCA (reduced to 2D for visualization)  
5. Applied K-Means (k=3 clusters)**  
6. Analyzed clusters & visualized with scatter plot  

## Results
- Identified 3 customer groups with distinct behaviors  
- Example:  
  - Cluster 0 → Younger, lower balance, frequent campaigns  
  - Cluster 1 → Middle-aged, stable duration, fewer contacts  
  - Cluster 2 → Older, higher previous contacts, more engaged  


