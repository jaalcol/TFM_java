# TFM_java

Repository dedicated to Java development for Apache Flink within the real-time anomaly detection Master's thesis.

## Main Functionality

- Reading data from Kafka.
- Real-time inference using models exported from Spark.
- Sending results to downstream systems.

## Description

The code is packaged as a shaded JAR for Flink, using Maven to manage dependencies and builds. It integrates with the data flow managed from Python.

## Technologies

- Java 11+
- Apache Flink
- Maven
- Shaded JAR for Flink
- Kafka (streaming)
- Machine learning models exported from PySpark