# Community_Clustering

* The repository code is an analysis of all the available features accumulated after merging data(on county level) from all the available sources.
* Here Clustering has been applied to group the data into groups . These groups are then analysed to find out the most important features contributing towards their grouping  i.e. which features are responsible for presence of any data piunt in one of the given groups.

##### The different clusters obtained are used as class labels for the data points and a supervised analysis if done to check the performance. 

Below image shows classification report for clustering with 4 different clusters.

![Classification_Report](https://github.com/community-insight-impact/community_clustering/blob/main/plots/classification_report.png)

* Then PCA is applied to get a better view at the clusters formed. Here are the clusters formed.

![Clusters](https://github.com/community-insight-impact/community_clustering/blob/main/plots/PCA_clusters.png)

# Some of the features of individual clusters are:

### Cluster 1: 
1. People in this group have lost a high amount of their days from what their previous life expectancy could be. 
2. There are more womens in this group who don’t have very long commutes and are also not affected much by housing problems. 
3. The death rates are moderate with less children dying than people with drug-overdose. 
### Cluster 2: 
1. This cluster has an almost equal number of males and females who take shorter commutes alone.
2. People face a little housing issues and the group has the most percentage of people having insurance.
3. Death rates are higher than cluster 1 but people have only lost a small amount of their previous life expectancy.
### Cluster 3: 
1. Females make up most of this cluster with severe housing problems and having to commute over longer distances.
2. This group has a very high death rate ( highest among all) . It has a high Chlamydia Rate with a large section of death resulting from drug overdose.
3. Strangely enough, the high death rates have not caused a significant decrease in the life expectancy of people.
### Cluster 4: 
1. This group consists more of males who are American Indian & Alaskan Natives.
2. It has low housing problems with no major disease outbreak like Chlamydia. It has a lot of outliers for multiple features.
3. It has a low death rate with people requiring shorter commutes.


*Note For more detauls and future tasks , Please have a look at the report.*

[Report](https://docs.google.com/document/d/1-B7UhoqtiWot8Nsn-yXmEL4q5ZBQ3GhHWzt29ip_hM0/edit?usp=sharing)
