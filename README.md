# Rask AI (rask)

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
