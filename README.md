# Schema Design

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
