# shopping_mall-customer-segmentation


## Breif Summary 
1.Visualized data using Histogram, Pie Chart, and Box Plot & conducted hypothesis testing to study features correlation

2.Identified the optimal number of clusters as 5 clusters from both Elbow Technique and Dendrogram visualization 

3.Applied K Means Clustering & Hierarchical Clustering to form clusters based on the Input Features & Plotted in 2D, 3D


## Project Description
This study aims to divide mall customers into many groups according to factors like age, spending capacity, spending score, etc. This can give us valuable information about the needs of each group, allowing us to develop marketing plans and guidelines to maximise client spending.

## Tools Used:
1. Scikit learn library in python for implementing clustering algorithms.
2. Pandas, numpy and matplotlib for data visualization and plotting.
3. Plotly for generating interactive graphs

## Data
Data has been taken from kaggle dataset Mall Customer Segmentation Data, corresponding csv file is present in Data folder of this repo. Link to download data: 
https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python/download

## Data Visualization
1. Histogram of individual features like age,sex, customer income and spending score is plotted to get idea of distribution.
2. Correlation and heat map are plotted to identify dependency between different features.
3. Pie chart is used to identify percentage of male vs female customer count.
4. Bivariate analysis between gender vs. annual income and spending score using violin plot and box plot respectively.

## Clustering Algorithms Implemented
1. **Elbow technique** is used to find optimal number of customers and clusters are generated using **K-means** clustering.
2. **Hierarchial** is used for generating clusters, optimal number of clusters is obtained using **Dendogram** method.

## Conclusion
The customer's spending scores in the mall can be optimised by using the appropriate marketing tactics and policies (based on the segment in which the customer resides).
