# Managed image releases

## Managed 1.5.5 (0.70.5)

## Managed Nango 1.5.5 (application 0.70.5)

- **Released:** 2026-05-28
- **Docker image:** `nangohq/nango:managed-1.5.5-0.70.5-a447dd8c75b2412d88862ceb02c298c3228b635b`
- **Pin CLI to:** `0.70.5`
- **Compare:** https://github.com/NangoHQ/nango/compare/0fe07a6d83aea0becc4cea382c5cead2f555718d...a447dd8c75b2412d88862ceb02c298c3228b635b
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(design-system)* Extend token pipeline with @theme utilities (#6258)
- *(metering)* Emit per-run S3 export metric for monitoring (#6272)
- *(functions)* Production versions of JIT function endpoints (#6214)
- *(records)* Add RecordsStore interface (#6263)
- *(orchestrator)* NAN-5727 add batched immediate route (#6249)
- *(server)* Meter bytes transferred on forward deliveries (#6240)

### Fixed

- *(shared)* Honor NANGO_SECRET_KEY_<ENV> for default API secret on self-hosted (#5979)
- *(docker)* Deduplicate dd-trace in package-lock.json (#6273)
- *(records)* Stop re-exporting test helper from package barrel

## [v0.70.5] - 2026-05-27

### Added

- *(metering)* Observability + 60s CH timeout for S3 export cron (#6217)
- *(webhooks)* Add support for folk webhook (#6218)
- *(integrations)* Add support for superhuman-mcp (#6219)
- *(integrations)* Add support for nexthink (#6203)
- *(integrations)* Add support for dynatrace (#6205)
- *(integrations)* Add support for tanium (#6202)
- *(integrations)* Add support for microsoft-intune (#6206)
- *(integrations)* Add support for Pushpay ChMS V1 (#6128)
- *(integrations)* Add support for ImmyBot (#6127)
- *(providers)* Add NinjaOne SaaS Backup integration (#6113)
- *(ci)* Add webapp PR preview deploy workflow (#6191)
- *(design-system)* Add basic Storybook setup with a11y and MCP addons (#6204)
- Add repo agent guidance and skills (#6235)
- *(integrations)* Add support for sage-200 (#6233)
- *(integrations)* Add BigChange OAuth2 Client Credentials provider (#6224)
- *(server)* Endpoint to list templates from and integration with deployed metadata (#6199)
- *(security)* Add SECURITY.md (#6255)
- *(webapp)* Lightweight feature flag system with dark/light mode toggle (#6223)
- *(metering)* Deterministic S3 keys + skip-if-exists for billing export (#6242)
- *(integrations)* Add support for lightfield (#5994)

### Changed

- Update version in manifest
- Extract Function abstraction and split domain/api types (#6196)
- Update Google OAuth review guide with YC office hour insights (#6165)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3de84647fe31300d903cb6ecc328fa0bce442fc9 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/83d64bfe895863c533c12abae2c1beab3ad6183d by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/d5fb95721f508685b134e70b13186ad74f6153be by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b77b57484633dce7e3cf70eadb833a1a8744421d by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/788a7d15ac8359781b47e054e859a30746b19abd by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/dc40b608db61117d110ee10c6aa7fcc3c55a861f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/768dbf01e0046d8aa7e09569f325d19d8ae2af2c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e1a4bda58d2ab641e4421d62de08f11f6571d0c6 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7c50289d4162a2df1b06ac88a062f4e46845632c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3fe9b9cddea46f112844b302671e4a6379810096 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/668d3caa5527efe932dd75382da433821750bd3d by Victor Lang'at
- Harden npm installs (#6226)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7d6c3e2e93ac5ebc3a9330bb914f4969e7737f1e by Marcin Dobrowolski
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a1edcd554837e5d7b241eef6f3e4be9db1abf659 by Victor Lang'at
- *(webapp)* Extract app bootstrap into src/app/, clean up src root (#6247)
- *(cli)* Bump node version (#6253)

### Fixed

- *(server)* Return credentials for get integration for gh oauth app (#6221)
- *(integration)* Fix prospeo api key regex pattern (#6222)
- Fix mcp provider docs (#6230)
- *(ci)* Shorten preview deploy comment URL and timestamp (#6236)
- *(eslint)* Eliminate IDE false positives in browser packages (#6251)
- *(security)* Vulns and new pattern (#6254)
- *(webapp)* Fix KeyValueInput inconsistent empty row and rename tabs (#6241)
- *(managed-release)* Publish release to new repo (#6227)

