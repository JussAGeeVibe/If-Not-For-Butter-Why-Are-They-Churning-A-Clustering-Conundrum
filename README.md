Customer Churn


If Not For Butter, Why Are They Churning? : A Clustering Conundrum

• Data set will be Telco Customer Churn  • Dataset contains 7042 rows with 21 columns of categorical and continuous data.

I sought to predict behavior to retain customers. Cleaned and engineered features based on categorical and continuous data. Imposed dimensionality reduction techniques and scaling before administering various clustering algos. Visualized the results to enhance the findings. 

Used Pandas, MatPlotLib, Seaborn, SKLearn, and Numpy. 
Clustering Algos: KMeans, Gaussian Mixture, Mean Shift, DBScan, and Agglomerative Hierarchical.

Included is a PowerPoint presentation of my findings.

I processed the data either leaving the numeric feautres as such or bucketing them accordingly. I found having all the features be catagorical yielded higher silhouette scores with reduced noise. When reducing the dimenions with FAMD, MCA, and t-SNE the best clustering algos were KMeans, Mean Shift, and DBScan.

Getting customers to sign contracts as opposed to month-month is the best way to minimize short term churn. The implementation of "mini-contracts" could be useful. Contracts of 3, 4 or 6 months. High initial fees that come with month-to-month can be daunting leaving the customer searching for alternatives every month. 