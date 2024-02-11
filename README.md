# clustering-assignment wine dataset

## Submitted By

**Name:** Sahil Manchanda  
**Roll no:** 102103134  
**Class:** 3CO5

## Overview

This project aims to implement various clustering algorithms using different pre-processing techniques and evaluate them on different parameters. The dataset used for this project is the Wine Dataset.

## Output
![sc1](/imgs/kmeanstable.png)
![sc2](/imgs/agglomtable.png)
![sc3](/imgs/dbscantable.png)

## Line Graphs
Line graphs were used to plot the variation of evaluation metrics (Silhouette Score, Calinski-Harabasz Score, Davies-Bouldin Score) across different subcluster sizes for each processing method. In this type of graph, each line represents a different processing method, and each subplot represents a different evaluation metric.

![sc4](/imgs/kmeansline.png)
![sc5](/imgs/agglomline.png)
![sc6](/imgs/dbscanline.png)


## Bar Graphs
Bar graphs were used to plot the average scores of each evaluation metric across different processing methods for each subcluster size. In this type of graph, each bar represents the average score of a particular metric for a specific processing method, and each subplot represents a different evaluation metric.

![sc1](/imgs/kmeansbar.png)
![sc1](/imgs/agglombar.png)
![sc1](/imgs/dbscanbar.png)


### Clustering Techniques

The clustering techniques used:

1. K Means Clustering
2. Agglomerative clustering
3. DBSCAN

### Evaluation Parameters

The performance of the clustering algorithms is evaluated based on:

- Silhouette Score
- Calinski-Harabasz Score
- Davies-Bouldin Score
