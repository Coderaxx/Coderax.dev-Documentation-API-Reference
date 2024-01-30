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

# Car Stats Viewer

### Introduction

The "Car Stats Viewer" driver for Homey enables integration of your Polestar 2 with Homey, allowing monitoring and control of your vehicle's status and features. This guide assists in setting up and using the "Car Stats Viewer" driver effectively.

### Getting Started

To use the "Car Stats Viewer" driver, install the Car Stats Viewer app on your Polestar 2 and the Polestar app on your Homey.

#### **Installing Car Stats Viewer on Polestar 2**

1. **Access Request**: Email polestar@coderax.dev with your Google Play email for access to the "internal test track" for the Car Stats Viewer app.
2. **App Installation**: After access, install the Car Stats Viewer app on your Polestar 2 via Google Play Store.

#### **Configuring Car Stats Viewer**

1. **Open the App**: In your Polestar 2, open the Car Stats Viewer app.
2. **API Settings**: Navigate to the app settings and locate "API settings".
3. **Webhook Setup**: Set up a webhook in Homey and input the webhook URL in the Car Stats Viewer app settings.

#### Integration with Homey

1. **Install the Polestar App**: Ensure the Polestar app is installed on your Homey Pro.
2. **Add Device**: In Homey, go to 'Devices', add a new device, and select the Car Stats Viewer driver from the Polestar app.
3. **Configuration**: Complete the setup by linking the Car Stats Viewer to Homey.

#### Features and Capabilities

* **Battery Status and Charging Monitoring**: Track your Polestar 2's battery level and charging progress.
* **Estimated Range and Vehicle Status**: Gain insights on your car’s range and condition.
* **Customizable Alerts and Automations**: Create Homey flows based on your vehicle's status, like battery level or charging completion.

#### Active Status Updates

* **Vehicle Activity**: Updates on your vehicle's status are only available when the car is active. The car determines its active state, usually when being driven, charged, or preheated.
* **Infotainment System**: The status updates correspond to the activity of the car's infotainment system.

#### Troubleshooting

* **Connectivity Issues**: Ensure both your Polestar 2 and Homey Pro have internet connectivity. Restart the Car Stats Viewer app if needed.
* **Webhook Problems**: Verify the webhook URL and settings if data isn't received in Homey.

#### Privacy and Data Handling

* The integration respects your privacy, using only necessary vehicle data to provide functionalities.
