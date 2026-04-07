#  WirelessCam

> Turn your Android phone into a high-quality wireless webcam for your Windows PC — no cables, no extra hardware.

![WirelessCam in action](link-to-your-screenshot-or-gif.gif) 
*(Note: Replace this line with a link to a GIF or screenshot showing the Desktop and Android app connected)*

Welcome to the official distribution repository for **WirelessCam**. This repository is used to host the latest compiled releases (installers and APKs) and track user issues. 

*(Note: WirelessCam is a proprietary, closed-source software. This repository does not contain the source code).*

---

##  Why WirelessCam?
Most people already carry a high-quality camera in their pocket. WirelessCam turns that camera into a first-class webcam on Windows. 

* **Zero Hardware Cost:** Only your phone and PC on the same Wi-Fi network are required.
* **Optimized for Low Latency:** Engineered to keep end-to-end video delay as low as possible on local home networks.
* **Plug-and-Play Compatibility:** The virtual camera integrates directly into Windows Media Foundation, making it automatically compatible with Chrome, Teams, Zoom, Discord, OBS Studio, and all modern apps.
* **Battery Aware:** Designed to minimize Android CPU usage, allowing for long video conferencing sessions without extreme battery drain.

---

##  Download & Installation

### System Requirements
* **PC:** Windows 11 22H2 (build 22621) or newer *(Strictly required by the modern Windows Virtual Camera APIs)*.
* **Phone:** Android 5.0 (API 21) or newer.

### 1. Windows Desktop App (Receiver)
1. Navigate to the **[Releases](../../releases/latest)** page on the right side of this repository.
2. Download the latest `WirelessCam-x.x.x.msi` installer.
3. Run the installer. *(Note: Administrator privileges are required, as it installs a secure background service for the virtual camera).*

### 2. Android Mobile App (Sender)
 **Play Store Status:** WirelessCam is currently in **Closed Testing** on the Google Play Console and will be officially available on the Play Store very soon! 

In the meantime, you can sideload the app directly:
1. Navigate to the **[Releases](../../releases/latest)** page directly from your Android phone.
2. Download the latest `WirelessCam-x.x.x.apk` file.
3. Open the file to install it. *(You may need to enable "Install unknown apps" in your Android settings).*

---

##  Quick Start Guide

1. **Connect to the same network:** Ensure both your Windows PC and your Android phone are connected to the same Local Area Network (Wi-Fi).
2. **Launch the Android App:** Open WirelessCam on your phone, grant the camera permissions, and note the **Local IP Address** displayed on your screen.
3. **Launch the Desktop App:** Open WirelessCam on your Windows PC.
4. **Connect:** Type the IP address shown on your phone into the Desktop app and click Connect. 
5. **Ready to stream!** Open your favorite video conferencing app (Zoom, Teams, OBS, etc.) and select **"WirelessCam"** from your camera input settings.

*(Note: While streaming, you can lock your phone screen; the app will continue to capture and send video in the background!)*

---

##  Bug Reports & Support

Having trouble connecting or experiencing unexpected crashes? 
Please check the [Issues tab](../../issues) to see if your problem has already been reported. If not, feel free to open a new issue detailing your problem, your exact Windows 11 build, and your Android device model.

---

##  License

This software is distributed under a proprietary End User License Agreement (EULA). 
By downloading, installing, or using this software, you agree to the terms outlined in the [LICENSE.txt](LICENSE.txt) file included in this repository. 
Redistribution, reverse engineering, and unauthorized modification of this software are strictly prohibited.
