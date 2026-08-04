# Schema Design

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

Schema Design is the practice of defining the structure, constraints, and semantics of data models used in APIs, databases, and data exchange formats. It encompasses schema-first API design approaches, data modeling methodologies, type systems, and tooling for creating, validating, and evolving data schemas. Key formats include JSON Schema, OpenAPI components/schemas, GraphQL types, Protocol Buffers, Apache Avro, and database DDL.

**URL:** [https://github.com/api-evangelist/schema-design](https://github.com/api-evangelist/schema-design)

## Tags

 - Schema Design, Data Modeling, API Design, JSON Schema, OpenAPI, GraphQL, Data Validation, Type Systems

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### JSON Schema Specification

JSON Schema is a vocabulary that allows you to annotate and validate JSON documents. It is the foundation for defining request and response body schemas in OpenAPI specifications.

**Human URL:** [https://json-schema.org](https://json-schema.org)

#### Tags

 - JSON Schema, Validation, Specification

#### Properties

- [Documentation](https://json-schema.org/learn/)
- [Reference](https://json-schema.org/specification)

### OpenAPI Schema Objects

OpenAPI uses a subset of JSON Schema (with extensions) to define the schema of request bodies, parameters, and response payloads.

**Human URL:** [https://spec.openapis.org/oas/v3.1.0#schema-object](https://spec.openapis.org/oas/v3.1.0#schema-object)

#### Tags

 - OpenAPI, REST, API Design, Schema

#### Properties

- [Documentation](https://spec.openapis.org/oas/v3.1.0#schema-object)
- [Reference](https://swagger.io/specification/)

### GraphQL Type System

GraphQL uses a strong type system to define the shape of data that can be queried, forming the contract between clients and servers.

**Human URL:** [https://graphql.org/learn/schema/](https://graphql.org/learn/schema/)

#### Tags

 - GraphQL, Type System, API Design, Schema

#### Properties

- [Documentation](https://graphql.org/learn/schema/)
- [Reference](https://spec.graphql.org/)

### Apache Avro Schema

Apache Avro is a data serialization system using JSON for schema definition, widely used in Apache Kafka event streaming.

**Human URL:** [https://avro.apache.org/docs/current/spec.html](https://avro.apache.org/docs/current/spec.html)

#### Tags

 - Avro, Event Streaming, Kafka, Serialization

#### Properties

- [Documentation](https://avro.apache.org/docs/current/spec.html)

### Protocol Buffers (Protobuf) Schema

Protocol Buffers is Google's language-neutral, extensible mechanism for serializing structured data, used heavily in gRPC APIs.

**Human URL:** [https://protobuf.dev/programming-guides/proto3/](https://protobuf.dev/programming-guides/proto3/)

#### Tags

 - Protobuf, gRPC, Serialization, API Design

#### Properties

- [Documentation](https://protobuf.dev/programming-guides/proto3/)

## Common Properties

- [Website](https://json-schema.org)
- [JSON-LD](json-ld/schema-design-context.jsonld)
- [Vocabulary](vocabulary/schema-design-vocabulary.yml)

## JSON Schema

| Schema | Description |
|---|---|
| [schema-design-api-schema-schema.json](json-schema/schema-design-api-schema-schema.json) | Schema representing an API schema definition entity |

## JSON Structure

| Structure | Description |
|---|---|
| [schema-design-api-schema-structure.json](json-structure/schema-design-api-schema-structure.json) | Structural documentation for API schema design patterns |

## JSON-LD

| Context | Description |
|---|---|
| [schema-design-context.jsonld](json-ld/schema-design-context.jsonld) | JSON-LD context for schema design vocabulary |

## Examples

| Example | Description |
|---|---|
| [schema-design-json-schema-example.json](examples/schema-design-json-schema-example.json) | Well-designed JSON Schema example for a user profile entity |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [schema-design-vocabulary.yml](vocabulary/schema-design-vocabulary.yml) | Schema design domain terminology and concepts |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
