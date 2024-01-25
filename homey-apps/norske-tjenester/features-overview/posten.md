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

# Posten

### **Overview**

The Posten functionality in the Norske Tjenester app allows users to stay updated with their mail delivery status in Norway. This feature is designed to provide convenience by notifying users about the expected delivery dates of their mail.

### **How It Works**

* The Posten device in the app uses the Norwegian postal service's API to fetch the latest information about mail delivery.
* Users can enter their postal code in the app settings, and the app will display the next expected delivery date for their location.
* The app periodically checks for updates and notifies users accordingly.

### **Setting Up Posten in Norske Tjenester**

1. **Install the App**: Ensure that the Norske Tjenester app is installed on your Homey Pro.
2. **Add Posten Device**: In the Homey app, go to 'Devices' and add a new device. Choose 'Posten' from the list of devices in the Norske Tjenester app.
3. **Configure Settings**: Enter your postal code in the device settings. This is crucial for the app to provide accurate delivery information.

### **Capabilities**

* **Posten Sensor**: Indicates the next mail delivery date. It shows dates like 'Today', 'Tomorrow', or the specific date for the next delivery.
* **Meter Posten Sensor**: Displays the number of days until the next mail delivery.

### **Troubleshooting**

* If you encounter issues with the Posten functionality, check your postal code settings and ensure your Homey Pro is connected to the internet.
* For more detailed troubleshooting, users can create a diagnostic report within the Homey app and email it to nt@coderax.dev for support.

### **Privacy and Data Usage**

* The app respects user privacy and only uses the postal code to fetch relevant mail delivery information.
