# Bnb-Clone  
_A Serverless Multi-Cloud Rental Application (AWS and GCP)_

---

## Overview  
**Bnb-Clone** is a modern, serverless, multi-cloud application designed to simplify vacation rentals. By leveraging the best of **AWS** and **GCP**, this application handles booking management, secure authentication, real-time chat, customer support, and data analysis with ease.  

---

## Features  
- **Effortless Booking Management**: Streamlined handling of rental bookings.  
- **Secure Authentication**: Built with **AWS Cognito** and **AWS Lambda**.  
- **Advanced Chatbot Support**: Powered by **AWS Lex** for intelligent interactions.  
- **Real-Time Chat**: Seamless conversations using **GCP Pub/Sub**, **Cloud Functions**, and **Firestore**.  
- **Instant Notifications**: Alerts delivered via **AWS SNS** and **SQS**.  
- **Data Insights and Visualization**: Actionable insights with **Looker Studio** and **Google Natural Language API**.  

---

## Tech Stack  
- **Cloud Providers**: AWS, GCP  
- **Programming Language**: Python  
- **Infrastructure as Code (IaC)**:  
  - **AWS CloudFormation**  
  - **GCP Cloud Deployment Manager**

---

## Architecture  
### AWS Components  
- **Cognito**: Provides user authentication and authorization.  
- **Lambda**: Powers serverless backend functionality.  
- **Lex**: Enhances user experience with chatbot capabilities.  
- **SQS & SNS**: Ensures efficient notification and queue management.  

### GCP Components  
- **Pub/Sub**: Enables real-time message streaming.  
- **Cloud Functions**: Handles serverless backend operations.  
- **Firestore**: A scalable NoSQL database for real-time data storage.  
- **Looker Studio**: Visualizes complex data into user-friendly dashboards.  
- **Google Natural Language API**: Performs sentiment analysis and text processing.  

---

## Deployment  
- **AWS CloudFormation**: Automated deployment of AWS resources with YAML templates.  
- **GCP Cloud Deployment Manager**: Simplified provisioning of GCP services.  

---

## Development Highlights  
- Serverless architecture implemented using **Python** for both **AWS Lambda** and **GCP Cloud Functions**.  
- Fully scalable and cost-efficient, ideal for modern cloud-native applications.  
