# Wolfram|Alpha (wolfram-alpha)

Wolfram|Alpha is a computational knowledge engine that provides answers to natural language queries using a vast curated knowledge base and computational algorithms. The Wolfram|Alpha API suite gives developers programmatic access to computational intelligence for web, mobile, and AI applications. APIs range from the full-featured Full Results API to specialized LLM, Short Answers, Simple, Spoken Results, and Fast Query Recognizer APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wolfram-alpha/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- Computational Knowledge
- Natural Language Processing
- Search

## Timestamps

- **Created:** 2024-10-18
- **Modified:** 2026-05-19

## APIs

### Wolfram|Alpha LLM API

The LLM API delivers computational knowledge results optimized for consumption by large language models and AI chat applications. Built on the same engine as the full API, it returns structured text with query interpretation, computed results, and relevant data formatted for LLM processing. Authentication uses an AppID query parameter or Bearer token.

- **Human URL:** [https://products.wolframalpha.com/llm-api/documentation](https://products.wolframalpha.com/llm-api/documentation)
- **Base URL:** `https://www.wolframalpha.com/api/v1/`

#### Tags

- AI
- Computational Knowledge
- LLM

#### Properties

- [Documentation](https://products.wolframalpha.com/llm-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-llm-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolfram-alpha-llm-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolfram-alpha-llm-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wolfram-alpha-llm-api-llm-api-response-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Wolfram|Alpha Full Results API

The Full Results API provides full programmatic access to all Wolfram|Alpha capabilities, including disambiguation, drilldown, asynchronous delivery, and results in multiple formats (XML, JSON). It supports customizable pod selection, location-aware queries, and display formatting.

- **Human URL:** [https://products.wolframalpha.com/api/documentation](https://products.wolframalpha.com/api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v2/`

#### Tags

- Computation
- Full Results
- Natural Language Processing

#### Properties

- [Documentation](https://products.wolframalpha.com/api/documentation)
- [OpenAPI](openapi/wolfram-alpha-full-results-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolfram-alpha-full-results-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolfram-alpha-full-results-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/wolfram-alpha-full-results-api-full-results-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wolfram-alpha-full-results-api-pod-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/wolfram-alpha-full-results-api-subpod-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Wolfram|Alpha Short Answers API

The Short Answers API returns a single concise plain-text result from Wolfram|Alpha, ideal for chatbots, mobile apps, and constrained displays. Returns HTTP 501 when no brief answer is available.

- **Human URL:** [https://products.wolframalpha.com/short-answers-api/documentation](https://products.wolframalpha.com/short-answers-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Natural Language Processing
- Short Answers
- Text

#### Properties

- [Documentation](https://products.wolframalpha.com/short-answers-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-short-answers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolfram-alpha-short-answers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolfram-alpha-short-answers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wolfram|Alpha Simple API

The Simple API returns complete Wolfram|Alpha results as a rendered image, requiring minimal coding. Suitable for embedding computational results visually in web applications without handling complex XML/JSON responses.

- **Human URL:** [https://products.wolframalpha.com/simple-api/documentation](https://products.wolframalpha.com/simple-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Images
- Natural Language Processing
- Visual Results

#### Properties

- [Documentation](https://products.wolframalpha.com/simple-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-simple-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolfram-alpha-simple-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolfram-alpha-simple-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wolfram|Alpha Spoken Results API

The Spoken Results API returns answers optimized for audio delivery, suitable for voice assistants, automotive systems, and accessibility features. Results are plain text formatted to be read aloud naturally.

- **Human URL:** [https://products.wolframalpha.com/spoken-results-api/documentation](https://products.wolframalpha.com/spoken-results-api/documentation)
- **Base URL:** `https://api.wolframalpha.com/v1/`

#### Tags

- Audio
- Natural Language Processing
- Voice

#### Properties

- [Documentation](https://products.wolframalpha.com/spoken-results-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-spoken-results-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/wolfram-alpha-spoken-results-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wolfram-alpha-spoken-results-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/wolfram-alpha-llc)
- [Website](https://www.wolframalpha.com)
- [Developer Portal](https://developer.wolframalpha.com/)
- [Portal](https://products.wolframalpha.com/api)
- [Sign Up](https://developer.wolframalpha.com/)
- [Authentication](https://products.wolframalpha.com/api/documentation)
- [Pricing](https://products.wolframalpha.com/api)
- [Terms of Service](https://products.wolframalpha.com/api/documentation)
- [Spectral Rules](rules/wolfram-alpha-spectral-rules.yml)
- [Vocabulary](vocabulary/wolfram-alpha-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
