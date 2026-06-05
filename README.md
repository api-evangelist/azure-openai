# Azure OpenAI Service (azure-openai)

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
