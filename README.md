# SeiZen Release Repository

This repository contains release artifacts for the SeiZen project, including Android APK files and IoT firmware binaries.

## Repository Purpose

This repository serves as a centralized storage location for all official releases of the SeiZen project. It maintains a clear separation between Android application releases and IoT device firmware releases.

## Repository Structure

```
SeiZen-Release/
├── android/     # Contains Android APK release files
└── firmware/    # Contains IoT firmware .bin files
```

## Release File Naming Convention

### Android APK Files

- Format: seizen*v{VERSION_NUMBER}\_build*{BUILD_NUMBER}.apk
- Example: seizen_v1.2.0_build_123.apk

### IoT Firmware Files

- Format: seizen*firmware_v{VERSION_NUMBER}\_build*{BUILD_NUMBER}.bin
- Example: seizen_firmware_v1.2.0_build_123.bin

## Version Tracking Guidelines

1. Use Semantic Versioning (MAJOR.MINOR.PATCH)

   - MAJOR: Breaking changes
   - MINOR: New features, backwards compatible
   - PATCH: Bug fixes, backwards compatible

2. Each release should include:
   - Version number
   - Build number
   - Release date
   - Change log (in release notes)
