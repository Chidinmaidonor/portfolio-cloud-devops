# ☁️ Cloud & DevOps Portfolio

Welcome to my **Cloud & DevOps portfolio**.    

My focus areas include:  
- 🚀 **Cloud Platforms** → AWS, Azure, GCP  
- 🐳 **Containers & Orchestration** → Docker, Kubernetes  
- 🔄 **CI/CD Pipelines** → GitHub Actions, Jenkins, GitLab CI  
- 📊 **Monitoring & Logging** → CloudWatch, Grafana  
- 🔐 **Infrastructure as Code (IaC)** → Terraform

---

## 🔹 Featured Projects

### 1. ⚡ Automated Machine Learning CI/CD Pipeline for Cloud Deployment
- **Project Overview:** Developed and deployed a CI/CD pipeline to streamline the machine learning workflow from training to deployment. The pipeline automated data preprocessing, model training, unit testing, and deployment to cloud infrastructure. Models were containerized using Docker and deployed on AWS EC2 instances, with AWS CloudWatch integrated for real-time monitoring, performance tracking, and automated alerts. This project demonstrated the application of DevOps principles in machine learning, improving reliability, scalability, and deployment efficiency.
-  **Tech Used:** CI/CD Tools: GitHub Actions, GitLab CI/CD

    - Cloud & Infrastructure: AWS EC2, AWS CloudWatch, S3

    - Containerization: Docker for packaging and deployment

    - Machine Learning: Python, scikit-learn, TensorFlow/PyTorch (for model development)

    - Monitoring & Automation: CloudWatch alerts, logging pipelines 
👉 [View Project](../projects/ml-cicd-pipeline/README.md)

---

### 2.   Cloud-Integrated Unauthorized Parking Detection System with Automated SMS Alerts”
- **Project Overview:** Designed and deployed an automated parking violation detection system that integrates IoT sensors with cloud services for real-time monitoring and alerting. The system uses ultrasonic sensors and camera modules to detect unauthorized vehicles in restricted zones, processes data on a microcontroller, and transmits events to a cloud platform. A serverless backend triggers SMS notifications to authorities or owners via cloud messaging APIs, ensuring rapid response. CI/CD workflows were used to automate system deployment and updates, improving reliability and scalability.
- **Tech Used:** 
    - Embedded Systems & IoT: Arduino/ESP32, Ultrasonic Sensor, Camera Module

    - Cloud Platforms: AWS IoT Core, AWS Lambda, AWS SNS (SMS Notification Service), S3 for event logging

    - DevOps & Automation: GitLab CI/CD for cloud workflow automation and continuous deployment

    - Programming Languages: C/C++ (firmware), Python (cloud integration scripts)

    - Tools: MQTT Protocol for IoT communication, Docker (for testing cloud microservices)
👉 [View Project]()

---

### 3. 🗄️ Serverless Image Processing and Classification Pipeline on AWS
-**Project Overview:** Designed and implemented a serverless architecture to automate image processing and classification tasks. Images uploaded to AWS S3 triggered event-driven AWS Lambda functions, which invoked Amazon Rekognition for object and feature classification. Metadata and results were stored in DynamoDB for scalable querying and retrieval. This architecture eliminated the need for server management, ensured cost efficiency, and enabled highly scalable, event-driven workflows.
- **Tech Used:**
    - Cloud & Serverless Services: AWS Lambda, AWS S3, Amazon Rekognition, DynamoDB

    - Architecture: Event-driven workflows using AWS triggers

    - Programming: Python for Lambda functions and integration logic

    - DevOps & Automation: GitHub/GitLab CI/CD for deployment automation

    - Monitoring: AWS CloudWatch for system performance and error logging
👉 [View Project]()

---

### 4. 🌐 Scalable Multi-Tier Web Application Deployment on AWS
- **Project Overview:** Implemented and deployed a three-tier web application architecture consisting of a frontend, backend, and database layer on AWS. The system leveraged EC2 instances for application hosting, RDS for managed relational databases, and Elastic Load Balancer to ensure high availability and fault tolerance. Infrastructure was provisioned and maintained using Terraform (Infrastructure as Code), enabling reproducible deployments, scalability, and simplified infrastructure management.
- **Tech Used:**
     - Cloud Infrastructure: AWS EC2, RDS, Elastic Load Balancer

     - Infrastructure as Code (IaC): Terraform

     - DevOps & Automation: GitHub/GitLab CI/CD for deployment workflows
 
     - Application Stack: Frontend (HTML/CSS/JavaScript), Backend (Python/Node.js), Database (MySQL/PostgreSQL on RDS)

     - Monitoring: AWS CloudWatch for performance and system health
👉 [View Project]()

---

### 5. 📈 Kubernetes Monitoring and Alerting Stack with Prometheus and Grafana
- **Project Overview:**Developed and deployed a monitoring solution for Kubernetes clusters by integrating Prometheus and Grafana. The system collected and visualized key performance metrics including CPU utilization, memory usage, and pod health, enabling real-time observability. Custom Grafana dashboards provided actionable insights, while Prometheus alerting rules were configured for proactive incident management, reducing downtime and ensuring workload reliability.
- **Tech Used:**
    - Container Orchestration: Kubernetes

    - Monitoring & Visualization: Prometheus, Grafana

    - Alerting & Incident Management: Prometheus Alertmanager, custom rules

    - Automation & Deployment: Helm, GitLab/GitHub CI/CD pipelines

    - Infrastructure: Docker, Linux-based clusters  
👉 [View Project]()

---
