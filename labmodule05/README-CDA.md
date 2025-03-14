# Constrained Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

This implementation focuses on enabling data management and transformation capabilities in the Constrained Device Application (CDA). By adding JSON serialization and deserialization functionalities to the sensor and actuator data, the CDA will be able to communicate seamlessly with the Gateway Device Application (GDA). The core objective of this implementation is to convert the sensor and actuator data into a consistent JSON format, making it easier for both the CDA and GDA to interpret and share the data. The implementation includes methods for serializing and deserializing the `SensorData`, `ActuatorData`, and `SystemPerformanceData` objects.

The system follows a robust architecture where the `DataUtil` class in the CDA is responsible for converting the data wrappers into a JSON format. These JSON-formatted messages are then used for communication between the CDA and GDA. As a result, both applications can efficiently exchange and process sensor readings, actuator commands, and system performance data in a consistent manner. Additionally, optional configurations for Time-Series databases like Redis or InfluxDB can be integrated for enhanced data storage and management capabilities.

### Code Repository and Branch

URL:  https://github.com/Ventupentu/java-components/tree/labmodule5

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below (e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too, since you need to ensure you haven't introduced regressions.

- DataUtilTest

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with some exceptions (such as your cloud connectivity tests). In such cases, they'll review your code to ensure it's correct. As for the tests you execute, you only need to list each test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- DataIntegrationTest

EOF.
