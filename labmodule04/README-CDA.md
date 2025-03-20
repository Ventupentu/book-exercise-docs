# Constrained Device Application (Connected Devices)

## Lab Module 04

### Description

In this implementation, we integrate the Sense HAT emulator into our Constrained Device Application (CDA) to simulate real-time sensor readings and actuation capabilities. The system collects environmental data, such as temperature, humidity, and pressure, using the emulator's built-in sensors and processes this information according to predefined logic. Additionally, the implementation includes an actuation mechanism that allows the CDA to interact with the emulator's LED display, providing a visual representation of specific events or conditions.

Our approach follows the design principles established in Lab Module 03, ensuring seamless integration with previous components. The implementation is structured into modules that handle data acquisition, processing, and actuation separately, improving maintainability and scalability. Data is periodically fetched from the Sense HAT emulator, stored, and analyzed for threshold-based alerts. If an alert condition is met, an actuation command is sent to the LED display. Furthermore, the system is designed to be deployable on a Raspberry Pi, allowing for real-world sensor interaction via the I2C bus and GPIO.

### Code Repository and Branch

**URL:**  https://github.com/Ventupentu/java-components/tree/labmodule04

### Unit Tests Executed

The following unit tests have been executed to ensure the correctness of the CDA implementation and to prevent regressions:

- ActuatorDataTest
- SensorDataTest
- SystemPerformanceDataTest
- HumiditySensorSimTaskTest
- PressureSensorSimTaskTest
- TemperatureSensorSimTaskTest
- HumidifierActuatorSimTaskTest
- HvacActuatorSimTaskTest
- ConfigUtilTest
- SystemCpuUtilTaskTest
- SystemMemUtilTaskTest

### Integration Tests Executed

The following integration tests have been executed to validate the end-to-end functionality of the system:

- HumidityEmulatorTaskTest.py
- PressureEmulatorTaskTest.py
- TemperatureEmulatorTaskTest.py
- HumidifierEmulatorTaskTest.py
- HvacEmulatorTaskTest.py
- LedDisplayEmulatorTaskTest.py
- SenseHatEmulatorQuickTest.py
- SensorEmulatorManagerTest.py
- SensorAdapterManagerTest
- ActuatorAdapterManagerTest
- DeviceDataManagerNoCommsTest
- ConstrainedDeviceAppTest
- SystemPerformanceManagerTest
- GatewayDeviceAppTest

EOF.

