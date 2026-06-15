# Vertica (vertica)

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
