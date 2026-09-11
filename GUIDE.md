# Example development guide

[Examples overview](README.md)

## Current contents

The [configuration example](examples/configuration/README.md) is a documentation-only structure using placeholders. It makes no requests, loads no credentials, and claims no working API, SDK, webhook, Minecraft, or Discord integration.

## Planned examples

| Area | Required before a runnable example |
| --- | --- |
| SDK initialization | Released package, language/runtime support, and version |
| API requests | Public endpoint and authentication contract |
| Pagination and errors | Documented response and retry behavior |
| Webhook receipt | Published signature, event, and delivery contract |
| Minecraft plugin | Tested server and game versions, permissions, and adapter |
| Discord integration | Released adapter and least-privilege setup instructions |

## Rules for runnable examples

Use only documented public interfaces. Explain dependencies, setup, execution, expected results, cleanup, compatibility, and limitations. Keep example operations small and reversible. Never imply that a sample is production-ready.

## Configuration and logging

Keep private configuration outside version control. An example file must contain obvious placeholders, never realistic tokens, IDs, webhook URLs, or personal information. Redact logs before sharing and avoid printing configuration values at startup.

## Webhook and error handling

Do not simulate security by accepting every event or inventing a verification scheme. A future webhook example must follow its real contract and reject invalid events. Retry behavior must account for side effects and the documented service policy.

## Licensing

Retain the [Apache License 2.0](LICENSE). Include third-party notices where needed. Follow [SECURITY.md](SECURITY.md) for reporting.
