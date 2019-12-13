# Initial Knowledge Check
Before diving into Databricks and Spark, it will help to have a baseline understanding of a few key concepts. Judge your understanding of these five key concepts:

1. APIs, libraries, and packages
2. Notebook architecture
3. Map and reduce functions
4. Switching between programming languages in a notebook (Spark calls this magic commands)
5. Mutability and data structures such as graphs, lists, and datasets

Were any of these topics brand new? Did you need to look them up before answering? If you are not comfortable with notebooks, distributing computing, clusters, and modular programming, try to do some research on your own and come back to this page.

# Databricks & Spark
Now, it is important to understand the term *big data*. Big data refers to working with and analyzing data sets that are too large or complex to be dealt with by traditional data-processing software. Common characteristics of big data are volume, velocity, and variety. 

**Volume** Data comes in from IoT devices, industrial equipment, points of sale, and social media.

**Velocity** Data comes in constantly, in real time, and sometimes late.

**Variety** Data comes in all forms - structured, unstructured, numeric, text, times, and anything else you can imagine.

How do we deal with the volume, velocity, and variety? Splitting the data and tasks into chunks and working on them at the same time. This known as distributed computing and parallel processing. This is where Spark and Databricks come in.

Spark is a programming framework built for high-performance distributed computing. It is a tool to organize data engineering and data science tasks to perform well over a large dataset on a specialized (Spark) cluster configuration.

*Spark Capabilities and Connections*

