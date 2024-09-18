
## Project Overview
The project builds a real-time music recommendation system for Spotify using distributed big data processing technologies. The primary goal is to provide personalized music recommendations to users in real-time by leveraging machine learning models integrated with Apache Kafka and PySpark. Real-time music data is ingested through Kafka, processed with PySpark and Spark Streaming, and Docker is utilized to containerize and manage the services for ease of deployment and scalability.

## Features of the Dataset:
    - Music Data Stream: Streaming music data from Kafka topics.
    - Real-Time Processing: Processing data as it arrives in real time.
    - User Preferences: Leveraging user preferences and past data to recommend songs.


## Contents

<li> data : Dataset
<li> jars : Spark jars connectors
<li> output : Result of recommendation
<li> containers_docker.txt : Guide for docker
<li> docker-compose.yml : Docker configuration
<li> kafka_topic.txt : Guide for Kafka
<li> Music_Recom_1.ipynb : Data Ingestion and Preprocessing
<li> Music_Recom_2.ipynb : Spark Streaming and Machine Learning

## Dependencies
Ensure the following are installed before running the code:

<li>Python
<li>Apache Kafka: For managing the real-time streaming data.
<li>PySpark: For distributed data processing and machine learning.
<li>Docker: To run and manage containerized services.
<li>Kafka-Python: Python client for interacting with Kafka.
<br>
<br>
Other necessary libraries and frameworks include Spark Streaming, Kafka Streams, Zookeeper, and standard Python libraries such as Pandas and Scikit-learn.

## How to run

<li> 1. Create the docker (containers_docker.txt)
<li> 2. Open Kafka Terminal
<li> 3. Create the Kafka topic (kafka_topic.txt)
<li> 4. Run Music_Recom_1.ipybnb
<li> 5. Consume data in Kafka topic (kafka_topic.txt)
<li> 6. Run Music_Recom_2.ipybnb
<li> 7. Change spotify client/secret/username

## Credits
This project was developed as part of the Data Science Academy's course. The system architecture follows best practices in real-time data processing and machine learning, focusing on scalable and efficient recommendation systems for the music streaming domain.