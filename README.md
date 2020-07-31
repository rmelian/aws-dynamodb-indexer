# Index dynamodb data to elasticsearch
This repo shows how to index dynamodb data to elasticsearch. 

![Diagram](assets/diagram.png)

* A lambda function is reponsible for getting the records from DynamoDB Streams and coping or updating Elasticsearch. 
* Python is used as lambda function language
* Serverless framework is used to build and deploy the services to AWS

