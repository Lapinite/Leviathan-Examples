<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="Leviathan Examples">

<br>

<img src="https://img.shields.io/badge/type-public%20examples-06131d?style=flat-square" alt="Public examples">
<img src="https://img.shields.io/badge/security-placeholder%20data%20only-06131d?style=flat-square" alt="Placeholder data only">
<img src="https://img.shields.io/badge/license-Apache--2.0-06131d?style=flat-square" alt="Apache 2.0">

**Small, understandable implementation patterns for public Leviathan APIs, SDKs, webhooks and integrations.**

[Guide](GUIDE.md) · [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) · [SDK](https://github.com/Lapinite/Leviathan-SDK) · [Integrations](https://github.com/Lapinite/Leviathan-Integrations) · [Security](SECURITY.md)

</div>

## Example lifecycle

<p align="center"><img width="100%" src="assets/example-flow.svg" alt="Animated Leviathan public example lifecycle"></p>

<p align="center"><sub>Each example moves from one public concept to a small runnable pattern, placeholder configuration, expected behavior and a production-readiness checklist.</sub></p>

## Pattern library

<p align="center"><img width="100%" src="assets/categories-map.svg" alt="Animated Leviathan example category map"></p>

<p align="center"><sub>API basics, integration events and operational safety are kept separate so every example stays small and understandable.</sub></p>

## Third-party boundaries

Where an example references Microsoft authentication, Xbox Live, XSTS, Minecraft Services, Mojang/Minecraft, Discord or another third-party system, it clearly identifies that platform as an external dependency and uses placeholders for identifiers or credentials that are not intended to be public.

Examples never imply that Leviathan owns or can bypass third-party authentication, entitlement, permission or security controls.

## Example design rules

1. **Small:** demonstrate one concept at a time.
2. **Explicit:** name the public contract being demonstrated.
3. **Safe:** use placeholders instead of real credentials or identifiers.
4. **Defensive:** show validation and error handling.
5. **Practical:** state what additional work is required before production use.

## Safe example policy

Never commit real access tokens, refresh tokens, client secrets, private keys, bot tokens, webhook credentials, database credentials, account details, private endpoints, personal information or internal-only service configuration.

Example logging must also avoid printing secrets.

## Production use

Before production use, developers should review security, validation, authentication, error handling, rate limits, storage, observability, deployment, compatibility and platform-specific requirements.

## Related repositories

<p align="center">
<a href="https://github.com/Lapinite/Leviathan-API-Docs"><strong>API Docs</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-SDK"><strong>SDK</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Integrations"><strong>Integrations</strong></a> ·
<a href="https://github.com/Lapinite/Leviathan-Docs"><strong>Docs</strong></a>
</p>

## License

This repository uses the Apache License 2.0. See [LICENSE](LICENSE).
