# Constrained Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-CDA-* issues (requirements).

## Description

The Constrained Device Application (CDA) is a lightweight IoT edge application developed in Python. In this module, the CDA is responsible for collecting and logging basic system performance metrics such as CPU utilization and memory usage at regular intervals. The application uses a `SystemPerformanceManager` module that schedules and manages data collection tasks for these metrics. Additionally, the CDA incorporates base system utility tasks to ensure modular and extendable performance monitoring.

The implementation follows a structured approach where the `SystemPerformanceManager` integrates `SystemCpuUtilTask` and `SystemMemUtilTask` to collect data efficiently. The CDA's main application ensures smooth operation by starting and stopping the performance monitoring tasks dynamically. The collected performance data is logged systematically, which provides insights into the system's operational status.

## Code Repository and Branch

URL: https://github.com/Ventupentu/python-components/tree/labmodule02

## Unit Tests Executed

- `ConfigUtilTest`
- `SystemCpuUtilTaskTest`
- `SystemMemUtilTaskTest`

## Integration Tests Executed

- `ConstrainedDeviceAppTest`
- `SystemPerformanceManagerTest`
