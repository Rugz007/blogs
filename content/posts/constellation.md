---
title: "Constellation - Automated MLOps Platform - Overview"
date: 2024-10-31
description: "Constellation is an automated MLOps platform that helps data scientists and ML engineers to build, deploy, and scale machine learning models."
---

## TL;DR
ML being a repetitive process can be a headache and let's not get started with collaborations. With Constellation, you can do everything from data visualization w/ dynamic graphs to one-click deployments in one place.

![Constellation](https://dqy38fnwh4fqs.cloudfront.net/UHR8ANBP6RRNAR9FEBQADJ6LJMRA/projects/constellation.webp)



# Images
![Constellation](https://i.imgur.com/hd6wlFL.png)
![Constellation](https://i.imgur.com/FwKnHQu.png)
![Constellation](https://i.imgur.com/gar5KZh.png)
![Constellation](https://i.imgur.com/Exqd07s.png)
![Constellation](https://i.imgur.com/Nm0qTGv.png)


## What is Constellation?
Constellation is an MLOps platform that centralizes your Machine Learning projects in one place and helps accelerate ML development for small teams and large organizations. It makes creating and deploying ML models easier and faster by reducing code and increasing interactivity.

## Motivation
Machine learning has become a popular solution for solving real-world problems. Despite the similar workflow that an ML engineer follows daily, the process involves multiple critical steps such as data collection, preprocessing, feature selection, model identification, experimentation, hyperparameter tuning, result comparison, model selection, API development, cloud service implementation, analytics and monitoring, and continuous performance evaluation.

Working with real-world data can be difficult due to its unclean nature, requiring substantial preprocessing before model training. Many preprocessing steps overlap regardless of the model, and comparing the performance of different models can be challenging. Hyperparameter tuning is a complex process, and versioning on commonly used tools can be complicated when comparing different parameter configurations.

It is critical to develop APIs for integrating a chosen model into an existing infrastructure, survey cloud service providers for deployment, set up analytics and monitoring, and continuously evaluate performance once a model is selected. These persistent issues are frequently encountered by both students and ML engineers in the industry.

As automation becomes more prevalent, there is an increasing need for a more efficient approach to avoid these repetitive and complex cycles. This project, 'Constellation,' aims to provide an MLOps platform that addresses these challenges and streamlines the machine learning workflow for both students and professionals in the industry.


## Scope of the Project
The ’Constellation’ project aims to develop an MLOps platform that simplifies the ma-
chine learning workflow and provides users with a comprehensive platform that caters
to all their ML needs. It consists of two main components - an SDK and a Web Plat-
form that work together to create an end-to-end data-independent MLOps platform. The
platform will have a user-friendly graphical interface, offer an auto-ML functionality and
allow easy comparison and analysis of different metrics. The aim is to address persistent
issues faced by both students and ML engineers and provide users with a more efficient
approach to machine learning.

## System Architecture
![System Architecture](https://i.imgur.com/89jbKv4.png)


## User flow of the platform
1. **Dataset Upload**: Users can upload their datasets on the platform. The platform parses the dataset to understand the data structure and uploads it to the Amazon Simple Storage Service (S3) for storage. The S3 bucket provides secure and scalable storage of the datasets, which can be accessed by the platform for creating machine learning pipelines.

2. **S3 Upload**: The parsed dataset is stored in an S3 bucket in a structured manner, which makes it easier to access and process the data. The S3 bucket also provides an option for data versioning, making it easier to roll back to a previous version if required.

3. **Project Creation**: Users can create projects and build machine learning pipelines using a GUI provided by the platform. The GUI provides a drag-and-drop interface for creating the pipeline, making it easier for users to build complex pipelines.

4. **Pipeline Creation**: Once the user has created the pipeline, the platform uses DFS and Topological Sort algorithms to create the directed acyclic graph (DAG) of the pipeline. The DAG represents the flow of data and operations in the pipeline, which is then converted into code. This code can be run on the user's local machine.

5. **Metrics Generation**: The user can run the generated code on their local machine, which generates metrics such as accuracy, precision, recall, and F1-score. These metrics are then uploaded to the platform database, which can be used for monitoring the performance of the pipeline.

6. **Container Deployment**: Users can create and deploy docker containers using docker-in-docker. The containers are deployed on the cloud and monitored using Prometheus. The Prometheus monitoring tool provides a dashboard for visualizing the performance of the deployed containers.


## What does Constellation solve?
Constellation overcomes the shortcomings of other MLOps platforms by utilizing a unique
methodology. First, it provides a user-friendly graphical user interface (GUI) that enables
users to create machine learning pipelines easily. The GUI allows users to design, build,
and visualize their pipelines from data preprocessing to model selection and hyperparam-
eter tuning.
Second, Constellation includes an SDK that generates code from the user’s pipeline,
enabling users to reuse their code and replicate their experiments easily. The SDK also
provides an auto-ML functionality that helps novice users to quickly get started with
their tasks.
Third, Constellation provides a collaborative space for users to compare and analyze
different experiment and project metrics easily. It includes extensive support for ML
libraries, and users can visualize their results with various charts and graphs.
Finally, Constellation enables the deployment of trained ML models on the cloud and
monitoring their performance and usage. This methodology ensures that users can create
robust and scalable ML solutions with well-defined workflows, addressing the persistent
issues faced by both students and ML engineers in the industry.

### Advantages of Constellation
- **User-friendly GUI**: Constellation provides a user-friendly graphical interface that enables users to create machine learning pipelines easily.
- **SDK for code generation**: Constellation includes an SDK that generates code from the user’s pipeline, enabling users to reuse their code and replicate their experiments easily.
- **Auto-ML functionality**: Constellation provides an auto-ML functionality that helps novice users to quickly get started with their tasks.
- **Collaborative space for comparison and analysis**: Constellation provides a collaborative space for users to compare and analyze different experiment and project metrics easily.
- **Support for ML libraries**: Constellation includes extensive support for ML libraries, and users can visualize their results with various charts and graphs.
- **Deployment on the cloud**: Constellation enables the deployment of trained ML models on the cloud and monitoring their performance and usage by just having one click deployment. 

### Disadvantages of Constellation
- **Limited support for custom ML libraries**: Constellation may have limited support for custom ML libraries, which may restrict users from using their preferred libraries.
- **Complexity in setting up the platform**: Setting up the platform may be complex for novice users, as it requires knowledge of ML concepts and cloud services.
- **Reliabitlity of code generation**: The reliability of code generation by the SDK may be a concern, as it may not always generate the desired code.
- **Limited support for cloud services**: Constellation may have limited support for cloud services, which may restrict users from deploying their models on their preferred cloud service provider.

## Conclusion
Constellation is an automated MLOps platform that helps data scientists and ML engineers to build, deploy, and scale machine learning models. It provides a user-friendly graphical interface, an SDK for code generation, auto-ML functionality, and a collaborative space for comparison and analysis. Constellation enables the deployment of trained ML models on the cloud and monitoring their performance and usage. It aims to streamline the machine learning workflow for both students and professionals in the industry and provide users with a more efficient approach to machine learning.
