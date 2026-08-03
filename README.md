# Azure OpenAI Service (azure-openai)

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

Azure OpenAI Service (part of Microsoft Foundry Models) provides REST API access to OpenAI models including GPT, o-series reasoning models, DALL-E, Whisper, and embedding models, hosted within Microsoft Azure with enterprise security, regional availability, private networking, content filtering, and Microsoft Entra ID integration. The data-plane REST API exposes endpoints for chat completions, completions, embeddings, image generation, audio transcription/translation, fine-tuning, and the Responses API, while the control-plane API manages Azure OpenAI resources and deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-openai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-openai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- LLM
- Generative AI
- Azure
- OpenAI
- Foundation Models
- Chat Completions
- Embeddings

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-29

## APIs

### Azure OpenAI Inference REST API

Data-plane REST API for running inference against deployed Azure OpenAI models, including chat completions, completions, embeddings, image generation, and audio transcription/translation. Authenticate with API key (api-key header) or Microsoft Entra ID bearer token.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/ai-services/openai/reference](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference)
- **Base URL:** `https://{your-resource-name}.openai.azure.com/openai`

#### Tags

- Inference
- Chat Completions
- Embeddings
- Image Generation
- Audio

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference)
- [A P I  Reference ( Latest)](https://learn.microsoft.com/en-us/azure/foundry/openai/latest)
- [A P I  Reference ( Preview)](https://learn.microsoft.com/en-us/azure/foundry/openai/reference-preview-latest)
- [Open A P I  Source](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/cognitiveservices/data-plane/AzureOpenAI)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/azure-openai/refs/heads/main/asyncapi/azure-openai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/azure-openai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-openai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure OpenAI Responses API

Stateful, agent-friendly API for building multi-turn AI experiences with tool use, file inputs, and conversation state managed on the service side.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/responses](https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/responses)
- **Base URL:** `https://{your-resource-name}.openai.azure.com/openai/responses`

#### Tags

- Responses
- Agents
- Tool Use

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/responses)
- [Postman Collection](collections/azure-openai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-openai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure OpenAI Control Plane API

Azure Resource Manager (ARM) REST API for creating and managing Azure OpenAI accounts, model deployments, network rules, and other resource configuration.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/cognitiveservices/](https://learn.microsoft.com/en-us/rest/api/cognitiveservices/)
- **Base URL:** `https://management.azure.com`

#### Tags

- ARM
- Control Plane
- Deployments
- Resource Management

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/cognitiveservices/)
- [Postman Collection](collections/azure-openai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-openai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://azure.microsoft.com/en-us/products/ai-services/openai-service)
- [Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [API Reference](https://learn.microsoft.com/en-us/azure/ai-services/openai/reference)
- [Quickstart](https://learn.microsoft.com/en-us/azure/ai-services/openai/quickstart)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/openai-service/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [Git Hub  Samples](https://github.com/Azure-Samples/Azure-OpenAI-Docs-Samples)
- [Open A P I  Source](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/cognitiveservices/data-plane/AzureOpenAI)
- [L L Ms Txt](https://azure.microsoft.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
