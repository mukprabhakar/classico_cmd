# classico_cmd

A small Flutter sample app (classico_cmd) — concise, cross-platform, and ready to run.

## Project

**Description:** Minimal Flutter project scaffolded for development and testing across Android, iOS, web, Windows, macOS, and Linux.

**Status:** Initial project files present (platform folders, `lib/main.dart`, tests).

## Prerequisites

- Install Flutter (stable) and ensure `flutter` is on your PATH.
- For platform-specific builds, install platform toolchains (Android SDK, Xcode for macOS/iOS, Visual Studio for Windows).

## Getting started (Windows)

1. Install Flutter and dependencies: follow https://flutter.dev/docs/get-started/install
2. From the project root, get packages:

```powershell
flutter pub get
```

3. Run the app (Windows desktop):

```powershell
flutter run -d windows
```

4. Run for Android emulator or device:

```powershell
flutter run -d <device-id>
```

5. Run tests:

```powershell
flutter test
```

## Build

- Release builds: `flutter build apk`, `flutter build windows`, `flutter build web`, etc.

## Project structure (high level)

- `lib/` — Dart source, `main.dart` entrypoint.
- `android/`, `ios/`, `windows/`, `macos/`, `linux/`, `web/` — platform integrations.
- `test/` — widget/unit tests.

## Contributing

Fork, create a branch, and open a PR. Keep changes focused and include tests where applicable.

## License

See repository root for license information (if any).

---
Updated: concise run instructions and project overview.
