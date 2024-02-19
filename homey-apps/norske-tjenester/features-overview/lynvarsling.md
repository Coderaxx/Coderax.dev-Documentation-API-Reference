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

# Lynvarsling

### Lightning Alert

The "Lightning Alert" is a new driver that notifies you of lightning activity in the vicinity of your location. This feature is designed to provide users with early warning of potential lightning strikes, allowing them to take necessary precautions.

### Features

* **Lightning Strike Alert**: The app will alert you if there is a risk of lightning strikes within a specified radius from your location.
* **Distance to Lightning Strike**: Displays the distance in kilometers to the nearest recorded lightning strike.
* **Location of Lightning Strike**: Provides information on the location of the nearest lightning strike.
* **Timestamp of Lightning Strike**: Shows the time of the last recorded lightning strike.
* **Peak Current**: Reports the highest current measured in amperes for the last lightning strike.

### Installation

The "Lightning Alert" driver is easy to add to your Homey app. Follow the standard procedure for adding new devices in the Homey app, and search for "Lightning Alert" under "Add device".

### Configuration

After adding "Lightning Alert" to your Homey app, you can configure the following settings:

* **Danger Radius**: Defines the radius in kilometers to alert about lightning strikes near your location. The default value is set to 10 km.

### Flows

"Lightning Alert" supports the creation of flows in the Homey app, allowing you to automate actions based on lightning activity. For example, you can set up a flow to turn on the lights in your home when a lightning strike is detected.

### Technical Implementation

The driver uses a combination of Homey's geolocation and an external service to monitor lightning activity. When lightning activity is detected within the configured radius, the device's status is updated, and relevant flows will be triggered.
