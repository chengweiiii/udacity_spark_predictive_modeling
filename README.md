## Table of Contents

1. [Configuration & Installation](#installation)
2. [Project Background](#Background)
3. [Project Problem Statement](#problem)
6. [Results & Findings](#results)
7. [Licensing, Authors, and Acknowledgements](#licensing)

## Configuration & Installation <a name="installation"></a>
Environment configuration: You may need to run code on Amazon emr-5.31.0 or above, and install JupyterHub 1.1.0 and Spark 2.4.6 when creating the cluster. Package Installation: You'll need to install pandas 1.2.0, matplotlib 3.3.3, seaborn 0.11.1, ipython==7.19.0 in your EMR notebook. [learn more](https://aws.amazon.com/tw/blogs/big-data/install-python-libraries-on-a-running-cluster-with-emr-notebooks/)

## Project Background<a name="Background"></a>

The goal of this project is to gain hands-on end-to-end experience of manipulating large datasets with Spark and learn how to use Spark ML to build machine learning pipelines and models.

Imagine we are working on a data science team for a popular digital music service, Sparkify, which is similar to Spotify. Every time a user interacts with the service while they are playing songs, logging out, thumb up a song, hearing an ad, it generates a log. Our job is to helping our business thrive.

## Project Problem Statement <a name="problem"></a>

* Goal: predict which users are at risk to churn.
* Strategy: The full dataset is really large (12GB), we have no choice but to use Spark for ETL and use Spark ML library for building machine learning pipeline. We also need to deploy our pipeline on Amazon EMR clusters to speed up the computation.
* Expected Result: build a "churn classifier" which can produce the probabilty of churn for each user.

## Results & Findings <a name="results"></a>
The notebook can be find in [main_2.ipynb](https://github.com/chengweiiii/udacity_spark_predictive_modeling/blob/main/main_2.ipynb), and the detail findings of the project can be found at the blog post available [here](https://chengweii-c.medium.com/an-end-to-end-spark-project-example-predict-user-churn-833740cc61f7).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The credit is given to Udacity Data Science Nano-degree as they provide the interesting problem and those large and realistic datasets. You can find the information at the link available [here](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

