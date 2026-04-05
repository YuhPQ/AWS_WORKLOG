---
title: "Worklog Week 11"
date: 2026-03-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Objectives of Week 11:

* Deploy the entire system to AWS.  
* Configure cloud infrastructure based on the designed architecture.  
* Ensure the system is accessible from the internet.  
* Set up monitoring and logging.  
* Test the system after deployment.  

---

### Tasks performed during this week:

| Day | Tasks | Start Date | End Date | Resources |
| --- | ----- | ---------- | -------- | --------- |
| 2 | - Build Docker image for backend <br>&emsp; + Configure Dockerfile <br>&emsp; + Test container locally | 23/03/2026 | 23/03/2026 | |
| 3 | - Push image to AWS: <br>&emsp; + Create repository on Amazon ECR <br>&emsp; + Push Docker image to ECR | 24/03/2026 | 24/03/2026 | |
| 4 | - Deploy backend: <br>&emsp; + Configure ECS (Fargate) <br>&emsp; + Create service and task definition | 25/03/2026 | 25/03/2026 | |
| 5 | - Configure Application Load Balancer: <br>&emsp; + Route requests to ECS <br>&emsp; + Open ports and configure Security Groups | 26/03/2026 | 26/03/2026 | |
| 6 | - Deploy frontend: <br>&emsp; + Build React app <br>&emsp; + Upload to S3 <br>&emsp; + (Optional) configure CloudFront CDN <br> - Set up CloudWatch for logging | 27/03/2026 | 27/03/2026 | |

---

### Achievements of Week 11:

* Deployed backend to AWS:
  * Built Docker image  
  * Pushed to Amazon ECR  
  * Successfully deployed on ECS (Fargate)  

---

* Configured networking:
  * Application Load Balancer routes requests  
  * Security Groups allow internet access  

---

* Deployed frontend:
  * Built React application  
  * Deployed on S3 (static hosting)  
  * (Optional) Used CloudFront for performance optimization  

---

* Set up system monitoring:
  * Used CloudWatch for backend logging  
  * Monitored service status  

---

* Tested system after deployment:
  * Accessed system via internet  
  * Tested user flow (browse, add to cart, checkout)  
  * Tested admin flow  
  * Ensured system stability across modules  

---

* Gained clear understanding of deployment pipeline:
  * Code → Docker → ECR → ECS → ALB → User  