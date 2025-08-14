\# 🖥️ Netdata Monitoring Setup (via Docker)



This repository demonstrates how to install and run \*\*Netdata\*\* using Docker to monitor system and container performance in real time.  

Netdata provides instant, per-second metrics for CPU, memory, disk, network, and applications, including Docker containers.



---



\## 📋 Objective

\- Install Netdata in Docker

\- Access and explore the dashboard

\- Monitor CPU, memory, disk, and Docker containers

\- Understand lightweight server monitoring



---



\## 🛠 Tools

\- \[Netdata](https://www.netdata.cloud/) (Free, Open Source)

\- Docker



---



\## 🚀 Step-by-Step Setup



\### 1️⃣ Create persistent volumes

```bash

docker volume create netdataconfig

docker volume create netdatalib

docker volume create netdatacache



