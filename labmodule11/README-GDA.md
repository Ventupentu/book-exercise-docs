# Gateway Device Application (Connected Devices)

## Lab Module 11

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do?

The implementation receives messages via MQTT and uploads them to the Ubidots cloud. The information sent includes the activation status of the LED actuator, memory and CPU usage, temperature, and humidity.

How does your implementation work?

In the `MqttClientConnector`, functionalities were added to connect to the cloud. The JSON received via MQTT is modified to comply with the Ubidots standard.

### Code Repository and Branch

NOTE: Be sure to include the branch.

URL: //github.com/Ventupentu/java-components/tree/labmodule11


### Unit Tests Executed

NOTE: The instructor will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: The instructor will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- MqttClientConnectorTest
- CloudClientConnectorTest
- 

EOF.

