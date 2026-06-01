# Nango Managed Image Releases

This repository publishes **release notifications and metadata** for Nango managed enterprise Docker images.

Managed self-hosted customers can subscribe here to learn when new managed images are available.

---

## Subscribe to release notifications

1. Open this repository on GitHub
2. Click **Watch**
3. Select **Custom**
4. Enable **Releases**

You will receive a notification whenever a new managed image release is published.

**RSS / Atom feed:**

```text
https://github.com/NangoHQ/managed-image-releases/releases.atom
```

This can be wired into Slack, Microsoft Teams, RSS readers, or internal automation.

---

## Latest release

- **Latest GitHub Release:** https://github.com/NangoHQ/managed-image-releases/releases/latest
- **Latest version manifest:** https://github.com/NangoHQ/managed-image-releases/blob/master/managed-manifest.json
- **Release history in repo:** https://github.com/NangoHQ/managed-image-releases/blob/master/CHANGELOG.md

`managed-manifest.json` is updated automatically on each release and mirrors the managed release state from the main Nango repository.

---

## Image tag format

Managed image tags follow this format:

```text
managed-{managed-release-version}-{application-version}-{commit-sha}
```

Example:

```text
managed-1.5.4-0.70.4-0fe07a6d83aea0becc4cea382c5cead2f555718d
```

- **managed-release-version:** semver for the managed image lifecycle (major = breaking, minor/patch = features/fixes)
- **application-version:** semver of the Nango application baked into the image
- **commit-sha:** full Git commit hash of the released source

Pin your **CLI version** to the `application-version` in the tag.

---

## Docker images

Managed images are published to Docker Hub:

```bash
docker pull nangohq/nango:managed-1.5.4-0.70.4-0fe07a6d83aea0becc4cea382c5cead2f555718d
```

Replace the tag with the one from the latest release.

---

## What each release includes

Each GitHub Release includes:

- Managed image tag
- Application version
- Source commit hash
- Release date
- Docker pull reference
- GitHub compare link to the previous managed release
- Generated changelog of changes since the previous managed release
- Link to the public Nango changelog: https://nango.dev/docs/updates/changelog

This repository is updated automatically by the Nango managed release workflow. Do not edit release files manually.

---

## Release policy

- Managed image releases are published on a regular cadence, with occasional hotfixes as needed
- Each release maps to a specific source commit
- Published image tags are not changed after release
- Customers are encouraged to stay reasonably current with managed image releases

For product context and deployment guidance, see the [self-hosting documentation](https://nango.dev/docs/guides/platform/self-hosting).

---

## Support

For enterprise support or upgrade assistance:

```text
support@nango.dev
```
