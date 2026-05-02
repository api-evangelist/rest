# REST

REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DELETE, PATCH), and resource-oriented URLs to provide scalable, cacheable, and loosely coupled interfaces. It has become the dominant approach for building web APIs, forming the foundation of modern API design principles and tooling ecosystems.

**URL:** [https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rest/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- API Design, Architecture, HTTP, REST, RESTful, Web Services

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### REST Architectural Style

Representational State Transfer (REST) architectural style as defined by Roy Fielding's 2000 dissertation. Provides six guiding constraints: client-server separation, statelessness, cacheability, uniform interface, layered system, and optional code-on-demand.

- **Documentation**: [Roy Fielding Dissertation](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm)
- **Specification**: [RFC 7231](https://www.rfc-editor.org/rfc/rfc7231)

### OpenAPI Specification

The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to RESTful APIs which allows both humans and computers to discover and understand capabilities of a service.

- **Documentation**: [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- **GitHub**: [OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification)

### HTTP Semantics

RFC 9110 defines the semantics of HTTP, the foundation of RESTful API communication.

- **Specification**: [RFC 9110](https://www.rfc-editor.org/rfc/rfc9110)

### JSON:API

A specification for how clients should request and modify resources, built on REST principles.

- **Documentation**: [JSON:API Format](https://jsonapi.org/format/)

## Artifacts

### JSON Schema

- [`json-schema/rest-api-schema.json`](json-schema/rest-api-schema.json) — Schema representing key properties and constraints of a RESTful API.

### JSON Structure

- [`json-structure/rest-architecture-structure.json`](json-structure/rest-architecture-structure.json) — Structure documenting REST constraints, HTTP methods, status codes, and related specifications.

### JSON-LD Context

- [`json-ld/rest-context.jsonld`](json-ld/rest-context.jsonld) — JSON-LD context mapping REST vocabulary to schema.org and HTTP ontologies.

### Vocabulary

- [`vocabulary/rest-vocabulary.yml`](vocabulary/rest-vocabulary.yml) — Normative vocabulary for REST architectural style covering 20 key terms.

## Links

- **Website**: [restfulapi.net](https://restfulapi.net)
- **OpenAPI Tools**: [openapi.tools](https://openapi.tools)
- **RFC 9110**: [HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110)
- **GitHub**: [OAI/OpenAPI-Specification](https://github.com/OAI/OpenAPI-Specification)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
