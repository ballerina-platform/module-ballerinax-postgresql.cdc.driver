## Overview

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
