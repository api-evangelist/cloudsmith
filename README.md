# Cloudsmith (cloudsmith)

Cloudsmith is a cloud-native, universal package management platform providing fully managed, geo-replicated artifact repositories for over 30 package formats (Docker, npm, Maven, NuGet, PyPI, RubyGems, RPM, Deb, Helm, Cargo, Go, Composer, Conan, Conda, Vagrant, Raw, and more). The Cloudsmith REST API (v1) at `api.cloudsmith.io` exposes operations for organizations, repositories, packages, files, entitlements, vulnerabilities, webhooks, audit logs, metrics, quotas, deny policies, namespaces, distros, formats, recycle bin, storage regions, and broadcasts.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company

## Tags

Artifact Management, DevOps, DevSecOps, Distribution, Package Management, Registry, Repository, Software Supply Chain, Universal, Vulnerability Scanning

## APIs

### Cloudsmith API (v1)

- Base URL: `https://api.cloudsmith.io`
- 217+ endpoints across 22 tag groups
- Top tag groups by operation count: `repos` (150), `orgs` (73), `packages` (71), `entitlements` (11), `webhooks` (5), `files` (5), `user` (5), `quota` (4), `vulnerabilities` (4), `metrics` (3), `audit-log` (2), `distros` (2), `formats` (2), `namespaces` (2), `recycle-bin` (2), `storage-regions` (2), `badges`, `broadcasts`, `bulk-action`, `rates`, `status`, `users`
- Authentication: API key in `Authorization: token YOUR_API_KEY`
- Pagination: `page` and `page_size` query params; default 30, max 500

Resources:
- [Documentation](https://docs.cloudsmith.com/api)
- [Getting Started](https://help.cloudsmith.io/reference/getting-started-with-the-api)
- [Live OpenAPI (Swagger 2.0)](https://api.cloudsmith.io/?format=openapi)
- [Local OpenAPI](openapi/cloudsmith-openapi.json)

## Common Properties

- [Website](https://cloudsmith.com/)
- [Documentation](https://docs.cloudsmith.com/)
- [Status](https://status.cloudsmith.io/)
- [GitHub](https://github.com/cloudsmith-io)
- [OpenAPI](openapi/cloudsmith-openapi.json)
- [JSON-LD](json-ld/cloudsmith-context.jsonld)
- [Spectral](rules/cloudsmith-rules.yml)
- [Naftiko Capabilities](capabilities/package-management.yaml)

## Maintainers

- **FN:** Kin Lane
- **Email:** kinlane@gmail.com
