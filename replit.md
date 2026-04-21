# Flutter Web App

A Flutter project configured to run as a web application on Replit.

## Project Setup

- **Framework**: Flutter 3.32.0 (Dart 3.8.0)
- **Platform**: Web
- **Entry point**: `lib/main.dart`

## Development

The "Start application" workflow runs:
```
flutter run -d web-server --web-hostname 0.0.0.0 --web-port 5000
```
This serves the Flutter web app on port 5000 for the Replit preview.

## Deployment

Configured for static deployment:
- **Build**: `flutter build web --release`
- **Public dir**: `build/web`

## Structure

- `lib/` — Dart source code
- `web/` — Web platform files (index.html, manifest, icons)
- `test/` — Tests
- `pubspec.yaml` — Dependencies and project metadata
