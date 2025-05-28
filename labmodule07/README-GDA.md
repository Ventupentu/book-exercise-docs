# Gateway Device Application (Connected Devices)

## Lab Module 07

Be sure to implement all the PIOT-GDA-* issues (requirements) listed.

### Description

This implementation adds MQTT client connectivity to the Gateway Device Application (GDA). The main goal is to enable the GDA to connect to an MQTT broker, subscribe to relevant topics, and publish messages as required for IoT gateway operations. The core of this implementation is the new `MqttClientConnector` class, which wraps the Eclipse Paho MQTT client and provides methods for connecting, disconnecting, subscribing, unsubscribing, and publishing messages. The DeviceDataManager is updated to instantiate and manage the MQTT client, including subscribing to all required topics on startup and unsubscribing on shutdown.

The implementation is designed to be modular and configurable. All MQTT connection parameters (host, port, keep-alive, etc.) are loaded from the configuration file using `ConfigUtil` and `ConfigConst`. The GDA can now act as a bridge between the Constrained Device Application (CDA) and cloud or local services using MQTT as the transport protocol. This enables seamless integration with other IoT components and platforms.

### Code Repository and Branch

URL:  
https://github.com/Ventupentu/java-components/tree/labmodule07

### Unit Tests Executed

- ConfigUtilTest
- DataUtilTest
- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- MqttClientConnectorTest

### Integration Tests Executed

- DeviceDataManagerTest
- MqttClientConnectorTest

> **Note:** All previous unit and integration tests were executed to ensure no regressions were introduced and that MQTT integration works as expected.

EOF.
