

##### Spark Processing

+ Spark uses clusters of machines to process big data by breaking a large task into smaller ones and distributing the work among several machines. Let’s look at how spark executes a spark application.

+ The secret to Spark’s performances is parallelism. 
  + Each parallelized action is referred to as a job. 
  + Each job is broken down into stages. Each job is broken down into stages, which is a set of ordered steps that, together, accomplish a job.
  + Tasks are created by the driver and assigned a partition of data to process. These are the smallest unit of work.

![SparkProcessing](/img/Spark_Processing.png)


##### Spark Cluster

![SparkCluster](/img/Spark_Cluster.png)
