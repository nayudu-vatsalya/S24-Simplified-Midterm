# Malware Detection - Simplified Midterm Project Overview
# Introduction:
This simplified midterm project aimed to deploy a machine learning model for malware classification as an API endpoint on AWS SageMaker. The deployed model was trained based on the work done in Lab 5.4, utilizing a dataset for feature extraction.

# Tasks:
# Model Deployment to AWS SageMaker: 
For this task, the model trained in Lab 5.4 was deployed as an API endpoint on AWS SageMaker. The deployment process included uploading the model to SageMaker and creating an endpoint to make it accessible for inference.

# Python Client Development: 
A Python client was developed to interact with the deployed SageMaker endpoint. The client takes an executable file as input, extracts relevant features, and sends the extracted features to the SageMaker endpoint for classification. After classification, the client retrieves and displays the results.

# Testing Client and Endpoint: 
The client and endpoint were tested using one malware PE file and one benign PE file. The testing process was demonstrated in the project's demo video.

# Deliverables:
Presentation and Demo Video: A short video presentation was created to describe the technical details of the project and demonstrate the implementation of the tasks. The video included a walkthrough of the model deployment process, client development, testing with sample files, and performance benchmarking. ([Watch Demo Video](https://youtu.be/jwl71Xm6q1E?feature=shared))

# Report: 
A comprehensive report covering the project overview, technical approaches for each task, performance analysis metrics (e.g., accuracy, precision, recall, F-1 score, confusion matrix), and references.

# GitHub Repository: 
All project files, including Jupyter notebooks , report, and presentation video, were hosted in a dedicated GitHub repository. 
# Submission:
The submission included a clone of the GitHub repository as a .zip file. Additionally, a link to the GitHub repository was provided in the submission description.
