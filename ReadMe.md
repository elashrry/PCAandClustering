I am trying to understand when I can safely conclude that there is no clustering in the data. I thought I can come up with examples where PCA can be misleading in expecting clusters in the data. 

The first example shows how we can not depend on PCA to say there is no clusters. It also shows that the default arguments of KMeans did not capture this sample situation quit well. 

It was hard to generate example where PCA shows clusters but there are none in the data. I think it can be tweaked to be more bizarre? 

Another interesting part was KMeans captures the "fake" clusters. I think it illustrates the classical issue of clustering analysis; it is very dependent on our interpretation of the data. A 2-dimensional U-shaped data will be considered two clusters by the KMeans algorithm, but it might not have a meaning, if it is a population density for example.  
