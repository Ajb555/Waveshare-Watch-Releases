# Waveshare Watch OTA Releases

Public distribution repository for Andrew's Waveshare ESP32-S3 Touch AMOLED 2.06 watch firmware.

## Release policy

- `latest.json` is the stable machine-readable OTA manifest.
- Installable firmware is published as versioned GitHub Release assets only after build and acceptance gates are complete.
- Application binaries are distributed separately from source, NVS, credentials, keys, recovery dumps, and full-flash images.
- The watch uses native ESP-IDF HTTPS OTA with normal certificate verification and A/B rollback support.

No current production firmware is published yet. The `transport-validation-2026-09-14` release contains a historical checkpoint binary solely to validate anonymous HTTPS delivery and redirect behavior. It is not offered as an update.

