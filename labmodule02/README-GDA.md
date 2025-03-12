# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues.

### Description

The Gateway Device Application (GDA) is a Java-based IoT edge application designed to gather and log essential system performance data. Similar to the CDA, the GDA collects metrics like CPU utilization and memory usage at predefined intervals. The `SystemPerformanceManager` module plays a central role in scheduling and managing these data collection tasks, ensuring consistent monitoring and logging.

The implementation structure ensures modularity and maintainability, incorporating `BaseSystemUtilTask` as a foundation for extensible performance monitoring. The `SystemCpuUtilTask` and `SystemMemUtilTask` classes are integrated into the `SystemPerformanceManager`, allowing seamless execution of monitoring functions. The application logs collected data for further analysis and debugging purposes, forming a critical part of the IoT edge computing infrastructure.

### Code Repository and Branch

URL: https://github.com/Ventupentu/java-components/tree/labmodule02

### Unit Tests Executed

- `ConfigUtilTest`
- `GatewayDeviceAppTest`
- `SystemCpuUtilTaskTest`
- `SystemMemUtilTaskTest`

### Integration Tests Executed

- `SystemPerformanceManagerTest`
- `GatewayDeviceAppTest`
