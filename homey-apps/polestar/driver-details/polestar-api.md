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

# Polestar API

### Introduction

The "Polestar API" driver for Homey offers an unofficial integration with Polestar, enabling direct data retrieval about your Polestar vehicle. This driver leverages the capabilities of the new "My Page" feature on the Polestar website to access real-time vehicle information.

### Unofficial API Integration

* **Direct Data Access**: This driver connects directly with Polestar's systems to fetch vehicle data.
* **Utilization of Polestar's 'My Page'**: The integration is based on the new interface provided by Polestar's website, allowing for comprehensive data access.

### Setting Up the Polestar API Driver

1. **Install the Polestar App**: Ensure the Polestar app is installed on your Homey Pro.
2. **Add Polestar API Device**: In the Homey app, go to 'Devices', add a new device, and select the Polestar API driver from the Polestar app.
3. **Configuration**: Follow the on-screen instructions to link your Polestar account with Homey.

### Features and Capabilities

* **Battery Status**: Get real-time updates on your vehicle's battery level.
* **Odometer Reading**: Track the total distance traveled by your vehicle.
* **Continuous Updates**: Unlike other drivers, the Polestar API driver updates the vehicle's status continuously, even when the car is not in use.

### Data Accessibility

* **Comprehensive Vehicle Information**: Access a wide range of data points about your Polestar vehicle, including but not limited to battery status and odometer readings.
* **Real-Time Updates**: Receive up-to-date information about your vehicle's status, ensuring you're always informed.

### Privacy and Data Handling

* **Unofficial Integration**: As this is an unofficial API, it's important to understand the data handling and privacy implications.
* **Secure Data Usage**: The driver uses secure methods to connect and retrieve data, ensuring your vehicle's information is handled responsibly.

### Troubleshooting

* **Connectivity Issues**: Ensure your Homey Pro and Polestar account are correctly linked and have internet access.
* **Data Retrieval Problems**: If data isn't updating as expected, check your Polestar account credentials and the configuration in the Homey app.
