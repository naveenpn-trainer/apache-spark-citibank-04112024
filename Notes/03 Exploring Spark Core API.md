# Exploring Spark Core API (RDD's)

> Resilient Distributed Data is a fundamental data structure of apache Spark

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe4gfoISkgoeB4GpRPyi7w1cT0v7UET4p-2PzhHZvWgnM-izDgOztq5EoLk9-L3D88M8CVotofD7XDElWFY9dfme57LP6H2B__BWLY7Ib_D0RTspAl6LNSJKzNwmWpmReep1bqn1tDfj6jtvPFTdVerCjg?key=_he-T4Jq934AhrSZa-Be-g)

## Partitions

> RDD is nothing but collection of partitions

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdhOzzgMVt_1HAGOVI0Pb-cIFRwXDpvkPIa8xlHZhlI1gxys1rm5LThStyB3xcRRHuy5mUw8V_JbOji-HoPFNz8In_a-9tscHF_998lO7BEUcn3NuzGNP3ZYRlwdMKTnAbOt1gvvhb6GQOh1Og1fwtP7ksn?key=uvmlVet7-pBAx-jz0PuzLA)

## Creating RDD

There are several ways through which we can create an RD

1. Create an RDD from collection
2. Create an RDD from external source

![img](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeouoc2Mc014fR0H5oFWwpPRPyQb8jng2hziKmwN9FfzGxaz7i21ISRiN_5BDaia-tOAZfTMtzNT_uMdSLCVMR7cPbAhKju6J15pzh45omMMBcFunm3heWHR2xxZnIDXpAb2WV1vGTcJcp1efxtMOZs7zI?key=uvmlVet7-pBAx-jz0PuzLA)





```
>>> type(sc)
<class 'pyspark.context.SparkContext'>
>>> type(spark)
<class 'pyspark.sql.session.SparkSession'>
>>> L = list(range(1,101))
>>> type(L)
<class 'list'>
>>> numbers_rdd = sc.parallelize(L)
>>> type(numbers_rdd)
<class 'pyspark.rdd.RDD'>
```















