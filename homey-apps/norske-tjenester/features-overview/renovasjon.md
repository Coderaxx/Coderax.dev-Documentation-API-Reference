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

# Renovasjon

### **Overview**

The Waste Collection Reminders feature in the Norske Tjenester app ensures that you never miss a garbage day again. This functionality provides timely reminders about your local waste collection schedule, helping you manage your household waste efficiently.

### **How It Works**

* The app integrates with various waste collection services across Norway to fetch the latest waste collection schedules.
* Users can select their local waste service provider and enter relevant details like their address or area code in the app settings.

### **Setting Up Waste Collection Reminders in Norske Tjenester**

1. **Install the App**: Ensure the Norske Tjenester app is installed on your Homey Pro.
2. **Add Waste Collection Device**: In the Homey app, go to 'Devices' and add a new device. Choose 'Waste Collection' from the list of devices in the Norske Tjenester app.
3. **Configure Settings**: Select your waste service provider and enter the necessary details to receive accurate collection schedules.

### **Capabilities**

* **Sensor Waste Collection**: Displays the type of waste being collected (e.g., general, plastic, paper) and the next collection date.
* **Meter Waste Days Left**: Shows the number of days left until the next waste collection.

### **Supported Waste Service Providers**

* The app supports a wide range of waste service providers across Norway. Users can choose their provider from the list in the app settings. For a full list of supported providers, visit [this](../supported-waste-providers.md) page.

### **Troubleshooting**

* If you're not receiving reminders, check that you have selected the correct waste service provider and entered the correct area details.
* Ensure your Homey Pro is connected to the internet for the app to fetch the latest schedules.
* For additional support, users can create a diagnostic report within the Homey app and email it to nt@coderax.dev.

### **Privacy and Data Usage**

* The app respects user privacy and only uses the provided information to fetch relevant waste collection schedules.
