## Overview

The PostgreSQL Change Data Capture (CDC) driver enables capturing and tracking data changes in PostgreSQL databases in real-time. It provides a reliable way to stream data modifications (Insert, Update, Delete) to downstream systems for processing or synchronization. The CDC driver is essential for building real-time data integration and synchronization pipelines.

### Key Features

- Real-time capturing of data changes (Insert, Update, Delete)\n- Seamless streaming of data modifications to downstream systems\n- Reliable tracking of database changes with minimal overhead\n- Support for various CDC mechanisms and configurations\n- Secure communication and efficient data handling\n- GraalVM compatible for native image builds


This library provides the necessary Debezium drivers required for the CDC (Change Data Capture) connector in Ballerina.
It enables listening to changes in Postgres databases seamlessly within Ballerina projects.

## Compatibility

| |     Version     |
|:---|:---------------:|
|Ballerina Language |  **2201.12.0**   |
|Debezium Postgres Driver | **3.0.8.Final** |

## Usage

To include the `postgresql.cdc.driver` dependency in your project, simply import the module as shown below:

```ballerina
import ballerinax/cdc;
import ballerinax/postgresql.cdc.driver as _;
```

The `postgresql.cdc.driver` library is bundled with the required drivers, so no additional configuration is needed.
