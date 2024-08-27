# Real-time-Stock-Market-Monitoring-System

## Introduction:

This project involves developing a backend system for real-time monitoring and analysis of stock market data. The system ingests live financial data from multiple APIs, stores historical data in PostgreSQL, and provides real-time metrics for visualization in Grafana. Implemented Prometheus for metric collection and alerting, with notifications set up for significant stock price movements. 
The system is containerized using Docker and deployed on Kubernetes for scalability.

## Key Features & Functionalities

-	Real-time Data fetching and processing of live data for 20+ stocks from various sources.
- Calculation of Trading Strategies such as 50-day and 200-day Simple Moving Averages (SMA) to identify market trends.
- Real-time alerts to the users of key trading signals like Golden Crossovers and Death Crosses and many more trading strategies to follow.
- Interactive visualizations for real-time and historical stock data and technical indicators.
- Utilizing a microservices architecture with load balancing and caching for efficient performance.
- Storing and managing historical financial data and calculate technical indicators.

## Tech Stack
- [Programming Languages](): Go, Python
- [APIs for Financial Data](): Yahoo Finance, NSE
- [Real-Time Data Processing](): Apache Kafka
- [Monitoring Tools](): Prometheus(for metric collection & alerting), Grafana(for visualization
- [Database](): PostgreSQL(for data storage), InfluxDB, Redis(for caching), ElasticSearch
- [Deployment & Orchestration](): Docker, Kubernetes
- [CI/CD](): Jenkins, GitHub Actions

