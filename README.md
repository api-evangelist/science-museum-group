# Science Museum Group (science-museum-group)

The Science Museum Group operates five UK science and technology museums: the Science Museum (London), the Science and Industry Museum (Manchester), the National Railway Museum (York), the National Science and Media Museum (Bradford), and Locomotion (Shildon). The group provides an open Collection API giving developers programmatic access to over 7 million objects, people, and documents via a JSONAPI-compliant REST interface.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/science-museum-group/refs/heads/main/apis.yml)

## Tags

- Museums
- Collections
- Cultural Heritage
- Open Data
- Science
- Technology
- United Kingdom

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Science Museum Group Collection API

A JSONAPI-compliant REST API providing open access to the Science Museum Group's collection of over 7 million objects, people, and documents across its five UK museums. Search and retrieve data about scientific instruments, industrial artifacts, railway objects, and cultural items with image access, pagination, and rich filtering.

**Human URL:** [https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api](https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api)

**Base URL:** `https://collection.sciencemuseumgroup.org.uk`

#### Tags

- Collections
- Museums
- Open Data
- Cultural Heritage
- Science
- JSONAPI

#### Properties

- [Documentation](https://www.sciencemuseumgroup.org.uk/our-work/our-collection/using-our-collection-api)
- [OpenAPI Specification](openapi/science-museum-group-collection-openapi.yml)
- [GitHub Repository](https://github.com/TheScienceMuseum/collectionsonline-api)
- [Spectral Rules](rules/science-museum-group-rules.yml)
- [Naftiko Capabilities](capabilities/collection-discovery.yaml)
- [JSON Schema](json-schema/science-museum-group-collection-object-schema.json)
- [JSON-LD Context](json-ld/science-museum-group-context.jsonld)
- [Vocabulary](vocabulary/science-museum-group-vocabulary.yml)

## Common Properties

- [GitHub Organization](https://github.com/TheScienceMuseum)
- [Website](https://www.sciencemuseumgroup.org.uk/)
- [Collections Portal](https://collection.sciencemuseumgroup.org.uk)

## Artifacts

### OpenAPI Specifications

- [Science Museum Group Collection API](openapi/science-museum-group-collection-openapi.yml) — Full OpenAPI 3.1 spec covering search and retrieval of objects, people, and documents.

### Spectral Rules

- [Science Museum Group API Rules](rules/science-museum-group-rules.yml) — Spectral ruleset enforcing JSONAPI compliance, naming conventions, and documentation standards.

### Capabilities

- [Collection Discovery](capabilities/collection-discovery.yaml) — Workflow capability composing search, browse, and retrieval operations with REST and MCP adapters.

#### Shared

- [Collection API](capabilities/shared/collection-api.yaml) — Per-API consumed definition for the Science Museum Group Collection API.

### JSON Schema

- [Collection Object Schema](json-schema/science-museum-group-collection-object-schema.json) — JSON Schema for collection object resources.

### JSON Structure

- [Collection Object Structure](json-structure/science-museum-group-collection-object-structure.json) — Structural documentation for collection object API responses.

### JSON-LD

- [Science Museum Group Context](json-ld/science-museum-group-context.jsonld) — Linked data context aligning collection vocabulary with schema.org.

### Examples

- [Search Objects Example](examples/science-museum-group-search-objects-example.json) — Example request/response for GET /search/objects.
- [Get Object Example](examples/science-museum-group-get-object-example.json) — Example request/response for GET /objects/{id}.

### Vocabulary

- [Science Museum Group Vocabulary](vocabulary/science-museum-group-vocabulary.yml) — Domain vocabulary for museum collections, JSONAPI conventions, and science/technology subject areas.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
