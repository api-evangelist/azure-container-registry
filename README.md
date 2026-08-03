# Azure Container Registry (azure-container-registry)

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

Azure Container Registry is a managed Docker registry service for storing and managing private container images with support for automated builds, geo-replication, and Azure deployment integration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-container-registry/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Container Images, Containers, Docker, Registry

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Azure Container Registry
Azure Container Registry is a managed Docker registry service for storing and managing private container images with support for automated builds, geo-replication, and Azure deployment integration.

**Human URL:** [https://azure.microsoft.com/en-us/products/container-registry](https://azure.microsoft.com/en-us/products/container-registry)

#### Tags:

 - Container Images, Containers, Docker, Registry

#### Properties

- [Documentation](https://azure.microsoft.com/en-us/products/container-registry)
- [OpenAPI](openapi/azure-container-registry-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Container Registry](openapi/azure-container-registry-openapi.yaml)

### JSON Schema

- [Event](json-schema/azure-container-registry-event-schema.json)
- [Operation Display Definition](json-schema/azure-container-registry-operation-display-definition-schema.json)
- [Event List Result](json-schema/azure-container-registry-event-list-result-schema.json)
- [Policies](json-schema/azure-container-registry-policies-schema.json)
- [Actor](json-schema/azure-container-registry-actor-schema.json)
- [Quarantine Policy](json-schema/azure-container-registry-quarantine-policy-schema.json)
- [Registry Name Status](json-schema/azure-container-registry-registry-name-status-schema.json)
- [Registry Name Check Request](json-schema/azure-container-registry-registry-name-check-request-schema.json)
- [Event Content](json-schema/azure-container-registry-event-content-schema.json)
- [Operation Service Specification Definition](json-schema/azure-container-registry-operation-service-specification-definition-schema.json)

### JSON-LD

- [Azure Container Registry Context](json-ld/azure-container-registry-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Container Registry](capabilities/shared/azure-container-registry.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Container Registry Management](capabilities/azure-container-registry-management.yaml) | Azure Container Registry | 5 | Cloud Engineer |

## Vocabulary

- [Azure Container Registry Vocabulary](vocabulary/azure-container-registry-vocabulary.yaml)

## Rules

- [Azure Container Registry Spectral Rules](rules/azure-container-registry-spectral-rules.yml) — 15 rules enforcing Azure Container Registry API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
