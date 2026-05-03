# Under Armour

Under Armour is an American company that manufactures footwear, sports, and casual apparel known for its performance products designed for athletes. Under Armour operates a Connected Fitness platform — powered by MapMyFitness — that provides developer APIs for integrating workout tracking, route data, user profiles, heart rate zones, and fitness devices into third-party applications.

## APIs

### MapMyFitness API (Under Armour Connected Fitness)

The MapMyFitness API provides RESTful access to fitness data including workouts, routes, user profiles, heart rate zones, fitness devices, and webhooks. The platform powers MapMyFitness, MapMyRun, MapMyRide, and MapMyWalk and supports over 400 partner apps and devices.

- **Base URL:** https://api.ua.com
- **Developer Portal:** https://developer.mapmyfitness.com/
- **Authentication:** OAuth 2.0
- **OpenAPI:** [openapi/mapmyfitness-openapi.yml](openapi/mapmyfitness-openapi.yml)

## Artifacts

### OpenAPI Specs

| File | Description |
|------|-------------|
| [openapi/mapmyfitness-openapi.yml](openapi/mapmyfitness-openapi.yml) | MapMyFitness API v7.1 — workouts, routes, users, heart rate zones, devices, webhooks |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/connected-fitness.yaml](capabilities/connected-fitness.yaml) | Workflow capability for Under Armour Connected Fitness (REST + MCP) |
| [capabilities/shared/mapmyfitness.yaml](capabilities/shared/mapmyfitness.yaml) | Shared per-API definition for MapMyFitness API |

### JSON Schema

| File | Description |
|------|-------------|
| [json-schema/under-armour-workout-schema.json](json-schema/under-armour-workout-schema.json) | Schema for a MapMyFitness workout record with aggregates and time series |

### JSON Structure

| File | Description |
|------|-------------|
| [json-structure/under-armour-workout-structure.json](json-structure/under-armour-workout-structure.json) | Field-level documentation for the Workout entity |

### JSON-LD

| File | Description |
|------|-------------|
| [json-ld/under-armour-context.jsonld](json-ld/under-armour-context.jsonld) | JSON-LD context mapping fitness data to schema.org vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/mapmyfitness-list-workouts-example.json](examples/mapmyfitness-list-workouts-example.json) | Example request/response for listing user workouts |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/under-armour-rules.yml](rules/under-armour-rules.yml) | Spectral ruleset enforcing Under Armour API conventions |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/under-armour-vocabulary.yml](vocabulary/under-armour-vocabulary.yml) | Domain vocabulary for Connected Fitness — workouts, routes, heart rate zones, devices |

## Properties

- [Website](https://www.under-armour.com)
- [Developer Portal](https://developer.mapmyfitness.com/)
- [Documentation](https://developer.mapmyfitness.com/docs/)
- [Authentication](https://developer.mapmyfitness.com/docs/v71_OAuth_2_Intro/)
