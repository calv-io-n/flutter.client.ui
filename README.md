# Flutter Template Starter

---
Begin a flutter APP

How to connect a device via adb, ensure adb is installed on your host machine.

Start your local android emulator. Afterwards reconnect execute the following command to make it accessable via network:

1. `adb tcpip 5555`

In your docker container connect to device:

2.  Open your VSC container terminal and `adb $DEVICE_LAN_IP:5555`
