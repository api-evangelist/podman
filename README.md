# Podman (podman)

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

Podman is a daemonless, open-source container engine for developing, managing, and running OCI containers on Linux, supporting both rootful and rootless operation as a drop-in replacement for Docker. The Podman REST API exposes a Docker-compatible surface alongside Libpod-specific endpoints for pods, volumes, networks, secrets, generators, and system management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/podman/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Native
- Containers
- DevOps
- OCI
- Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Podman REST API

The Podman REST API (libpod) provides a Docker-compatible API surface plus Podman-specific Libpod endpoints for managing containers, images, pods, volumes, networks, secrets, manifests, and the Podman system service. The API is published as a Swagger 2.0 specification generated from the Podman source tree.

- **Human URL:** [https://docs.podman.io/en/latest/_static/api.html](https://docs.podman.io/en/latest/_static/api.html)
- **Base URL:** `http://d/v6.0.0/libpod`

#### Tags

- Containers
- DevOps
- OCI

#### Properties

- [Documentation](https://docs.podman.io/en/latest/_static/api.html)
- [Getting Started](https://docs.podman.io/en/latest/markdown/podman-system-service.1.html)
- [OpenAPI](openapi/podman-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/podman.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/podman.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://podman.io/)
- [Documentation](https://docs.podman.io/)
- [GitHub Organization](https://github.com/containers)
- [Source Code](https://github.com/containers/podman)
- [Blog](https://podman.io/blogs/)
- [Community](https://podman.io/community/)
- [Getting Started](https://podman.io/get-started)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
