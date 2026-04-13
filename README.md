# 💬 ChatAppActiveMQ

An instant messaging application developed in **Java** in 2023 as part of an academic project for a **Bachelor’s Degree (BAC +3) in Software Engineering (BIU P08)**, במסגרת the course **Software Engineering Workshop**.

👨‍💻 Developed by **Josh N’zighali**

---

## 📌 Overview

**ChatAppActiveMQ** is a real-time chat application that enables multiple users to communicate simultaneously using an asynchronous messaging system.

The application is built on a **Message-Oriented Middleware (MOM)** architecture, ensuring:
- Reliable message delivery  
- High performance  
- Scalability  

---

## ⚙️ Features

- 💬 Real-time messaging between multiple users  
- 📩 Instant sending and receiving of messages  
- 👥 User connection management  
- 📦 Message queue system using ActiveMQ  
- 🖥️ Simple and intuitive user interface  
- ⚠️ Communication error handling  

---

## 🛠️ Technologies Used

- **Java (JDK 8+)**
- **Apache ActiveMQ**
- **JMS (Java Message Service)**
- **Swing / JavaFX**
- **Client-Server Architecture**

---

## 🧠 Architecture

The application follows a **Producer–Consumer model**:

- **Producer** → Sends messages to the queue  
- **Consumer** → Receives messages from the queue  
- **ActiveMQ Broker** → Manages message queues and delivery  

This ensures asynchronous and decoupled communication between users.

---

## 👨‍💻 Contributions

- Designed the messaging system architecture  
- Integrated ActiveMQ for message queue handling  
- Implemented producer/consumer communication logic  
- Built the user interface  
- Conducted testing and system validation  

---

## 🎯 Learning Objectives

- Understand distributed messaging systems  
- Learn how to use JMS and ActiveMQ  
- Implement asynchronous communication in Java  
- Apply software engineering and architecture principles  

---

## ✅ Results

This project demonstrates the ability to build a **reliable distributed application**, capable of handling real-time communication efficiently between multiple users.

---

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or higher  
- Apache ActiveMQ installed and running  

### Run the Application

1. Start ActiveMQ server:
   ```bash
   activemq start
