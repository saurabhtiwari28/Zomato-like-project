# 🚀 **DevOps Project: ZOMATO Clone App Deployment**
Overview: Developed a Zomato-like application to provide users with an intuitive platform for restaurant discovery, food ordering, and reviews, while implementing a robust DevOps pipeline to automate the development, testing, deployment, and monitoring processes.
In this **DevOps project**, I demonstrate how to **deploy a ZOMATO Clone App** using a variety of modern DevOps tools and services.

## 🛠️ Tools & Services Used:

1. **GitHub** ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
2. **Jenkins** ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
3. **SonarQube** ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
4. **Docker** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
5. **Kubernetes** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
6. **Prometheus** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
7. **Grafana** ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
8. **ArgoCD** ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
9. **OWASP** ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
10. **Trivy** ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white)

---

### Project Stages:

1. **Stage 1** - Deployment of App to Docker Container
2. **Stage 2** - Deployment of App to K8S Cluster with Monitoring

Project Highlights:

    GitHub & Jenkins for CI/CD:
        Integrated GitHub for version control, enabling collaborative development.
        Set up Jenkins for Continuous Integration to automatically build and test code. Automated unit tests, integration tests, and static code analysis using SonarQube for code quality and OWASP ZAP for security testing.

    Docker & Security Scanning:
        Containerized the application using Docker, ensuring consistency across environments.
        Integrated Docker Scout and Trivy to scan Docker images for vulnerabilities before deployment, enhancing security in production.

    Automated Deployment with Kubernetes:
        Set up Amazon EKS to manage a Kubernetes cluster for high scalability and availability of the application.
        Deployed the application using Argo CD for continuous delivery, ensuring seamless updates and rollbacks.
        Utilized Helm to manage Kubernetes resources, making the deployment process more efficient and reproducible.

    Monitoring & Alerts:
        Configured Prometheus to monitor system metrics using Node Exporter and application metrics.
        Visualized data in real-time using Grafana dashboards, providing insights into system performance and resource usage.
        Set up email alerts through Prometheus and Jenkins for automated notifications on build failures, security vulnerabilities, and critical system metrics.

Achievements & Impact:

    Automation & Efficiency: Streamlined the entire development lifecycle, reducing manual intervention and ensuring consistent, error-free deployments with the automated CI/CD pipeline.
    Security-First Approach: Embedded security into the DevOps pipeline with automated scans using OWASP ZAP, SonarQube, and Trivy, proactively identifying and addressing security vulnerabilities.
    Scalability: Leveraged Kubernetes (EKS) to automatically scale the application based on traffic, ensuring high availability and efficient resource management.
    Real-Time Monitoring: With Prometheus and Grafana, achieved comprehensive visibility into system health and application performance, enabling proactive issue detection.

This project demonstrates my ability to design and implement a full-scale DevOps pipeline, from code development to deployment, while ensuring security, scalability, and operational efficiency in a real-world application.
