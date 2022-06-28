# Dapublock

A *Dart* package to automatically update your pubspec dependencies in your project.

## Installation

Add the following dependency to your `pubspec.yaml`:

```yaml
dev_dependencies:
  dapublock: ^1.0.1
```

#### Run the updater

```bash
flutter pub upgrade
flutter pub pub run dapublock:dapublock.dart PUBSPEC_FOLDER
```

For example:

```bash
flutter pub upgrade
flutter pub pub run dapublock:dapublock.dart .
```