# Neon (neon)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Neon is a serverless Postgres platform that provides fully managed, scalable PostgreSQL databases optimized for modern cloud and edge application development. Their developer platform offers management APIs, data APIs, authentication services, and serverless drivers for building and automating database-driven workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml)

## Tags

- Databases
- Serverless
- Postgres
- Infrastructure
- Authentication
- Edge

## Timestamps

- **Created:** 2025-03-07
- **Modified:** 2026-05-19

## APIs

### Neon Management API

The Neon Management API is a RESTful interface for programmatically managing Neon serverless Postgres resources. It allows developers to create and manage projects, branches, databases, roles, compute endpoints, and operations. The API uses bearer token authentication and supports everything available through the Neon Console, enabling automation of database infrastructure workflows. An OpenAPI 3.0 specification is available along with TypeScript, Python, and Go SDKs.

- **Human URL:** [https://neon.com/docs/reference/api-reference](https://neon.com/docs/reference/api-reference)
- **Base URL:** `https://console.neon.tech/api/v2`

#### Tags

- Databases
- Serverless
- Postgres
- Projects
- Branches
- Compute
- Infrastructure

#### Properties

- [Documentation](https://neon.com/docs/reference/api-reference)
- [Documentation](https://api-docs.neon.tech/reference/getting-started-with-neon-api)
- [OpenAPI](openapi/neon-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/neon-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neon-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon Data API

The Neon Data API provides a secure, stateless HTTP interface to Neon Postgres databases, allowing developers to access and manage data directly from web browsers, serverless functions, and edge runtimes using standard HTTP methods. It is fully compatible with PostgREST, enabling querying via standard HTTP clients like Postman or cURL. The Data API supports JWT-based authentication and integrates with Row-Level Security policies, making it suitable for building secure client-facing applications without a traditional backend.

- **Human URL:** [https://neon.com/docs/data-api/overview](https://neon.com/docs/data-api/overview)

#### Tags

- Databases
- Serverless
- Postgres
- REST
- Data
- PostgREST
- HTTP

#### Properties

- [Documentation](https://neon.com/docs/data-api/overview)
- [Documentation](https://neon.com/docs/data-api/get-started)
- [Postman Collection](collections/neon-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neon-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon Serverless Driver

The Neon Serverless Driver is a low-latency JavaScript and TypeScript driver that enables querying Neon Postgres databases from serverless and edge environments over HTTP or WebSockets in place of TCP. It supports two query modes: HTTP mode using the neon function for fast single non-interactive transactions, and WebSocket mode using Pool and Client constructors for session and transaction support with node-postgres compatibility. The driver is available as @neondatabase/serverless on npm and is optimized for deployment on platforms like Cloudflare Workers, Vercel Edge Functions, and AWS Lambda.

- **Human URL:** [https://neon.com/docs/serverless/serverless-driver](https://neon.com/docs/serverless/serverless-driver)

#### Tags

- Databases
- Serverless
- Postgres
- JavaScript
- TypeScript
- WebSocket
- Edge
- Driver

#### Properties

- [Documentation](https://neon.com/docs/serverless/serverless-driver)
- [Postman Collection](collections/neon-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neon-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Neon Auth

Neon Auth is a managed authentication service built on Better Auth that connects directly to a Neon Postgres database. It stores authentication data including users, sessions, and OAuth configurations in the database's neon_auth schema. Neon Auth provides client and server SDKs, supports multiple OAuth providers, and integrates with the Neon Data API for automatic JWT validation. It enables Row-Level Security policies through the auth.uid() function, allowing developers to implement fine-grained data access control based on authenticated users.

- **Human URL:** [https://neon.com/docs/auth/overview](https://neon.com/docs/auth/overview)

#### Tags

- Authentication
- Authorization
- OAuth
- JWT
- Security
- Identity

#### Properties

- [Documentation](https://neon.com/docs/auth/overview)
- [Documentation](https://neon.com/docs/neon-auth/api)
- [AsyncAPI](asyncapi/neon-auth-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/neon-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/neon-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/neondatabase)
- [LinkedIn](https://www.linkedin.com/company/neondatabase)
- [Portal](https://neon.com/docs)
- [Blog](https://neon.com/blog)
- [Pricing](https://neon.com/pricing)
- [Login](https://console.neon.tech)
- [Sign Up](https://console.neon.tech/signup)
- [Support](https://neon.com/docs/introduction/support)
- [Status Page](https://neonstatus.com)
- [Terms of Service](https://neon.com/terms-of-service)
- [Privacy Policy](https://neon.com/privacy-policy)
- [Website](https://neon.com)
- [Features](undefined)
- [L L Ms Txt](https://api-docs.neon.tech/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
