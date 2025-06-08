# Tesla CanDash

A maintained continuation of the deleted CanDash Dashboard application by [nmullaney](https://github.com/nmullaney).

## What is CANdash?

Tesla CANdash is an Android app that transforms your Android device into an instrument cluster for your Tesla Model 3 or Y. Designed to enhance the Tesla user experience, it adds features unavailable in your current instrumentation, such as live blind spot monitoring.

## Features

- **Speed** and **Distance to Empty**
- **State of Charge** and **Selected Gear**
- **Live Blind Spot Monitoring**
- **Emergency Blind Spot Alerting** when changing lanes into traffic
- **Motor Temperature and Torque (Front and Rear)**
- **Coolant Flow** and **Battery Temperature**
- **Live Power Display** in HP or kW
- **Autopilot Availability** and **Alerts**
- **Door/Aperture Open Alerting**
- **Automatic Night Mode** based on vehicle status
- **Manual Night Mode** for dark preference
- Compatible from **Android 6.0.1 and older**
- Fully compatible with Android split screen functionality

## Setup

1. Purchase and install a [CANserver](http://www.jwardell.com/canserver/) in your Tesla, ideally using the [EVOffer diagnostic harness](https://evoffer.com/product/model-3-y-can-diagnostic-cable/).
2. Ensure your CANserver is on firmware Version 2.1.
3. Optionally, use the [S3XY Buttons](https://abstractocean.com/products/s3xy-buttons) device for native CANdash support. (Note: AutoPilot and Blind Spot Monitoring features are not supported with S3XY Commander.)
4. Connect your Android device to the CANserver (either directly or via a personal hotspot).
5. Sideload the compiled APK onto your Android device. You can use [ADB](https://developer.android.com/studio/command-line/adb) or any file transfer method you prefer.
6. Follow the setup instructions for connecting and scanning your CANserver IP from within the app.

## Compile

To compile the application:

1. Clone this repository.
2. Open the project from the `android/` subdirectory.
3. Compile as you would a typical Android project.

## Dash View

- Tap various parts of the dashboard (speed units, power meter, battery) for interactive features.
- The display responds to light conditions and connected signals to show alerts and status.

## Auto Launch

Utilize **Tasker** for automating hotspot setup or other app-specific actions when your device is in your vehicle.
