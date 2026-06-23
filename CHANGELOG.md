# Managed image releases

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

