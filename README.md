# Big data and visualization

Margie's Travel (MT) provides concierge services for business travelers. In an increasingly crowded market, they are always looking for ways to differentiate themselves, and provide added value to their corporate customers.

They are looking to pilot a web app that their internal customer service agents can use to provide additional information useful to the traveler during the flight booking process. They want to enable their agents to enter in the flight information and produce a prediction as to whether the departing flight will encounter a 15-minute or longer delay, considering the weather forecasted for the departure hour.

## Target audience

- Application developers
- Data scientists
- Data engineers
- Data architects

## Abstract

### Workshop

In this workshop, you will deploy a web app using Machine Learning Services to predict travel delays given flight delay data and weather conditions. Plan a bulk data import operation, followed by preparation, such as cleaning and manipulating the data for testing, and training your machine learning model.

At the end of this workshop, you will be better able to build a complete machine learning model in Azure Databricks for predicting if an upcoming flight will experience delays. In addition, you will learn to store the trained model in Azure Machine Learning Model Management, then deploy to Docker containers for scalable on-demand predictions, use Azure Data Factory (ADF) for data movement and operationalizing ML scoring, summarize data with Azure Databricks and Spark SQL, and visualize batch predictions on a map using Power BI.

### Whiteboard Design Session
>[Student guide](Whiteboard%20design%20session/WDS%20student%20guide%20-%20Big%20data%20and%20visualization)

In this whiteboard design session, you will work with a group to design a solution for ingesting and preparing historic flight delay and weather data, and creating, training, and deploying a machine learning model that can predict flight delays. 

At the end of this whiteboard design session you will have learned how to include a web application that obtains weather forecasts from a 3rd party, collects flight information from end users, and sends that information to the deployed machine learning model for scoring. Part of the exercise will include providing visualizations of historic flight delays, and orchestrating the collection and batch scoring of historic and new flight delay data.

### Hands-on Lab
> [Student guide](Hands-on%20lab)

This hands-on lab is designed to provide exposure to many of Microsoft's transformative line of business applications built using Microsoft big data and advanced analytics.

By the end of the lab, you will be able to show an end-to-end solution, leveraging many of these technologies, but not necessarily doing work in every component possible.

## Azure services and related products

- [Azure Databricks](https://docs.microsoft.com/en-us/azure/azure-databricks//)
- [Azure Machine Learning services](https://docs.microsoft.com/en-us/azure/machine-learning/service/)
- [Azure Data Factory (ADF)](https://docs.microsoft.com/azure/data-factory/introduction/)
- [Azure Storage](https://azure.microsoft.com/en-us/services/storage/)
- [Power BI Desktop](https://powerbi.com)
- [Azure App Service](https://azure.microsoft.com/en-us/services/app-service/)

## Azure solution

[Machine Learning](https://azure.microsoft.com/en-us/solutions/architecture/advanced-analytics-on-big-data/)
