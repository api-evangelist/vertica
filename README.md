# Vertica (vertica)

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

Vertica (now branded OpenText Analytics Database) is a high-performance, columnar, MPP analytics database designed for petabyte-scale data warehousing, data lakehouse, and advanced analytics workloads across on-premises, cloud, and Kubernetes deployments. The platform delivers in-database machine learning, geospatial and time-series analytics, separation of storage and compute, and broad SQL compatibility. Vertica exposes a REST API via the Node Management Agent (NMA) for programmatic cluster and database operations authenticated with mutual TLS.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vertica/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vertica/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Database
- Analytics Database
- Data Warehouse
- Data Lakehouse
- Columnar Database
- MPP
- In-Database Machine Learning
- SQL

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Vertica Node Management Agent API

REST API exposed by the Vertica Node Management Agent (NMA) on every database node for administering clusters, databases, and nodes. The NMA listens on port 5554, authenticates clients via mutual TLS, and publishes its own Swagger documentation at the /api-docs/ endpoint.

- **Human URL:** [https://docs.vertica.com/latest/en/admin/managing-db/node-management-agent/](https://docs.vertica.com/latest/en/admin/managing-db/node-management-agent/)
- **Base URL:** `https://<node-host>:5554`

#### Tags

- Node Management
- Cluster Administration
- REST
- mTLS

#### Properties

- [Documentation](https://docs.vertica.com/latest/en/admin/managing-db/node-management-agent/)
- [Endpoints  Reference](https://docs.vertica.com/latest/en/admin/managing-db/node-management-agent/nma-endpoints/)
- [OpenAPI](https://<node-host>:5554/api-docs/nma_swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.vertica.com/latest/en/admin/managing-db/node-management-agent/custom-certificates/)
- [Postman Collection](collections/vertica.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertica.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vertica Management Console REST API

Agent-backed REST API used by Vertica Management Console for monitoring, provisioning, and managing Vertica databases and clusters. Returns JSON responses for node, database, and cluster operations.

- **Human URL:** [https://docs.vertica.com/latest/en/connecting-to/management-api/rest-apis-agent/](https://docs.vertica.com/latest/en/connecting-to/management-api/rest-apis-agent/)
- **Base URL:** `https://<management-host>:5444`

#### Tags

- Management Console
- Monitoring
- Provisioning

#### Properties

- [Documentation](https://docs.vertica.com/latest/en/connecting-to/management-api/rest-apis-agent/)
- [Postman Collection](collections/vertica.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vertica.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/vertica-co)
- [Website](https://www.vertica.com)
- [Product  Page](https://www.opentext.com/products/analytics-database)
- [Documentation](https://docs.vertica.com/)
- [Community  Edition](https://docs.vertica.com/latest/en/getting-started/community-edition-ce/)
- [Community](https://community.opentext.com/data-analytics/analytics-db)
- [GitHub Organization](https://github.com/vertica)
- [Git Hub vcluster](https://github.com/vertica/vcluster)
- [Support](https://www.opentext.com/support)
- [Parent  Company](https://www.opentext.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
