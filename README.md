# Images Compressing With The K-Means & Clustering With Scipy




### Dataset
* For the first one we use two images ``image.jpg`` and  ``image2.jpg`` for testing image compressing.
* For the second example we use ``fromage.txt``, it's a small dataset for testing the clustering using ``scipy packages``.





### K-Means Algorithm
Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the inter-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.
The way kmeans algorithm works is as follows:

* Specify number of clusters K.
* Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.
* Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.




### Requirements
- Python 3.7




### Installation
- Get the package from PyPi :
- All requirement that you will need its exist in ``requirements.txt`` so you just need to run this command :
```
!pip install -r requirements.txt
```



### Test
Congratulation.
- Open the notebook ```main.ipynb``` and edit it as you want.<br/>

- [main.ipynb](main.ipynb)




## Authors
* **El Houcine ES SANHAJI** - *Initial work* - [essanhaji](https://github.com/essanhaji)




## Thank you.
