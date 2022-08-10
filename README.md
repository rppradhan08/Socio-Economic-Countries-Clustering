# **Humanitarian Aid to Underdeveloped Countries**[[src](https://www.kaggle.com/hellbuoy/pca-kmeans-hierarchical-clustering)]

## **Problem Statement**

HELP International is an international humanitarian NGO that is committed to fighting poverty and providing the people of backward countries with basic amenities and relief during the time of disasters and natural calamities. It runs a lot of operational projects from time to time along with advocacy drives to raise awareness as well as for funding purposes.

After the recent funding programs, they have been able to raise around $ 10 million. Now the CEO of the NGO needs to decide how to use this money strategically and effectively. The significant issues that come while making this decision are mostly related to choosing the countries that are in the direst need of aid.

## **Business Goal**

The job is to categorize the countries using socio-economic and health factors that determine the overall development of the country. Then we need to suggest the countries which the NGO needs to focus on the most.

## **Approach**

To determine the underlying countries multiple clustering algorithms were utilized to reach a final verdict. Initially, various attributes which measure countries overall growth were compared to get a higher level picture. At later stages algorithms like k-means and hierarchical were used to determine the optimal number of clusters. After comparing clusters based on GDP, child mortality, and avg_income, cluster-profiling was performed to determine the cluster which consisted of underdeveloped countries. Finally, the top_5 countries were shortlisted for aid.

## **Steps Involved**

1. Reading and understanding data

2. Data Formatting

3. Performing EDA
4. Data Preparation for clustering

- Outlier Treatment
- Performing Scaling
- Hopkins Check

5. Clustering using K-Means and Hierarchical Clustering

- K-Means Clustering:

  - Choose optimal value of K
  - Run K-means using optimal K
  - Visualize Clusters
  - Cluster profiling using "gdpp","child_mort" & "income"

- Hierarchical Clustering:

  - Plot dendrogram using single and complete linkage
  - Choose optimal linkage
  - Visualize Clusters
  - Cluster profiling using "gdpp","child_mort" & "income"

6. Country Recommendation

For detailed explaination and analysis please refer `Clustering_Assignment.ipynb` 
