# Python Garmin Connect data converter to InfluxDB Cloud(v3)

This script forked by [garmin-influxdb](https://github.com/stratus-ss/garmin-influxdb) and It has been modified to be compatible with influxDB Cloud v3.

## Getting started

requirements:
- uv
- direnv

1. set environment variable.
```
$ cp .envrc.template .envrc
$ vi .envrc
```

2. run script
```
$ uv run garmin-to-influxdb.py
```
