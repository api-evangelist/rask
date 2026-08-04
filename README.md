# Rask AI (rask)

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

Rask AI is an AI video and audio localization platform offering automated dubbing, translation, transcription, voice cloning, and lip-sync across 130+ languages. Its REST API lets developers upload media, transcribe and translate it, create localization projects, and retrieve dubbed video, audio, and voiceover artifacts programmatically using an OAuth2 Bearer token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rask/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rask/refs/heads/main/apis.yml)

## Tags

- AI
- Video Localization
- Dubbing
- Translation
- Transcription

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Rask AI Projects & Dubbing Jobs API

Create and manage localization projects (dubbing jobs) from an uploaded video, specifying source and destination languages, speaker count, transcription, and glossary. Projects are processed asynchronously and return translated video, translated audio, and voiceover artifacts.

- **Human URL:** [https://docs.api.rask.ai/workflow/translation](https://docs.api.rask.ai/workflow/translation)
- **Base URL:** `https://api.rask.ai/v2`

#### Tags

- Projects
- Dubbing
- Localization

#### Properties

- [Documentation](https://docs.api.rask.ai)
- [API Reference](https://docs.api.rask.ai/api-reference/project/create_project)
- [OpenAPI](openapi/rask-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rask.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rask.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rask AI Translation API

Translate transcribed media into 130+ destination languages as part of the project generation workflow, with optional glossary support for consistent terminology and multi-speaker handling.

- **Human URL:** [https://docs.api.rask.ai/workflow/translation](https://docs.api.rask.ai/workflow/translation)
- **Base URL:** `https://api.rask.ai/v2`

#### Tags

- Translation
- Languages

#### Properties

- [Documentation](https://docs.api.rask.ai/workflow/translation)
- [API Reference](https://docs.api.rask.ai/languages/destination)
- [OpenAPI](openapi/rask-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rask.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rask.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rask AI Voices API

Retrieve and assign project voices and speakers, including voice cloning that creates a digital copy of the original speaker's voice across supported languages for multi-speaker localization.

- **Human URL:** [https://docs.api.rask.ai/workflow/voices](https://docs.api.rask.ai/workflow/voices)
- **Base URL:** `https://api.rask.ai/v2`

#### Tags

- Voices
- Voice Cloning
- Speakers

#### Properties

- [Documentation](https://docs.api.rask.ai/workflow/voices)
- [OpenAPI](openapi/rask-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rask.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rask.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rask AI Transcription API

Automatically transcribe uploaded video and audio into editable text segments, or supply an SRT file for higher dubbing accuracy. Transcriptions feed the translation and project generation steps.

- **Human URL:** [https://www.rask.ai/api/transcription-api](https://www.rask.ai/api/transcription-api)
- **Base URL:** `https://api.rask.ai/v2`

#### Tags

- Transcription
- Speech to Text
- SRT

#### Properties

- [Documentation](https://www.rask.ai/api/transcription-api)
- [API Reference](https://docs.api.rask.ai/api-reference/project/create_transcription)
- [OpenAPI](openapi/rask-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rask.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rask.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rask AI Job Status API

Poll an individual project to monitor its asynchronous processing status and retrieve output artifact links (translated video, translated audio, voiceover) once localization completes.

- **Human URL:** [https://docs.api.rask.ai/api-reference/project/get_project](https://docs.api.rask.ai/api-reference/project/get_project)
- **Base URL:** `https://api.rask.ai/v2`

#### Tags

- Job Status
- Async
- Artifacts

#### Properties

- [Documentation](https://docs.api.rask.ai/api-reference/project/get_project)
- [API Reference](https://docs.api.rask.ai/api-reference/project/get_project)
- [OpenAPI](openapi/rask-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rask.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rask.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/braskai)
- [LinkedIn](https://www.linkedin.com/company/rask-ai)
- [Website](https://www.rask.ai)
- [Documentation](https://docs.api.rask.ai)
- [Plans](plans/rask-plans-pricing.yml)
- [Rate Limits](rate-limits/rask-rate-limits.yml)
- [Fin Ops](finops/rask-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
