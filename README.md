# PhoneHealthCheck 📱

An open-source Android app that comprehensively tests your phone's functionalities and generates detailed reports for selling used Android phones.

## Features

### Hardware Testing
- 📷 Camera (Front & Rear) - Photo capture, focus, flash
- 🎤 Microphone - Audio input, noise level
- 🔊 Speaker - Audio output, volume levels
- 📡 Sensors - Accelerometer, Gyroscope, Compass, Proximity, Light, Barometer
- 📳 Vibration Motor - Haptic feedback
- 🔋 Battery - Health, capacity, temperature

### Connectivity Testing
- 📶 Cellular Signal - 4G/5G connectivity
- 📡 WiFi - Connection and speed
- 🔵 Bluetooth - Pairing and connectivity
- 🏷️ NFC - Tag detection (if available)
- 🛰️ GPS/Location - Signal acquisition

### Software & Display Testing
- 🖥️ Display - Screen brightness, color accuracy
- 💾 Storage - Available space, read/write speed
- 🧠 RAM - Memory usage and capacity
- 📱 System Info - Android version, device model
- 🔐 Biometrics - Fingerprint sensor, Face recognition
- 🔊 Audio Jack - 3.5mm jack detection

### Report Generation
- ✅ Simple UI with test status
- 📄 Export results to TXT file
- 📋 Copy results to clipboard for marketplace posting
- 🎯 Pass/Fail status for each test
- 📊 Detailed diagnostics for failed tests

## Getting Started

### Prerequisites
- Android 8.0 (API 26) or higher
- Device with necessary permissions enabled

### Installation
1. Clone the repository
2. Open in Android Studio
3. Build and run on your test device

### Usage
1. Launch the app
2. Review the test list
3. Run automated tests (most happen automatically)
4. Complete interactive tests when prompted
5. View results in the app
6. Export to file or copy to clipboard
7. Share results on your marketplace listing

## Project Structure

```
PhoneHealthCheck/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/phonehealthcheck/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── tests/
│   │   │   │   │   ├── HardwareTests.kt
│   │   │   │   │   ├── ConnectivityTests.kt
│   │   │   │   │   ├── SoftwareTests.kt
│   │   │   │   │   └── DisplayTests.kt
│   │   │   │   ├── models/
│   │   │   │   │   ├── TestResult.kt
│   │   │   │   │   └── PhoneStatus.kt
│   │   │   │   ├── utils/
│   │   │   │   │   ├── ReportGenerator.kt
│   │   │   │   │   └── PermissionManager.kt
│   │   │   │   └── ui/
│   │   │   │       ├── adapters/
│   │   │   │       └── fragments/
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── values/
│   │   │   │   └── drawable/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── build.gradle
└── settings.gradle
```

## Permissions Required

The app will request the following permissions:
- `CAMERA`
- `RECORD_AUDIO`
- `ACCESS_FINE_LOCATION`
- `ACCESS_COARSE_LOCATION`
- `BLUETOOTH`
- `BLUETOOTH_ADMIN`
- `NFC`
- `READ_PHONE_STATE`
- `ACCESS_NETWORK_STATE`
- `WRITE_EXTERNAL_STORAGE`
- `READ_EXTERNAL_STORAGE`
- `VIBRATE`
- `BODY_SENSORS`

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This app is provided as-is for educational and personal use. Users are responsible for testing their own devices. The developers are not liable for any damage or data loss caused by using this application.

## Support

For issues, feature requests, or questions, please open an issue on GitHub.

---

**Made with ❤️ for the used phone community**
