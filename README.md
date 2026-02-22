Real-Time Stock Market Data Pipeline

Project Overview
This project builds an end-to-end real-time data engineering pipeline that collects live stock prices, streams them using Apache Kafka, stores them in AWS S3, and queries them using Amazon Athena.

Tech Stack
- Python
- Apache Kafka
- AWS EC2
- AWS S3
- AWS Glue
- Amazon Athena
- yFinance API

Architecture

Producer → Kafka → Consumer → S3 → Athena

## ⚙️ Features
✔ Real-time stock data ingestion  
✔ Kafka streaming pipeline  
✔ Automatic storage in S3  
✔ Athena SQL analytics  
✔ Scalable cloud architecture  

Sample Query

SELECT * FROM kafka_stock_market_abhishek LIMIT 10;
