# Stacker

Stacker is a no-code platform that enables organizations to build custom business applications, internal tools, and customer portals on top of their existing data sources — including Airtable, Google Sheets, SQL databases, and Salesforce — without writing code. Its drag-and-drop interface, role-based access controls, and Open API enable teams to create data-driven portals, automate workflows, and integrate with third-party services.

**Website:** [https://stacker.ai/](https://stacker.ai/)
**Documentation:** [https://docs.stackerhq.com/](https://docs.stackerhq.com/)

## Tags

- No-Code, Low-Code, Application Development, Portals, Workflow Automation

## APIs

### Stacker API
Programmatic access to objects, records, accounts, and stacks within the Stacker platform. Supports full record lifecycle operations (create, read, search, update, delete, bulk upsert) and account/object discovery.

- **Base URL:** `https://api.go.stackerhq.com`
- **Authentication:** API Key via `X-Integration-Key` header
- **Docs:** [Open API Overview](https://docs.stackerhq.com/stacker/ai-and-automations/open-api-overview)

## OpenAPI Specifications

| Spec | Path |
|---|---|
| Stacker API | [openapi/stacker-openapi.yml](openapi/stacker-openapi.yml) |

## Spectral Rules

| Ruleset | Path |
|---|---|
| Stacker API Rules | [rules/stacker-rules.yml](rules/stacker-rules.yml) |

## Naftiko Capabilities

### Shared Definitions

| API | Path |
|---|---|
| Stacker API | [capabilities/shared/stacker-api.yaml](capabilities/shared/stacker-api.yaml) |

### Workflow Capabilities

| Workflow | Description | Path |
|---|---|---|
| Data Management | Full record lifecycle management for Stacker applications | [capabilities/data-management.yaml](capabilities/data-management.yaml) |

## JSON Schema

| Schema | Path |
|---|---|
| Stacker Record | [json-schema/stacker-record-schema.json](json-schema/stacker-record-schema.json) |
| Search Request | [json-schema/stacker-search-request-schema.json](json-schema/stacker-search-request-schema.json) |

## JSON Structure

| Structure | Path |
|---|---|
| Stacker Record | [json-structure/stacker-record-structure.json](json-structure/stacker-record-structure.json) |

## JSON-LD

| Context | Path |
|---|---|
| Stacker Context | [json-ld/stacker-context.jsonld](json-ld/stacker-context.jsonld) |

## Examples

| Example | Path |
|---|---|
| Search Records | [examples/stacker-search-records-example.json](examples/stacker-search-records-example.json) |
| Create Record | [examples/stacker-create-record-example.json](examples/stacker-create-record-example.json) |

## Vocabulary

| Vocabulary | Path |
|---|---|
| Stacker Vocabulary | [vocabulary/stacker-vocabulary.yml](vocabulary/stacker-vocabulary.yml) |

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02
