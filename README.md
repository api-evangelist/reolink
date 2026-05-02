# Reolink

Reolink is a provider of security cameras and smart home surveillance technology. Their cameras offer an HTTP API that enables direct device control and configuration through JSON-based POST requests. The API supports comprehensive camera management including PTZ control, video encoding settings, recording search and playback, motion and AI-powered object detection, network configuration, LED control, and user authentication. The API is accessible on the local network via the device IP address.

**Human URL:** [https://reolink.com](https://reolink.com)

**API Documentation:** [https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)

---

## APIs

### Reolink Camera HTTP API

The Reolink Camera HTTP API uses JSON-based HTTP POST requests to `https://{camera_ip}/cgi-bin/api.cgi`. Session tokens are obtained via the Login command and passed as query parameters. The API covers 11 functional modules with 50+ operations.

**API Modules:**
- Authentication (Login, Logout)
- System (Device Info, Time, Storage, Reboot, Channels)
- Security (Users, Online Sessions)
- Network (Ports, WiFi, DDNS, NTP, Email, FTP, Push, UPnP)
- Video (Image, OSD, ISP, Privacy Mask, Snapshot)
- Encoding (Video Encoding Settings)
- Recording (Schedule, Search)
- PTZ (Control, Presets, Patrol, Calibration)
- Alarm (Motion Detection, AI Detection, Audio Alarm)
- LED (IR Lights, White Light, Power LED)
- AI (Object Detection State, Config, Auto-Tracking, Autofocus)

- **Documentation:** [https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)
- **OpenAPI Spec:** [openapi/reolink-camera-api-openapi.yml](openapi/reolink-camera-api-openapi.yml)
- **Rules:** [rules/reolink-rules.yml](rules/reolink-rules.yml)
- **Capabilities:** [capabilities/camera-management.yaml](capabilities/camera-management.yaml)

---

## Artifacts

### OpenAPI

| File | Description |
|---|---|
| [openapi/reolink-camera-api-openapi.yml](openapi/reolink-camera-api-openapi.yml) | Reolink Camera HTTP API v8.0 — 50+ operations |

### Rules

| File | Description |
|---|---|
| [rules/reolink-rules.yml](rules/reolink-rules.yml) | Spectral ruleset for Reolink API conventions |

### Capabilities

| File | Description |
|---|---|
| [capabilities/camera-management.yaml](capabilities/camera-management.yaml) | Camera management workflow — 15 MCP tools |
| [capabilities/shared/camera-api.yaml](capabilities/shared/camera-api.yaml) | Shared Reolink Camera API consumed definition |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/device-info.json](json-schema/device-info.json) | JSON Schema for device information |
| [json-schema/command-request.json](json-schema/command-request.json) | JSON Schema for API command request |
| [json-schema/command-response.json](json-schema/command-response.json) | JSON Schema for API command response |
| [json-schema/login.json](json-schema/login.json) | JSON Schema for login command |
| [json-schema/ptz-control.json](json-schema/ptz-control.json) | JSON Schema for PTZ control |
| [json-schema/recording-search.json](json-schema/recording-search.json) | JSON Schema for recording search |
| [json-schema/alarm-settings.json](json-schema/alarm-settings.json) | JSON Schema for alarm settings |
| [json-schema/network-settings.json](json-schema/network-settings.json) | JSON Schema for network settings |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/reolink-device-structure.json](json-structure/reolink-device-structure.json) | Structural documentation for device resources |

### JSON-LD

| File | Description |
|---|---|
| [json-ld/reolink-context.jsonld](json-ld/reolink-context.jsonld) | JSON-LD context for Reolink camera API |

### Examples

| File | Description |
|---|---|
| [examples/reolink-login-example.json](examples/reolink-login-example.json) | Authenticate and obtain session token |
| [examples/reolink-ptz-control-example.json](examples/reolink-ptz-control-example.json) | PTZ pan/tilt control command |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/reolink-vocabulary.yml](vocabulary/reolink-vocabulary.yml) | Security camera domain vocabulary |

---

## Common Properties

| Property | URL |
|---|---|
| Website | [https://reolink.com](https://reolink.com) |
| Community Forum | [https://community.reolink.com](https://community.reolink.com) |
| Support | [https://support.reolink.com](https://support.reolink.com) |
| Blog | [https://reolink.com/blog](https://reolink.com/blog) |
| Community API GitHub | [https://github.com/ReolinkCameraAPI](https://github.com/ReolinkCameraAPI) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
