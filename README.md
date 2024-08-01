# Fraud Prediction using Auto AI

Automation and artificial intelligence (AI) are transforming businesses and will contribute to economic growth via contributions to productivity. They will also help address challenges in areas of healthcare, technology & other areas. At the same time, these technologies will transform the nature of work and the workplace itself. In this code pattern, we will focus on building state of the art systems for churning out predictions which can be used in different scenarios. We will try to predict fraudulent transactions which we know can reduce monetary loss and risk mitigation. The same approach can be used for predicting customer churn, demand and supply forecast and others. Building predictive models require time, effort and good knowledge of algorithms to create effective systems which can predict the outcome accurately. With that being said, IBM has introduced Auto AI which will automate all the tasks involved in building predictive models for different requirements. We will get to see how Auto AI can churn out great models quickly which will save time and effort and aid in faster decision making process.

When the reader has completed this code pattern, they will understand how to :

* Quickly set up the services on cloud for model building.
* Ingest the data and initiate the Auto AI process.
* Build different models using Auto AI and evaluate the performance.
* Choose the best model and complete the deployment.
* Generate predictions using the deployed model by making ReST calls.
* Compare the process of using Auto AI and building the model manually.

# Architecture Diagram

![](https://github.com/IBM/predict-fraud-using-auto-ai/blob/master/images/architecture.png)

1. User logs into Watson Studio, creates a project and initiates an instance of Auto AI & Object Storage.
2. User uploads the data file in the CSV format to the object storage.
3. User initiates the model building process using Auto AI and create pipelines.
4. User evaluates different pipelines from Auto AI and selects the best model for deployment.
5. User generates accurate predictions by making ReST call to the deployed model.

## Included components

* [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio): Analyze data using RStudio, Jupyter, and Python in a configured, collaborative environment that includes IBM value-adds, such as managed Spark.

* [IBM Auto AI](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/autoai-overview.html):The AutoAI graphical tool in Watson Studio automatically analyzes your data and generates candidate model pipelines customized for your predictive modeling problem.  

* [IBM Cloud Object Storage](https://console.bluemix.net/catalog/services/cloud-object-storage): An IBM Cloud service that provides an unstructured cloud data store to build and deliver cost effective apps and services with high reliability and fast speed to market. This code pattern uses Cloud Object Storage.


## Featured technologies

* [Artificial Intelligence](https://developer.ibm.com/technologies/artificial-intelligence/): Any system which can mimic cognitive functions that humans associate with the human mind, such as learning and problem solving.
* [Data Science](https://developer.ibm.com/code/technologies/data-science/): Systems and scientific methods to analyze structured and unstructured data in order to extract knowledge and insights.
* [Analytics](https://developer.ibm.com/code/technologies/analytics/): Analytics delivers the value of data for the enterprise.
* [Python](https://www.python.org/): Python is a programming language that lets you work more quickly and integrate your systems more effectively.
