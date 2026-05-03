# Smartproxy

Smartproxy (now also known as Decodo) is a proxy network and web scraping infrastructure platform providing residential, datacenter, mobile, and ISP proxies for web data collection at scale.

## Overview

The Smartproxy API enables programmatic management of:

- Proxy sub-user accounts with individual traffic limits and credentials
- Traffic usage monitoring and reporting per sub-user
- IP whitelist management for credential-free proxy authentication
- Active subscription plan details and limits
- Available proxy endpoint discovery by type and location

## APIs

| API | Description |
|-----|-------------|
| [Smartproxy Account Management API](https://help.smartproxy.com/reference/introduction-1) | Programmatic proxy account, sub-user, and traffic management |

## Developer Resources

- **Documentation**: [help.smartproxy.com](https://help.smartproxy.com/reference/introduction-1)
- **Getting Started**: [Quick Start Guide](https://help.smartproxy.com/docs/quick-start-1)
- **GitHub**: [github.com/Smartproxy](https://github.com/Smartproxy)
- **Code Examples**: [Smartproxy-API on GitHub](https://github.com/Smartproxy/Smartproxy-API)

## Artifacts

### OpenAPI Specifications
- [Smartproxy API](openapi/smartproxy-openapi.yml) — Full OpenAPI spec for proxy account management

### Spectral Rules
- [Smartproxy Rules](rules/smartproxy-rules.yml) — Spectral ruleset enforcing Smartproxy API conventions

### Capabilities
- [Proxy Account Management](capabilities/proxy-account-management.yaml) — Unified workflow for proxy sub-user, traffic, and endpoint management

### JSON Schema
- [Sub-User Schema](json-schema/smartproxy-sub-user-schema.json) — Schema for proxy sub-user accounts
- [Endpoint Schema](json-schema/smartproxy-endpoint-schema.json) — Schema for proxy server endpoints

### JSON Structure
- [Smartproxy Structure](json-structure/smartproxy-structure.json) — Hierarchical resource structure documentation

### JSON-LD
- [Smartproxy Context](json-ld/smartproxy-context.jsonld) — Linked data context for proxy service concepts

### Examples
- [Get Sub-Users](examples/smartproxy-get-sub-users-example.json) — Example request/response for listing sub-users
- [Create Sub-User](examples/smartproxy-create-sub-user-example.json) — Example request/response for creating a sub-user

### Vocabulary
- [Smartproxy Vocabulary](vocabulary/smartproxy-vocabulary.yml) — Proxy network domain terminology

## Tags

Proxies, Web Scraping, Data Collection, Residential Proxies, Datacenter Proxies, Mobile Proxies, Network Infrastructure
