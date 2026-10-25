# Navori Android updates

This repository hosts verified Navori Android release assets and public update metadata.

- Consumer app: `navori-release.apk` (`com.navori.gecko`).
- Demo and Developer APKs are separate variants, not the consumer download.
- `navori-update.json` contains package identities, versions, sizes, and SHA-256 checksums for the in-app updater.

[Download the latest consumer APK](https://github.com/Frank-sys486/navori-update/releases/latest/download/navori-release.apk) after the first release is published.

Updates require an explicit download and Android installation confirmation. Update in place to preserve local sessions and records; do not uninstall to update.

The publishing workflow verifies a complete new release before removing older published Navori versions. No application source, signing keys, private configuration, or account records belong in this repository.
