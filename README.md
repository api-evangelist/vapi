# Vapi (vapi)

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

Vapi is a voice AI agents platform for building, testing, and deploying real-time voice agents across phone, web, and SIP. The Vapi REST API exposes assistants, calls, chats, campaigns, phone numbers, tools, files, squads, sessions, structured outputs, and analytics, plus server/client webhook events. A published OpenAPI spec is available at https://api.vapi.ai/api-json.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vapi/refs/heads/main/apis.yml)

## Tags

- AI
- Voice
- Agents
- Realtime
- CPaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-19

## APIs

### Vapi Platform API

REST API for managing Vapi voice AI agents. Supports CRUD on Assistants, Squads, Calls, Chats, Campaigns, Sessions, Phone Numbers, Tools, Files, Structured Outputs, Insight, Eval, Observability, and Analytics. Auth is bearer token; base URL is https://api.vapi.ai.

- **Human URL:** [https://docs.vapi.ai/api-reference](https://docs.vapi.ai/api-reference)
- **Base URL:** `https://api.vapi.ai`

#### Tags

- Voice
- Agents
- Calls
- Phone Numbers
- Realtime

#### Properties

- [Documentation](https://docs.vapi.ai/api-reference)
- [OpenAPI](openapi/vapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Sign Up](https://dashboard.vapi.ai/)
- [Pricing](https://vapi.ai/pricing)

### Vapi Webhooks API

Server- and client-side webhook events emitted by Vapi during voice sessions, including end-of-call reports, transcripts, function calls, status updates, and tool invocations.

- **Human URL:** [https://docs.vapi.ai/server-url](https://docs.vapi.ai/server-url)
- **Base URL:** `https://docs.vapi.ai`

#### Tags

- Webhooks
- Events
- Voice

#### Properties

- [Documentation](https://docs.vapi.ai/server-url)
- [Postman Collection](collections/vapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/VapiAI)
- [LinkedIn](https://www.linkedin.com/company/vapi-ai)
- [Website](https://vapi.ai/)
- [Documentation](https://docs.vapi.ai/)
- [OpenAPI](openapi/vapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](plans/vapi-plans-pricing.yml)
- [Rate Limits](rate-limits/vapi-rate-limits.yml)
- [Fin Ops](finops/vapi-finops.yml)
- [L L Ms Txt](https://vapi.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
