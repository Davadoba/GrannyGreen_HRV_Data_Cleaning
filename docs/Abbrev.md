## EmotiBit TypeTag Mapping
These tags refer to the naming conventions used for emotibit measurements in the data file names, with most of them having the same 2-letter abbreviation for the column containing the actual measurement values.

Data files can be found in `/data-files`

| Tag | Name | Description | Category |
|---|---|---|---|
| `AK` | Acknowledgement | Internal system acknowledgement. | System |
| `AX` | Accelerometer X | Acceleration along the X-axis. | Motion |
| `AY` | Accelerometer Y | Acceleration along the Y-axis. | Motion |
| `AZ` | Accelerometer Z | Acceleration along the Z-axis. | Motion |
| `B` | Battery Percentage | Device battery charge percentage. | Device |
| `BI` | Beat Interval | Time interval between successive heartbeats. | Biometric |
| `BV` | Battery Voltage | Device battery voltage. | Device |
| `EA` | Electrodermal Activity | Skin conductance activity signal. | Biometric |
| `EL` | Electrodermal Level | Skin conductance level. | Biometric |
| `EM` | System Configuration Logs | System configuration log messages. | System |
| `GX` | Gyroscope X | Angular velocity around the X-axis. | Motion |
| `GY` | Gyroscope Y | Angular velocity around the Y-axis. | Motion |
| `GZ` | Gyroscope Z | Angular velocity around the Z-axis. | Motion |
| `HR` | Heart Rate | Estimated heart rate, typically in BPM. | Biometric |
| `MX` | Magnetometer X | Magnetic field along the X-axis. | Motion |
| `MY` | Magnetometer Y | Magnetic field along the Y-axis. | Motion |
| `MZ` | Magnetometer Z | Magnetic field along the Z-axis. | Motion |
| `PG` | PPG Green | Green-light photoplethysmography signal. | Biometric |
| `PI` | PPG Infrared | Infrared photoplethysmography signal. | Biometric |
| `PR` | PPG Red | Red-light photoplethysmography signal. | Biometric |
| `RB` | Record Begin | Recording-start marker or event. | System |
| `RD` | Request Data | Internal data request message. | System |
| `SA` | Skin Conductance Response Amplitude | Amplitude of a detected skin conductance response. | Biometric |
| `SF` | Skin Conductance Response Frequency | Frequency of detected skin conductance responses. | Biometric |
| `SR` | Skin Conductance Response Rise Time | Rise time of a detected skin conductance response. | Biometric |
| `T1` | Temperature Channel 1 | Temperature measurement from channel T1. Located on outer side of device. Measures ambient temperature. | Temperature |
| `TH` | Thermopile Temperature | Temperature measurement from a thermopile sensor. Measures peripheral skin temperature. | Temperature |
| `TL` | Local Time | Contains Local Timestamps(Unix Epoch Seconds) From Host, Indicating Real-world time, and Corresponding EmotiBit Device Uptime Clock in Milliseconds. | System |
| `timesyncs` | EmotiBit <-> Host Time Sync | A log of regular "pings" between the Emotibit and Host meant to sync the Emotibit uptime to real-world time | System |
| `timeSyncMap` | Time Sync Map | TE0 & TE1 are emotibit internal millisecond uptime timestamps chosen as the start & end. TL0 & TL1 are the corresponding Unix Epoch real-world time anchords in seconds. | System |