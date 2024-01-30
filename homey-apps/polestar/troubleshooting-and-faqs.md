---
description: >-
  Remember to always check the FAQ for issues similar to yours. This page is
  regularly updated.
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

# Troubleshooting and FAQs

## **Common Issues and Solutions**

### **Q1: How do I install the Polestar app on my Homey Pro?**

#### **A:** To install the Polestar app, open the Homey app, go to 'Apps', search for 'Polestar', and click 'Install'. Follow the on-screen instructions to complete the installation.

### **Q2: What are the differences between the ps2, polestar-2-csv, and polestar-2 drivers?**

#### **A:**

* **ps2**: Uses the official Polestar API for real-time data and control.
* **polestar-2-csv**: Connects through the "Car Stats Viewer" app for detailed vehicle statistics.
* **polestar-2**: Integrates with Tibber for energy management but is deprecated and doesn't support adding new devices.

### **Q3: How can I connect my Polestar vehicle to the Homey app?**

#### **A:** Depending on the driver you're using:

* For **ps2**, follow the instructions provided in the app for connecting via the official Polestar API.
* For **polestar-2-csv**, use the "Car Stats Viewer" app to establish a connection.
* For **polestar-2**, ensure you have a Tibber account and Polestar is added as a Power-Up in Tibber.

### **Q4: The app is not updating my vehicle's status. What should I do?**

**A:** Ensure your vehicle is properly connected and online. Check if the app has the necessary permissions and your Homey Pro is connected to the internet. Restarting the app or Homey Pro can sometimes resolve update issues.

### **Q5: Can I add a new vehicle using the polestar-2 driver?**

**A:** No, the polestar-2 driver is deprecated, and it's not possible to add new vehicles using this driver. Existing setups will continue to work.

### **Q6: Where can I report a bug or suggest a feature?**

**A:** You can report bugs or suggest features by creating an issue on the GitHub repository or contacting the developer directly via email.

### **Q7: Is there a way to automate actions based on my vehicle's status?**

**A:** Yes, you can create flows in Homey that trigger actions based on various statuses of your Polestar vehicle, like charging status, battery level, etc.

### **Q8: How secure is the connection between my Polestar vehicle and Homey?**

**A:** The app uses secure methods to connect to your vehicle, ensuring that your data and control commands are encrypted and protected.

### **Q9: Can I use the app if I don't have a Tibber account?**

**A:** A Tibber account is not required for the ps2 and polestar-2-csv drivers. However, for the polestar-2 driver, a Tibber account is necessary for integration.

### **Q10: How do I update the Polestar app on Homey?**

**A:** Updates are usually automatic. However, you can manually check for updates by going to the 'Apps' section in the Homey app, selecting Polestar, and clicking 'Update' if available.

### **Q11: What should I do if I encounter connectivity issues with my vehicle?**

**A:** First, check your vehicle's network connection and ensure it's online. If the issue persists, try restarting the Polestar app on Homey and re-establishing the connection with your vehicle.

### **Q12: Can I control multiple Polestar vehicles with the app?**

**A:** Yes, you can control multiple vehicles as long as each is properly set up with the respective driver in the app. Note that the polestar-2 driver does not support adding new vehicles.

### **Q13: How can I contribute to the development of the Polestar app?**

**A:** You can contribute by providing feedback, reporting bugs, suggesting features, or even contributing code. Check the `CONTRIBUTING.md` file in the GitHub repository for more details.

### **Q14: Will there be more features added to the app in the future?**

**A:** The app is continuously being improved. Keep an eye on the GitHub repository and Homey app updates for new features and enhancements.

### **Q15: Who can I contact for support if I have issues with the app?**

**A:** For support, you can reach out through the GitHub repository's issues section or contact the developer directly via the provided email address.

### **Q16: Is it possible to control my Polestar vehicle (like starting preheating or unlocking) using the app?**

**A:** Currently, it is not possible to control your Polestar vehicle using the app, such as starting preheating or unlocking. This functionality will not be available until Polestar launches an official API that allows for control and data access of the vehicle. The app currently focuses on monitoring and providing information about your vehicle's status.
