# Chiaki for Android (NG) Next

> [!WARNING]
> This fork has been **completely vibecoded** with the assistance of AI. Use at your own risk. I am absolutely not an expert in video processing stuff.

Chiaki is a free and open-source PlayStation Remote Play client for Android. This is a specialized fork focused on providing the best possible experience on Android devices, with fix of the occasional missing profile and connection lost.

## Key Features

- **PS4 & PS5 Support**: Connect to your PlayStation 4 or PlayStation 5 from anywhere.
- **Enhanced Video Quality**:
  - **Dynamic Bitrate**: Manually set your bitrate up to **100,000 kbps** for ultra-clear streaming.
  - **Post-processing Filters**: Integrated specialized **Debanding** to reduce color artifacts.
- **Advanced Controls**:
  - **Touchpad Emulation**: Use your touchscreen as a DualShock 4 / DualSense touchpad.
  - **Interactive Button Remapping**: Easily remap any button on your physical controller by pressing the button you want to assign.
  - **Motion Sensors**: Use your Android device's gyroscope and accelerometer for motion-controlled games.
  - **Haptic Feedback**: Support for rumble and touch haptics.
- **Performance Optimized**: Low-latency streaming optimized for Android NDK.

## Getting Started

### Prerequisites

- A PlayStation 4 or PlayStation 5 console connected to your network.
- Your PSN Account ID (you can find it using the provided script).

### Installation

1. Download the latest APK from the [Releases](https://github.com/SalamiTheMan/chiaki-ng-android-extended/releases) page.
2. Install the APK on your Android device.
3. Open Chiaki and follow the instructions to register your console.

### Obtaining your PSN Account ID

To register your console, you need your 8-byte PSN Account ID (Base64). You can use the helper script provided in this repository:

```bash
python3 scripts/psn-account-id.py
```

## Build Instructions (Developers)

To build the project yourself:

1. Clone the repository with submodules:
   ```bash
   git clone --recursive https://github.com/SalamiTheMan/chiaki-ng-android-extended.git
   ```
2. Open the `android/` directory in Android Studio.
3. Ensure you have the Android NDK and CMake installed.
4. Build the project using Gradle

## Disclaimer

This project is not endorsed or certified by Sony Interactive Entertainment LLC. PlayStation, DualShock, and DualSense are trademarks of Sony Interactive Entertainment LLC.
