# Neon (neon)
Neon is a serverless Postgres platform that provides fully managed, scalable PostgreSQL databases optimized for modern cloud and edge application development. Their developer platform offers management APIs, data APIs, authentication services, and serverless drivers for building and automating database-driven workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/neon/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Databases, Serverless, Postgres, Infrastructure, Authentication, Edge

## Timestamps

- **Created:** 2025-03-07
- **Modified:** 2026-03-20

## APIs

### Neon Management API
The Neon Management API is a RESTful interface for programmatically managing Neon serverless Postgres resources. It allows developers to create and manage projects, branches, databases, roles, compute endpoints, and operations. The API uses bearer token authentication and supports everything available through the Neon Console, enabling automation of database infrastructure workflows. An OpenAPI 3.0 specification is available along with TypeScript, Python, and Go SDKs.

**Human URL:** [https://neon.com/docs/reference/api-reference](https://neon.com/docs/reference/api-reference)


#### Tags:

 - Databases, Serverless, Postgres, Projects, Branches, Compute, Infrastructure

#### Properties

- [Documentation](https://neon.com/docs/reference/api-reference)
- [Documentation](https://api-docs.neon.tech/reference/getting-started-with-neon-api)
- [OpenAPI](openapi/neon-management-api-openapi.yml)

### Neon Data API
The Neon Data API provides a secure, stateless HTTP interface to Neon Postgres databases, allowing developers to access and manage data directly from web browsers, serverless functions, and edge runtimes using standard HTTP methods. It is fully compatible with PostgREST, enabling querying via standard HTTP clients like Postman or cURL. The Data API supports JWT-based authentication and integrates with Row-Level Security policies, making it suitable for building secure client-facing applications without a traditional backend.

**Human URL:** [https://neon.com/docs/data-api/overview](https://neon.com/docs/data-api/overview)


#### Tags:

 - Databases, Serverless, Postgres, REST, Data, PostgREST, HTTP

#### Properties

- [Documentation](https://neon.com/docs/data-api/overview)
- [Documentation](https://neon.com/docs/data-api/get-started)

### Neon Serverless Driver
The Neon Serverless Driver is a low-latency JavaScript and TypeScript driver that enables querying Neon Postgres databases from serverless and edge environments over HTTP or WebSockets in place of TCP. It supports two query modes: HTTP mode using the neon function for fast single non-interactive transactions, and WebSocket mode using Pool and Client constructors for session and transaction support with node-postgres compatibility. The driver is available as @neondatabase/serverless on npm and is optimized for deployment on platforms like Cloudflare Workers, Vercel Edge Functions, and AWS Lambda.

**Human URL:** [https://neon.com/docs/serverless/serverless-driver](https://neon.com/docs/serverless/serverless-driver)


#### Tags:

 - Databases, Serverless, Postgres, JavaScript, TypeScript, WebSocket, Edge, Driver

#### Properties

- [Documentation](https://neon.com/docs/serverless/serverless-driver)

### Neon Auth
Neon Auth is a managed authentication service built on Better Auth that connects directly to a Neon Postgres database. It stores authentication data including users, sessions, and OAuth configurations in the database's neon_auth schema. Neon Auth provides client and server SDKs, supports multiple OAuth providers, and integrates with the Neon Data API for automatic JWT validation. It enables Row-Level Security policies through the auth.uid() function, allowing developers to implement fine-grained data access control based on authenticated users.

**Human URL:** [https://neon.com/docs/auth/overview](https://neon.com/docs/auth/overview)


#### Tags:

 - Authentication, Authorization, OAuth, JWT, Security, Identity

#### Properties

- [Documentation](https://neon.com/docs/auth/overview)
- [Documentation](https://neon.com/docs/neon-auth/api)
- [AsyncAPI](asyncapi/neon-auth-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://neon.com/docs)
- [Blog](https://neon.com/blog)
- [Pricing](https://neon.com/pricing)
- [Login](https://console.neon.tech)
- [Sign Up](https://console.neon.tech/signup)
- [Support](https://neon.com/docs/introduction/support)
- [Status](https://neonstatus.com)
- [TermsOfService](https://neon.com/terms-of-service)
- [PrivacyPolicy](https://neon.com/privacy-policy)
- [Website](https://neon.com)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
