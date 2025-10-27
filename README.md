# Turbina Native Binaries

Pre-compiled C++ core binaries for Turbina SDK.

## 🚀 Platforms

- ✅ **Android** (arm64-v8a, armeabi-v7a, x86_64) - 1.7 MB each
- ✅ **iOS** (Universal XCFramework) - 537 KB

## 📦 Current Release

**Version**: v1.0.0

**Binaries Available**:
- `turbina-android-arm64-v8a.tar.gz`
- `turbina-android-armeabi-v7a.tar.gz`
- `turbina-android-x86_64.tar.gz`
- `turbina-ios.tar.gz`
- `checksums.txt` (SHA-256)

## 📥 Usage

These binaries are **automatically downloaded** by the Turbina Flutter SDK.

**Do not download manually** - the SDK handles this automatically during initialization.

```dart
import 'package:turbina_sdk/turbina_sdk.dart';

final turbina = TurbinaSDKFFI();
await turbina.initialize(TurbinaConfig(
  licenseKey: 'sk_live_your_key',
  appId: 'com.yourcompany.app',
));
```

The SDK will automatically:
1. 🔍 Detect your platform (Android/iOS)
2. 📥 Download the correct binary
3. ✅ Verify SHA-256 checksum
4. 💾 Cache locally for faster future loads

## 🔒 Security

All binaries are:
- ✅ Compiled from verified source
- ✅ Signed with SHA-256 checksums
- ✅ Scanned for security vulnerabilities
- ✅ Publicly available for transparency
- ✅ Built with production optimizations

## 📊 Release Stats

| Platform | Architecture | Size | Compression |
|----------|-------------|------|-------------|
| Android | arm64-v8a | 1.7 MB | gzip |
| Android | armeabi-v7a | 1.6 MB | gzip |
| Android | x86_64 | 1.7 MB | gzip |
| iOS | Universal | 537 KB | gzip |

## 🔗 Downloads

Binaries are available in [Releases](https://github.com/Chancilson/-turbina-binaries/releases).

**Latest Release**: [v1.0.0](https://github.com/Chancilson/-turbina-binaries/releases/tag/v1.0.0)

## 📄 License

See [LICENSE](https://github.com/Chancilson/Turbina/blob/main/LICENSE) in main repository.

---

**Made with ❤️ by Turbina**

[Website](https://turbina.live) • [Documentation](https://www.turbina.live/docs) • [Dashboard](https://www.turbina.live/dashboard)
