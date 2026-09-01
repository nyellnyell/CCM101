# Checkpoint 4 – Cloud Platform Recommendation Challenge

## Client A – Startup Company
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Explanation:**  
  Amazon Web Services is the ideal choice for a startup launching a mobile application with plans for rapid growth on a tight budget. AWS offers flexible pay-as-you-go pricing alongside a generous Free Tier that minimizes initial infrastructure costs. Its massive global footprint and auto-scaling mechanisms allow startup platforms to scale seamlessly from thousands to millions of users without needing architecture redesigns. Furthermore, AWS provides fully managed mobile backend integrations that significantly accelerate time-to-market.
* **Three (3) Recommended Services:**
  1. **AWS Amplify / Amazon Cognito:** For authentication, backend integration, and mobile app deployment.
  2. **Amazon DynamoDB:** A fast, flexible NoSQL database that automatically scales with app traffic.
  3. **Amazon EC2 / AWS Lambda:** For serverless and scalable backend compute power.

---

## Client B – University
* **Recommended Cloud Platform:** Microsoft Azure
* **Explanation:**  
  Microsoft Azure is the natural choice for a university already embedded in the Microsoft ecosystem with Windows Server, Microsoft 365, and Active Directory. Migrating to Azure ensures seamless hybrid infrastructure integration without requiring extensive re-engineering or retraining of IT staff. Azure allows the university to extend its existing Active Directory seamlessly into the cloud using Microsoft Entra ID for unified single sign-on across all academic services. Additionally, Microsoft offers substantial educational licensing discounts and tailored cloud governance features for higher education.
* **Three (3) Recommended Services:**
  1. **Microsoft Entra ID (formerly Azure Active Directory):** For centralized user access control and single sign-on across university systems.
  2. **Azure Virtual Machines:** For hosting existing legacy software workloads built on Windows Server.
  3. **Azure SQL Database:** For managing student records, enrollment databases, and administrative software.

---

## Client C – AI Research Company
* **Recommended Cloud Platform:** Google Cloud Platform (GCP)
* **Explanation:**  
  Google Cloud Platform is the industry leader for data-intensive projects, high-performance computing (HPC), and artificial intelligence model training. GCP provides cutting-edge hardware options, including custom Tensor Processing Units (TPUs) alongside advanced NVIDIA GPUs optimized for deep learning algorithms. Its integrated machine learning environment, Vertex AI, streamlines the end-to-end data pipeline from model preparation to training and deployment. By leveraging GCP's high-throughput infrastructure, the research company can drastically reduce AI model training times and lower operational costs.
* **Three (3) Recommended Services:**
  1. **Vertex AI:** A fully managed platform to build, train, and deploy machine learning models.
  2. **Google Kubernetes Engine (GKE):** For orchestrating containerized high-performance computing clusters.
  3. **BigQuery:** A serverless data warehouse for processing and analyzing massive research datasets.

---

## Client D – Global E-Commerce Company
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Explanation:**  
  AWS is the proven gold standard for global e-commerce platforms requiring high availability, ultra-low latency, and robust auto-scaling. Born out of Amazon’s own retail infrastructure, AWS offers an extensive global network of Regions, Availability Zones, and CloudFront Edge locations to serve international shoppers with minimal latency. Its elasticity allows online stores to handle sudden, massive traffic surges during global sales events like Black Friday without downtime. Additionally, AWS maintains top-tier compliance standards, such as PCI-DSS, essential for securely processing credit card transactions globally.
* **Three (3) Recommended Services:**
  1. **Amazon CloudFront:** A global Content Delivery Network (CDN) to serve static product media quickly to customers worldwide.
  2. **Amazon Aurora / Amazon RDS:** High-performance, multi-region relational database service for processing customer orders and inventory management.
  3. **AWS Auto Scaling & Elastic Load Balancing (ELB):** Automatically adjusts compute capacity to maintain smooth site performance during peak traffic spikes.

---

## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | Amazon Web Services (AWS) | Offers a broad Free Tier, flexible pay-as-you-go pricing, and scalable serverless tools that help startups grow without large initial capital expenditure. |
| **Enterprise Organization** | Microsoft Azure / AWS | Provides enterprise-grade hybrid cloud support, robust security compliance certifications, and seamless scalability for large-scale operations. |
| **Microsoft Environment** | Microsoft Azure | Offers native integration with Active Directory (Entra ID), Windows Server, Office 365, and existing Microsoft enterprise licensing agreements. |
| **AI / Machine Learning** | Google Cloud Platform (GCP) | Leads the industry with Vertex AI, custom TPUs, and advanced big data processing services optimized for building and training AI models. |
| **Kubernetes Deployment** | Google Cloud Platform (GCP) | As the creator of Kubernetes, GCP offers Google Kubernetes Engine (GKE), providing superior managed Kubernetes capabilities, performance, and operational efficiency. |
| **Global Web Application** | Amazon Web Services (AWS) | Features an extensive global network of Regions, Availability Zones, and CloudFront Edge locations to ensure low-latency access and high availability worldwide. |
