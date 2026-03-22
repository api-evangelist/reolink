# Reolink (reolink)
Reolink is a provider of security cameras and smart home surveillance technology. Their cameras offer an HTTP API that enables direct device control and configuration through JSON-based POST requests. The API supports comprehensive camera management including PTZ control, video encoding settings, recording search and playback, motion and AI-powered object detection, network configuration, LED control, and user authentication. The API is accessible on the local network via the device IP address.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/reolink/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Security Cameras, IoT, Surveillance

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-16 

## APIs

### Reolink Camera HTTP API
The Reolink Camera HTTP API provides a JSON-based interface for controlling and configuring Reolink IP cameras and NVRs. All commands are sent as HTTP POST requests to the /cgi-bin/api.cgi endpoint. The API covers 11 functional modules including authentication, system management, security, network configuration, video and image settings, encoding, recording and playback, PTZ control, alarm and motion detection, LED control, and AI-powered object detection with auto-tracking. Authentication uses a token-based session system obtained via the Login command.

**Human URL:** [https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)


#### Tags:

 - Security Cameras, IoT, Surveillance

#### Properties

- [Documentation](https://community.reolink.com/topic/4196/reolink-camera-api-user-guide_v8-updated-in-april-2023)
- [OpenAPI](openapi/reolink-camera-api-openapi.yml)
- [JSONSchema](json-schema/device-info.json)
- [JSONSchema](json-schema/command-request.json)
- [JSONSchema](json-schema/command-response.json)
- [JSONSchema](json-schema/login.json)
- [JSONSchema](json-schema/ptz-control.json)
- [JSONSchema](json-schema/recording-search.json)
- [JSONSchema](json-schema/alarm-settings.json)
- [JSONSchema](json-schema/network-settings.json)
- [JSONLD](json-ld/reolink-context.jsonld)

## Common Properties

- [Website](https://reolink.com)
- [Forum](https://community.reolink.com/)
- [Support](https://support.reolink.com/)
- [Blog](https://reolink.com/blog/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
