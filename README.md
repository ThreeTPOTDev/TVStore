(https://github.com/user-attachments/files/28308437/README.md)
<img width="706" height="166" alt="Android TV logo" src="https://github.com/user-attachments/assets/d501e770-bdac-4397-93d3-307cc2fb0314" />

# TVStore

TVStore is an independent, community-run, open-source app store for Android TV and Google TV devices. It is designed for big-screen navigation, remote controls, and devices that should not need Google Play Services to discover or install apps.

## Alpha Status

TVStore is currently in Alpha through June 2026.

This first version is focused on proving the core idea:

- A TV-first app store experience with large, remote-friendly UI.
- Catalog browsing for Android TV and Google TV apps.
- Device and CPU architecture awareness, including ARM, ARM64, x86, x86_64, Snapdragon, and Chromebook-class devices.
- A privacy-focused design without Google Play Services tracking.
- A planned remote-install flow for sending apps from web or mobile to a paired TV device.

Alpha builds may contain placeholder catalog data, incomplete install flows, and rough UI edges while the project validates the foundation.

## How Is TVStore Different?

- Built for televisions first, not adapted from a phone store.
- Designed to work without Google Play Services.
- Community-run and open source.
- Focused on broad Android TV hardware support.
- Planned support for remote installs across paired devices.

## Planned Alpha Features

- Browse featured apps and categories.
- View app details, version info, supported architectures, and privacy notes.
- Queue installs from the TV interface.
- Prepare the foundation for remote install requests.
- Document contribution and app submission guidelines.

## Roadmap

### Alpha - Until June 2026

- Build the first usable TV catalog interface.
- Define the app metadata format.
- Prototype install queue behavior.
- Prepare contribution guidelines.
- Collect early testing feedback.

### Beta

- Add real package download support.
- Add app signing and integrity checks.
- Add device pairing for remote installs.
- Expand catalog moderation tools.

### Stable

- Publish verified release builds.
- Support updates and app version history.
- Provide a complete community submission workflow.

## Build From Source

The app source is expected to target Android TV / Google TV devices.

Recommended development environment:

- Android Studio
- JDK 17
- Android SDK 35 or newer
- Android Gradle Plugin 8.x

## Contributing

Contributions are welcome during Alpha. Helpful areas include:

- Android TV UI and remote-navigation improvements.
- Catalog metadata design.
- App compatibility testing.
- Translations.
- Privacy and security review.
- Documentation.

## License

TVStore is licensed under the GNU General Public License v3.0. See `LICENSE` for details.
