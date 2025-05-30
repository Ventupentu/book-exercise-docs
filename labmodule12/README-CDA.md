# Gateway Device Application (Connected Devices)

## Lab Module 12 - Semester Project - GDA Components

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

The GDA has been enhanced to support advanced data aggregation, protocol bridging, and cloud integration for the semester project. It now receives and processes sensor data (including vibration, humidity, temperature, and pressure) and actuator commands from multiple CDAs via MQTT and CoAP. The GDA can forward relevant data to cloud services (such as Ubidots), store it locally, and provide management and monitoring interfaces. The system is designed to be robust, scalable, and easily extensible for new sensor types or cloud endpoints.

The GDA manages all protocol connections, including MQTT client, CoAP server, and optional persistence layers. It ensures reliable message delivery, topic subscription management, and data transformation as needed for downstream services. The codebase includes comprehensive unit and integration tests to validate all core features and prevent regressions.

### Code Repository and Branch

URL:  
https://github.com/Ventupentu/python-components/tree/labmodule_12

### Unit Tests Executed

- ConfigUtilTest
- DataUtilTest
- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- MqttClientConnectorTest
- CoapServerGatewayTest

### Integration Tests Executed

- DeviceDataManagerTest
- MqttClientConnectorTest
- CoapServerGatewayTest
- GatewayDeviceAppTest

EOF.
