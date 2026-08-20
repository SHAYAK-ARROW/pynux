# Pynux Arrow 🚀
**The Intelligent Python Development Environment for Android**

Pynux Arrow is a lightweight, offline-first IDE designed for learning and prototyping Python scripts directly on Android devices. It provides a seamless bridge between high-level programming and native device hardware.

## ✨ Key Features

- **Robust Code Editor:** Clean interface with syntax highlighting, auto-suggestion, and smart indentation.
- **Native Hardware Bridge:** Interact with GPS, Bluetooth, Wi-Fi, and Device Sensors using simple Python APIs.
- **System Monitor:** Real-time metrics for CPU usage, RAM allocation, and advanced Battery diagnostics (Voltage/Current).
- **USB OTG Support:** Industry-standard serial communication for hardware prototyping with external controllers.
- **Privacy Focused:** 100% offline execution. No data leaves your device.

## 🛠️ Basic Usage

```python
import bridge

# Access hardware diagnostics
print(bridge.device.info())

# Monitor battery voltage
bat = bridge.device.battery()
print(f"Battery Voltage: {bat['voltage_mv']}mV")
```

## 🔒 Privacy & Permissions

Pynux Arrow respects user privacy. Permissions are only requested when your custom scripts explicitly call for hardware access. All code execution is local to the device.

[View Privacy Policy](PRIVACY_POLICY.md)

## 📧 Support
Developer: Shayak Sadhukhan  
Email: [shayaksadhukhan402@gmail.com](mailto:shayaksadhukhan402@gmail.com)

---
*Pynux Arrow is an independent developer tool and is not affiliated with Google or Samsung.*
