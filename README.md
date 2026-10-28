# Hi, I'm Tanat Kerdtip

### About Me
- **Education:** 4th-year Computer Science student (Minor in DevOps) @ Thammasat University, graduating May 2027
- **Now:** Programmer Intern @ CDG Systems (CDG Group)
- **Interests:** DevOps, DevSecOps, and Platform Engineering
- **Resume:** [tanatworks.github.io](https://tanatworks.github.io/)

## Experience

### Programmer Intern @ CDG Systems (CDG Group)
*Jun 2026 – Present · Bangkok*

- Contribute to rebuilding legacy enterprise web systems with a modern web stack
- Build and test RESTful APIs and database queries in an Agile team, managing code with Git

### Teaching Assistant, CS222 Operating Systems @ Thammasat University
*Mar 2026 – May 2026*

- Graded Linux, Bash, and C process-management assignments for a class of 80+ students

## Projects

### [Geemu](https://github.com/tanatworks/Geemu): DevSecOps Pipeline on AWS
*DevOps Engineer · Mar 2026 – May 2026 · Team of 2*

- Automated Amazon EKS setup in a Jenkins pipeline, from Terraform provisioning to ArgoCD installation
- Built a 12-stage Jenkins CI/CD pipeline with SAST (SonarQube), dependency scanning (OWASP), and container image scanning (Trivy) that runs in ~3 minutes
- Deployed to EKS through GitOps with ArgoCD, with GitHub Actions triggering builds and skipping `[skip ci]` commits

**Tech:** AWS (EC2, EKS, VPC), Terraform, Jenkins, GitHub Actions, SonarQube, OWASP Dependency-Check, Trivy, Docker, Kubernetes, ArgoCD

![Geemu architecture](https://raw.githubusercontent.com/tanatworks/Geemu/main/docs/architecture.gif)

### [MonitorDisaster](https://github.com/tanatworks/CS366_MonitorDisasterService): Disaster Monitoring Microservice
*Backend & Cloud Developer · Jan 2026 – May 2026 · Solo*

- Built a REST API that ingests real-time sensor data and publishes disaster alerts via Amazon SNS
- Processed cross-cloud events from Amazon SQS, storing area status and incident reports in DynamoDB
- Added a retry worker with exponential backoff and trace IDs to keep data consistent across services

**Tech:** Node.js, Express, AWS (ECS Fargate, API Gateway, SQS, SNS, DynamoDB), Docker

### [Miley](https://github.com/Somxhai/Miley-Chatbot): Product Recommendation LINE Chatbot
*Backend & DevOps Developer · Aug 2025 – Dec 2025 · Team project*

- Co-provisioned AWS infrastructure (ECS, DynamoDB, VPC) with CloudFormation (IaC) for repeatable deployments
- Co-built the LINE message path (API Gateway, ALB, ECS, SQS, Lambda) to the Qwen3 LLM and back to LINE
- Set up Amazon CloudWatch dashboards to monitor each service's response time

**Tech:** AWS (ECS, Lambda, API Gateway, ALB, SQS, DynamoDB, VPC, CloudWatch, CloudFormation), LINE Messaging API, Qwen3 LLM

![Miley AWS Architecture](https://github.com/Somxhai/Miley-Chatbot/raw/docs/img/docs/img/Final_pic/Miley_AWS_Architecture.png)

### [Chalapao](https://github.com/Somxhai/chalapao): Online Borrowing Website
*Frontend Developer · Jan 2025 – May 2025*

- Built a full-stack inventory management system to improve item tracking
- Deployed with Docker to keep environments consistent

**Tech:** PostgreSQL, Docker Compose

### Public Safety Surveillance: Firearm Detection
*AI/ML Developer · Jan 2025 – May 2025*

- Trained a YOLOv11 object-detection model on Roboflow to tell real firearms from water guns, aimed at public safety during Songkran

**Tech:** Python, YOLOv11, Roboflow

### [Online Petition Submission](https://github.com/krittamark/cs261-group1-100001): Web App
*Full-stack Developer · Aug 2024 – Dec 2024*

- Built a student petition tracking system with Express and Spring Boot to simplify submissions
- Containerized services with Docker and worked in an Agile team for iterative delivery

**Tech:** Express, Spring Boot, Docker

---
## Tech Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

`EC2` `ECS` `EKS` `Lambda` `S3` `SQS` `SNS` `VPC` `CloudWatch` `CloudFormation (IaC)`

**CI/CD & DevSecOps**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

`SonarQube (SAST)` `OWASP Dependency-Check` `Trivy`

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Backend & Web**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)

`SQL` `NoSQL`

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

`SVN`

**Currently Learning**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

---

## Contact
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanat-kerdtip/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tanat.kerdtip@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-1B3A6B?style=for-the-badge&logo=googledocs&logoColor=white)](https://tanatworks.github.io/)
