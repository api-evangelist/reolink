# Reolink (reolink)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
