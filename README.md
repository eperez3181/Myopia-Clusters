# Unsupervised-Machine-Learning: Myopia Clusters
By: Estela Perez
## Background
The purpose of this assignment was to process raw data to fit the machine learning models. Several clustering algorithms were used to explore where the patients could be placed into distinct groups of patients that would be better to analyze separately. All in effort to predict myopia, or nearsightedness.
## Steps
#### Part 1: Prepared the Data
* Used Pandas DataFrame to read in the myopia.csv file
* Removed unecessary column from dataset
* Standardized dataset

#### Part 2: Applied Dimensionality Reduction
* Performed dimensionality reduction with PCA
* Reduced the dataset dimensions with t-SNE
* Created a scatter plot of the t-SNE output 
* ![image](https://user-images.githubusercontent.com/98370960/188077517-f1886009-9e10-4dfe-8316-f7473e2bce11.png)


#### Part 3: Performed a Cluster Analysis with K-means
* Created an elbow plot to identify the best number of clusters
* ![image](https://user-images.githubusercontent.com/98370960/188077642-00b39ff0-6caf-4f42-a837-1c57b500dbdb.png)


#### Part 4: Made a Recommendation
Based on the data findings, the patients would be able to be clustered. By looking at the scatter plot and elbow plot, I would recommend patients be placed into 5 clusters
