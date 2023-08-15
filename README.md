# shopping_mall-customer-segmentation using Azure


## Brief Summary 

Objective: Identify target Consumers by clustering analysis
• Analysed correlation between features & identified 4 as the optimal number of clusters using Elbow technique
• Deployed K-Means & K-Means++ clustering models with data preprocessing & PCA using Azure ML Designer
• Performed cluster profiling to identify target customers & marketing focus areas by analyzing purchasing habits



## Project Description
This study aims to divide mall customers into many groups according to factors like age, spending capacity, spending score, etc. This can give us valuable information about the needs of each group, allowing us to develop marketing plans and guidelines to maximise client spending.

## Tools Used:
1. Scikit learn library in python for implementing elbow method .
2. Pandas, numpy and matplotlib for data visualization and plotting.
3. Plotly for generating interactive graphs
4. Azure ML designer is used to apply data cleaning, PCA and apply Kmeans & kmeans++ clustering analysis and it is deployed to the real time analysis.
5. ![Screenshot (21)](https://github.com/meetj6897/shopping_mall-customer-segmentation/assets/101456221/6f750167-607d-42b0-b715-46ce316ac5eb)
![Screenshot (22)](https://github.com/meetj6897/shopping_mall-customer-segmentation/assets/101456221/86090942-8889-4c34-a060-c807133faa7e)
6. profiling cluster by analysing all the cluster with their feature
   ![image](https://github.com/meetj6897/shopping_mall-customer-segmentation/assets/101456221/e0e057f1-3ee3-46cb-a696-dad09e6e669f)



## Data
Data has been taken from kaggle dataset Mall Customer Segmentation Data, corresponding csv file is present in Data folder of this repo. Link to download data: 
(https://www.kaggle.com/code/karnikakapoor/customer-segmentation-clustering/input)

## Data Visualization
1. Histogram of individual features like age, sex, customer income and spending score is plotted to get idea of distribution.
2. Correlation and heat map are plotted to identify dependency between different features.
3. Bivariate analysis between gender vs. annual income and spending score using violin plot and box plot respectively.

## Clustering Algorithms Implemented
1. **Elbow technique** is used to find an optimal number of customers and clusters are generated using **K-means & K-means++** clustering.

## Conclusion
The customer's spending scores in the mall can be optimised by using the appropriate marketing tactics and policies (based on the segment in which the customer resides).
