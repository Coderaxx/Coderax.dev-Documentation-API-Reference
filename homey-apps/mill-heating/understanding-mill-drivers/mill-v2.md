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

# Mill v2

### Individual Device Control

* The Mill v2 Driver is tailored for individual device control. It requires devices to be set in "Control Individually" mode in the Mill app.

### Separate Device Control in Homey

* Each heater appears as an individual device in Homey, offering precise control over each unit.

### Capabilities

* **Temperature Control:** Allows setting target temperatures for individual devices.
* **On/Off Control:** Users can turn each device on or off directly from Homey.
* **Mode Control:** The driver supports changing the operation mode of individual devices.

### Local and Cloud API Support

* The v2 driver can interact with both local and cloud APIs.
* **Local API Support:** Only available for Gen. 3 devices, providing faster response and more reliable control under certain network conditions.
* **Cloud API:** Required for Gen. 1 and Gen. 2 devices.

### Enhanced Flexibility

* This driver is ideal for users who desire granular control over each heater and prefer to set up schedules or programs within Homey.
