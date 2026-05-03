# Wolfram|Alpha (wolfram-alpha)
Wolfram|Alpha is a computational knowledge engine that provides answers to natural language queries using a vast curated knowledge base and computational algorithms. The Wolfram|Alpha API suite gives developers programmatic access to computational intelligence for web, mobile, and AI applications. APIs range from the full-featured Full Results API to specialized LLM, Short Answers, Simple, Spoken Results, and Fast Query Recognizer APIs.

**URL:** [https://www.wolframalpha.com](https://www.wolframalpha.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Artificial Intelligence, Computational Knowledge, Natural Language Processing, Search

## Timestamps

- **Created:** 2024-10-18
- **Modified:** 2026-05-03

## APIs

### Wolfram|Alpha LLM API
The LLM API delivers computational knowledge results optimized for consumption by large language models and AI chat applications. Built on the same engine as the full API, it returns structured text with query interpretation, computed results, and relevant data formatted for LLM processing. Authentication uses an AppID query parameter or Bearer token.

**Human URL:** [https://products.wolframalpha.com/llm-api/documentation](https://products.wolframalpha.com/llm-api/documentation)

#### Tags:

 - AI, Computational Knowledge, LLM

#### Properties

- [Documentation](https://products.wolframalpha.com/llm-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-llm-api-openapi.yml)
- [LLM API Response Schema](json-schema/wolfram-alpha-llm-api-llm-api-response-schema.json)

### Wolfram|Alpha Full Results API
The Full Results API provides full programmatic access to all Wolfram|Alpha capabilities, including disambiguation, drilldown, asynchronous delivery, and results in multiple formats (XML, JSON). It supports customizable pod selection, location-aware queries, and display formatting.

**Human URL:** [https://products.wolframalpha.com/api/documentation](https://products.wolframalpha.com/api/documentation)

#### Tags:

 - Computation, Full Results, Natural Language Processing

#### Properties

- [Documentation](https://products.wolframalpha.com/api/documentation)
- [OpenAPI](openapi/wolfram-alpha-full-results-api-openapi.yml)
- [Full Results Response Schema](json-schema/wolfram-alpha-full-results-api-full-results-response-schema.json)
- [Pod Schema](json-schema/wolfram-alpha-full-results-api-pod-schema.json)
- [Subpod Schema](json-schema/wolfram-alpha-full-results-api-subpod-schema.json)

### Wolfram|Alpha Short Answers API
The Short Answers API returns a single concise plain-text result from Wolfram|Alpha, ideal for chatbots, mobile apps, and constrained displays. Returns HTTP 501 when no brief answer is available.

**Human URL:** [https://products.wolframalpha.com/short-answers-api/documentation](https://products.wolframalpha.com/short-answers-api/documentation)

#### Tags:

 - Natural Language Processing, Short Answers, Text

#### Properties

- [Documentation](https://products.wolframalpha.com/short-answers-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-short-answers-api-openapi.yml)

### Wolfram|Alpha Simple API
The Simple API returns complete Wolfram|Alpha results as a rendered image, requiring minimal coding. Suitable for embedding computational results visually in web applications without handling complex XML/JSON responses.

**Human URL:** [https://products.wolframalpha.com/simple-api/documentation](https://products.wolframalpha.com/simple-api/documentation)

#### Tags:

 - Images, Natural Language Processing, Visual Results

#### Properties

- [Documentation](https://products.wolframalpha.com/simple-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-simple-api-openapi.yml)

### Wolfram|Alpha Spoken Results API
The Spoken Results API returns answers optimized for audio delivery, suitable for voice assistants, automotive systems, and accessibility features. Results are plain text formatted to be read aloud naturally.

**Human URL:** [https://products.wolframalpha.com/spoken-results-api/documentation](https://products.wolframalpha.com/spoken-results-api/documentation)

#### Tags:

 - Audio, Natural Language Processing, Voice

#### Properties

- [Documentation](https://products.wolframalpha.com/spoken-results-api/documentation)
- [OpenAPI](openapi/wolfram-alpha-spoken-results-api-openapi.yml)

## Common Properties

- [Website](https://www.wolframalpha.com)
- [Developer Portal](https://developer.wolframalpha.com/)
- [Portal](https://products.wolframalpha.com/api)
- [Sign Up](https://developer.wolframalpha.com/)
- [Authentication](https://products.wolframalpha.com/api/documentation)
- [Pricing](https://products.wolframalpha.com/api)
- [Terms of Service](https://products.wolframalpha.com/api/documentation)
- [Spectral Rules](rules/wolfram-alpha-spectral-rules.yml)
- [AI Knowledge Integration](capabilities/ai-knowledge-integration.yaml)
- [Computational Search](capabilities/computational-search.yaml)
- [Vocabulary](vocabulary/wolfram-alpha-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Computational Intelligence | Access Wolfram's curated knowledge base and computation engine for math, science, geography, and more. |
| Multiple Output Formats | Choose from XML, JSON, plain text, image, or audio output depending on your application needs. |
| LLM-Optimized Responses | Specialized API endpoint returns structured text formatted for large language model consumption. |
| Sub-10ms Query Classification | Fast Query Recognizer classifies queries before sending to the full engine, reducing latency. |
| Location-Aware Queries | Pass IP, coordinates, or location names for geographically relevant results. |

## Use Cases

| Name | Description |
|------|-------------|
| AI Assistant Integration | Provide LLMs with computational knowledge results via the LLM API. |
| Chatbot Answers | Return concise answers to natural language questions in chatbot interfaces using the Short Answers API. |
| Voice Applications | Deliver audio-ready answer strings for voice assistants using the Spoken Results API. |
| Educational Platforms | Embed Wolfram computational results visually in learning platforms using the Simple API. |
| Search Augmentation | Pre-classify user queries with the Fast Query Recognizer to route to Wolfram only when appropriate. |

## Integrations

| Name | Description |
|------|-------------|
| Mathematica | Wolfram Language integration for computational workflows. |
| OpenAI / ChatGPT Plugin | Official ChatGPT plugin for Wolfram computational knowledge. |
| Siri / Voice Assistants | Spoken Results API used by voice assistant integrations. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Wolfram|Alpha LLM API](openapi/wolfram-alpha-llm-api-openapi.yml)
- [Wolfram|Alpha Full Results API](openapi/wolfram-alpha-full-results-api-openapi.yml)
- [Wolfram|Alpha Short Answers API](openapi/wolfram-alpha-short-answers-api-openapi.yml)
- [Wolfram|Alpha Simple API](openapi/wolfram-alpha-simple-api-openapi.yml)
- [Wolfram|Alpha Spoken Results API](openapi/wolfram-alpha-spoken-results-api-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [LLM API](capabilities/shared/llm-api.yaml) — 1 operation for computational LLM queries
- [Full Results API](capabilities/shared/full-results-api.yaml) — 1 operation for complete pod-based results
- [Short Answers API](capabilities/shared/short-answers-api.yaml) — 1 operation for concise text answers
- [Spoken Results API](capabilities/shared/spoken-results-api.yaml) — 1 operation for audio-optimized answers

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [AI Knowledge Integration](capabilities/ai-knowledge-integration.yaml) | LLM API, Short Answers, Spoken Results | 3 | AI Developer, Chatbot Engineer |
| [Computational Search](capabilities/computational-search.yaml) | Full Results API, LLM API | 2 | Search Engineer, Platform Developer |

## Vocabulary

- [Wolfram|Alpha Vocabulary](vocabulary/wolfram-alpha-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 3 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Wolfram|Alpha Spectral Rules](rules/wolfram-alpha-spectral-rules.yml) — Spectral ruleset enforcing Wolfram|Alpha API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
