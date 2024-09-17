
## Project Overview
The project builds a real-time music recommendation system for Spotify using distributed big data processing technologies. The primary goal is to provide personalized music recommendations to users in real-time by leveraging machine learning models integrated with Apache Kafka and PySpark. Real-time music data is ingested through Kafka, processed with PySpark and Spark Streaming, and Docker is utilized to containerize and manage the services for ease of deployment and scalability.

## Features of the Dataset:
    - Music Data Stream: Streaming music data from Kafka topics.
    - Real-Time Processing: Processing data as it arrives in real time.
    - User Preferences: Leveraging user preferences and past data to recommend songs.


## Contents



## Dependencies
Ensure the following are installed before running the code:

<li>Python
<li>Apache Kafka: For managing the real-time streaming data.
<li>PySpark: For distributed data processing and machine learning.
<li>Docker: To run and manage containerized services.
<li>Kafka-Python: Python client for interacting with Kafka.
<br>
Other necessary libraries and frameworks include Spark Streaming, Kafka Streams, Zookeeper, and standard Python libraries such as Pandas and Scikit-learn.

## Credits
This project was developed as part of the Data Science Academy's course. The system architecture follows best practices in real-time data processing and machine learning, focusing on scalable and efficient recommendation systems for the music streaming domain.