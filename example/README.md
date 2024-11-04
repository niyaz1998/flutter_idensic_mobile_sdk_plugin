# IdensicMobileSDK Example

Demonstrates how to use the IdensicMobileSDK plugin.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## How to run

Update `lib/main.dart` to set an alive `accessToken`

### iOS

Possible it'll be required to update pod manually:

```bash
cd ios && pod update IdensicMobileSDK && cd ..
```

Then open in xcode:

```bash
xed ios/
```

Ensure please you have Bitcode disabled for the whole project and for the `flutter_idensic_mobile_sdk_plugin` target under `Pods` project in particlar:
```
Pods -> flutter_idensic_mobile_sdk_plugin -> Build Settings -> Enable Bitcode -> No
```

## Fonts used in the sample's Custom Theme

- [Scriptina](https://www.1001fonts.com/scriptina-font.html)
- [Caslon Antique](https://www.1001fonts.com/caslon-antique-font.html)
- [Requiem](https://www.1001fonts.com/requiem-font.html)
- [DAGGERSQUARE](https://www.1001fonts.com/daggersquare-font.html)
- [Plasma Drip (BRK)](https://www.1001fonts.com/plasma-drip-font.html)
