# Sayo Controller updates

This repository hosts signed update feeds and released macOS App / O3C device firmware files. Application source code is maintained separately and is not published here.

No installable release has been published yet. The signed stable and beta feeds currently announce that no update is available.

## Updating

Open Sayo → Settings → Updates to check the App and device separately. Device updates require a connected USB device and explicit confirmation. Keep the cable connected until the update finishes.

- [Stable update channel](https://github.com/TobyWu666/sayo-controller-updates/releases/tag/updates-stable)
- [Beta update channel](https://github.com/TobyWu666/sayo-controller-updates/releases/tag/updates-beta)

App and firmware releases use `MAJOR.MINOR.PATCH` plus an increasing build number, such as `0.3.0 (8)`. Compatible App and device versions can differ. Sayo checks the hardware model, protocol, minimum App version and signed image before allowing a device update.

Only signed update metadata and reviewed release artifacts belong in this repository. macOS App releases must be Developer ID signed and notarized before the update channel is activated.
