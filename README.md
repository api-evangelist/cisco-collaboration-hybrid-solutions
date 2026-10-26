# Cisco Collaboration Hybrid Solutions (cisco-collaboration-hybrid-solutions)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs for Cisco's hybrid collaboration solutions that combine Webex cloud services with on-premises Unified Communications Manager (CUCM), Expressway, and supporting infrastructure. Hybrid Services let an organization keep calling, calendaring, and identity on-premises while using Webex for meetings, messaging, devices, and management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-collaboration-hybrid-solutions/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Calling
- Collaboration
- Hybrid Cloud
- Meetings
- Messaging
- Unified Communications
- Webex

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-23

## APIs

### Webex APIs

Core Webex platform APIs for messaging, meetings, teams, spaces, memberships, attachments, and webhooks.

- **Human URL:** [https://developer.webex.com/](https://developer.webex.com/)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Collaboration
- Meetings
- Messaging
- Spaces
- Teams

#### Properties

- [Documentation](https://developer.webex.com/docs/api/getting-started)
- [OpenAPI](https://developer.webex.com/docs/api/v1/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.webex.com/docs/integrations)
- [S D Ks](https://developer.webex.com/docs/sdks)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meetings API

Schedule, list, update, and cancel Webex meetings; manage participants, recordings, transcripts, and meeting templates.

- **Human URL:** [https://developer.cisco.com/docs/webex-meetings/](https://developer.cisco.com/docs/webex-meetings/)
- **Base URL:** `https://webexapis.com/v1/meetings`

#### Tags

- Meetings
- Recordings
- Scheduling

#### Properties

- [Documentation](https://developer.cisco.com/docs/webex-meetings/)
- [Reference](https://developer.webex.com/docs/api/v1/meetings)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Hybrid Services API

Manage Webex Hybrid Calendar, Hybrid Call Service, Hybrid Message, Video Mesh nodes, and other connectors that bridge on-premises collaboration infrastructure to the Webex cloud.

- **Human URL:** [https://developer.cisco.com/docs/webex-hybrid-services/](https://developer.cisco.com/docs/webex-hybrid-services/)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Calendar
- Connectors
- Hybrid
- Media

#### Properties

- [Documentation](https://developer.cisco.com/docs/webex-hybrid-services/)
- [Reference](https://developer.webex.com/docs/api/v1/hybrid-clusters)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Calling API

Cloud calling capabilities including call control, dial plans, voicemail, voice portals, queues, hunt groups, and number provisioning.

- **Human URL:** [https://developer.webex.com/docs/api/v1/webex-calling](https://developer.webex.com/docs/api/v1/webex-calling)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Call Control
- Calling
- Telephony
- Voicemail

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/webex-calling)
- [Reference](https://developer.webex.com/docs/api/v1/call-controls)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Control Hub API

Administer Webex organizations, users, licenses, audit events, and service settings programmatically.

- **Human URL:** [https://developer.webex.com/docs/api/v1/organizations](https://developer.webex.com/docs/api/v1/organizations)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Administration
- Management
- Organizations
- Users

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/organizations)
- [Reference](https://developer.webex.com/docs/api/v1/admin-audit-events)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Devices API

Manage and control Webex Room and Desk Devices including remote configuration, status queries, and the device-side xAPI.

- **Human URL:** [https://developer.webex.com/docs/api/v1/devices](https://developer.webex.com/docs/api/v1/devices)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Devices
- Endpoints
- Room Systems

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/devices)
- [x A P I  Reference](https://roomos.cisco.com/xapi)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Events API

Create and manage Webex Webinars and large-format virtual events, including registration, panelists, and analytics.

- **Human URL:** [https://developer.webex.com/docs/api/v1/events](https://developer.webex.com/docs/api/v1/events)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Events
- Virtual Events
- Webinars

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/events)
- [Postman Collection](collections/cisco-collaboration-hybrid-solutions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-collaboration-hybrid-solutions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.cisco.com/collaboration/)
- [Webex  Developer  Portal](https://developer.webex.com/)
- [Getting Started](https://developer.webex.com/docs/getting-started)
- [Authentication](https://developer.webex.com/docs/integrations)
- [Webhooks](https://developer.webex.com/docs/api/guides/webhooks)
- [Changelog](https://developer.webex.com/changelog)
- [Status Page](https://status.webex.com/)
- [Community](https://community.cisco.com/t5/collaboration-voice-and-video/bd-p/discussions-collaboration)
- [GitHub Organization](https://github.com/WebexSamples)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [JSON-LD](json-ld/cisco-collaboration-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
