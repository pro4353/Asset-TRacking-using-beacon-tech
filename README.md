# Android-BLE-Connect-Example
Simple example application that allows you to scan, and connect to a ble device on Android (M) API 23
Asset tracking is a task over the years. Asset Tracking using Beacons is the main idea . 
Beacons can be a game changer in this. 
Beacons are some small Bluetooth radio transmitters.
Standard Beacons range for 70 meters.
Asset Tracking can be done for 35-400 meters using Beacons.
Beacons are a small devices , based on BLE technology i.e., Bluetooth Low Energy .
Using BLE , beacons transmits a unique Id for every 1/10th of a second.
Any Smart phone with Bluetooth can detect the UUID and it gets to know which beacon is next to it.
All the data required for action is taken from the cloud, as the device connects to that specific beacon.
In a warehouse rather than finding out a product manually by filtering. Beacons can bring a great change in spotting any product in a single tap. 

Work can be categorized to 2 parts
a)Working with Bluetooth module
b)Working on App development

Using ESP 32 module(i.e., Bluetooth module) was a task I accomplished in this duration.
I’ve been knowing how coding is done on a module(ie., Arduino IDE).
1)Naming module
2)Scanning module from different devices
3)Signal Strength of module in different devices
4)Making module work as Beacon

Discussing the last point :
ESP32 Module is been coded so that is acts like a server.
It acts like a server sending signals every few seconds as mentioned in code.

Using Bluetooth modules , so as to establish a communication between server and Bluetooth device.
Here, comes the client receiving the signals sent by server(i.e.,Module).

b)Working on App development
Using Android Studio so as to develop app.
Using sample codes available , I’ve learnt what profiles are offered in Bluetooth API.
Able to use emulator on a real device, checking with it.
 Now , An basic working model is created that scans for BLE devices and lists all available devices.


S.No
Area of Work
Results
   1
Bluetooth Modules
ESP32 module is acting as a beacon (server).
   2
Android Studio
Developed basic apps and view the app on phone simultaneously on Android Studio.


FINAL OUTCOME : 
	An android application , that does asset tracking using Beacon Technology.
CONCLUSION :
	Working of module as a server.
	ESP32 bluetooth module basic functionalities are been executed.
	Android App scanning BLE devices is created.
