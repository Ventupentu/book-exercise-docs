# Gateway Device Application (Connected Devices)

## Lab Module 05

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

This implementation involves building the data management and transformation capabilities for the Gateway Device Application (GDA). The goal is to add JSON serialization and deserialization functionalities for handling sensor and actuator data, enabling seamless data exchange between the GDA and CDA. The GDA will leverage the `DataUtil` class to convert sensor and actuator data objects into a JSON format, allowing it to communicate effectively with the CDA. This process ensures that both applications can interpret and exchange data in a standardized manner, facilitating smooth integration.

In addition to JSON serialization, this implementation also includes optional configuration for integrating Time-Series databases such as Redis or InfluxDB. These databases will serve as data stores for sensor readings and actuator commands, enabling better data persistence and management. By implementing these features, the GDA becomes more capable of handling and processing large volumes of sensor and actuator data while maintaining data consistency and integrity.

### Code Repository and Branch

URL: https://github.com/Ventupentu/java-components/tree/labmodule5

### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below (e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too, since you need to ensure you haven't introduced regressions.

- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- SystemSatateDataTest
- DataUtilTest
- ConfigUtilTest
- GatewayDeviceAppTest
- SystemCpuUtilTaskTest
- SystemMemUtilTaskTest


### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with some exceptions (such as your cloud connectivity tests). In such cases, they'll review your code to ensure it's correct. As for the tests you execute, you only need to list each test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- SystemPerformanceManagerTest
- DataIntegrationTest
- DeviceDataManagerNoCommsTest
- GatewayDeviceAppTest

EOF.
