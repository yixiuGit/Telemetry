# IOS_XE-Realtime_Monitor
Display real time IOS_XE device information

This is to display real time statistics on network devices running on IOS_XE, such as
- Device memory usage
- Device cpu usage
- Interface speed
- Interface Tx/Rx packets

# Requirements
- IOS XE 10.6+
- ubuntu 18.04
- Influxdb
- Telegraf
- Grafana

# TIG(Telegraf, Influxdb, Grafana) installation
- https://technowikis.com/5889/how-install-telegraf-influxdb-and-grafana-stack-ubuntu-linux

# Configuration on network device
- refer telemetry_config.txt

# Display sample
- refer telemetry_display.png
