# Constrained Device Application (Connected Devices)

## Lab Module 03

Be sure to implement all the PIOT-CDA-* issues (requirements).

### Description

Lab Module 03 focuses on building a simple simulation and data generation capability within the CDA. The implementation involves using a provided or custom-built data generator to simulate sensor readings for humidity, pressure, and temperature. The generated data is then packaged into telemetry objects, which contain additional information about the device and its environment. A threshold-based trigger is also incorporated to simulate actuation events when specific conditions are met.

The implementation applies Object-Oriented design principles to facilitate easy expansion, allowing additional simulated sensing and actuation capabilities to be integrated seamlessly. The simulation logs actuation events as part of the emulated process, ensuring that data flow and device responses are accurately represented within the CDA framework.

### Code Repository and Branch

URL: https://github.com/Ventupentu/python-components/tree/labmodule03

### Unit Tests Executed

The following unit tests were executed to validate the implementation and ensure no regressions were introduced:

- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- HumiditySensorSimTaskTest
- PressureSensorSimTaskTest
- TemperatureSensorSimTaskTest
- HumidifierActuatorSimTaskTest
- HvacActuatorSimTaskTest

### Integration Tests Executed

The following integration tests were executed to verify system-wide functionality:

- SensorAdapterManagerTest
- ActuatorAdapterManagerTest
- DeviceDataManagerNoCommsTest
- ConstrainedDeviceAppTest

EOF.

