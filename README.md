# SSO (sso)

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
