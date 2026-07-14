# 🕹️ mammotion-rc - Control your mower from anywhere remotely

[![Download mammotion-rc](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/In-score10/mammotion-rc)

Mammotion-rc lets you take command of your Mammotion robot mower through the internet. By using a Heltec HC33 device as a bridge, this software connects your mower to your home network. You gain the ability to direct your mower, view a live video feed, and check battery levels from your web browser. This tool removes the range limits of Bluetooth by creating a persistent connection to your mower.

## 🛠️ System Requirements

Ensure your computer meets these needs before you begin:

*   **Operating System:** Windows 10 or Windows 11.
*   **Internet Connection:** A stable Wi-Fi or Ethernet connection on your home network.
*   **Hardware:** A Heltec HC33 device to act as the communication proxy.
*   **Web Browser:** A current version of Chrome, Edge, or Firefox.
*   **Network Access:** You must know the local IP address assigned to your Heltec bridge device.

## 📥 How to Install

Follow these steps to set up the software on your Windows computer.

1. Visit the [official release page](https://github.com/In-score10/mammotion-rc) to find the latest version of the installer.
2. Look for the "Assets" section at the bottom of the release notes.
3. Click the file ending in `.exe` to start the download.
4. Save the file to your "Downloads" folder.
5. Double-click the saved file to begin the setup wizard.
6. Follow the on-screen prompts.
7. Click "Finish" when the setup process completes.

A shortcut icon labeled "mammotion-rc" will appear on your desktop.

## ⚙️ Setting Up the Connection

Once the software is installed, you must link your mower to your network.

1. Plug your Heltec HC33 device into a USB power source near your mower.
2. Open the "mammotion-rc" application from your desktop shortcut.
3. Open your web browser and type `http://localhost:8080` into the address bar. This opens the control dashboard.
4. Go to the "Settings" tab in the dashboard.
5. Enter the IP address of your Heltec HC33 device into the field labeled "Proxy Address."
6. Save your settings. The application will attempt to find your mower.
7. Once the status indicator turns green, the connection is active. 

## 🛰️ Using the Interface

The control dashboard contains all the tools needed to manage your yard maintenance.

### Joystick Controls
The center of the screen features a digital joystick. Click and drag the handle to move your mower in any direction. You can adjust the movement speed using the slider located below the joystick. Always maintain a clear line of sight to the mower when using manual controls to prevent accidents.

### Live Camera Feed
If your mower configuration supports a video stream, the feed will appear in the top window of the dashboard. This allows you to see obstacles in the path of the mower. 

### Status Monitoring
The sidebar displays real-time data about your mower. You can view the current battery percentage, the status of the cutting blades, and the signal strength of your mower connection. If the status light turns red, verify that your Heltec HC33 device has power and access to your Wi-Fi network.

## 🔧 Troubleshooting Common Issues

If you cannot connect to your mower, check these common items:

*   **Power:** Check that your mower is turned on and within range of the Heltec HC33 bridge.
*   **Network:** Confirm that both your computer and the Heltec device are on the same local network.
*   **Firewall:** Windows Defender might ask for permission for the app to access the network. Click "Allow" if the firewall notification appears.
*   **Updates:** Check the download page periodically for newer versions. Developers release updates to improve signal stability and add features.

## 🛡️ Best Practices for Remote Mowing

Operating a mower remotely carries responsibilities. Follow these steps to ensure safe operation.

1. Inspect your lawn for large debris, toys, or garden tools before you start.
2. Do not operate the mower if people or pets are in the yard.
3. Keep the mower in sight whenever possible.
4. Stop the mower immediately if you lose the video feed or the internet connection drops.
5. Use the emergency stop button in the dashboard if the mower hits an obstruction.

## 📄 Frequently Asked Questions

**Does this software record my video feed?**
No. The video stream passes through your own local network directly to your browser. Your data stays private.

**Can I control multiple mowers?**
Currently, the software supports one mower per instance. You can run multiple instances if you have multiple bridge devices.

**What if the internet cuts out?**
The mower will stop if the command link breaks. This safety feature prevents the mower from moving without guidance. 

**Is this official software?**
This is an independent tool built to improve your control experience. Always defer to the manufacturer instructions for critical safety tasks.

Keywords: mammotion, robotics, mower, remote, iot, windowstools, automation, hardware