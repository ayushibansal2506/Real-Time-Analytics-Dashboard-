# Real-Time Analytics Dashboard

A scalable real-time analytics platform designed to process, analyze, and visualize streaming event data. The system ingests high-volume user events, processes them using distributed streaming frameworks, and provides real-time insights through interactive dashboards.

## Overview

This project demonstrates the design and implementation of an end-to-end data engineering pipeline capable of handling real-time event streams. The platform collects user activity data, processes it in real time, stores analytical metrics, and enables visualization for monitoring and decision-making.

## Features

* Real-time event ingestion and processing
* Stream processing pipeline for analytics generation
* Automated data transformation and aggregation
* Interactive dashboard visualization
* Containerized deployment using Docker
* Scalable architecture for high-volume event streams
* Monitoring and performance tracking

## Architecture

```text
Event Producers
       │
       ▼
     Kafka
       │
       ▼
 Spark Streaming
       │
 ┌─────┴─────┐
 ▼           ▼
Analytics   Storage
Database    Layer
       │
       ▼
 Dashboard &
 Visualization
```

## Tech Stack

### Data Processing

* Apache Kafka
* Apache Spark Streaming
* Python

### Data Storage

* PostgreSQL

### Infrastructure

* Docker
* Docker Compose

### Analytics & Visualization

* Real-Time Monitoring Dashboard

## Project Structure

```text
.
├── dags/
├── script/
├── docker-compose.yml
├── spark_stream.py
├── requirements.txt
├── README.md
└── Data engineering architecture.png
```

## Workflow

1. Generate or receive streaming event data.
2. Publish events to Kafka topics.
3. Consume events using Spark Streaming.
4. Process and aggregate metrics in real time.
5. Store processed data in the analytics database.
6. Visualize business metrics through dashboards.

## Key Learning Outcomes

Through this project, I gained experience in:

* Building real-time data pipelines
* Stream processing with Kafka and Spark
* Distributed data processing concepts
* Data ingestion and transformation workflows
* Containerized deployments using Docker
* Analytics system design and monitoring

## Future Improvements

* Redis-based caching layer
* Kubernetes deployment
* Advanced monitoring and alerting
* Data quality validation pipelines
* CI/CD automation
* Cloud deployment (AWS/GCP)



Ayushi Bansal
M.Sc. Chemistry + B.E. Mechanical Engineering
BITS Pilani, Hyderabad Campus

