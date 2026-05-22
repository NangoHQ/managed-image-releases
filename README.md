# Nango Managed Image Releases

This repository publishes release notifications and metadata for Nango managed enterprise images.

Customers running Nango managed self-hosted deployments can subscribe to this repository to receive notifications about:

- New managed image releases
- Security updates
- Bug fixes
- Recommended upgrades
- Critical advisories

---

## Subscribe to Release Notifications

GitHub provides built-in release notifications.

To subscribe:

1. Open the repository on GitHub
2. Click **Watch**
3. Select **Custom**
4. Enable **Releases**

You will then receive notifications whenever a new managed image release is published.

---

## Release Format

Managed image releases follow the format:

```text
managed-<major-version>-<app-version>-<commit-hash>
```

Example:

```text
managed-1.17-0.62.0-abc123
```

Each release includes:

- Managed image tag
- Base Nango application version
- Source commit hash
- Release date
- Upgrade recommendations
- Security or bugfix notes
- Docker pull instructions

---

## Docker Images

Managed images are published to Docker Hub.

Example:

```bash
docker pull nangohq/nango:<tag>
```

---

## Latest Release

The latest managed image release is available on the GitHub Pages site:

```text
https://nangohq.github.io/managed-image-releases/
```

---

## RSS Feed

GitHub also provides an Atom/RSS feed for releases:

```text
https://github.com/NangoHQ/managed-image-releases/releases.atom
```

This can be integrated with:

- Slack
- Microsoft Teams
- RSS readers
- Internal automation systems

---

## Release Policy

- Releases are immutable once published
- Every image release maps to a specific source commit
- Security and critical bugfix releases may be published outside the normal release cadence
- Customers are encouraged to stay reasonably up to date with managed image releases

---

## Support

For enterprise support or upgrade assistance, contact:

```text
support@nango.dev
```