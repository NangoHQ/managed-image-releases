# Managed image releases

## Managed 1.6.20 (0.71.12)

## Managed Nango 1.6.20 (application 0.71.12)

- **Released:** 2026-10-05
- **Docker image:** `nangohq/nango:managed-1.6.20-0.71.12-d316fc8b070a0684f20bad00200b54ea3a62da19`
- **Pin CLI to:** `0.71.12`
- **Compare:** https://github.com/NangoHQ/nango/compare/153f8c5450e7dd7049504df4a323e25499369002...d316fc8b070a0684f20bad00200b54ea3a62da19
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Changed

- Update version in manifest

### Fixed

- *(release)* Fix managed manifest app version for 1.6.19 (#7775)
- *(actions)* Opt out of logging action input (#7770)

## Managed 1.6.19 (0.71.12)

## Managed Nango 1.6.19 (application 0.71.12)

- **Released:** 2026-10-02
- **Docker image:** `nangohq/nango:managed-1.6.19-0.71.12-153f8c5450e7dd7049504df4a323e25499369002`
- **Pin CLI to:** `0.71.12`
- **Compare:** https://github.com/NangoHQ/nango/compare/fe85242b81ab9d3ac808a72ca7bdd2788c8e86fb...153f8c5450e7dd7049504df4a323e25499369002
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Fixed

- *(linear-mcp)* Omit empty client_secret from token/refresh requests (#7769)
- *(orchestrator)* Revert "fix: dequeue query tweaks (#7743)" (#7772)

## [v0.71.12] - 2026-10-02

### Added

- *(webhooks)* Add allow unverified webhooks integration option (NAN-7312) (#7726)
- *(integrations)* Add support for Discord Bot (#7678)
- *(integrations)* Add support for Slack app configuration tokens (#7669)
- *(server)* Add the Agent Playground chat API (#7697)
- *(integrations)* Add support for modmed-fhir (#7745)
- *(integrations)* Add Discogs OAuth1 and personal token providers (#7340)
- *(integrations)* Add support for Mailtrap (#7150)
- *(runner-sdk)* Support redirect error in nango.uncontrolledfetch (#7758)

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/73b6621f698206dbb7561601f031ab3af02c10e5 by Victor Lang'at
- Update version in manifest
- *(docs)* Free self-hosted should be single tenant (#7751)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/900eb400acae4023ff10903315905207bc3a5dc7 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fec2851c5d727f250db62f8b275603cd65c96996 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3fce1c855f03b768a4a256cb6bac745b8296c3b6 by Victor Lang'at
- Function invocation endpoint (#7724)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5e38e8f0dfa1ea031ee2230f8d8d3204514667d4 by Victor Lang'at
- Rename the server and CLI events to the taxonomy (#7753)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/23df553a789b6e30ba1640d4605cf5bfa7ca7cae by Victor Lang'at

### Fixed

- *(server)* Fix tool search reporting a just-connected app as not connected (#7748)
- *(proxy)* Time out stalled requests and abort them on cancel (#7709)
- Dequeue query tweaks (#7743)
- *(microsoft-admin)* Stop double-encoding the client_credentials scope (#7712)
- *(mcp)* Protect credentials and confirm destructive actions (#7750)
- *(posthog)* Fix duplicate persons and internal filters in PostHog (#7716)

## Managed 1.6.19 (0.71.11)

## Managed Nango 1.6.19 (application 0.71.11)

- **Released:** 2026-10-02
- **Docker image:** `nangohq/nango:managed-1.6.19-0.71.11-75a6224d421049ae0ec40cbb7b50221ed0500b0d`
- **Pin CLI to:** `0.71.11`
- **Compare:** https://github.com/NangoHQ/nango/compare/fe85242b81ab9d3ac808a72ca7bdd2788c8e86fb...75a6224d421049ae0ec40cbb7b50221ed0500b0d
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webhooks)* Add allow unverified webhooks integration option (NAN-7312) (#7726) by @agusayerza
- *(integrations)* Add support for Discord Bot (#7678) by @arctic-char
- *(integrations)* Add support for Slack app configuration tokens (#7669) by @arctic-char
- *(server)* Add the Agent Playground chat API (#7697) by @macko911
- *(integrations)* Add support for modmed-fhir (#7745) by @hassan254-prog
- *(integrations)* Add Discogs OAuth1 and personal token providers (#7340) by @aquarazorda
- *(integrations)* Add support for Mailtrap (#7150) by @mazu-rok
- *(runner-sdk)* Support redirect error in nango.uncontrolledfetch (#7758) by @rbwest

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/73b6621f698206dbb7561601f031ab3af02c10e5 by Victor Lang'at by @github-actions[bot]
- Update version in manifest by @actions-user
- *(docs)* Free self-hosted should be single tenant (#7751) by @rossmcewan
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/900eb400acae4023ff10903315905207bc3a5dc7 by Victor Lang'at by @github-actions[bot]
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fec2851c5d727f250db62f8b275603cd65c96996 by Victor Lang'at by @github-actions[bot]
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3fce1c855f03b768a4a256cb6bac745b8296c3b6 by Victor Lang'at by @github-actions[bot]
- Function invocation endpoint (#7724) by @TBonnin
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5e38e8f0dfa1ea031ee2230f8d8d3204514667d4 by Victor Lang'at by @github-actions[bot]
- Rename the server and CLI events to the taxonomy (#7753) by @macko911
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/23df553a789b6e30ba1640d4605cf5bfa7ca7cae by Victor Lang'at by @github-actions[bot]

### Fixed

- *(server)* Fix tool search reporting a just-connected app as not connected (#7748) by @macko911
- *(proxy)* Time out stalled requests and abort them on cancel (#7709) by @agusayerza
- Dequeue query tweaks (#7743) by @TBonnin
- *(microsoft-admin)* Stop double-encoding the client_credentials scope (#7712) by @arhaikal
- *(mcp)* Protect credentials and confirm destructive actions (#7750) by @marcindobry
- *(posthog)* Fix duplicate persons and internal filters in PostHog (#7716) by @macko911

## Managed 1.6.18 (0.71.11)

## Managed Nango 1.6.18 (application 0.71.11)

- **Released:** 2026-10-01
- **Docker image:** `nangohq/nango:managed-1.6.18-0.71.11-fe85242b81ab9d3ac808a72ca7bdd2788c8e86fb`
- **Pin CLI to:** `0.71.11`
- **Compare:** https://github.com/NangoHQ/nango/compare/03ac7879367e3c722db3283475ad3499c506fbb4...fe85242b81ab9d3ac808a72ca7bdd2788c8e86fb
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(sanity-sync)* Add integration templates sync (#7554)

### Changed

- Update version in manifest
- *(webapp)* Rename the remaining webapp events to the taxonomy (#7720)

### Fixed

- *(server)* Fix the dark OAuth success page in light mode (#7742)
- Upgrade @grpc/grpc-js (#7747)
- *(plans)* Give Growth add-on customers the xl API rate limit (#7691)
- *(file)* Copy templates remotely whenever remote storage is on (#7752)

## Managed 1.6.17 (0.71.11)

## Managed Nango 1.6.17 (application 0.71.11)

- **Released:** 2026-10-01
- **Docker image:** `nangohq/nango:managed-1.6.17-0.71.11-03ac7879367e3c722db3283475ad3499c506fbb4`
- **Pin CLI to:** `0.71.11`
- **Compare:** https://github.com/NangoHQ/nango/compare/82c35f702fe1d4c92834b6b4627f8ac86e5f8e55...03ac7879367e3c722db3283475ad3499c506fbb4
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webapp)* Show startup-deal accounts the new billing metrics (#7566)
- *(kms)* Add Azure Key Vault as a DEK wrapping provider (#7717)

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e1f139a2b33d2e976c811c95a38c2dd2a413fe47 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6d0f6e4e575cdf9f2f89e16086d2e2069fefbb1c by Victor Lang'at

### Fixed

- Allow cronjob to enable growth add-on for scale-legacy (#7731)

## [v0.71.11] - 2026-09-30

### Added

- *(posthog)* Count server-side events in account-level PostHog insights (#7687)
- *(integrations)* Add support for HitPay (#7684)
- Add PATCH /functions/:uuid to enable/disable (#7703)
- *(flags)* Gate catalog tools on the tools-catalog flag (#7699)
- *(integrations)* Add support for weflow (#7711)
- *(webhooks)* Verify airtable webhook MAC signatures (NAN-7215) (#7628)
- *(integrations)* Add support for openrouter (#7710)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1f08afc49a27b9f22f80ae31f2b2679f0e1bda99 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/d70f170c0b429fb03681fc4dc63972cb783fa44b by Victor Lang'at
- Replace blue favicon with the website/app wolf favicon (light & dark mode) (#7714)
- Point get connection and node sdk links to current paths (#7718)
- *(webapp)* Remove webapp analytics events nobody uses (#7663)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/0a5ff5d9daf7e481dc14e5b8109e823c43430c86 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ce75a75c9a8ffdbf9a6f6a484cf05fdf410e5f28 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4866befe2e85d879f0ce0cad12a7ee12fa73727d by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b8b5922290472952609ea17f505624b760b0ddc6 by Victor Lang'at

### Fixed

- *(webapp)* Move remaining hand-rolled fetches onto react-query (part 1) (#7652)
- *(integrations)* Disable PKCE for eway-crm (#7723)
- Vulns (#7725)
- *(agent-sessions)* Tell nango_tool_search what to do about a missing connection (NAN-7174) (#7705)
- More vulns (#7729)

## Managed 1.6.16 (0.71.10)

## Managed Nango 1.6.16 (application 0.71.10)

- **Released:** 2026-09-29
- **Docker image:** `nangohq/nango:managed-1.6.16-0.71.10-82c35f702fe1d4c92834b6b4627f8ac86e5f8e55`
- **Pin CLI to:** `0.71.10`
- **Compare:** https://github.com/NangoHQ/nango/compare/8d4951b5e9583c0b84751559fb12b3fb0adeee55...82c35f702fe1d4c92834b6b4627f8ac86e5f8e55
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webapp)* Rotate the webhook signing key from the dashboard (NAN-6608) (#7680)

### Changed

- Update version in manifest
- *(all)* Bump zod versions (#7700)

## Managed 1.6.15 (0.71.10)

## Managed Nango 1.6.15 (application 0.71.10)

- **Released:** 2026-09-29
- **Docker image:** `nangohq/nango:managed-1.6.15-0.71.10-8d4951b5e9583c0b84751559fb12b3fb0adeee55`
- **Pin CLI to:** `0.71.10`
- **Compare:** https://github.com/NangoHQ/nango/compare/f0ccb50a4dc666229fbb9b91bbe9c08a8ebc57c6...8d4951b5e9583c0b84751559fb12b3fb0adeee55
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(functions)* List live catalog actions (NAN-6903) (#7612)
- *(webhooks)* Verify salesforce webhooks with a Nango webhook secret (NAN-7214) (#7630)
- *(posthog)* Show the account in Billing Bot plan-change alerts again (#7651)
- *(integrations)* Add support for Tracify (#7507)
- *(integrations)* Add support for Omnisend (#7515)
- *(functions)* Run live catalog actions (NAN-6903) (#7613)
- Add partial index to functions config for http trigger with subscriptions (#7656)
- *(integrations)* Add Billit Access Point (#7659)
- Add function uuid (#7662)
- *(logs)* Add support for Elastic Cloud Serverless (#7673)
- Add /functions/:uuid (#7674)
- *(webhooks)* Validate Bot Framework JWTs on Microsoft Teams webhooks (NAN-6938) (#7661)
- Add GET /functions API endpoint (#7679)
- *(server)* Track Management MCP usage in PostHog (#7653)
- *(webapp)* List catalog actions in the playground (#7682)
- *(integrations)* Add support for astro-mcp (#7695)
- *(integrations)* Add support for eclinicalworks (#7694)

### Changed

- Changelog entry for Management MCP OAuth and new tools (#7658)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fd0a116d2872bd8f8e9f2301f4855d72d949bb1d by Victor Lang'at
- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/98217a8f0256c58480fa197d95d51f7c12d4b340 by Rhys Balevicius
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/46dc5e6f2359e5bc42c1118c7e60b9c70f41a3ff by Rhys Balevicius
- Box the Management MCP OAuth screenshot (#7665)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1f51ebe9c3648515a3726a8195d12e1a2e280a41 by arctic-char
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/9d2a2311e455b2c3b35c916adeddfedeb44e0ed3 by arctic-char
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/83a1a4955f7466e89cae8cc2b0ba768485d91319 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e52b81d237dcbd00e103da6050d5f5d140b8841b by Victor Lang'at
- Migrate webflow docs (#7686)

### Fixed

- *(deploy)* Return a clean error when the previous sync version can't be auto-incremented (#7657)
- *(webapp)* Stop sending autocapture events to PostHog (#7655)
- *(webapp)* Solve issue with inaccessible Upgrade link in tooltips (#7467)
- *(posthog)* Stop merging every CLI device on an account into one PostHog person (#7654)
- *(docs)* Update self-hosting docs (#7689)
- *(plans)* Give Growth add-on customers the environments the add-on promises (#7690)
- *(shared)* Get api url (#7704)

## Managed 1.6.14 (0.71.10)

## Managed Nango 1.6.14 (application 0.71.10)

- **Released:** 2026-09-25
- **Docker image:** `nangohq/nango:managed-1.6.14-0.71.10-f0ccb50a4dc666229fbb9b91bbe9c08a8ebc57c6`
- **Pin CLI to:** `0.71.10`
- **Compare:** https://github.com/NangoHQ/nango/compare/0a2c37c5300b27f8882624921a7365720758e26e...f0ccb50a4dc666229fbb9b91bbe9c08a8ebc57c6
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- Create/delete schedules if needed when connection is created/deleted (#7584)
- Delete functions/schedules when integrations are deleted (#7589)
- *(mcp)* Hook up OAuth to Management MCP (#7550)
- *(server)* Ask for environment before OAuth MCP queries (#7601)
- *(providers)* Add Anarlog MCP provider (#7303)
- *(integrations)* Support MCP_OAUTH2 across create/update/get for static, dynamic, and cimd (#7464)
- *(webapp)* Redirect from sign in/up pages when user already authenticated (#7580)
- *(agent-sessions)* Add the nango_create_connection meta tool (#7592)
- *(mfa)* Allow a recovery code to disable 2FA (NAN-7154) (#7597)
- *(integrations)* Add support for Simpplr (#7548)
- *(oauth2_cc)* Fall back to JWT exp for OAUTH2_CC token expiry (#7605)
- Delete functions as part of the retention deletion logic (#7602)
- *(mcp)* Add missing hints to Management MCP tools (#7608)
- Add NANGO_ADMIN_KEY to env example (#7619)
- *(integrations)* Add pleo api key to the api key regex (#7623)
- *(halo-psa)* Add authenticated webhook routing (#7615)
- *(authz)* Authorize public routes through grants (#7490)
- *(integrations)* Add support for mailerlite (#7618)
- *(webhooks)* Flag unverified webhooks in forwarded payloads (NAN-7212) (#7627)
- *(posthog)* Tag events with account, environment and is-prod (NAN-7113) (#7572)
- *(integrations)* Add support for clay mcp (#7617)
- *(posthog)* Emit agent session lifecycle and tool call events (NAN-7114) (#7574)
- *(integrations)* Add support for textus (#7620)
- *(integrations)* Add support for beeline-vms (#7622)
- *(integrations)* Add support for symplr-ctm (#7625)
- *(integrations)* Add support for ukg-pro-wfm-cc (#7636)
- *(integrations)* Add support for eway-crm (#7637)
- *(integrations)* Add support for jobnimbus (#7638)
- *(integrations)* Add support for posthog capture (#7645)
- *(server)* Add MCP titles and type action input (#7640)
- *(integrations)* Add MCP_OAUTH2_GENERIC integrations to the public API (#7529)
- *(CLI)* Accept on-events trigger for functions (#7634)
- *(webhooks)* Require a Nango webhook secret for unsigned providers (NAN-7213) (#7629)
- *(catalog)* Add live catalog reader and runnable resolver (NAN-6903) (#7611)
- *(posthog)* Send tool search queries and results (NAN-6944) (#7585)

### Changed

- Update version in manifest
- September changelog entries and tighter dividers (#7591)
- Make the docs favicon the same size as everyone else's (#7599)
- Remove E2B sandbox provider (#7600)
- Recommend OAuth for Management MCP (#7603)
- Retire old daily_function_executions CH table (#7595)
- Remove daily-fn-exec one-off data migration script (#7596)
- Loosen the changelog divider gap to 48px (#7609)
- *(posthog)* Remove the legacy backend events (NAN-7125) (#7573)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/809982d12aad67a359ac6e75a1adb59ad292dfde by Givi
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/957b65ee32ecbfe1d0761228986633825654b372 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6ef2e92eb45d3cec792ee7d8d2eda97618b3bed7 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3e8305e2383842cfc95ca2390e9859686911f790 by Victor Lang'at
- *(authz)* Replace withScope with can (#7492)
- *(github-app)* Explain how to add the webhook secret to an existing app (NAN-7210) (#7647)

### Fixed

- *(retry)* Retry EPIPE as a network error (#7606)
- *(auth)* Stop a link cancelling onboarding for Google signups (#7579)
- *(oauth-server)* Support ChatGPT CIMD metadata choices (#7607)
- *(connectwise-psa)* Support self-hosted webhook signing-key origins (#7616)
- *(webapp)* Sign users out when their session expires on any page (#7552)
- *(webapp)* Make Getting Started code snippet readable in light mode (#7621)
- *(webapp)* Remove SWR from the webapp (#7635)
- *(cron)* Allow startup-deal growth add-on transitions (#7648)
- Support OpenAI plugin OAuth submission (#7633)
- *(server)* Delete variant sync records on cleanup, not base (#7649)

## [v0.71.10] - 2026-09-21

### Added

- *(function)* Implement getVariant() (#7569)
- *(integrations)* Add support for apple calendar (#7535)

### Changed

- Make BYOC the main self-hosting path (#7453)

## Managed 1.6.13 (0.71.9)

## Managed Nango 1.6.13 (application 0.71.9)

- **Released:** 2026-09-21
- **Docker image:** `nangohq/nango:managed-1.6.13-0.71.9-0a2c37c5300b27f8882624921a7365720758e26e`
- **Pin CLI to:** `0.71.9`
- **Compare:** https://github.com/NangoHQ/nango/compare/bc65eb8aec98cd184c0da0701eed7bae4ab6830f...0a2c37c5300b27f8882624921a7365720758e26e
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(auth)* Return to the requested page after login (#7520)
- *(integrations)* Add Linkly (API key) (#7516)
- Extend one-off PAYG migration script (#7553)
- *(oauth)* Add dashboard login and consent flow (NAN-6924) (#7481)
- *(tracking)* Track plan_change:v2 (#7558)
- Scheduled functions can execute (#7563)
- *(integrations)* Add Autumn (API key) (#7576)
- *(providers)* Move stripe-app-sandbox appDomain to integration_config (#7227)
- *(integrations)* Add support for hex mcp (#7578)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f78affc941f935241a71eb6911209cbb92f3ec20 by Hassan_Wari
- *(providers)* Update the Pleo logo to their new brand (#7565)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/261c9cb19d13c9bf1d664e66c3870e98477fd9ab by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/47dd7fd51835f9e9fcf7038573b67f5563d27856 by Victor Lang'at
- Clarify external contribution guidelines (#7577)
- *(records)* Share one helper for composite model names (#7415)

### Fixed

- *(integrations)* Send netsapiens token request as JSON (#7559)
- *(providers)* Fix pleo api key verification endpoint (#7564)
- *(cron)* Allow growth cron to pre-enable growth flag (#7555)
- *(persist)* Restore per-tick limit on auto-deleting records (#7571)
- *(connect-ui)* Stop the theme flashing before the dialog loads (#7497)
- *(webapp)* Land billing deep links on the right section (#7567)

## [v0.71.9] - 2026-09-16

### Added

- *(agent-sessions)* Give MCP tool failures an agent-facing message and code (NAN-6604) (#7473)
- *(integrations)* Add support for pleo-api-key (#7534)

### Changed

- *(shared)* Coalesce customer key lookups (#7466)

### Fixed

- *(shared)* Propagate environment lookup failures (#7472)
- *(frontend)* Route TWO_STEP credentials before OAuth2 client creden… (#7556)

## [v0.71.8] - 2026-09-16

### Added

- *(agent-sessions)* Reap expired sessions and their tokens (NAN-6599) (#7511)
- *(integrations)* Add SalesCaptain (#7149)
- *(audit)* Audit agent session creation and termination (NAN-6751) (#7508)
- *(agent-sessions)* Log a tool search operation (NAN-6605) (#7509)
- *(functions)* Support deployment of function with schedule trigger (#7512)
- *(jobs)* Emit function execution health metric at the source (NAN-6988) (#7527)
- Add one-off Orb pay-as-you-go migration scheduler (#7494)
- *(plans)* Growth add-on management cron (#7530)
- *(integrations)* Add Neon MCP support (#7545)
- *(usage)* Cap free-plan data transfer (#7413)
- *(functions)* Upsert schedules if needed when deploying functions (#7525)
- *(webhooks)* Add support for zoom webhooks (#7484)

### Changed

- *(agent)* Trim the agent session operation payloads (NAN-6950) (#7510)
- *(google)* Document webhook auth as required (NAN-7030) (#7524)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e4563fe2082cd44fc82df0857d3179bcaa3c2f32 by murphy-con
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/64a671aa2b83f449b3f29e94822bb62761902b51 by murphy-con
- *(skills)* Document migration mismatch and local feature flags (#7496)
- *(functions)* Rename DeployedNangoFunction to ListedNangoFunction (#7531)

### Fixed

- *(runner)* Log when reporting a task result fails (#7523)
- *(syncs)* Keep the variant badge beside the sync name (#7423)
- *(webhooks)* Enforce signature validation on GitHub App webhooks (NAN-6934) (#7462)
- *(billing)* Show the cent Orb rounds up on per-metric charges (#7495)
- *(billing)* Stop dropping charges when prices change mid-month (#7470)
- *(utils)* Flush buffered metrics before services exit (#7538)
- *(plans)* Normalize pg bigint limits as number (#7448)
- *(integrations)* Switch lovable mcp client registration (#7546)
- *(jobs)* Record interrupted sync segments in the health metric (#7549)
- Fix ms dataverse sidebartitle (#7551)
- *(deploy)* Reject nango.yaml deploys and remove dead legacy compile code (#7480)

## Managed 1.6.12 (0.71.7)

## Managed Nango 1.6.12 (application 0.71.7)

- **Released:** 2026-09-17
- **Docker image:** `nangohq/nango:managed-1.6.12-0.71.7-bc65eb8aec98cd184c0da0701eed7bae4ab6830f`
- **Pin CLI to:** `0.71.7`
- **Compare:** https://github.com/NangoHQ/nango/compare/3f636c8052ff5a4c672c4c96e6f5996ca89a9088...bc65eb8aec98cd184c0da0701eed7bae4ab6830f
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(logs)* Stamp the session actor on action runs (NAN-6949) (#7443)
- *(logs)* Add an agent session filter to the logs page (NAN-6606) (#7446)
- *(integrations)* Add support for highq (#7487)
- *(integrations)* Add support for pandadoc eu and mcp (#7500)
- *(integrations)* Add support for infor (#7513)
- *(integrations)* Add support for microsoft-dataverse (#7505)
- *(integrations)* Add support for scavio (#7165)
- Add OAuth authorization server package (#7463)
- *(mcp)* Support static server URL and configurable scopes for MCP_OAUTH2_GENERIC (#7465)
- *(shared)* Add support for GCP and Azure buckets (#7519)

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/bb789a55bfcf744b3c83aa9132e4ffa562106aa3 by arctic-char

## [v0.71.7] - 2026-09-11

### Added

- *(billing)* Show per-metric charges for past months on the billing page (#7457)
- *(server)* Return a specific error for oversized request bodies (#7368)
- *(api)* Add public environment list endpoint (#7342)
- *(api)* List environment API keys (#7350)
- *(api)* Get environment API keys by UUID (#7352)
- *(integrations)* Add Bandwidth OAuth2 client-credentials provider (#7359)
- *(integrations)* Add support for inteliquent (#7360)
- *(webapp)* Show existing customers what they'd pay on the new pricing (#7458)
- *(github)* Add deployment for byoc-gcp-1 (#7461)
- *(orch)* Add support for scheduled functions (#7460)
- *(cli)* Add --no-sourcemap flag to disable inline source maps (#7506)

### Changed

- Update version in manifest
- Link self-hosting audit trail setup from changelog (#7471)
- *(agent-sessions)* Tone down beta messaging (#7475)

### Fixed

- *(proxy)* Stop getRawBody from crashing on stream request bodies (#7441)
- *(webapp)* Stop showing usage months from before the account existed (#7438)
- *(billing)* Show discounted metrics as billed (#7468)
- *(proxy)* Don't crash on a bare '%' in the request body for providers that don't need canonical params (#7469)
- *(webapp)* Hide the current-plan column when it has no charges (#7483)
- *(provider)* Allow hyphen in pipelinecrm api key (#7489)
- *(billing)* Stop accounts from self-serve upgrading to a retired plan (#7451)
- *(ci)* Stop Ubuntu mirror outages from failing the connect-ui tests (#7504)
- *(providers)* Fix supabase regex key (#7491)
- *(runner)* Allow node:-prefixed core module specifiers in sandboxed scripts (#7488)
- *(server)* Surface a clear 400 for unsupported multipart Content-Type on /proxy (#7498)
- *(webapp)* Stop the usage table cutting off figures and wrapping headers (#7499)
- Vulnerability fixes (#7486)
- *(wrap-dek)* Changes to support gcp kms (#7445)

## Managed 1.6.11 (0.71.6)

## Managed Nango 1.6.11 (application 0.71.6)

- **Released:** 2026-09-09
- **Docker image:** `nangohq/nango:managed-1.6.11-0.71.6-3f636c8052ff5a4c672c4c96e6f5996ca89a9088`
- **Pin CLI to:** `0.71.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/c043f09997fc6943ea5cca715cc502e6e6ce9bf4...3f636c8052ff5a4c672c4c96e6f5996ca89a9088
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(docs)* Add log retention to docs (#7435)
- *(integrations)* Add support for Moneybird (#7433)
- *(integrations)* Add bol.com OAuth2 client-credentials provider (#7436)

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/59fd4bfe9087379986552ee73b41209ea298d65e by Victor Lang'at
- Update version in manifest

### Fixed

- *(server)* Return 500 when secret key auth hits an unexpected error (NAN-4668) (#7456)

## Managed 1.6.10 (0.71.6)

## Managed Nango 1.6.10 (application 0.71.6)

- **Released:** 2026-09-09
- **Docker image:** `nangohq/nango:managed-1.6.10-0.71.6-c043f09997fc6943ea5cca715cc502e6e6ce9bf4`
- **Pin CLI to:** `0.71.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/42653e8800379afc30aad86e414ccb569b8697c1...c043f09997fc6943ea5cca715cc502e6e6ce9bf4
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webhooks)* Back off throttled groups on jobs SQS consumer (NAN-6407) (#7328)
- *(webhooks)* Defer saturated dispatch messages in SQS (NAN-6406) (#7334)
- *(orch)* Add executeFunctionBatch (#7374)
- *(audit)* Postgres writer and reader for the self-hosted audit trail (#7346)
- *(plans)* Add the growth add-on for pay-as-you-go (#7301)
- *(audit)* Run the Postgres migration and partition daemon from the server (#7355)
- *(webapp)* Rework the audit trail filter UI (#7397)
- Add screenshot to the agent sessions changelog entry (#7411)
- *(providers)* Add outlook webhook support (#7389)
- *(webapp)* Let customers add and remove the Growth add-on (#7402)
- *(syncs)* Paginate and virtualize the connection Syncs tab (NAN-6819) (#7369)
- *(integrations)* Add support for netsapiens (#7361)
- *(webapp)* Show the Pay-as-you-go migration in-app (#7425)
- *(integrations)* Add eu base url to typeform (#7407)
- *(webapp)* Show spend and per-metric charges to all customers (#7364)
- Add support for webhook functions (#7384)
- Allow setting function http trigger subscriptions (#7428)
- *(webhooks)* Add webhook support for granola (#7357)
- *(webhooks)* Add gong webhooks (#7434)
- *(integrations)* Add LiveSwitch provider (#7158)
- *(agent-session)* Create proxy tool (#7414)
- *(webhooks)* Improve fathom webhooks to use query as the connection id value (#7410)
- *(integrations)* Add support for outline (#7440)
- *(webapp)* Polish the audit event drawer and export dialog (#7417)
- *(integrations)* Add support for amplemarket (#7442)
- *(integrations)* Add support for airtable mcp (#7450)

### Changed

- Update version in manifest
- Document agent session termination (#7391)
- *(mcp)* Upgrade TypeScript SDK to v2 (#7383)
- Update AGENTS.md (#7406)
- Changelog for audit trail, agent sessions beta, new pricing, and August roundup (#7409)
- Update for new pricing plans (#7390)
- *(billing)* Remove the s26-pricing flag (#7426)
- *(audit)* Retire the audit-trail rollout flag (#7429)
- *(proxy)* Remove the proxy-forward-all-response-headers flag (NAN-6922) (#7431)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/56c9369bd7c6878a7fce4fb05f7825a8a31a6d76 by Marcin Dobrowolski
- *(mfa)* Retire the mfa rollout flag (NAN-6921) (#7432)
- *(billing)* Retire the HTTP billing events sent to Orb (NAN-6503) (#7427)
- Restructure the security guide (#7437)

### Fixed

- *(design-system)* Attach tooltip arrow to chip (#7395)
- *(connect)* Allow previews at the connection cap (#7379)
- *(cli)* Stop compile test hanging on npm audit (#7396)
- *(providers)* Disable PKCE for Digits OAuth2 (#7399)
- *(webhooks)* Dedupe Attio record events (#7386)
- *(syncs)* Render rows in production builds (NAN-6914) (#7418)
- *(orchestrator)* Drain the processor queue after the loop exits (NAN-6896) (#7403)
- *(jobs)* Decouple the consumer and server shutdowns (NAN-6896) (#7404)
- *(server)* Block unverified gmail webhooks with env setting (#7424)
- *(server)* Prevent disabled MCP action execution (#7439)
- *(connect-ui)* Keep base-path recovery out of the CDN build (#7401)
- *(server)* Clamp proxy retry to maximum duration (#7264)
- *(webapp)* Keep dev tools while impersonating customers (#7444)
- *(webhooks)* Enforce signature validation in webhook routing scripts (#7430)

## Managed 1.6.9 (0.71.6)

## Managed Nango 1.6.9 (application 0.71.6)

- **Released:** 2026-09-03
- **Docker image:** `nangohq/nango:managed-1.6.9-0.71.6-42653e8800379afc30aad86e414ccb569b8697c1`
- **Pin CLI to:** `0.71.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/b0ce6392ab8ed84e08902b25e21675946a0939ea...42653e8800379afc30aad86e414ccb569b8697c1
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(server)* Tag internal callers instead of excluding them from deprecated endpoint metric (#7353)
- *(audit)* Day-partitioned Postgres schema for the self-hosted audit trail (#7335)
- *(audit)* Daily partition lifecycle for the self-hosted audit table (#7343)
- Add deploy all workflow (#7380)
- *(audit)* Show how many events a read matches (#7365)
- *(agent-sessions)* Add DELETE /sessions/{id} to terminate a session (NAN-6598) (#7336)

### Changed

- Update version in manifest
- Draft the agent sessions guide (NAN-6832) (#7317)
- Match the website favicon (#7367)
- Audit trail (NAN-6487) (#7164)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1efbe17acea944b505ac50b3453862788b5c4b5b by Marcin Dobrowolski
- Retire the permission vocabulary for scopes (#7341)

### Fixed

- *(webapp)* Adapt favicons to the browser theme (#7366)
- *(billing)* Read Orb subtotal for metric charges (#7371)
- *(vulns)* Npm audit fix (#7376)
- *(docker)* Remove npm from docker images (#7381)
- *(docker)* Cleanup lambda npm (#7382)
- *(server)* Validate google incoming webhooks (#7373)
- *(persist)* Stream deleteHardAllRecords progress to avoid client timeout on large deletes (#7375)

## Managed 1.6.8 (0.71.6)

## Managed Nango 1.6.8 (application 0.71.6)

- **Released:** 2026-09-02
- **Docker image:** `nangohq/nango:managed-1.6.8-0.71.6-b0ce6392ab8ed84e08902b25e21675946a0939ea`
- **Pin CLI to:** `0.71.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/b14e3aa3e113fd0996a2484e6ba7befe3261ecc1...b0ce6392ab8ed84e08902b25e21675946a0939ea
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(mcp)* Add providers get tool (#7283)

### Changed

- *(granola)* Correct plan requirement and desktop app flow (#7347)
- Alphabetize the APIs & Integrations nav list (#7345)

### Fixed

- *(sync)* Resolve variant-scoped model recordCount (#7270)
- *(audit)* Let the auth type name the connect session, not the end user (#7348)
- Npm audit fix (#7349)
- *(dockerfile)* Fix vulns in image (#7351)
- *(syncs)* Batch schedule search fan-out (#7318)

## [v0.71.6] - 2026-09-02

### Added

- *(plans)* Add the pay-as-you-go plan (#7279)
- *(plans)* Add upgrade path from free to PAYG (#7281)
- *(metering)* Add daily function executions v2 backfill (#7188)
- *(usage)* Read all function metrics from v2 table (#7203)
- *(server)* Connection deleted webhook (#7235)
- *(server)* Add the nango_execute meta tool (NAN-6601) (#7261)
- *(server)* Add the nango_tool_search meta tool (NAN-6603) (#7262)
- *(webapp)* Show the new pricing's plans (#7306)
- *(audit)* Record the policy scope on every event (NAN-6802) (#7310)
- *(plans)* Block moves between Starter and Growth (#7320)
- *(plans)* Cap free function runtime instead of legacy metrics (#7315)
- *(webapp)* Rework the billing overrides dev panel (#7314)
- *(audit)* Name api keys and environments by their uuid (#7319)
- *(integrations)* Add support for scrollstash-mcp (#7282)
- *(providers)* Add sandbox env to factorial (#7228)
- *(integrations)* Add support for meta-ads-mcp (#7321)
- *(integrations)* Add support for finta (#7275)
- *(integrations)* Add support for greenfield-meditech (#7326)
- *(audit)* Attribute public-key OAuth callbacks (#7329)
- *(audit)* Count events that could not name an actor (#7322)
- *(integrations)* Add support for epic fhir (#7332)
- *(server)* Add action trigger management MCP tool (#7284)
- *(integrations)* Add support for nooks (#7337)
- *(mcp)* Add sync trigger management tool (#7257)
- *(cli)* Support mtls (#7325)
- *(server)* Track usage of deprecated public endpoints (#7280)

### Changed

- Update version in manifest
- *(server)* Use grants and scopes instead of permissions in private API (#7293)
- *(kms)* Rename file (#7307)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7c51ba656fd0c2690d96bea0af938b2659cece09 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/02b840bafa26f2af89953c21c376eb6c5ed460ea by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4f107b1670183cf485017912952decd0a2218186 by Victor Lang'at

### Fixed

- *(integrations)* Support regional SaaS Backup hosts for NinjaOne (#7300)
- *(connections)* Include shared credentials when selecting connections for cron refresh (#7312)
- *(docs)* Point nango.dev/demo links at /contact (#7305)
- *(runner)* Auth runner start (#7288)
- *(webapp)* Show usage on the 1st of the month (#7323)
- *(auth)* Raise API key credential max length to 4096 (#7327)
- Name the Growth add-on in upgrade prompts (#7316)
- *(api)* Use UUIDs for public environment management  (#7309)
- *(webapp)* Align usage bars across metric rows (#7331)

## Managed 1.6.7 (0.71.5)

## Managed Nango 1.6.7 (application 0.71.5)

- **Released:** 2026-08-31
- **Docker image:** `nangohq/nango:managed-1.6.7-0.71.5-b14e3aa3e113fd0996a2484e6ba7befe3261ecc1`
- **Pin CLI to:** `0.71.5`
- **Compare:** https://github.com/NangoHQ/nango/compare/3b2c0410e3b8444d5eacb45817f74ee8d462711a...b14e3aa3e113fd0996a2484e6ba7befe3261ecc1
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(usage)* Reconcile usage and billable data transfer (#7265)
- *(webapp)* Show customers the usage and limits they're billed on using new pricing (#7251)
- *(authz)* Namespace decides the where, and drop the top-level wildcard (#7287)
- *(audit)* Check every event's metadata against the vocabulary (#7276)
- *(mcp)* Add sync_set_state management tool (#7256)
- *(providers)* Add GitLab (Group Access Token) provider (#7199)
- *(audit)* Name the deprecated public-key flow as its own actor (#7302)
- *(kms)* Add support for gcp kms (#7291)

### Changed

- *(audit)* Split the audit middleware into one file per resource (#7271)
- *(audit)* Split the store contracts from their implementations (#7272)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/8c33aed0ede39e8b56989dffcbaf8e388ffe8f64 by Victor Lang'at

### Fixed

- *(server)* Count every shadow comparison, not just the failures (#7263)
- *(server)* Datadog tag and record every authorization comparison (#7292)
- *(orchestrator)* Count rate limited and duplicate tasks as rejected (NAN-6809) (#7294)
- *(functions)* Metadata and checkpoint is working. do not gate them (#7289)
- *(persist)* Stream deleteOutdatedRecords progress to avoid client timeout on large deletes (#7192)
- *(audit)* Name the integration when a bulk sync pause or start targets nothing (NAN-6791) (#7304)

## [v0.71.5] - 2026-08-27

### Added

- *(server)* Add public environment api-keys management endpoints (#7007)
- *(team)* Prefill invite form from join request (NAN-6564) (#7093)
- *(integrations)* Add support for transporeon carrier (#7140)
- Add changelog entry for dashboard password change (#7141)
- *(plans)* Add audit trail entitlement columns (NAN-6483) (#6966)
- *(design-system)* Lift Alert into design system (#7122)
- *(audit)* Gate the audit trail on plan entitlements (NAN-6484) (#6968)
- *(mcp)* Add connections get tool (#7066)
- *(audit)* Retain audit events for a year, not 90 days (NAN-6485) (#7162)
- *(providers)* Add Hail (#6840)
- Add shopify webhook docs (#7114)
- *(integrations)* Add support for Pushpay ChMS V2 (#7011)
- *(webapp)* Add a billing & usage summary strip (#7109)
- *(billing)* Alert customers when an invoice is overdue (#6845)
- *(integrations)* Add support for CDW (#7155)
- *(server)* Add agent session persistence (NAN-6593) (#7152)
- *(runner)* Tighten runner egress networkpolicy (#7144)
- *(server)* Track usage of deprecated functions endpoint (#7153)
- *(functions)* Add logging/tracking to POST /functions/invocations (#7160)
- *(billing)* Show overdue alert to all members (#7177)
- *(server)* Mint and validate agent session tokens (NAN-6596) (#7169)
- *(mfa)* Require a second factor to change or reset a password (NAN-6586) (#7110)
- *(webapp)* Show billed-this-month spend in the summary strip (#7145)
- *(integrations)* Add support for sage-300-cre (#7163)
- *(integrations)* Add support for stedi (#7185)
- *(integrations)* Add support for omni analytics (#7186)
- *(audit)* Record connection.created for every creation route (NAN-6470) (#7146)
- *(mcp)* Add proxy request tool (#7135)
- *(integrations)* Add support for athenahealth (#7187)
- *(integrations)* Add RyderShip integration (#6651)
- *(integrations)* Add support for splunk (#6567)
- *(integrations)* Add support for streamline-ai (#7161)
- *(audit)* Export the audit trail as CSV from the dashboard (#7175)
- *(integrations)* Add support for epost-klara (#7189)
- *(logs)* Add an actor to operations (NAN-6592) (#7184)
- *(kvstore)* Sliding window rate limiter (NAN-6609) (#7116)
- *(orchestrator)* Add immediate task throttling (NAN-6404) (#7170)
- *(scheduler)* Support per-group task cap overrides (#7154)
- *(persist)* Enforce connection-to-environment ownership on all routes (#7198)
- *(usage)* Add v2 function execution aggregates (#7172)
- *(design-system)* Lift Tooltip into design system (#7176)
- *(webapp)* Align Billing & usage page with the latest designs (#7139)
- *(server)* Track usage of the connections search param (#7179)
- *(audit)* Mark events reached through an impersonation session (#7183)
- *(audit)* Record the scopes an API key was granted, on every route (#7212)
- *(mcp)* Add functions list tool (#7182)
- *(server)* Add webhook for recovered oauth connection (#7202)
- *(billing)* Let customers set spend alerts (#7180)
- *(audit)* Record sync.triggered on the public API, and unify sync audit events across public and private (NAN-6715) (#7210)
- *(mcp)* Track tool call outcomes in Datadog (#7226)
- *(audit)* Identify deployed functions by integration and name, and record the deploy source (#7224)
- *(authz)* Add grant language and roles (NAN-6657) (#7218)
- Add documentation tools to management MCP (#7211)
- *(agent-sessions)* Resolve tenant connection selectors (NAN-6594) (#7217)
- *(usage)* Export and cap function runtime in started seconds (#7173)
- Add changelog entries for account API keys, team join at signup, and Japanese Connect UI (#7234)
- Add GET /functions/invocations/:id endpoint (#7229)
- Add function_runtime in plan with default=lambda (#7230)
- *(audit)* Add the missing details to failed connection and webhook events (#7242)
- *(auth)* Internal service auth (#7167)
- *(integrations)* Add support for vincere (#7079)
- *(audit)* Let an impersonated session read a recorded account's trail (#7246)
- *(audit)* Count recorded and dropped audit events per resource (#7247)
- *(server)* Track account ID in management MCP metrics (#7248)
- *(mfa)* Record why an MFA verification was rejected (NAN-6615) (#7216)
- *(server)* Normalized principal and shadow evaluation (NAN-6657) (#7237)
- *(server)* Compile a toolset policy into a resolved tool list (NAN-6595) (#7231)
- *(server)* Add POST /sessions to create an agent session (NAN-6597) (#7232)
- *(server)* Serve a session-scoped MCP endpoint at /session/{id}/mcp (NAN-6600) (#7239)
- *(mcp)* Add deploy function tool (#7213)
- *(mcp)* Add deploy template tool (#7214)
- *(mcp)* Add deployment status tool (#7215)
- *(audit)* Stop auditing the public metadata and sync trigger endpoints (#7269)
- Show per-metric charges for paid plans (#7208)
- *(functions)* Support for http trigger (#7250)
- *(runner)* Split persist_logs DT telemetry callsites (#7249)
- *(metering)* Export runner->persist data transfer to Orb (#7253)

### Changed

- Update version in manifest
- Link self-hosted 2FA setup from changelog entry (#7137)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7c3f0df6ece37b0175cf7009ce5ba0a7bf5f3150 by Victor Lang'at
- *(design-system)* Put Design System first in Storybook (#7138)
- Document public environment management APIs (#7148)
- Start MDX body headings at H2 (#7194)
- Demote connect guide H1 headings to H2 (#7197)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/91ecf3e04fb0523ec534d175e70c40244dc1bde3 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/59236082c6afed77259e4454611af1e521bf1729 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/32568c4f8c95e79117da63ea443e61e16cf4ee52 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/80803b3b93c962dc4f550cf5dd610a0a982a6fa7 by Quentin de Quelen
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b521e55f70398e1bb519a1e9aef7e4a594936b6e by Victor Lang'at
- PostInvocation create a orchestrator task (#7195)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/965f2d99e8529286b8a7c6c0cd325311fd25667c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a15a14d386a12a4326634ddeb10fe64f59eb46e4 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4afb9793b2f1ee919b1663a82aba217721b13ed8 by Victor Lang'at
- Changelog for Management MCP tools, connection recovery webhook, and 2FA on password changes (#7238)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b8bd9f83607f5e7154dfbbcf4895e9652603e2b8 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/80f9c8da4c24ef3d8d23fd7e2ec24384fc553fce by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ffb3660049ff396b95ae64e48825f3001c9f6533 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a16b84511c0f588e4a03472e84c8d336672ce1ef by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5a61467f333264adb4b09162a67f24a204f29b5a by Victor Lang'at
- Execute simple function (#7219)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ace291ffa324bebe0ff746cc3c2c7757065a5d9f by Victor Lang'at
- Link Management MCP reference to coding agent setup (#7259)
- Refresh coding agent MCP setup (#7252)

### Fixed

- *(server)* Emit MCP schemas as JSON Schema 2020-12 (#7147)
- *(mfa)* Reuse the session's recent MFA verification for impersonation (NAN-6614) (#7128)
- *(webapp)* Properly handle oauth_scopes_override (#7034)
- *(billing)* Filter overdue invoices by due date (#7168)
- *(auth)* Bind invitation signup tokens to invited email (#7151)
- *(sync)* Don't resume manually paused syncs on connection reauth (#7136)
- *(audit)* Stop one bad event from duplicating the ones batched with it (#7166)
- *(providers)* Update instagram authorization url (#7190)
- Fix heading hierarchy on core and integration pages (#7201)
- *(webapp)* Overdue alert sends you to the billing page (#7191)
- *(webapp)* Correct the spend headline's reveal and tooltip (#7196)
- *(connect-ui)* Pre-bundle react/jsx-runtime in vitest config (#7205)
- *(server)* Harden pre/post connection proxy request (#7206)
- *(providers)* Accept any Auvik region instead of a fixed enum (#7223)
- *(audit)* Identify an accepted or declined invite by the user, not the email (#7225)
- *(audit)* Align the field order and the target format across every read surface (#7241)
- *(audit)* Record what a user update changed (#7240)
- *(audit)* Record the integration's name and provider on its events (#7243)
- *(audit)* Record which environment a public API key was created in (#7245)
- *(onboarding)* Rank team suggestions by users on the matching domain (#7236)
- *(design-system)* Align toast and compact Alert with the Figma spec (#7244)
- *(audit)* Record the login when SSO holds it for MFA (#7255)

## Managed 1.6.6 (0.71.4)

## Managed Nango 1.6.6 (application 0.71.4)

- **Released:** 2026-08-17
- **Docker image:** `nangohq/nango:managed-1.6.6-0.71.4-3b2c0410e3b8444d5eacb45817f74ee8d462711a`
- **Pin CLI to:** `0.71.4`
- **Compare:** https://github.com/NangoHQ/nango/compare/b6a11be5e83e48fc2f4758685ce2d6a12d817fad...3b2c0410e3b8444d5eacb45817f74ee8d462711a
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(mcp)* Add missing schema and hints to management mcp tools (#7090)
- Add account API key dashboard (#7025)
- *(webapp)* Redesign billing details section (#6908)
- *(webapp)* Address post-merge Account API keys UI review (#7095)
- *(integrations)* Add support for chartboost (#6463)
- *(integrations)* Add support for neon (#6823)
- *(integrations)* Add support for meilisearch (#6713)
- *(integrations)* Add support for livetennisapi (#6910)
- *(server)* Add public environment management endpoints (#6973)
- *(integrations)* Add support for agentline (#7102)
- *(integrations)* Add support for agency-zoom (#7105)
- *(integrations)* Add support for chili-pipper (#7103)
- *(integrations)* Add support for statsig (#7104)
- *(integrations)* Add support for factorial api key (#7088)
- *(feature-flags)* NAN-6476 serve flags from env vars (#7080)
- *(webapp)* Add change password to user profile (#6931)
- *(ci)* Add Storybook PR preview deploys (#7084)
- *(mcp)* Add Connect Session creation tool (#7108)
- *(shared-credentials)* Allow for github-app to be added as a shared credential (#7069)
- *(webapp)* Add a primary action to the billing page header (#7111)
- *(server)* Cleanup endpoint (#7126)
- Add POST /functions/invocations (#7106)
- *(metrics)* Add provider config key to metrics - opt in only (#7120)
- *(design-system)* Add link variants to Button per Figma (#6887)
- *(server)* Let the dashboard's API target be configured separately from NANGO_SERVER_URL (#7064)

### Changed

- Update version in manifest
- *(webapp)* Move InputOTP out of components-v2 (#7089)
- *(env)* Centralize environment creation validation (#6972)
- *(action)* Extract a non-HTTP action executor from runAction (NAN-6591) (#7115)
- Replace mentions of secret key with API key (#7107)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ad1f47ff31378b945e1925b5d464608ec2c6edfb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/172e3507fc38b648ef382135d8e9fd15679ea51e by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/78a950c69fab9ac98dc3546b4f1e092cd57ee6e5 by Steven Zhou
- *(webapp)* Migrate StyledLink to design-system Button (#7112)

### Fixed

- Keep auth tokens out of PostHog and Sentry (#7078)
- *(webapp)* Align env settings panel border (#7091)
- *(design-system)* Migrate border.interactive to border.input (#7086)
- *(mfa)* Tolerate authenticator clock drift (NAN-6568) (#7097)
- *(inputs)* Render placeholders with a dedicated token (#7113)
- *(design-system)* Sync danger-family tokens from design/tokens (#7083)
- Js-yaml upgrade (#7124)
- Upgrade postcss fix high transitive (#7125)
- *(webapp)* Improve usability of billing emails input field (#7134)

## Managed 1.6.5 (0.71.4)

## Managed Nango 1.6.5 (application 0.71.4)

- **Released:** 2026-08-12
- **Docker image:** `nangohq/nango:managed-1.6.5-0.71.4-b6a11be5e83e48fc2f4758685ce2d6a12d817fad`
- **Pin CLI to:** `0.71.4`
- **Compare:** https://github.com/NangoHQ/nango/compare/3d6911d08f7a24b2b34dc70b38c4fc2ff043fbfc...b6a11be5e83e48fc2f4758685ce2d6a12d817fad
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(integrations)* Add support for hibob-oauth (#7041)
- Add account API key CRUD endpoints (#7024)
- *(integrations)* Add support for Garmin OAuth2 (#7037)
- *(email)* Add generic HTTP API email provider (#7029)
- *(webapp)* Redesign billing plans section (#6907)
- *(cli)* Deploy functions (#7068)
- *(webapp)* Redesign team settings page (#6904)
- *(providers)* Add luma-v2 targeting public-api.luma.com (#6922)
- *(integrations)* Add support for okta api key (#7073)
- *(integrations)* Add support for yokoy (#7077)
- *(environment)* Rotate webhook signing key (NAN-6550) (#7082)
- *(integrations)* Add support for viewpoint-vista (#7048)
- *(integrations)* Add support for revolut-business (#7075)
- *(mcp)* Add connections list tool (#7057)
- *(logs)* Add a log retention env var (#7045)
- *(mcp)* Add integrations delete tool (#7032)

### Changed

- Link self-hosting guide from Management MCP changelog entry (#7071)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/532a3d96454bc35ff996a64f6f45125ba56d2f21 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/0cc2143233d4b3fd62ff86e368acdf6a3725ff95 by Victor Lang'at

### Fixed

- *(webapp)* Disallow crawling of app.nango.dev in robots.txt (#7074)
- *(cli)* Derive integrationId from path root (#7072)

## [v0.71.4] - 2026-08-10

### Added

- *(integrations)* Add ServiceNow JWT bearer authentication (#7010)
- Implement functions bundle deployment endpoint (#7035)
- *(integrations)* Add regional instance support for NinjaOne RMM providers (#7039)
- Account-level api keys (#6991)
- Add integration-scoped functions deployment (#7055)
- *(mcp)* Add integrations update tool (#7051)
- *(integrations)* Support Devin v3 credentials (#7065)
- *(integrations)* Add support for redo (#7049)
- *(integrations)* Add support for facebook-system-user (#7040)
- *(integrations)* Add support for shopline (#7047)

### Changed

- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f499bb42bb87451f2122b967d5f824d36cced994 by Victor Lang'at
- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3196dff2ef40f31ac60e25413350b7ad8d698660 by Victor Lang'at
- *(authz)* Make environment optional on request locals (#6971)

### Fixed

- *(auth)* Surface underlying provider errors for JWT and TwoStep auth failures (#6803)
- Vulns (#7050)
- Retain peer dependencies in docker images  (#7059)
- Fix docs for zendesk (#7058)
- *(webapp)* Keep PHI out of PostHog and Sentry (#6906)

## Managed 1.6.4 (0.71.3)

## Managed Nango 1.6.4 (application 0.71.3)

- **Released:** 2026-08-07
- **Docker image:** `nangohq/nango:managed-1.6.4-0.71.3-3d6911d08f7a24b2b34dc70b38c4fc2ff043fbfc`
- **Pin CLI to:** `0.71.3`
- **Compare:** https://github.com/NangoHQ/nango/compare/d9783cb2211312d673184aff9974df9535972863...3d6911d08f7a24b2b34dc70b38c4fc2ff043fbfc
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(audit)* Address review comments on the audit consumer (#6958)
- *(scheduler)* Per-environment concurrency overrides (#6877)
- *(audit)* Filter the audit log by resource, and by resource + action (#6979)
- Add July 2026 changelog updates: (#7006)
- *(server)* Allow custom properties on integration import (#7008)
- *(auth)* Add account discovery during new-user onboarding (#6879)
- *(auth)* Add account invitation requests during onboarding (#6918)
- *(integrations)* Improve google ads to request for developer token (#7014)
- *(integrations)* Add support for myob (#7018)
- *(integrations)* Add support for trustpilot (#7009)
- *(integrations)* Add support for ukg-pro-wfm-ropc (#7015)
- *(integrations)* Add support for lovable-mcp (#7019)
- *(integrations)* Add support for holded-v2 (#7020)
- *(integrations)* Add support for back-market (#7021)
- *(integrations)* Add support for threads (#7028)
- *(byoc)* Add charm-sandbox environment (#7038)
- *(integrations)* Add support for judge.me (#7031)
- *(mcp)* Add integrations get tool (#7001)
- *(integrations)* Add support for onshape (#7022)
- *(function)* Add /functions/deployments/bundle endpoint (#7005)
- *(mcp)* Add integrations create tool (#7002)

### Changed

- *(shared)* Move functions/ to functions/legacy (#6982)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6c77111c22306d9feb17ff561ba7b1ff9aacfb7c by Victor Lang'at
- *(audit)* Drop the unused usage.audit_trail_events table (NAN-6339) (#6975)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/c6a74f000da0a1625f510286b3ccef9233d9a5ac by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/35d1dc0a809b30faaf0189df8ee10620ace041f7 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e56efb872d4a74a613f3d9bfca59577394befe18 by Victor Lang'at
- Move flow service to server (#7012)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/368202d36f41223ca651a0fb976827c94e95dc6d by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ce404c60b6fa72e164d6097625b9dd75c510e039 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b9a32621f1be73f457e161122a60eb660cc83ebd by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/29d132cb8959b325c7afe972219f257d5c7b778c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3b75b285cb609b197f6160ca5710ad97a1202849 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/2318910751f936093662bbe5567599ec5602c4dd by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/9dc258de80bab7c6799f787d395d8652095513aa by Victor Lang'at
- *(mcp)* Rename control plane server to management (#7013)

### Fixed

- Upgrade packages (#6997)
- *(function)* Align types between types package and runner-sdk (#6964)
- Ipv6 classification (#6998)
- *(scheduler)* Give each suite its own db schema and close its pool (NAN-6500) (#6988)
- /connect/telemetry fails if timestamp is outside of allowed range (#6999)
- *(webapp)* Don't prefill overrideAuthParams with integration defaults on connection create (#6990)
- *(proxy)* Drop unresolved headers (#7027)
- Upgrade dd-trace (#6905)
- Unidic upgrade for vulns (#7044)
- *(logs)* Upgrade otel packages (#7046)

## [v0.71.3] - 2026-08-03

### Added

- *(integrations)* Add support for zoom-cc (#6953)
- *(mcp)* Add integrations list tool (#6977)
- *(integrations)* Add support for pipelinecrm (#6981)
- *(impersonation)* Require the admin's own MFA to impersonate (NAN-6481) (#6961)

### Changed

- *(ci)* Amortize module imports in integration tests (NAN-6488) (#6970)
- Wrap long endpoint URLs in the API playground (#6986)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6d2fa6b9f2a74c9b8f6a6c9519e8ce47b481a621 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5d6901b2138d64c3c233684dcd65f3dfb2472dfc by Victor Lang'at
- *(audit)* Derive the audit event vocabulary from one table (#6983)
- Db migrations and types for functions configs (#6960)
- Update version in manifest

### Fixed

- *(audit)* Allow account 0 to record audit events (#6978)

## Managed 1.6.3 (0.71.2)

## Managed Nango 1.6.3 (application 0.71.2)

- **Released:** 2026-08-03
- **Docker image:** `nangohq/nango:managed-1.6.3-0.71.2-d9783cb2211312d673184aff9974df9535972863`
- **Pin CLI to:** `0.71.2`
- **Compare:** https://github.com/NangoHQ/nango/compare/fad81b1da5b2495db013a2b6cd922049ed57da2c...d9783cb2211312d673184aff9974df9535972863
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(audit)* Dedicated audit ClickHouse database + own migration (NAN-6339) (#6934)
- Add function deployment status endpoint (#6729)
- *(audit)* Batch the consumer's writes and stop dropping events on failure (#6954)
- *(audit)* Record MFA events (enroll/enable/disable/recovery/verify) (#6947)
- *(integrations)* Add support for syncore (#6939)
- *(audit)* Record billing payment-method add/remove (#6948)
- *(audit)* Read and write audit events from the dedicated audit database (NAN-6339) (#6962)
- *(integrations)* Add support for transporeon-oauth2-cc (#6957)
- *(audit)* Record sync command actions (pause/start/trigger/cancel) (#6945)
- *(integrations)* Refractor apple-app-store and use JWT method instead (#6955)
- *(integrations)* Add support for ingenious-build (#6969)
- *(audit)* Record create/deploy/invite/pause-start lifecycle events (#6943)
- *(integrations)* Add support for basin (#6940)
- *(audit)* Record authentication events (login/logout/signup/reset + SSO) (#6946)
- *(mtls)* Add mtls support to internal service-to-service calls (#6928)

### Changed

- Update version in manifest
- Update external contribution guidelines (#6944)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ba00535c07b7f280eb875b6ef96f01a4cfdc48a2 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/970a26b1ab2803e7ebdb36e1278111ad674945eb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b5294dc1c7122280307eeefce3553bc784dd5eee by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a590347c4411172566fe0e96b167b78df03cbdea by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/632189a4f732190f6d89f6e5a7ceee9164cfb036 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/dc394ae65eb9ca7b9a465fa821a22f64ecfe7fc1 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/8b302c3a8af5819009448c77032adfbc17376ce6 by Victor Lang'at

### Fixed

- *(mfa)* Enforce MFA on managed auth logins (NAN-6463) (#6950)
- *(providers)* Allow dots in contentstack api domain (#6913)
- *(audit)* Move audit middleware logic to unit tests, one integration suite for live-stack cases (#6952)
- *(server)* Fix token refresh race condition (#6941)
- *(webhooks)* Fix jira webhook routing (#6967)
- *(auth)* Require explicit email confirmation before sign-in (#6899)
- *(server)* Remove credential scope from connect sessions (#6959)

## Managed 1.6.2 (0.71.2)

## Managed Nango 1.6.2 (application 0.71.2)

- **Released:** 2026-07-29
- **Docker image:** `nangohq/nango:managed-1.6.2-0.71.2-fad81b1da5b2495db013a2b6cd922049ed57da2c`
- **Pin CLI to:** `0.71.2`
- **Compare:** https://github.com/NangoHQ/nango/compare/6c4a526ed4928b2fb815f9933b502722230f50e6...fad81b1da5b2495db013a2b6cd922049ed57da2c
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webhooks)* Add GitLab webhook routing (#6683)
- *(webapp)* Redesign 2FA setup screens (#6878)
- *(types)* Enforce audit coverage via an endpoint opt-out policy (NAN-6269) (#6916)
- *(integrations)* Add Agentcard (#6795)
- *(scheduler)* Add unique index to ensure one active task per schedule (#6925)
- *(audit)* Record control-plane mutation events, type-locked to endpoint policy (NAN-6444) (#6917)
- *(integrations)* Add support for adoxx-cc (#6936)
- Add self-hosted Management MCP setup (#6937)
- *(audit)* Publish audit events to pub/sub, consume in metering (NAN-6271) (#6783)
- *(providers)* Allow servicenow to use hostname instead of subdomain (#6938)
- Add changelog entry for two-factor authentication (CON-159) (#6949)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3a6f60f05c332c72e22dcf038f09df4e241b77a9 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a1dbfcff9c17557bc97dbbab4e41e4d2aefc615b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b44cd16977f438bfe630631626d042778ae8b02c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/2dec270fdaea56dfb8efd17d6bff91124f1cf89e by Victor Lang'at
- *(scheduler)* Count queue sizes with count(*) so the index answers it alone (#6923)
- *(orch)* Don't wait for locked schedule when scheduling immediate task (#6926)
- *(mcp)* Rename management server env var (#6935)

### Fixed

- *(mcp-generic)* Omit empty client_secret on token refresh (#6921)
- Js-yaml upgrade (#6903)
- *(providers)* Allow region interpolation in the Ironclad authorization url (#6930)
- *(security)* Oauth token outbound validation (#6672)
- *(docs)* Stop changelog Update blocks clipping off the left edge (NAN-6464) (#6942)

## Managed 1.6.1 (0.71.2)

## Managed Nango 1.6.1 (application 0.71.2)

- **Released:** 2026-07-26
- **Docker image:** `nangohq/nango:managed-1.6.1-0.71.2-6c4a526ed4928b2fb815f9933b502722230f50e6`
- **Pin CLI to:** `0.71.2`
- **Compare:** https://github.com/NangoHQ/nango/compare/b27d0d367c67d1bf61f11a01c5e57fd550778b05...6c4a526ed4928b2fb815f9933b502722230f50e6
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(auth)* Gate sign-in behind MFA (#6822)
- *(auth)* Add MFA sign-in challenge (#6832)
- *(audit)* RBAC-gated account-scoped audit trail read API (NAN-6343) (#6831)
- *(design-system)* Validate removed tokens against webapp usages (#6816)
- *(auth)* Shadow cache to measure auth cache hit ratio (#6858)
- *(webapp)* Reach usage breakdown values and keep long legends readable (#6841)
- *(integrations)* Add support for optum-real (#6852)
- *(webapp)* Stack billing page sections, drop tabs (#6847)
- *(webapp)* Bring collapsible usage table to paid plans (#6861)
- *(integrations)* Add support for dentally (#6862)
- *(design-system)* Lift Badge into design system (#6842)
- *(auth)* Cache the persist auth context in-process (#6886)
- *(integrations)* Add support for semble (#6860)
- *(integrations)* Add support for ergo (#6863)
- *(integrations)* Add support for dynamic-mockups (#6866)
- *(account)* Add same-domain-account search (#6827)
- *(integrations)* Add support for hubstaff (#6865)
- *(design-system)* Lift Dialog into design system NAN-6410 (#6869)
- *(design-system)* Add AlertDialog, replace ConfirmDialog (#6892)
- *(webapp)* Audit-log dashboard UI (NAN-6343) (#6859)
- *(integrations)* Add support for youcanbook-me-public (#6895)
- *(integrations)* Add support for resova (#6868)
- *(integrations)* Add support for spendesk (#6890)
- *(integrations)* Add support for glean (#6897)
- *(auth)* Show per-member 2FA status on team settings (#6894)
- *(integrations)* Add support for chatgpt-enterprise (#6896)
- *(connect-ui)* Honor custom server websockets path (#6891)

### Changed

- *(utils)* Remove Sentry integration from Node services (#6864)
- *(scripts)* Move dependency to devDependency (#6875)
- *(auth)* Remove the persist-light-auth-context rollout flag (#6888)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/9b3060a68b605d7940d3352140d4c523234a05bf by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/995baa9a38663109844a497e5faee3c5ae27e35f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/2ab623142ac23407437dfd3776e4bede3177990b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7f6526743a2f8332c4ce0cf9dff4a4c56854f548 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/02bcd91761dfb6682dc72d84bd0199e1f6e50f03 by Victor Lang'at

### Fixed

- *(billing)* Log Orb ingest failure cause (#6856)
- *(webhooks)* Skip HubSpot import events before dispatch (#6857)
- *(connect-ui)* Show error instead of infinite loading spinner (#6777)
- *(records)* Stop autoPruningCandidate test flaking in CI (#6848)
- *(orchestrator)* Change NOTIFY to use parameterized pg_notify (#6867)
- *(in-app)* Fix the brand bg color to respect the app theme (#6837)
- Vulns (#6874)
- *(scripts)* Fix package file (#6889)
- *(webapp)* Match paid usage header to free plan (#6885)
- *(proxy)* Forward provider response headers on the buffered path (#6701)
- Orb ingestion errors on duplicate idempotency keys (#6900)
- *(providers)* Cursor-admin api key description says Greenhouse (#6911)

## [v0.71.2] - 2026-07-21

### Added

- *(webapp)* Free usage charts as progress toward the cap (#6790)
- *(design-system)* Lift Card into design system (#6835)
- *(webapp)* Alert Free accounts nearing or hitting plan limits (#6791)
- *(webhooks)* Add jobber webhook support (#6836)
- *(webapp)* Edit connection webhook URL override in Settings (#6740)

### Changed

- Flatten management mcp reference (#6843)
- *(billing)* Retire the parity-phase getUsage source toggle (#6764)
- *(jobs)* Log underlying cause of 'runner unable to execute' error (#6851)
- *(scheduler)* Avoid unnecessary db roundtrip on task retirement (#6810)

### Fixed

- *(server)* Stop proxy integration test hitting real GitHub API (#6844)
- *(providers/zendesk)* Request expires_in so tokens can be refreshed (#6763)
- *(server/node-sdk/runner-sdk)* Fix types at API boundary to account for dates in credentials being serialized to strings (#6820)

## [v0.71.1] - 2026-07-20

### Changed

- Update version in manifest

### Fixed

- *(server)* Route connectwise-psa webhooks by ProductInstanceId (#6808)
- *(docs)* Raise Ask AI panel above the navbar (#6838)

## Managed 1.6.0 (0.71.0)

## Managed Nango 1.6.0 (application 0.71.0)

- **Released:** 2026-07-20
- **Docker image:** `nangohq/nango:managed-1.6.0-0.71.0-b27d0d367c67d1bf61f11a01c5e57fd550778b05`
- **Pin CLI to:** `0.71.0`
- **Compare:** https://github.com/NangoHQ/nango/compare/27ea2b528e7df47b99d9250c6880753c81cd1e7d...b27d0d367c67d1bf61f11a01c5e57fd550778b05
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(providers)* Add Auvik us6 region (#6707)
- *(design-system)* Add focus ring to input fields (#6698)
- *(design-system)* Reduce default form-control height to 32px (#6699)
- *(mcp)* Register control-plane MCP server (#6659)
- *(function)* Tweak function input and concurrency (#6697)
- Add HTTP API reference pages for function endpoints (#6526)
- *(mcp)* Support client ID metadata documents (CIMD) (#6708)
- *(cli)* Expose createFunction as an experimental feature (#6714)
- Reach any value when filtering usage, not just top-N (NAN-6038) (#6674)
- *(design-system)* Apply AA-safe primary button color (#6724)
- *(webapp)* Token editor dev tool for live design token tweaking (#6442)
- *(webapp)* Redesign profile settings with label-left layout (#6671)
- Add proxy DTO metering (#6709)
- *(connect-ui)* Add Japanese (ja) language support (#6721)
- *(integrations)* Add support for google-health (#6650)
- *(integrations)* Add support for aspire (#6712)
- *(webhooks)* Add support for google-drive webhooks (#6719)
- Enable `can_override_docs_connect_url` for Growth+ (#6730)
- *(node-client)* Add function and provider template methods (#6732)
- *(providers)* Add proxy base_url to notion-mcp (#6716)
- *(integrations)* Add support for ninety-io (#6718)
- *(metering)* Track written row count per S3 export file (#6736)
- *(integrations)* Add support for haileyhr (#6735)
- *(mcp)* Add logs list operations tool (#6660)
- *(integrations)* Add support for dope-security (#6731)
- *(mcp)* Add logs get operation tool (#6661)
- *(integrations)* Add support for microsoft-dynamics-365-finance-and-operations (#6726)
- *(integrations)* Add support for humaans-io (#6727)
- *(integrations)* Add support for google-calendar-mcp (#6728)
- *(integrations)* Add support for veed (#6744)
- *(connections)* Allow patching connection-level webhook_url (#6739)
- Ingest Data Transfer into Orb (#6758)
- *(webhooks)* Update google drive webhook script (#6759)
- *(telemetry)* Implement CLI usage tracking (#6691)
- *(integrations)* Add support for autosana (#6750)
- *(integrations)* Add support for trading-economics (#6746)
- *(integrations)* Add support for leapsome (#6747)
- *(integrations)* Add support for workramp (#6749)
- *(integrations)* Add support for sanity-mcp (#6748)
- *(integrations)* Add support for timetastic (#6745)
- *(integrations)* Add support for mandrill (#6743)
- *(cli)* Minimal support for function compilation (#6738)
- *(integrations)* Add support for ids-fulfillment (#6737)
- *(billing)* Time-based cutover for HTTP↔S3 event-name suffix swap (#6705)
- *(integrations)* Add support for phrase (#6766)
- *(integrations)* Add support for zero (#6767)
- *(integrarions)* Add support for embat (#6768)
- *(integrations)* Add support for workato (#6771)
- *(integrations)* Add support for n8n (#6772)
- *(integrations)* Add support for millionverifier (#6769)
- *(integrations)* Add support for ConnectSecure (#6720)
- *(audit)* Audit-log emit boundary + route wiring (NAN-6214) (#6755)
- *(webapp)* Add analytics events to the usage page (#6761)
- *(integrations)* Add support for tripletex (#6300)
- Add MCP Auth guide (#6785)
- *(integrations)* Add support for baserow (#6781)
- *(providers)* Add an optional hostname to salesforce sandbox (#6797)
- *(webapp)* Edit connection metadata and tags via UI (#6760)
- *(providers)* Add apple app store connect ui configurations (#6780)
- *(audit)* Add audit_trail_events ClickHouse table (NAN-6272) (#6787)
- *(integrations)* Add support for sage-member (#6717)
- *(integrations)* Allow client credentials for sage intacct to be defined at integration level (#6751)
- Add Control Plane MCP reference (#6757)
- *(integrations)* Add support for odoo-api-key (#6807)
- *(auth)* Add MFA factor storage (#6792)
- *(integrations)* Add support for datadog oauth (#6796)
- *(integrations)* Add support for postscript (#6804)
- *(audit)* Write audit events directly to ClickHouse (fire-and-forget) (NAN-6272) (#6805)
- *(integrations)* Add support for cerby (#6793)
- *(integrations)* Add support for veeva-vault-oauth (#6806)
- *(event-script)* Gate hubspot pre-connection-deletion script with metadata (#6817)
- *(auth)* Add MFA enrollment settings (#6814)
- *(webapp)* Show Free-plan usage against plan limits (#6789)
- Add changelog entries for Management MCP, editable tags/metadata, CIMD (#6821)
- *(integrations)* Add support for pave (#6818)
- *(integrations)* Add support for microsoft services using the client credentials flow (#6819)
- *(ratelimit)* Add 10xl and 12xl rate limit tiers (#6824)
- Move webhook_url override to top-level field. (#6778)
- *(integrations)* Add support for vantage-apparel (#6833)
- *(connect-ui)* Non-root base path via relative base + runtime basepath (#6802)

### Changed

- Update version in manifest
- *(server)* Move shared function handlers to better file paths (#6681)
- Document connection-level webhook_url override (#6715)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3f2aa29f5d80b956341e40cde582082f85dad975 by Victor Lang'at
- Prefer shared-env collaboration for multiplayer DX (#6733)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/96a64bc741e6d89be704fe77d1980b7835378806 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/8bcb3b5d785ccce13ad7ca758d333b374598d45e by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f84d5741abf2a9764abd6e550dbf49bc31ca0d66 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e286bd20c5795f9e8bfbc9053e65669941c08c89 by Victor Lang'at
- Improve google drive webhook docs (#6756)
- *(webapp)* Remove unused usageBreakdown feature flag (#6752)
- Speed up deploys (#6770)
- *(scripts)* Realistic ClickHouse seed data and quieter output (#6676)
- Monitor how many tasks are dequeued (#6774)
- *(orch)* Skip dequeue query when group lock is contended (#6782)
- *(webapp)* Route all analytics events through typed catalog (#6784)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6bf416ff5f996743c3ea37417a13e2f73cddb8ff by Marcin Dobrowolski
- *(design-system)* Sync generated tokens (#6788)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/735d210f2cada157d547c91fb0148ce2f3337cb6 by Victor Lang'at
- *(persist)* Fetch a narrow internal auth context on the auth hot path (#6800)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4af2d561b9a865c9dd54444ff26e716cb5c85bb4 by Tom Shani
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/340f5d4b7b000df98b5a6bb3bbf16342591c0c81 by Tom Shani
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ab39aef4d18b793d39b23abdfb2ccf5f48c44fd1 by Tom Shani
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/84f3261851bbd0b79eedc7f4e3aa77e9a4bbec1e by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/50b570fb794db91b7da47aacf69c836064c0fdcb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1320cb5d64a30806a75a683f5c89fd072b9a7ae5 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/65022fdb88cc3c5062f890e7ee3f89afd8d2d055 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b45c06cc663db0f874402211ab12e73d49f30f72 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6e77382c74b911ab142aa8e8af87ea997b78ae8f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a7f2621ce4a1ed2e4a22936ffabfd1ed96fa4aeb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fddb32f77b2f08fe8fdccfe28b9c2089222e86db by Victor Lang'at
- Update API count from 800+ to 900+ (#6834)

### Fixed

- *(csp)* Allow Plain widget and disable Zod JIT in Connect UI (#6696)
- *(webapp)* Make usage chart legend series clearly toggleable (#6670)
- *(providers)* Loosen acumatica instance url pattern (#6703)
- *(webapp)* Preserve query string when switching hash-navigated tabs (#6686)
- *(webapp)* Fix focus rings in sidebar navigation (#6711)
- *(webapp)* Enable auth submit buttons by default (#6722)
- *(server)* Allow github raw templates in helmet CSP (#6725)
- *(auth)* Surface provider error details for client credentials and microsoft admin token failures (#6723)
- *(providers)* Loosen sap-business-1 service layer url pattern (#6734)
- *(webapp)* Persist records docs banner dismissal (#6754)
- *(server)* Allow data: fonts and blob: images in CSP (#6742)
- *(webapp)* Size Logs table columns to fit their content (#6753)
- *(server)* Bump OAuth2 CC token max length (#6798)
- *(providers)* Callrail apiKey pattern accepts ctrk_ prefix longer hex (#6776)
- Docs generation for functions (#6799)
- *(auth)* Make user emails case-insensitive (#6762)

## Managed 1.5.12 (0.70.9)

## Managed Nango 1.5.12 (application 0.70.9)

- **Released:** 2026-07-06
- **Docker image:** `nangohq/nango:managed-1.5.12-0.70.9-27ea2b528e7df47b99d9250c6880753c81cd1e7d`
- **Pin CLI to:** `0.70.9`
- **Compare:** https://github.com/NangoHQ/nango/compare/aae30d044d7e229807d51a3957c212f3fb689e1a...27ea2b528e7df47b99d9250c6880753c81cd1e7d
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(integrations)* Add support for ahrefs (#6610)
- *(in-app)* Change in app launcher icon (#6607)
- *(integrations)* Add support for microsoft-oauth2-cc-cert (#6609)
- *(integrations)* Add support for surecontact (#6623)
- *(integrations)* Add suppport for jamie (#6620)
- *(integrations)* Add support for dialpad-wfm (#6619)
- *(integrations)* Add support for acumatica (#6617)
- *(integrations)* Add support for sage-intacct-cc (#6616)
- Add SAP Ariba Integration (#5749)
- *(connect-ui)* Add a11y regression test suite (#6584)
- *(egress)* Introduce egress package (#6615)
- Add new Orb plans (#6635)
- Drill into usage breakdowns by filtering to a single value (NAN-5874) (#6528)
- Add changelog entry for usage breakdowns (#6658)
- *(server)* Meter GET /records egress bytes (#6648)
- *(docs)* Enhance integration configuration details for private API (#6656)
- Add custom timeouts per service (#6667)
- *(design-system)* Align input and button sizing on one scale (#6645)
- *(design-system)* Add Field and Label, migrate webapp form fields (#6657)
- *(design-system)* Add interactive border token (#6655)
- Add CreateFunction definition (#6664)
- *(server/webapp)* Show function code (#6679)
- Connection-level webhook url override (#6639)
- *(providers)* Regenerate assertion for two_step only when the assertion expires (#6680)
- *(providers)* Add subdomain connection config for youcanbook-me (#6684)
- Add June 2026 changelog entries (#6685)
- *(ratelimit)* Add new rate limits (#6689)
- *(integrations)* Add support for everflow (#6687)
- *(integrations)* Add support for konnektive (#6688)
- *(metering)* Cron to monitor billing-events S3 DLQ bucket (#6668)
- *(analytics)* Implement tracking for playground interactions (#6682)
- Integrate feature flags across services (#6677)
- *(webhooks)* Gate webhook-triggered sync completion webhooks behind a flag (#6665)

### Changed

- *(usage)* Remove dead code from the capping migration (#6624)
- *(traces)* Increase retention priority for jobs start action if flag enabled (#6631)
- Drop @tabler/icons-react from webapp and connect-ui (#6643)
- *(webapp)* Migrate to design-system Input/InputGroup (#6636)
- *(scripts)* Seed local ClickHouse usage data for local dev (#6642)
- Default export_runner_telemetry to true (#6652)
- *(webapp)* Adopt design-system Field for ad-hoc form labels (#6663)
- *(server)* Bump oauth2 access token length limit (#6675)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/63357f08c2f2e852fab7ee76e4813cfbbe095516 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1c779d9cb3140896c4952dae746a272142dab9bb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b68a648d92896fd7727e1742ee60c487e10c0db4 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/bd9cc270bad86e619255850409b10e535742b87b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a944f32eb84c2acc9bfdafdf7ff654fca1320792 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/9c9eb53b49bdadd8fbc9b9741ed45459b939fba2 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4df475df0b1dcdffcd61469c28ab3e4494249b6f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4d77f2a022f3e3a3d76329a582ef4b6d9171f291 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5d09872a4ef04a3f7ec8f694e12791f985426b9b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3d8319aa74f8ad0bbe47402878c97b1acabc0c87 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/03a6b7ac35c9350f804077373a1578d2fa89ae00 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/99b5a6fa95c72ccfb9b5103a90d073d70cab8f60 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f6486c725c5a62803a2d63c82d2a2d7c3a10abe2 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/20fc4ccfd1c49c426ea4d859693b1092ddf01469 by Victor Lang'at
- Use checkpoints in sync webhooks to check for sync type (#6629)

### Fixed

- *(webapp)* Coerce authorization params to strings on form reset (#6626)
- *(connect-ui)* Resolve WCAG 2.2 AA violations (#6589)
- *(ci)* Skip CLI publish/verify on fork PRs (#6627)
- Fix microsoft-oauth2-cc-cert docs (#6634)
- *(scripts)* Fix low vulnerability (#6625)
- Correct public function endpoint scopes (#6578)
- *(runner)* Move redis requirements to persist (#6566)
- *(webapp)* Align dashboard page layouts (#6637)
- *(cli,dashboard)* Resolve symlinked integrations in pull and github links (#6632)
- *(webapp)* Connections integration column shows provider instead of integration unique_key (#6633)
- *(providers)* Fix Tanium verification URL and hostname (#6644)
- *(webapp)* Cap billing content width on wide screens (#6653)
- *(providers)* Use case-sensitive /Login endpoint for sap-business-one (#6638)
- *(egress)* Outbound url policy across all customer-controlled egress paths (#6646)
- Schedule plan change callout message (#6666)
- *(providers)* ModMed API Key incorrectly expects UUID formatting (#6678)
- *(providers)* Update RecruitCRM API base URL and endpoints (#6662)
- *(runner)* Harden function access (#6669)
- *(connect-ui)* Preserve apiURL base path in API and WebSocket requests (#6695)

## [v0.70.9] - 2026-06-23

### Added

- Public endpoint to deploy function template (#6558)
- *(integrations)* Add support for ironclad-cc (#6585)
- *(usage)* Compose filter with breakdown (NAN-5874) (#6545)
- *(usage)* Drop the 6h CH inner cache from the capping path (#6605)

### Changed

- Update version in manifest

### Fixed

- *(metrics)* Improve traces on startAction (#6612)
- *(frontend)* Make ConnectUI.open() idempotent (#6611)

## Managed 1.5.11 (0.70.8)

## Managed Nango 1.5.11 (application 0.70.8)

- **Released:** 2026-06-23
- **Docker image:** `nangohq/nango:managed-1.5.11-0.70.8-aae30d044d7e229807d51a3957c212f3fb689e1a`
- **Pin CLI to:** `0.70.8`
- **Compare:** https://github.com/NangoHQ/nango/compare/2c0c2b7d0287b0dce3728b8ff07aa83f124e4b8d...aae30d044d7e229807d51a3957c212f3fb689e1a
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(observability)* Add nango.usage.revalidate.work span for lock-acquired path (#6586)
- *(metering)* Persist data_transfer events to CH (#6483)
- *(integrations)* Add a skip_encode config to attio-mcp (#6577)
- *(feature-flags)* Implement OAuth state cookie enforcement flag (#6533)
- Separate function catalog (#6465)
- *(integrations)* Add support for boondmanager (#6594)
- *(sync_jobs)* Backfill id_big from id (NAN-5491 Phase 3b) (#6377)
- *(integrations)* Add support for netsuite-client-credentials (#6583)
- *(sync_jobs)* Build unique index on id_big (NAN-5491 Phase 3c) (#6378)
- *(integrations)* Add support for workday-cc (#6588)
- *(sync_jobs)* Validate id_big NOT NULL (NAN-5491 Phase 3d) (#6379)
- *(sync_jobs)* Atomic PK swap from int4 id to bigint (NAN-5491 Phase 3e) (#6380)
- *(sync_jobs)* Drop legacy id_old and lift sequence to bigint (NAN-5491 Phase 3f) (#6381)

### Changed

- Update version in manifest
- *(lint)* Move import sorting to Prettier (#6582)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/9b90d563da83c22abcd518d1f6f795e865995457 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a25e1767d723dd55aa190e80a94e6a43523c8237 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/6e7f1bfa5ac51e442b459131ef28af99424204f4 by Victor Lang'at
- Make tsconfigs compatible with typescript-go (#6593)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/13b04626a556f4a2484e90b416b7c2f836bc5e23 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5746cac87f06e2c80843c02258a0e75b1b0d4926 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/c33f8fe2f97083392dbdd599671e3ce8997ca7b2 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/60c8a54ffc81b42ae2d066cdfdbd7cbbf10d3b0b by Victor Lang'at
- *(lint)* Replace ESLint with oxlint (#6604)
- Update egress-metering middleware (#6591)

### Fixed

- *(in-app)* Fix the in-app chat support button location (#6590)
- *(webapp)* Stop logs table bouncing on auto-refresh (#6592)
- *(server)* Enforce RBAC on flow read routes (#6603)
- *(vulns)* Fix high vulnerabilities (#6608)

## [v0.70.8] - 2026-06-19

## Managed 1.5.10 (0.70.7)

## Managed Nango 1.5.10 (application 0.70.7)

- **Released:** 2026-06-19
- **Docker image:** `nangohq/nango:managed-1.5.10-0.70.7-2c0c2b7d0287b0dce3728b8ff07aa83f124e4b8d`
- **Pin CLI to:** `0.70.7`
- **Compare:** https://github.com/NangoHQ/nango/compare/e81f6c2beee75409b5c78c0f4e55bfc4d643042d...2c0c2b7d0287b0dce3728b8ff07aa83f124e4b8d
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(telemetry)* Wire data transfer through pubsub (#6530)
- *(integrations)* Add support for shopvox (#6532)
- *(usage)* Flip capping source from Orb to ClickHouse via percentage rollout (#6509)
- *(support)* In app chat support (#6455)
- *(webapp)* Redesign app shell (#6543)
- *(metering)* Add usage-events subscribe env var (#6572)
- *(webapp)* Records list page (#5862)
- *(webhooks)* Add createFunction/createWebhook authoring primitive (NAN-5885) 1/n (#6447)
- Prevent overriding design-system component styles (#6504)
- *(observability)* Instrument usage-tracker call decisions and metering consumer (#6580)
- *(sandbox)* Add AgentCore deployment step in GH Actions (#6534)

### Changed

- Remove metrics section from self-hosted (#6550)
- *(runner)* Increase telemetry batching thresholds (#6551)
- *(runner)* Further increase telemetry batching thresholds (#6554)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/947ce1196c9a663e7c7cf33bc3c663c0d80fe4f5 by Victor Lang'at
- *(webapp)* Migrate to design-system Button (#6503)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/044202db3f9d7b3a65bfa6799c00b154446a45a1 by Marcin Dobrowolski
- *(tests)* Shard integration tests across 4 runners (#6568)
- *(server)* Move deletion logic out of cron folder (#6560)
- Reintroduce DT telemetry wiring over pubsub (#6557)

### Fixed

- Revert wire data transfer through pubsub (#6535)
- *(metering)* Fix incr errors due to float (#6523)
- Vulns and upgrades (#6529)
- *(providers)* Fix sap-success-factors company id pattern (#6553)
- *(read-ai)* Use correct OAuth2 authorization endpoint (#6541)
- *(sync)* Respect auto_start when reauthenticating a connection (#6544)
- *(logger)* Fix the logger formatting (#6522)
- Disclosure of account existence in password reset (#6559)
- *(providers)* Fix attio-mcp scope separator (#6570)
- *(providers)* Fix verification endpoint for reply.io (#6512)
- *(webapp)* Replace virtualized records table with plain table (#6579)
- *(vulns)* Resolve 2 highs (#6581)

## [v0.70.7] - 2026-06-16

### Added

- *(functions)* Add delete endpoint with async teardown pipeline (#6358)
- *(integrations)* Add support for youcanbook-me (#6511)
- *(webhook)* Add url deny list to webhook (#6507)
- *(integrations)* Add support for agiloft (#6506)
- *(integrations)* Add support for attio-mcp (#6510)
- *(webapp)* Add "Delete function" button (#6457)
- *(server)* Public endpoints for function management (#6472)
- Add Read.ai OAuth2 provider (#6476)
- *(utils)* Hoist webhook utils (#6450)
- *(pubsub)* Add publishBatch to transports (#6451)
- *(telemetry)* Wire data transfer through pubsub (#6452)
- Wrapped and plaintext key are mutually exclusive (#6488)
- *(design-system)* Component foundations (#6246)
- *(webapp)* Reset playground on logout (#6461)
- *(sandbox)* Add AgentCore sandbox provider (#6502)
- *(server)* Mark connections as refresh failed if validate-connection fails on reconnect (#6467)

### Changed

- Update version in manifest
- "fix(redis): harden redis usage to tolerate connection issues" (#6514)
- Remove kvstore FeatureFlags (#6513)
- *(webapp)* Multi-worktree dev via dev CORS (alt to #6473) (#6477)
- *(metering)* Remove kms dependency (#6520)
- Revert pubsub wiring for data transfer (#6525)
- "revert: "fix(redis): harden redis usage to tolerate connection issues"" (#6521)

### Fixed

- *(redis)* Harden redis usage to tolerate connection issues (#6423)
- *(node-client)* Accept webhookSigningKey, add apiKey (NAN-5980) (#6493)
- *(server)* Proxy splat url does not match query only routes (#6508)
- *(ci)* Isolate npm publish setup for trusted publishing (#6531)

## Managed 1.5.9 (0.70.6)

## Managed Nango 1.5.9 (application 0.70.6)

- **Released:** 2026-06-15
- **Docker image:** `nangohq/nango:managed-1.5.9-0.70.6-e81f6c2beee75409b5c78c0f4e55bfc4d643042d`
- **Pin CLI to:** `0.70.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/50423dd0f8986fd173d33418340b8d9bd4d2c1f4...e81f6c2beee75409b5c78c0f4e55bfc4d643042d
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(records_seen)* Drop NOT NULL on sync_job_id (NAN-5491 Phase 2e) (#6348)
- *(records_seen)* Stop writing sync_job_id (NAN-5491 Phase 2f) (#6349)
- *(records_seen)* Drop sync_job_id column (NAN-5491 Phase 2g) (#6350)
- *(integrations)* Add support for thomson-reuters-legal-tracker (#6431)
- Add generic task queue package wired into the server (#6312)
- *(webapp)* Break down billing usage by dimension (EXT-1144) (#6384)
- *(webapp)* Enable dev tools panel on staging (#6454)
- *(integrations)* Add support for a-leads (#6414)
- *(integrations)* Add support for leadfeeder (#6417)
- *(integrations)* Add support for adyntel (#6415)
- *(integrations)* Add support for diffbot (#6421)
- *(integrations)* Add support for discolike (#6422)
- *(integrations)* Add support for mattermost (#6432)
- *(integrations)* Add support for robinhood-mcp (#6439)
- *(usage)* Clickhouse capping read primitive (#6460)
- *(webapp)* Hide usage card for paid accounts (#6469)
- *(integrations)* Add support for cloudflare-mcp (#6437)
- *(webapp)* Adopt DS semantic tokens, theme-awareness and visual fixes (#6468)
- *(integrations)* Add support for tempo (#6435)
- *(webapp)* Add light mode (#6445)
- *(integration)* Add support for raindrop-mcp (#6438)
- Add @nangohq/kms package (#6471)
- *(feature-flags)* Add unleash openfeature client (#5910)
- *(usage)* Dual-write Orb + ClickHouse on the capping path with divergence telemetry (#6482)
- *(kvstore)* Support rotating IAM tokens for Redis via node-redis v… (#6441)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5d9b20de4879e0764639f67930439338ebdd0bb6 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/aadc62f465512f17413d339d6617692516d702a8 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a142bcbec0ed54c892004907fc6eabd1df388ccc by Victor Lang'at
- Raise eslint heap limit to 8GB (#6480)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/8219bca5fcdc7e55c696f0d2e2fa90a517b87272 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/347c40f847ea423c0b5ad77732fc4f4115c02302 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fc5990660e19c0cda938fa2772ddc5dfb98a6070 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3a06586d9c98f065cef26580a3742a370e58e602 by Marcin Dobrowolski
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/12b5c61cf97d453dd818d0c9438faf1cf8bd1009 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/4e43bce8ffeb974d534397804ff075f384b9cc9d by Marcin Dobrowolski
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/39e98e9805f344b16382dbb0310c50bfd31313c3 by Victor Lang'at
- *(sandbox)* Refactor the sandbox code to abstract away the provider better (#6440)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/921a3f0e15bebe3ca7a711de214d42d8b12a40d6 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e13d876d33241316aa6673214fc868d7c232862f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/ced999a9aee150f80bce36ebb3a39bf0f94fbf3c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/d7e9f43d1939a8d9a0d8416c322881de0a9b9811 by Victor Lang'at
- Changelog for light mode (#6505)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f7887dff786f62644a5ce6266a7d45fd8e17bf59 by Victor Lang'at

### Fixed

- *(sandbox)* Disable e2b background command timeout (#6436)
- *(vulns)* Update vitest version in tasks (#6453)
- *(server)* Bind Slack admin connection id to the caller (#6434)
- *(server)* Gate Slack alert admin routes with RBAC (#6433)
- *(webapp)* Prevent horizontal scroll and fix scrollbar color in logs (#6443)
- *(webapp)* De-conflict breakdown chart colors (#6459)
- Fix webhook docs (#6470)
- *(webapp)* Preserve theme and flags on logout (#6456)
- *(scheduler)* Run cancel task transition inside the transaction (#6428)
- *(providers)* Update the authorization url for twitter-v2 (#6479)
- *(orchestrator/jobs)* Surface real error on processor task span (#6474)
- *(sync_jobs)* Restore CRON_DELETE_OLD_JOBS_MAX_DAYS default to 31 (NAN-5491) (#6496)
- *(server)* Increase min password length to 12 (#6464)
- *(vulns)* Fix critical (#6498)
- *(proxy)* Harden proxy base url override config (#6458)
- *(kms)* Resolve DEK from wrapped key by default  (#6487)
- *(records)* Split records_seen entries to limit size of ids array (#6485)
- *(auth)* Invalidate other sessions on password change and reset (#6490)

## Managed 1.5.8 (0.70.6)

## Managed Nango 1.5.8 (application 0.70.6)

- **Released:** 2026-06-10
- **Docker image:** `nangohq/nango:managed-1.5.8-0.70.6-50423dd0f8986fd173d33418340b8d9bd4d2c1f4`
- **Pin CLI to:** `0.70.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/fe4a94f3ed76e2386edb41c6b7d8d5de467daf94...50423dd0f8986fd173d33418340b8d9bd4d2c1f4
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(usage)* Shadow ClickHouse against Orb for /plans/billing-usage (#6324)
- *(ci)* Add composite setup-node action with npm cache (#6177)
- *(connect-ui)* Add a dropdown to connect ui (#6180)
- *(usage)* Top-N seen-values endpoint for billing-usage filters (#6326)
- *(integrations)* Add N-able N-central support (#6333)
- *(providers)* Add a token-response-headers for TWO_STEP (#6334)
- *(usage)* Filter[<metric>]=<dim>:<value> on /plans/billing-usage (#6337)
- *(records)* Add multi-store routing to RecordsRouter (#6314)
- *(runner)* Meter uncontrolled fetch transfers (#6215)
- *(records_seen)* Add generation bigint column (NAN-5491 Phase 2a) (#6344)
- *(records_seen)* Dual-write generation + create per-partition generation index (NAN-5491 Phase 2b) (#6345)
- *(integrations)* Add support for dualentry mcp (#6339)
- *(webapp)* Add vite proxy for multi-worktree dev (#6261)
- *(webapp)* Migrate v1 Command to plain HTML, delete source (#6336)
- Add v2 SecretTextArea and migrate callsite (#6341)
- *(design-system)* Port PeriodSelector to v2 primitives (#6360)
- *(usage)* Resolve environment_id to env name on top-dimension-values (#6389)
- *(webapp)* Migrate v1 MultiSelect to v2 in Logs (#6361)
- *(integrations)* Add support for chatarmin (#6374)
- *(runner)* Track persist-bound records/logs calls (#6291)
- *(integrations)* Add Private API Key (Generic) integration support (#6386)
- *(server)* Track API egress bytes (#6331)
- *(integrations)* Add support for walmart (#6392)
- *(oauth)* Enrich missing-state-cookie metric to debug impacted users (#6395)
- *(records_seen)* Backfill generation from sync_job_id (NAN-5491 Phase 2c) (#6346)
- *(records_seen)* Switch deleteOutdatedRecords reads to generation (NAN-5491 Phase 2d) (#6347)
- *(integrations)* Add support for swoogo (#6257)
- *(sync_jobs)* Shrink retention + add id_big shadow column (NAN-5491 Phase 3a) (#6376)
- *(records)* Route to secondary store based on plan (#6363)
- *(scheduler)* Add at() for one-shot deferred tasks (#6309)
- *(usage)* Server-side rollout flags for routing billing-usage to ClickHouse (#6405)
- Make function deployments async (#6404)
- *(webapp)* Show dev tools panel for Nango admins in production (#6418)
- Add AWS SigV4 proxy integration (#5041)

### Changed

- Serialize deploys per service and stage (#6320)
- Update version in manifest
- *(server)* Upload js and ts file to S3 in parallel during function deploy (#6329)
- Self-hosted docs update (#6328)
- Automate Slack deploy notifications to #deploys (#6316)
- Report e2b running sandboxes (#6317)
- *(webapp)* Migrate v1 components with API-different v2 counterparts (#6322)
- *(test)* Mock httpCall to fix flaky request tests (#6351)
- *(test)* Mock fetch in loggedFetch unit tests to eliminate flakiness (#6311)
- *(webapp)* Replace v1 Info pattern with v2 Alert (#6362)
- *(server)* Skip unchanged function upload during deployment (#6330)
- *(webapp)* Move GoogleButton to components-v2/patterns (#6342)
- *(webapp)* Migrate v1 TagsInput to v2 ScopesInput (#6338)
- *(webapp)* Migrate v1 Drawer (vaul) to v2 Sheet (#6340)
- *(webapp)* Replace v1 SimpleTooltip with v2 ConditionalTooltip (#6357)
- Remove experimental /remote-function endpoints (#6390)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/019b38242ea5aeb460ffd521803de3a5be5a07fb by Victor Lang'at
- *(webapp)* Delete unused v1 source files and Storybook stories (NAN-5846) (#6373)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f4c2756a54def06da0125208df33802d51faafce by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/de84a228849ae165e23d735553e6ef04231badcd by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b06c1368cb3f2e23d482f0e0f1edcb1e5e089115 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7e09dda896536c3f8e9d33d5e8dba30f672974d5 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/0c60f7541c1e553d2effa2205b797da72587983b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/5aae537fef342a311c8ebc648df91d18443efcaa by Victor Lang'at
- *(webapp)* Remove redundant UI library dependencies (#6399)
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e88a651c9ff39dc50602e8cfd6042c106c4560da by Victor Lang'at
- *(scheduler)* Move backpressure monitoring to orchestrator (#6297)
- *(records)* Decrypt records with bounded concurrency in getRecords (#6407)

### Fixed

- *(webhook)* Bypass integration level webhook signing for Folk (#6343)
- *(tests)* Set hookTimeout to match testTimeout in integration config (#6366)
- *(server)* Preserve `token_response_metadata` fields when processing connection config overrides (#6359)
- *(server)* Fix token refresh for slack (#6293)
- *(providers)* Deprecate okta-cc subdomain in favor of hostname (#6385)
- Add missing index on api_secrets (hashed) (#6387)
- *(deploy)* Always upload files for new functions regardless of checkIfChanged result (#6398)
- End user deletion timeouts (#6409)
- *(runner)* Retry httpFetch on UND_ERR_SOCKET and HTTP 5xx/429 (#6410)
- *(invite)* Send login link to existing users instead of signup link (#6406)
- *(usage)* Resolve environment_id to env name in /plans/billing-usage breakdown (#6413)
- *(runner)* UND_ERR_SOCKET retries skipped (#6424)
- *(server)* Function deploy skips for changed dependencies (#6411)
- *(providers)* Fix followupboss token request (#6403)
- *(vulns)* Removed webflow-api and npm audit fix (#6430)

## Managed 1.5.7 (0.70.6)

## Managed Nango 1.5.7 (application 0.70.6)

- **Released:** 2026-06-02
- **Docker image:** `nangohq/nango:managed-1.5.7-0.70.6-fe4a94f3ed76e2386edb41c6b7d8d5de467daf94`
- **Pin CLI to:** `0.70.6`
- **Compare:** https://github.com/NangoHQ/nango/compare/9a9883712fd634fa4b4b5b5d24d8c2ab5c7ef579...fe4a94f3ed76e2386edb41c6b7d8d5de467daf94
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(webapp)* Migrate v1 components to v2 callsites (#6295)
- *(usage)* CH-backed /plans/billing-usage (dev-gated, foundations for shadowing) (#6286)
- *(logs)* Add OpenSearch backend selectable via NANGO_LOGS_PROVIDER (#5873)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/1c09156b2b26d30d0d31ce23539eeb9031e82f3f by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/cfa631a0e262d973fce64e0503c5f903a3825682 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/c2133954cc54ad67499cdb545834b5b522793cc1 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3a8d398c33213da93e57325747c8ba3cde81024c by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/450bee7fe4ee9376189b879ad3dfdfcefb558aed by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/2583beddda94ad6649fc453fbfe1118c27b76457 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/b51ecb75d2cdc54158080b9427678d6bcf9222eb by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/40b3b22fc790ab63efae50ceb6526e4675af3635 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/fbf962861f88773422b1ef1694c11eb663b30eec by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/f7d1ebfac4dffa564418a8d9bd22d0968e86137b by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/3f46f7b322d593884f478c6bba25c5416776cbca by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/a4e2b4075b68a751a927ac5233ee5440e08df1ad by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/e62766772c12c994678723bf6853931bd1609ab8 by Victor Lang'at
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/7bc150ab26710bee1e85ad065e9bbf7f8b6a6907 by Victor Lang'at
- Changelog for agent-led onboarding, JIT APIs (#6313)

### Fixed

- Vitest upgrade (#6315)

## [v0.70.6] - 2026-06-01

### Added

- Add non-technical links to llms.txt (#6310)
- *(webapp)* Allow local dashboard dev server to connect to remote API (#6303)

### Fixed

- *(webapp)* Update enterprise contact link to /demo (#6308)

## Managed 1.5.6 (0.70.5)

## Managed Nango 1.5.6 (application 0.70.5)

- **Released:** 2026-06-01
- **Docker image:** `nangohq/nango:managed-1.5.6-0.70.5-9a9883712fd634fa4b4b5b5d24d8c2ab5c7ef579`
- **Pin CLI to:** `0.70.5`
- **Compare:** https://github.com/NangoHQ/nango/compare/a447dd8c75b2412d88862ceb02c298c3228b635b...9a9883712fd634fa4b4b5b5d24d8c2ab5c7ef579
- **Public changelog:** https://nango.dev/docs/updates/changelog

### Changes

## [Unreleased]

### Added

- *(integrations)* Allow mercury to also connect to sandbox environments (#6270)
- *(integrations)* Add support for theirstack (#6269)
- *(webapp)* Restructure component directories by taxonomy (#6274)
- *(integrations)* Add support for altrata (#6266)
- *(integrations)* Add support for pverify (#6265)
- *(integrations)* Add support for toast (#6237)
- *(ci)* Deploy design system Storybook to storybook.nango.dev (#6284)
- *(records)* Add records router (#6285)
- *(storybook)* Catalog v1 and v2 components (#6292)
- *(sync_jobs)* Prep sync_job_id for int4 → bigint widening (NAN-5491 Phase 0) (#6260)
- Add Cursor Cloud specific instructions to AGENTS.md (#6245)
- *(records)* Stop populating records.sync_job_id (NAN-5491 Phase 1) (#6262)
- *(runner)* Send runner telemetry to persist (#6209)

### Changed

- Update version in manifest
- *(integration-templates)* Automatic update from https://github.com/NangoHQ/integration-templates/commit/545e9efc7e737663aea76f6868c3c34084ab7e94 by Victor Lang'at
- Improve AI related docs (#6220)
- *(scheduler)* Decouple from orchestrator (#6276)

### Fixed

- *(scheduler)* Test(scheduler): close integration coverage gaps (#6275)
- *(bigchange)* Remove token_request_auth_method — endpoint rejects Basic, requires body (#6267)
- *(proxy)* Restore header forwarding through redirects when byte-metering transport is active (#6282)
- *(webapp)* Resolve CASA DAST findings (#6294)
- *(vulns)* Fix vulnerabilities (#6302)

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

