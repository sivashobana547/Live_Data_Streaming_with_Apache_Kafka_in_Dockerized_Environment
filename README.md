# 🚀 Real-Time Data Streaming with Apache Kafka Using Docker and Docker Compose

## 📌 Project Overview
This project demonstrates a real-time data streaming system built using Apache Kafka, fully containerized with Docker and orchestrated using Docker Compose. The goal is to enable live communication between two command-line processes using Kafka’s producer–consumer model in a distributed environment.

---

## 🧠 Why This Project Matters
- Simulates real-world streaming pipelines  
- Demonstrates event-driven architecture  
- Shows practical Docker Compose orchestration  
- Builds strong foundation for data engineering roles  

---

## 🏗️ Architecture Overview
[Producer CLI] → [Kafka Topic] → [Consumer CLI]  
(All components run inside Docker containers)

---

## ⚙️ Technologies Used
- Apache Kafka  
- Docker  
- Docker Compose  
- Command Line Interface (CLI)  

---

## 🧩 Components
- Kafka Broker  
- Zookeeper  
- Producer (CLI-based)  
- Consumer (CLI-based)  

---

## 🛠️ Docker Compose Setup
Docker Compose is used to manage Kafka and Zookeeper services, handle container networking, and enable reproducible multi-container deployment using a single command.

---

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
