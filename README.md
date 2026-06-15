# Reolink (reolink)

Reolink is a provider of security cameras and smart home surveillance technology. Their cameras offer an HTTP API that enables direct device control and configuration through JSON-based POST requests. The API supports comprehensive camera management including PTZ control, video encoding settings, recording search and playback, motion and AI-powered object detection, network configuration, LED control, and user authentication. The API is accessible on the local network via the device IP address.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- IoT
- Security Cameras
- Surveillance
- Smart Home
- AI Detection

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Reolink Camera HTTP API

The Reolink Camera HTTP API provides a JSON-based interface for controlling and configuring Reolink IP cameras and NVRs. All commands are sent as HTTP POST requests to the /cgi-bin/api.cgi endpoint. The API covers 11 functional modules including authentication, system management, security, network configuration, video and image settings, encoding, recording and playback, PTZ control, alarm and motion detection, LED control, and AI-powered object detection with auto-tracking.

- **Human URL:** [https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)

#### Tags

- IoT
- Security Cameras
- Surveillance
- Smart Home
- AI Detection

#### Properties

- [Documentation](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)
- [OpenAPI](openapi/reolink-camera-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/reolink-camera-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/reolink-camera-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/device-info.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/command-request.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/command-response.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/login.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ptz-control.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/recording-search.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alarm-settings.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/network-settings.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/reolink-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Rules](rules/reolink-rules.yml)
- [Capabilities](capabilities/camera-management.yaml)
- [JSON Structure](json-structure/reolink-device-structure.json)
- [Vocabulary](vocabulary/reolink-vocabulary.yml)
- [Example](examples/reolink-login-example.json)
- [Example](examples/reolink-ptz-control-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/reolink-technology)
- [Website](https://reolink.com)
- [Forum](https://community.reolink.com/)
- [Support](https://support.reolink.com/)
- [Blog](https://reolink.com/blog/)
- [GitHub Organization](https://github.com/ReolinkCameraAPI)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
