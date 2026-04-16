\# 🚀 Monitoring System - Vishwas



A production-style cloud monitoring system built using AWS, Docker, Prometheus, and Grafana to collect, process, and visualize real-time system metrics.



\---



\## 🌐 Live Architecture



```

User → EC2 → Nginx → Docker App

&#x20;                ↓

&#x20;       Node Exporter → Prometheus → Grafana

&#x20;                ↑

&#x20;            CI/CD (GitHub Actions)

```



\---



\## 📌 Overview



This project demonstrates a complete DevOps workflow — from deploying an application to monitoring system performance in real time.



It was built to explore observability, automation, and infrastructure management using industry-standard tools.



\---



\## ⚙️ Tech Stack



\* ☁️ AWS EC2 (Ubuntu)

\* 🌐 Nginx (Web Server)

\* 🐳 Docker (Containerization)

\* 🔁 GitHub Actions (CI/CD)

\* 📊 Prometheus (Metrics Collection)

\* 📈 Grafana (Visualization)

\* 📡 Node Exporter (System Metrics)



\---



\## 🚀 Features



\* Real-time monitoring of CPU, memory, disk, and network usage

\* Automated deployment using CI/CD pipeline

\* Containerized application using Docker

\* Metrics scraping and storage using Prometheus

\* Interactive dashboards with Grafana

\* Basic incident detection and troubleshooting



\---



\## 🔧 Setup Instructions



\### 1. Clone Repository



```bash

git clone https://github.com/vishwasgv/monitoring-system.git

cd monitoring-system

```



\---



\### 2. Run Application (Docker)



```bash

docker build -t monitoring-app .

docker run -d -p 80:80 monitoring-app

```



\---



\### 3. Start Node Exporter



```bash

cd node\_exporter-\*

./node\_exporter

```



\---



\### 4. Start Prometheus



```bash

cd prometheus-\*

./prometheus

```



\---



\### 5. Access Services



\* App: http://<EC2-IP>

\* Prometheus: http://<EC2-IP>:9090

\* Grafana: http://<EC2-IP>:3000



\---



\## 📊 Dashboard Preview



(Add your Grafana screenshot here)



\---



\## 🧠 Learnings



\* Understanding system observability and monitoring pipelines

\* Debugging real-world issues (port conflicts, service failures)

\* Managing multiple services simultaneously

\* Building CI/CD pipelines for automated deployments

\* Working with cloud infrastructure (AWS EC2)



\---



\## 🔥 Challenges Faced



\* Fixing Nginx service failures

\* Handling Docker port conflicts

\* Resolving Prometheus connection issues

\* Managing multiple processes across terminals

\* Debugging security group/network access issues



\---



\## 🚀 Future Improvements



\* Add alerting (Slack/Email notifications)

\* Convert services to systemd for auto-start

\* Monitor multiple servers (scaling)

\* Add HTTPS with reverse proxy

\* Improve UI and frontend



\---



\## 🤝 Connect



If you found this interesting or have suggestions, feel free to connect or reach out!



\---



⭐ If you like this project, consider giving it a star!



