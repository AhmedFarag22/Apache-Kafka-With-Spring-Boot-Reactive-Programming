# 📡 Real-time Wikimedia Stream Processing with Apache Kafka & Spring Boot

## 🚀 Overview
This project demonstrates how to build a **real-time data pipeline** using **Spring Boot** and **Apache Kafka**.  
It listens to **Wikimedia’s Recent Changes Streaming API** 🌍 and publishes every event into a Kafka topic.  
On the other side, a Kafka Consumer service subscribes to the topic and processes the incoming data.  

This setup is a practical example of **Event-Driven Architecture**, widely used in **Microservices** and **Big Data** systems.

---

## ✨ Key Features
- 🔹 **Producer Service**:
  - Connects to Wikimedia’s public streaming API.
  - Uses `WebClient` (Reactive & Non-blocking) to consume live events.
  - Publishes each event to a Kafka topic (`wikimedia-stream`).

- 🔹 **Consumer Service**:
  - Subscribes to the Kafka topic (`wikimedia-stream`).
  - Processes and logs each incoming message.
  - Configurable `groupId` to allow multiple consumer groups.

- 🔹 **Technologies & Skills Demonstrated**:
  - **Spring Boot** (REST, Kafka Integration).
  - **Apache Kafka** (Producer, Consumer, Topics).
  - **WebClient** (Reactive programming, streaming APIs).
  - **Event-driven microservices architecture**.
  - Real-time data ingestion & processing.

---


📬 Contact

👨‍💻 Author: Ahmed Farag
📧 Email: farag0336@gmail.com

💼 LinkedIn: [Ahmed Farag](https://www.linkedin.com/in/ahmed-farag-93a74324a/)

💻 Passionate about Java, Spring Boot & Full Stack Development.
