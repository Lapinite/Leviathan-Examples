<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="Leviathan Examples">

<br>

<img src="https://img.shields.io/badge/type-public%20examples-06131d?style=flat-square" alt="Public examples">
<img src="https://img.shields.io/badge/security-placeholder%20data%20only-06131d?style=flat-square" alt="Placeholder data only">
<img src="https://img.shields.io/badge/license-Apache--2.0-06131d?style=flat-square" alt="Apache 2.0">

**Small, understandable implementation patterns for public Leviathan APIs, SDKs, webhooks and integrations.**

[Guide](GUIDE.md) · [API Docs](https://github.com/Lapinite/Leviathan-API-Docs) · [SDK](https://github.com/Lapinite/Leviathan-SDK) · [Integrations](https://github.com/Lapinite/Leviathan-Integrations) · [Security](SECURITY.md)

</div>

## Example categories

<table width="100%">
<tr>
<td width="33%" valign="top"><strong>API Basics</strong><br><sub>SDK initialization · requests · pagination · error handling</sub></td>
<td width="33%" valign="top"><strong>Events & Integrations</strong><br><sub>Webhooks · verification · Minecraft patterns · Discord patterns</sub></td>
<td width="33%" valign="top"><strong>Operational Safety</strong><br><sub>Configuration · logging · validation · production-readiness notes</sub></td>
</tr>
</table>

## Purpose

Examples in this repository should demonstrate one concept at a time without exposing production credentials or internal infrastructure. They are intended to be readable reference implementations rather than complete production applications.

Examples may cover:

- SDK initialization
- public API requests
- supported authentication-flow integration
- pagination and error handling
- webhook receipt and verification
- Minecraft server integration patterns
- Discord integration patterns
- safe configuration handling

## Example design rules

A useful Leviathan example should be:

1. **Small** enough to understand quickly.
2. **Explicit** about what public interface it demonstrates.
3. **Safe** by using placeholders instead of real credentials or identifiers.
4. **Defensive** about validation and error handling.
5. **Clear** about what additional work is required before production use.

## Safe example policy

Never commit real access tokens, refresh tokens, client secrets, private keys, bot tokens, webhook credentials, database credentials, account details, private endpoints, personal information, or internal-only service configuration.

Example logging must also avoid printing secrets.

## Production use

Examples are educational starting points. Before production use, developers should review security, validation, authentication, error handling, rate limits, storage, observability, deployment, compatibility, and platform-specific requirements.

## Planned example flow

```text
README / Guide
     ↓
Small runnable example
     ↓
Documented configuration
     ↓
Expected request / event
     ↓
Expected output / error handling
     ↓
Production considerations
```

## Related repositories

| Repository | Role |
| --- | --- |
| [Leviathan API Docs](https://github.com/Lapinite/Leviathan-API-Docs) | Public API behavior |
| [Leviathan SDK](https://github.com/Lapinite/Leviathan-SDK) | SDK interfaces and helpers |
| [Leviathan Integrations](https://github.com/Lapinite/Leviathan-Integrations) | Integration patterns |
| [Leviathan Docs](https://github.com/Lapinite/Leviathan-Docs) | Ecosystem documentation |

## License

This repository uses the Apache License 2.0. See [LICENSE](LICENSE).
