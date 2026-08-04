# SSO (sso)

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

Single Sign-On (SSO) is an authentication technology that allows users to log in once and gain access to multiple related applications and services without re-authenticating. SSO implementations rely on protocols such as SAML 2.0, OpenID Connect (OIDC), and OAuth 2.0. Major identity providers including Okta, Microsoft Entra ID, Google, Ping Identity, Auth0, and Keycloak expose SSO APIs that allow applications to integrate federated authentication, token exchange, assertion validation, and session management.

**APIs.json:** [https://github.com/api-evangelist/sso](https://github.com/api-evangelist/sso)

## Tags

- Authentication
- Authorization
- Identity
- OAuth
- OIDC
- SAML
- Security
- Single Sign-On
- SSO

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### SAML SSO Authentication API

The SAML 2.0 Single Sign-On API enables service providers and identity providers to exchange authentication assertions via XML-signed messages. It supports HTTP Redirect Binding and HTTP POST Binding for AuthnRequest and Response flows, Assertion Consumer Service (ACS) endpoints, Single Logout (SLO), and IdP metadata retrieval as defined by the OASIS SAML 2.0 specification.

- **Human URL:** [https://www.oasis-open.org/standards#samlv2.0](https://www.oasis-open.org/standards#samlv2.0)
- **Base URL:** `https://your-idp.example.com`

#### Tags

- Authentication
- Federation
- Identity
- SAML
- Single Sign-On
- SSO

#### Properties

- [Documentation](https://www.oasis-open.org/standards#samlv2.0)
- [Documentation](https://wiki.oasis-open.org/security/FrontPage)
- [OpenAPI](openapi/sso-saml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sso-saml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sso-saml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenID Connect (OIDC) Authentication API

The OpenID Connect (OIDC) API is a lightweight identity layer built on top of OAuth 2.0. It enables applications to verify user identity through the Authorization Code Flow, Implicit Flow, and Hybrid Flow. Key endpoints include the Authorization Endpoint, Token Endpoint, UserInfo Endpoint, and JWKS URI for token signature verification. OIDC is supported by all major identity providers.

- **Human URL:** [https://openid.net/connect/](https://openid.net/connect/)
- **Base URL:** `https://your-idp.example.com`

#### Tags

- Authentication
- Identity
- JWT
- OAuth
- OIDC
- Single Sign-On
- SSO

#### Properties

- [Documentation](https://openid.net/connect/)
- [Specification](https://openid.net/developers/specs/)
- [OpenAPI](openapi/sso-oidc-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sso-oidc.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sso-oidc.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Specification](https://www.oasis-open.org/standards#samlv2.0)
- [Specification](https://openid.net/connect/)
- [Specification](https://oauth.net/2/)
- [Git Hub Org](https://github.com/api-evangelist/sso)
- [JSON-LD](json-ld/sso-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/sso-saml-assertion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sso-oidc-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/sso-vocabulary.yml)
- [Spectral Rules](rules/sso-rules.yml)
