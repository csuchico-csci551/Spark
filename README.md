# Apache Spark
Apache Spark is an open-source distributed general-purpose cluster-computing framework. Spark provides an interface for programming entire clusters with implicit data parallelism and fault tolerance.[1] It is an alternative parallel programming approach that is regularly used in "Big Data" applications. The goal of this assignment is to give you some experience with an alternative to cluster programming with MPI.

## Project Requirements.

Spark is commonly used to simplify and distribute making sense of large data sets across a cluster of computers. To gain some familiarity and experience with this, you will need to do the following:

1. Find a large/massive dataset, ideally of something that you might be curious/interested in.
  * An example would be from one of these JSON data sets from the US Government:
    * https://catalog.data.gov/dataset?res_format=JSON
2. Write a simple Spark application, I would recommend in **pyspark**, that aggregate the data into a simpler form. Like taking all of the temperature data from the world and simplifying it down to the average temp of the earth for each month.
3. Graph your simplified data and write up a short discussion of how you can now make generalizations from this data reduction.
4. Contrast writing Spark code vs MPI code. Write this contrast up into a short report.
  * Was it easier or harder to write?
  * Are the goals the same?
  * What would be easier with Spark than MPI?
  * What would be harder with Spark than MPI?
  * etc.


### Running Project

If you aren't using a [NVidia Jetson Nano Cluster](https://github.com/csuchico-csci551/JetsonCluster) with Apache Spark. You can alternatively use [Apache Spark on Amazon EMR](https://aws.amazon.com/emr/features/spark/) or [Apache Spark on GCP](https://cloud.google.com/dataproc/). There may be other providers of Apache Spark.

## Project Deliverables

Submit a tar.gz file to Tyson's turnin system with the following.

* Datasource being by your Apache Spark application
* Apache Spark code
* Report with:
  * data results/conclusions from the Spark application
  * Contrast of Spark vs MPI

## Evaluation

The assignment value will be broken down by the following:

* 10 - Data source
* 40 - Apache Spark code compiles/runs generating results
* 25 - Report details on results/conclusion from the data results of your spark code.
* 25 - Report conclusions contrasting MPI & Spark.

[1]: https://en.wikipedia.org/wiki/Apache_Spark
