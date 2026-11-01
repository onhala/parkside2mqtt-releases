# parkside2mqtt Releases & LoxBerry Distribution

Public distribution repository for [parkside2mqtt](https://github.com/onhala/parkside2mqtt) LoxBerry plugin packages and auto-update manifests.

## Installation into LoxBerry
1. Download the latest `parkside2mqtt-loxberry-v*.zip` from [Releases](https://github.com/onhala/parkside2mqtt-releases/releases).
2. Open your LoxBerry Web UI -> Plugin Management -> Install Plugin.
3. Select the downloaded `.zip` file and install.

## Automatic Updates
The plugin is configured with automatic update manifests:
- **Release Manifest:** `https://raw.githubusercontent.com/onhala/parkside2mqtt-releases/master/release.cfg`
- **Pre-Release Manifest:** `https://raw.githubusercontent.com/onhala/parkside2mqtt-releases/master/prerelease.cfg`

When a new version is published, LoxBerry will automatically detect and notify or apply the update based on your LoxBerry settings.
