I am trying to understand when I can safely conclude that there is no clustering in the data. I thought I can come up with examples where PCA can be misleading in expecting clusters in the data. 

The first example shows how we can not depend on PCA to say there is no clusters. It also shows that the default arguments of KMeans did not capture this simple situation quit well. To help get this extreme example, I did not scale the features. A good advice in general is to scale the variables, however, this is not always adivasble if the features have same scale, for example, exams scores. Thus, this example could be a valid reason not to trust the visualisation produced by PCA. 

It was hard to generate an example where PCA shows clusters but there are none in the data. I think it can be tweaked to be more bizarre? 

Another interesting part was KMeans captures the "fake" clusters. I think it illustrates the classical issue of clustering analysis; it is very dependent on our interpretation of the data. A 2-dimensional U-shaped data will be considered two clusters by the KMeans algorithm, but it might not have a meaning, for example, if it is a population density.  
