# <%= appName %> Spark Application

This is an [Apache Spark](https://spark.apache.org) application using Python API.


## Bootstrap

You need install Apache Spark, [pip](https://pip.pypa.io) and [nose](http://readthedocs.org/docs/nose) first.

Then set `SPARK_HOME` environment variable, e.g.

```bash
$ export SPARK_HOME=/usr/local/Cellar/apache-spark/1.3.1_1/libexec
```


## Running Spark application in local mode

```
$ bin/run-local
```


## Running test

```
$ bin/test
```
