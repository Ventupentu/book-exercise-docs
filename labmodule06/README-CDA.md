# Constrained Device Application (Connected Devices)

## Lab Module 06

Be sure to implement all the PIOT-CDA-* issues (requirements) listed.

### Description

This implementation introduces MQTT connectivity to the Constrained Device Application (CDA) by developing the `MqttClientConnector.py` module. The main goal is to enable the CDA to publish and subscribe to MQTT messages, allowing seamless communication with other IoT devices, the Gateway Device Application (GDA), and cloud platforms. The implementation follows the official lab instructions, integrating the new connector in a modular and reusable way within the existing architecture.

Due to repository and branch management issues, the development for this lab (Lab Module 06) was completed and merged into the branch for Lab Module 10. Therefore, all changes and the final integration of the MQTT connector can be found in the branch/practice 10 of the repository. This approach was chosen to avoid code duplication and to facilitate continuous integration, as technical and synchronization issues with branches were encountered during development.

### Code Repository and Branch

URL:  
https://github.com/Ventupentu/python-components/tree/labmodule10

> **Note:** Although this documentation is for Lab Module 06, the actual implementation is in the branch/practice 10 due to the reasons mentioned above.

### Unit Tests Executed

- ConfigUtilTest
- DataUtilTest
- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- HumiditySensorSimTaskTest
- PressureSensorSimTaskTest
- TemperatureSensorSimTaskTest
- HumidifierActuatorSimTaskTest
- HvacActuatorSimTaskTest
- MqttClientConnectorTest

### Integration Tests Executed

- DeviceDataManagerNoCommsTest
- SensorAdapterManagerTest
- ActuatorAdapterManagerTest
- SensorEmulatorManagerTest
- ActuatorEmulatorManagerTest
- MqttClientConnectorTest
- ConstrainedDeviceAppTest

> **Note:** Integration and unit tests include those from previous modules to ensure no regressions are introduced and that MQTT integration works correctly within the global system context.

EOF.
