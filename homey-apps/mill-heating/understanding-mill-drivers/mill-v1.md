---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Mill v1

### Room-Based Control

* The Mill Driver is designed for room-based control. It requires that devices are assigned to a room in the Mill app and are not set in "Control Individually" mode.

### Unified Room Control in Homey

* In this driver, each room configured in the Mill app is represented as a single device in Homey. This approach groups multiple heaters together, allowing for unified control of all heaters in a room.

### Capabilities

* **Temperature Control:** The driver allows setting target temperatures for different modes like comfort, sleep, and away.
* **Mode Control:** Users can change the mode of the room (e.g., weekly\_program, comfort, sleep, away, vacation).
* **Power Usage Monitoring:** It includes the capability to monitor and report the power usage of all devices in a room.

### Flow Cards and API Interaction

* The driver supports various Homey flow cards for triggering actions based on mode changes, heating status, and matching modes.
* It interacts with the Mill Cloud API to fetch and update room and device states.
