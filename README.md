# SSO

Single Sign-On (SSO) is an authentication technology that allows users to log in once and gain access to multiple related applications and services without re-authenticating. SSO implementations rely on protocols such as SAML 2.0, OpenID Connect (OIDC), and OAuth 2.0. Major identity providers including Okta, Microsoft Entra ID, Google, Ping Identity, Auth0, and Keycloak expose SSO APIs that allow applications to integrate federated authentication, token exchange, assertion validation, and session management.

## Tags

Authentication, Authorization, Identity, OAuth, OIDC, SAML, Security, Single Sign-On, SSO

## APIs

### SAML SSO Authentication API

The SAML 2.0 Single Sign-On API enables service providers and identity providers to exchange authentication assertions via XML-signed messages. It supports HTTP Redirect Binding and HTTP POST Binding for AuthnRequest and Response flows, Assertion Consumer Service (ACS) endpoints, Single Logout (SLO), and IdP metadata retrieval as defined by OASIS SAML 2.0.

**Documentation:** [https://www.oasis-open.org/standards#samlv2.0](https://www.oasis-open.org/standards#samlv2.0)

#### Properties

- [OpenAPI](openapi/sso-saml-openapi.yml)

### OpenID Connect (OIDC) Authentication API

The OpenID Connect (OIDC) API is a lightweight identity layer built on top of OAuth 2.0. It enables applications to verify user identity through Authorization Code Flow, Implicit Flow, and Hybrid Flow. Key endpoints include Authorization, Token, UserInfo, JWKS, and Discovery.

**Documentation:** [https://openid.net/connect/](https://openid.net/connect/)

#### Properties

- [OpenAPI](openapi/sso-oidc-openapi.yml)

## Common Properties

- [SAML 2.0 Specification](https://www.oasis-open.org/standards#samlv2.0)
- [OpenID Connect](https://openid.net/connect/)
- [OAuth 2.0](https://oauth.net/2/)
- [JSON-LD](json-ld/sso-context.jsonld)
- [JSON Schema - SAML Assertion](json-schema/sso-saml-assertion-schema.json)
- [JSON Schema - OIDC Token](json-schema/sso-oidc-token-schema.json)
- [Vocabulary](vocabulary/sso-vocabulary.yml)
- [Spectral Rules](rules/sso-rules.yml)

## Capabilities

### Shared Definitions (`capabilities/shared/`)

| File | Description |
|------|-------------|
| [oidc-authentication.yaml](capabilities/shared/oidc-authentication.yaml) | OpenID Connect authentication — token exchange, user info, JWKS, provider discovery |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [identity-federation.yaml](capabilities/identity-federation.yaml) | Unified SSO identity federation workflow combining OIDC authentication, user profile retrieval, key management, and provider discovery (4 REST paths, 4 MCP tools) |
