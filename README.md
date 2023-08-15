# Elastisearch_Kibana_POC
Log Analysis using Elastiseacrh and Kibana
![](https://github.com/ansel9618/Elastisearch_Kibana_POC/blob/main/Images/overall_diagram.png)

## Elasticsearch Docker Deployment
For this usecase Docker images for Elasticsearch and Kibana as well as a Docker compose file was used for implementation. The container was then started in a local linux system.


## Writing events to Elasticsearch
Before writing to Elastiseacrh you create a new index for the search engine and create data with a Python script that will be indexed and easily accessed. After that, you will write the log information into Elasticsearch. 
refer:-[Python-Elastisearch](https://elasticsearch-py.readthedocs.io/en/v8.9.0/)

![Creating Index](https://github.com/ansel9618/Elastisearch_Kibana_POC/blob/main/Images/Creating%20index.png)


![Writing events](https://github.com/ansel9618/Elastisearch_Kibana_POC/blob/main/Images/writing_events2_Elastisearch.png)


## Analyzing logs with Kibana
Once the data is in, you work with Kibana to read data out and visualize it on dashboards.Here we can create customized elements and dashboards for the use case in order to find out what is going on in your pipelines and processes or whether data is missing somewhere. Finally,Looked into the log analysis where you can search for errors in your data.

![Dashboard](https://github.com/ansel9618/Elastisearch_Kibana_POC/blob/main/Images/Dashboards.png)
