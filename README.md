# Kmeans-clustering-using-Spark

C1 file - Contains randomly chosen centroids from available points<br/>
C2 file -  centroids are chosed such that they are father from each other<br/>
Data - All data points that needs to be clustered.<br/>

Algorithm - Use Eucledian and Manhattan distant measures and C1 and C2 files and compare which gives best result.<br/>
             In Each iteration assign point to the centroid that it is closer to, recompute centroid as mean of points in the cluster.<br/>
             Do this till the points no longer move much or do this for fixed number of iterations we choose.<br/>
             
