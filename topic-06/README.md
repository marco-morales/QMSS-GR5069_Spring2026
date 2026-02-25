## TOPIC 6 - Data Pipeline in Practice

#### In preparation for this week:
* read/listen/watch as much as you can from the annotated materials below

---

For this week, we are going to focus on the ins and outs of how to build a data pipeline for data products in an organization. We will reference key terms from Week 1 such as __scalability__, __reproducibility__, and __reliability__. Our conversation will begin with how data is collected from various systems and products as raw data and how it makes its way into ready data to be used by data scientists and analysts. Let's begin this week by reading this [article](https://towardsdatascience.com/data-science-for-startups-tracking-data-4087b66952a1) that goes into great depth on how data is collected into managed services such as Pub/Sub or Kinesis.

In 2006, the phrase "Data is the new Oil" by [Clive Humby](https://ana.blogs.com/maestros/2006/11/data_is_the_new.html) became one of the most common phrase during that time. Why was that the case? The comparison came about because of the volume of raw data that was being tracked by various systems and because of the various forms of insights you can gather from the data. In recent times, people are being careful with the phrase as seen in this [article](https://towardsdatascience.com/data-is-not-the-new-oil-bdb31f61bc2d). Data as we all know must be used carefully and the reality in going from raw data to refined/processed data isn't such a smooth road like Oil.

After our informative discussion on Data Collection, we will discuss how we can from our raw data to processed data by performing some __data transformation__ and __data aggregation__. As Data Scientists, you will not be able to derive valuable insights from raw datasets or make predictions from raw datasets. With that being said, the raw data has to go through some phases before it makes its way to your models. The process of going through all those phases are considered as a data pipeline. This [article](https://towardsdatascience.com/data-science-for-startups-data-pipelines-786f6746a59a) goes very in-depth on how data pipelines are used in organizations. As a workshop class, we will have the opportunity to be hands on practice how we can extract data from a data storage, perform some basic data transformations and aggregations and the store the data back into a data store.

Read more about Data Formats, Data Aggregations, Data Storage:

* [__Data Formats__](http://bigdata.black/infrastructure/storage/choose-data-format/) Choosing the right data format
* [__Data Aggregations__](https://towardsdatascience.com/aggregation-and-grouping-66396f26dd95) Implementing Data Aggregations on your raw data
* [__Data Storage__](https://aws.amazon.com/blogs/startups/picking-the-right-data-store-for-your-workload/) What to think about when picking a data storage for your data





### Cloud computing for our live workshops

We will be using "the Cloud" for the majority of our collaborative work in this course, including our live in-class workshops. It is important to understand the basics and meaning of **Cloud Computing**. This [Medium Article](https://towardsdatascience.com/aws-and-cloud-computing-for-dummies-84525fbabd1e) talks about the traditional IT Infrastructure, types of cloud services and benefits of the cloud.

#### An Introduction to Apache Spark

What is [**Apache Spark**](https://spark.apache.org)? - Many organizations have adapted to using Apache Spark for large scale data processing and machine learning models. Apache Spark has been proven to provide speed, efficiency and reliability in many use cases. In this course we will be using [**Databricks**](https://databricks.com) which is a managed Apache Spark Platform that allows the management of Apache Spark easy. In addition, Databricks provides a very collaborative platform for both Data Scientists and Data Engineers to build data pipelines and productionalize machine learning models very easily. Skim as much as you can from the materials below (it will pay off later in the class):

* [**Intro to Apache Spark**](https://www.youtube.com/watch?v=9U4ED7KQwlE&t=22s): a 60-min video to provide an easy to digest introduction to Spark for all audiences
* [**"An Architecture for Fast and General Data Processing on Large Clusters"**](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2014/EECS-2014-12.pdf): Mattei Zaharia's doctoral dissertation to get a great theoretical introduction to Spark
* [**Learning Spark, 2nd edition**](https://pages.databricks.com/rs/094-YMS-629/images/LearningSpark2.0.pdf): a book-length introduction to Spark - from zero to Spark in 12 chapters!
* free [**self-paced learning courses**](https://docs.google.com/document/d/14YSH67RYaIcgHbgxs-MaDOjpWWGEfskkmDFIOREiRDs/edit) from [Databricks](https://databricks.com) for university students
* [Databricks notebook gallery](https://databricks.com/discover/notebook-gallery) featuring sample notebooks for a large range of use cases
* [Apache Spark GitHub Repo](https://github.com/apache/spark)
* [Research Papers](https://spark.apache.org/research.html)
