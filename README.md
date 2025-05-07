# 💸 Billionaire App

The **Billionaire App** is a simple Flutter project that demonstrates persistent local state using `shared_preferences`. It simulates a bank account where users can increase their balance by tapping a button.

## 🖼️ Preview

<img src="assets/screenshots/billionaire_app_preview.png" width="300">

## ✨ Features

- 🏦 Display of bank balance in a formatted currency style.
- 💰 Button to add money to the balance.
- 🔄 Persistent data using `shared_preferences`.
- 🎨 Custom app icon and app name.
- 📱 Responsive and clean UI design.

## 🚀 Getting Started

To run this project on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/billionaire_app.git
   cd billionaire_app
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```

## 🧩 Dependencies

- [shared_preferences](https://pub.dev/packages/shared_preferences)
- Flutter SDK (stable channel)

## 📦 Build Setup

Make sure you have Flutter installed and configured correctly.

- **App icon**: Custom app icons were added manually using an online icon generator and placed directly in:
  - `android/app/src/main/res` for Android
  - `ios/Runner/Assets.xcassets` for iOS

- **App name**: Updated manually in the following files:
  - `AndroidManifest.xml` for Android
  - `Info.plist` for iOS

## 📱 Platforms Supported

- Android ✅
- iOS ✅ (with platform adjustments)

## 📄 License

This project is open-source and free to use under the MIT License.

---

*Built with ❤️ using Flutter.*
