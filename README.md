# Kafka Project

This project demonstrates the usage of Apache Kafka.

## Prerequisites

Before you begin, ensure you have the following installed:
- IDE (Integrated Development Environment)
- Java Development Kit (JDK) 17

## Getting Started

Follow these steps to set up and run the Kafka project:

### 1. Clone the Repository

```bash
git clone https://github.com/itiwarishubham/kafka.git
```

### 2. Configure the Application

- Download Apache Kafka from https://kafka.apache.org/downloads and follow these steps:
- Unzip the downloaded binary

### 3. Run the Application

Start Zookeeper
```bash
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
```
Start Kafka Server
```bash
.\bin\windows\kafka-server-start.bat .\config\server.properties
```
Start Kafka Console Consumer
```bash
.\bin\windows\kafka-console-consumer.bat --topic test --from-beginning --bootstrap-server localhost:9092
```
