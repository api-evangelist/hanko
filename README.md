# Hanko (hanko)

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

Hanko is a passkey-first, open-source authentication platform and cloud service that provides REST APIs for passkeys (WebAuthn/FIDO2), passwords, OAuth social login, SAML SSO, multi-factor authentication, session management, and user management. It is available as a managed cloud service and as a self-hosted open-source deployment, and is positioned as a modern alternative to Auth0, Clerk, and WorkOS. Hanko is headquartered in Germany and emphasizes privacy-first, European-hosted infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hanko/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hanko/refs/heads/main/apis.yml)

**Naftiko:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hanko-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hanko-api-evangelist&utm_content=repo)

## Tags

- Authentication
- Passkeys
- WebAuthn
- FIDO2
- Identity
- OAuth
- SAML
- Passwordless
- Open Source

## APIs

| API | Description | Docs | OpenAPI |
|-----|-------------|------|---------|
| Hanko Public API | Frontend-facing authentication endpoints: WebAuthn, OAuth, SAML, sessions, user management | [Docs](https://docs.hanko.io) | [OpenAPI](https://docs.hanko.io/openapi-public.yaml) |
| Hanko Admin API | Backend management: users, sessions, emails, webhooks, audit logs, credentials | [Docs](https://docs.hanko.io) | [OpenAPI](https://docs.hanko.io/openapi-admin.yaml) |
| Hanko Passkey API | Standalone FIDO2 passkey server for adding passkeys to any existing auth system | [Docs](https://docs.hanko.io/passkey-api/introduction) | [OpenAPI](https://docs.hanko.io/openapi-passkeys.yaml) |
| Hanko Flow API | Structured multi-step authentication flows powering Hanko Elements UI | [Docs](https://docs.hanko.io) | [OpenAPI](https://docs.hanko.io/openapi-flow.yaml) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/hanko-plans-pricing.yml](plans/hanko-plans-pricing.yml) |
| Rate Limits | [rate-limits/hanko-rate-limits.yml](rate-limits/hanko-rate-limits.yml) |
| FinOps | [finops/hanko-finops.yml](finops/hanko-finops.yml) |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.hanko.io](https://www.hanko.io) |
| Documentation | [https://docs.hanko.io](https://docs.hanko.io) |
| GitHub Organization | [https://github.com/teamhanko](https://github.com/teamhanko) |
| LinkedIn | [https://www.linkedin.com/company/teamhanko](https://www.linkedin.com/company/teamhanko) |
| Blog | [https://www.hanko.io/blog](https://www.hanko.io/blog) |
| Pricing | [https://www.hanko.io/pricing](https://www.hanko.io/pricing) |
| Status Page | [https://status.hanko.io](https://status.hanko.io) |
| X (Twitter) | [https://twitter.com/hanko](https://twitter.com/hanko) |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
