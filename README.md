# NHOC
Noval Approach on Tuning of Hadoop's confirguation
 
     In this project, an approach called RFHOC to automatically tune the Hadoop
configuration parameters for optimized performance for a given application
running on a given cluster. RFHOC constructs two ensembles of
performance models using a random-forest approach for the map and reduce
stage respectively. Leveraging these models, RFHOC employs a genetic
algorithm to automatically search the Hadoop configuration space. The
evaluation of RFHOC using five typical Hadoop programs, each with five
different input data sets, shows that it achieves a performance speedup by a
factor of 2.11_ on average and up to 7.4_ over the recently proposed costbased optimization (CBO) approach. In addition, RFHOC’s performance
benefit increases with input data set size.

     Map Reduce is a widely used programming model for processing and
generation vast data sets on large scale compute clusters. The Hadoop
framework has up to 190 configuration parameters, and overall performance
is highly sensitive to the settings of these parameters. 
