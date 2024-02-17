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

## Individual Device Control

The Mill v2 Driver is designed specifically for individual device control. It necessitates that devices be configured in "Control Individually" mode within the Mill app for optimal functionality.

## Separate Device Control in Homey

Within Homey, each heater is represented as a separate device, enabling precise control over each unit independently.

## Capabilities

* **Temperature Control:** Allows setting target temperatures for individual devices.
* **On/Off Control:** Allows users to turn each device on or off directly from Homey.
* **Mode Control:** Supports the alteration of the operational mode for individual devices.

## Local and Cloud API Support

The v2 driver can interact with both local and cloud APIs.

* **Local API:** Exclusively available for Generation 3 devices, offering quicker response times and more reliable control under certain network conditions.
* **Cloud API:** Mandatory for Generation 1 and Generation 2 devices.

## Enhanced Flexibility

This driver is ideally suited for users seeking detailed control over each heater and who prefer to establish schedules or programs within Homey itself.

## Pairing

### **Choosing the API Method**

During the pairing of a Mill Gen 3 heater or socket with the Homey app, you are presented with two methods for connecting your devices:

1. **Autoscan (Local API):** Utilizes an automatic scanning feature to search the network for Mill devices, simplifying the addition process by identifying and integrating supported devices directly into the Homey app.
2. **Manual IP Entry (Local API):** Similar to Autoscan but requires manually inputting the device's IP address. This method is useful if the device’s IP address is already known, or if the Autoscan feature fails to detect the device.
3. **Cloud API Connection:** If you own Gen 1 or Gen 2 Mill devices, or if you prefer a more flexible setup that doesn't rely on your local network configuration, the Cloud API provides an alternative method to integrate Mill devices with Homey. This option facilitates remote management of your devices through the internet, offering a broader range of connectivity beyond the local network.

### **Importance of a Static IP Address**

Although the Autoscan feature facilitates the initial addition of Mill devices to the Homey app, it does not negate the need for a static IP address. Devices should be set up with static IP addresses to ensure reliable and continuous communication with the Homey app, for the following reasons:

* **Reliability:** A static IP address ensures the device is always accessible at the same address, crucial for consistent management and control.
* **Reconnection:** If a Mill device is assigned a new IP address by the network (e.g., after a router restart), the Homey app may lose its connection to the device. Re-establishing this connection requires manually updating the IP address in the device settings within the Homey app or re-pairing the device using its new IP address.

### **Cloud API Advantages**

Using the Cloud API option for Mill devices introduces several advantages:

* **Wider Accessibility:** Enables control of your Mill devices from anywhere, not limited by local network constraints.
* **Ease of Setup:** Simplifies the pairing process by eliminating the need to assign and manage static IP addresses for each device.
* **Compatibility:** Essential for integrating Gen 1 and Gen 2 devices that may not support local API connections.

### **Recommendations**

* **Configure a Static IP:** It is highly recommended to configure a static IP address for each Mill device on your network. This is usually accomplished through your router's settings, where a permanent IP address can be bound to the device's MAC address.
* **Update on IP Change:** If a device's IP address changes after it has been added to Homey, you must update the IP address in the device settings within the Homey app to restore functionality.
* **Consider Cloud API for Flexibility:** For those with Gen 1 or Gen 2 devices, or anyone seeking an integration method that offers remote access and management, the Cloud API provides a valuable alternative.

By implementing these practices, you ensure seamless integration and operation of Mill devices in your Homey-powered smart home.
