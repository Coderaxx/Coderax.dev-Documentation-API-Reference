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

# Sporing

### **Overview**

The Package Tracking feature in the Norske Tjenester app allows users to track their shipments from Posten/Bring and PostNord. This functionality provides real-time updates on the status of your packages, ensuring you're always informed about their whereabouts.

### **How It Works**

* The app uses the tracking APIs of Posten/Bring and PostNord to fetch the latest tracking information.
* Users can enter their package tracking number in the app settings, and the app will display the current status of their shipment.

### **Setting Up Package Tracking in Norske Tjenester**

1. **Install the App**: Make sure the Norske Tjenester app is installed on your Homey Pro.
2. **Add Package Tracking Device**: In the Homey app, go to 'Devices' and add a new device. Choose 'Package Tracking' from the list of devices in the Norske Tjenester app.
3. **Configure Settings**: Enter your package tracking number in the device settings. This number is essential for the app to track your shipment.

### **Capabilities**

* **Sensor Tracking**: Shows the latest event or status update for your package.
* **Sensor Tracking Sender**: Displays the name of the sender associated with the tracking number.

### **Troubleshooting**

* Ensure that the tracking number is entered correctly in the app settings.
* If the tracking information is not updating, check your internet connection and try refreshing the data.
* For further assistance, users can create a diagnostic report within the Homey app and email it to nt@coderax.dev for support.

### **Privacy and Data Usage**

* The app respects user privacy and only uses the tracking number to fetch relevant shipment information.
