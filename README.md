# Real-Time Stream Processing with Apache Spark and Kafka

A distributed stream processing system built using Apache Spark Streaming and Apache Kafka, containerized with Docker for scalable real-time data processing.

## 🎯 Project Overview

This project demonstrates the implementation of a real-time data streaming pipeline using industry-standard tools for distributed computing. The system processes streaming data from Kafka topics using Spark Structured Streaming, showcasing modern big data processing architectures.

## 🛠️ Technologies Used

- **Apache Kafka** - Distributed event streaming platform
- **Apache Spark** (Spark Structured Streaming) - Real-time data processing engine
- **Apache Zookeeper** - Coordination service for distributed systems
- **Docker** - Containerization platform for consistent deployment
- **Scala** - Programming language for Spark applications

## 📋 Key Features

- Real-time message streaming and processing
- Dockerized microservices architecture
- Kafka topic management and message production
- Spark DataFrame operations on streaming data
- Console-based output for stream monitoring

## 🏗️ System Architecture

The system consists of three main components running in Docker containers:

1. **Zookeeper Container** - Manages Kafka cluster coordination
2. **Kafka Container** - Handles message brokering and topic management
3. **Spark Container** - Processes streaming data in real-time

All containers communicate through a dedicated Docker network (`kafka-net`) for isolated and secure data flow.

## 💡 Implementation Highlights

### Data Pipeline Flow
1. Created Kafka topic (`testTopic`) for message streaming
2. Produced messages to the Kafka topic using console producer
3. Configured Spark Structured Streaming to consume from Kafka
4. Processed streaming data using DataFrame transformations
5. Output results to console in real-time batches

### Technical Achievements
- Successfully configured multi-container Docker networking
- Integrated Kafka with Spark using proper dependency packages
- Implemented schema validation for streaming DataFrames
- Handled streaming query lifecycle management

## 📊 Results

The system successfully demonstrated:
- Real-time message ingestion from Kafka topics
- DataFrame-based stream processing in Spark
- Continuous query execution with batch processing
- Structured output formatting for monitoring

## 🚀 Skills Demonstrated

- **Distributed Systems**: Understanding of message brokers and stream processing
- **Big Data Technologies**: Hands-on experience with Apache Spark and Kafka
- **Containerization**: Docker networking and multi-container orchestration
- **Data Engineering**: Building scalable data pipelines
- **Problem-Solving**: Debugging connectivity and dependency issues

## 📄 Documentation

For detailed implementation steps, commands, and technical documentation, see the [full project report](streaming.pdf).

## 🎓 Background

Built this project to explore distributed computing and real-time data processing technologies. Collaborated with a fellow student to deepen understanding of modern data engineering architectures and gain hands-on experience with industry-standard tools used by companies like Netflix, Uber, and LinkedIn for their streaming infrastructure.

## 🔗 Connect

**Meriem Lmoubariki**
- GitHub: [@myriamlmiii](https://github.com/myriamlmiii)

---

*This project showcases proficiency in distributed systems, real-time data processing, and modern data engineering practices.*