![image](https://user-images.githubusercontent.com/56167793/68433702-0c23f400-016c-11ea-9faa-2d071f870c84.png)/

Databricks is a platform built on top of Spark. It makes using Spark easy. It provides its users an interactive, notebook-based development environment to quickly build Spark code and helps them create and manage clusters to run Spark code. It also provides many more bells and whistles to make using Spark as easy as possible.

*Example Azure Spark Streaming Achitecture*

![image](https://user-images.githubusercontent.com/56167793/68433938-9c623900-016c-11ea-93c4-d7875570bd95.png)
Photo: databricks.com

Application developers and data scientists incorporate Spark into their applications to rapidly query, analyze, and transform data at scale. Tasks most frequently associated with Spark include ETL and SQL batch jobs across large data sets, processing of streaming data from sensors, IoT, or financial systems, and machine learning tasks.

# Avanade and Databricks

Avanade utilizes Databricks for different purposes depending on our client's needs. Here are a few examples:

One communications client had trouble performing big data calculations. They took too long and could not be performed in real-time. This diminished the precision of the results because by the time the calculations were completed, new information was available and needed to be accounted for. Avanade created an Azure Databricks solution in a PoC, proving real time calculations were possible.

Databricks was leveraged to create a predictive maintenance program for an automotive client. The program recommends maintenance actions to replace or adjust driving chains during routine workshop visits. The project increased customer satisfaction and resulted in cost savings through reduced shop visits and warranty cases.

A banking client had a problem with customers abandoning the credit card application process before completion. After starting a project to remedy the abandonment issue, the client realized there were many improvements to data, process, and systems that needed to happen in parallel to scale the solution they created. Avanade created a data platform based in Azure PaaS to improve insight into the customer throughout the credit card application process. To enable this vision, Avanade used Databricks to build a unified view into every metric for each of the client's customers across multiple time intervals, which became the data model upon which the churn models were built for the abandonment use case.

In the insurance industry, Avanade and Accenture worked to bring together multiple insurance quote data sources, as well as data from the client's websites into a curated data lake. The team used Databricks to provide data transformations before making the data available to the client's data science team and creating a data warehouse to support the client's reporting needs.

# How to use this Pathway 

Before starting any studying, read through this guide to familiarize yourself with the available resources. Although the steps are listed in order, you may skip or repeat sections based on your progression or deep-dive into a specific use case you find interesting.

![PathImage](https://user-images.githubusercontent.com/56167793/68046082-3ff8a880-fc98-11e9-857f-f2c0d255bf5e.png)

1.	Complete the Set Up section below.
2.	If you are new to python, scala, or big data you may find it helpful to begin by using one of the Understanding Spark, Python, & Scala resources below. We recommend Python unless you have previous Scala knowledge. 
 If you understand the purpose of clusters and distributed computing (such as MapReduce), datastructures such as lists and arrays, and syntax, you can probably skip this step. 
3.	Complete the Avanade University regimen [HERE](https://avanade.sharepoint.com/sites/HR/learn/tech/an/Pages/Databricks.aspx). These are fantastic courses that come straight from the horse's mouth.
You will need to request a voucher for the courses, which may take time due to limited availability of vouchers. In the meantime, you can study the resources on this page.
4.	If at any point you feel like you need more information, try one of the Databricks Architecture & Best Practices resources below to hone the concepts. 
 Some resources here may be more specifically tailored to your daily work. For example, a data engineer may want to focus on Data ingestion with Azure Data Factory.
5.	Explore the Azure connections most relevant to your work using the Azure Databricks resources below.
6.	Practice by working with the notebooks on this page.
7.	Create a pull request and suggest changes or additions to this pathway. If you roll-off a Databricks project, feel free to write a brief client story on this repository.

# Set Up

* You need an Azure subscription to use Azure Databricks. If you do not already have a subscription, it is available through Avanade. You can practice on the Databricks Community Edition, however you will find the Azure subscription necessary when diving into Azure Databricks.
* Join the Databricks Teams Channel.

# Basic Python, Scala, and Spark Resources

[About Spark](https://databricks.com/spark/about)

[Intro to Python](https://www.edx.org/course/6-00-1x-introduction-to-computer-science-and-programming-using-python-3) 

[Functional Programming in Scala](https://www.coursera.org/learn/progfun1)

[Learning Spark](http://shop.oreilly.com/product/0636920028512.do)
 
If you prefer reading a book to online courses, this book is excellent.

# Databricks Architecture & Best Practices

[Introduction to Azure DataBricks](https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-databricks/)

[Azure Databricks: Getting Started](https://docs.azuredatabricks.net/getting-started/index.html)

[DS320 DataStax Enterprise Analytics with Spark](https://academy.datastax.com/resources/getting-started-apache-spark)

Note: This resource focuses on Scala and Cassandra but is a useful resource for understanding Spark under the hood regardless of your preferred language or connectors.

[Best Practices Resources from Databricks](https://avanade.sharepoint.com/:f:/s/DatabricksinAvanade/EqxR3t1Ey95HtDgY13vMg0wB_DixUb9DFZLZPLPXLYI-cQ?e=SSAISW)

Databricks provided us with these best practices as part of our partnership. This link will only work once you are in the Databricks Teams Channel.

[Spark Overview](http://spark.apache.org/docs/latest/)

Official documentation can be dry but also helpful! Read this overview and then peruse the documentation links at the bottom of the page. There is a plethora of information.

# Azure Databricks

*Example Data Flow*

![image](https://user-images.githubusercontent.com/56167793/68433889-83f21e80-016c-11ea-975b-adc0b09cfbf2.png)
Photo: azure.microsoft.com

[Perform Basic Data Transformations in Azure Databricks](https://docs.microsoft.com/en-us/learn/modules/perform-basic-data-transformation-in-azure-databricks/) 

[Create Data Visualizations using Azure Databricks and Power BI](https://docs.microsoft.com/en-us/learn/modules/create-data-visualizations-using-azure-databricks-and-power-bi/)

[Data Ingestion with Azure Data Factory](https://docs.microsoft.com/en-us/learn/modules/data-ingestion-with-azure-data-factory/)

[Access SQL Data Warehouse Instances with Azure Databricks](https://docs.microsoft.com/en-us/learn/modules/understand-the-sql-dw-connector-with-azure-databricks/)

# Summary
This pathway gave guidance on learning about Spark and Databricks. You should now be able to apply these skills to data engineering, data science, azure architectures, and any unique work you are faced with. You may also be interested in taking the [Databricks Certified Developer](https://academy.databricks.com/category/certifications) exam. We recommend the Python version unless you have previous Scala knowledge.

Next, it is important to share the Databricks work you complete with the TC. Please make suggestions on this page by creating a pull request with changes. If you roll off a Databricks project, share your client stories and challenges with a pull request or work with Grant Stephens to schedule a time to present to the TC. We will be rewarding excellent contributors with Go Team! awards. Pull request instructions can be found [HERE](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

Requests will be reviewed monthly. If you would like your request reviewed sooner, please contact Jennifer Gagner, Matt Russell, or Grant Stephens.




