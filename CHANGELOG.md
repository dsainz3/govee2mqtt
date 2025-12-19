# Changelog

All notable changes to the Python v2 implementation and HAOS add-on are
documented here. This changelog is required to be updated for every change.

## 0.1.5

- Allow HAOS add-on to auto-detect MQTT service when `mqtt_host` is unset.
- Guard device state polling against HTTP 400 responses so one device does not crash the loop.
- Enforce changelog updates via pre-commit hook.

## 0.1.4

- Fix HAOS add-on init handling to avoid s6 PID1 errors.
- Vendor Python app sources into `addon-v2/app` for add-on builds.
- Add debug logging across API, MQTT, discovery, and command handling.

## 0.1.2

- Initial Python v2 scaffold, discovery, and polling loop.
- Add HAOS add-on scaffolding and Docker build.
