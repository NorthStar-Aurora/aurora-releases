<p align="center">
  <img src="https://img.shields.io/github/v/release/NorthStar-Aurora/aurora-releases?style=for-the-badge&label=Latest&color=d4af37" alt="Latest Release">
  <img src="https://img.shields.io/badge/Platform-ASUS_ROG_Ally-0a1628?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/License-Proprietary-8b2942?style=for-the-badge" alt="License">
</p>

# Aurora Releases

Official binary releases for **Aurora Console** — the touch-first operator console for professional light show management.

## Quick Start

1. **Download** the latest `.tar.gz` from [Releases](https://github.com/NorthStar-Aurora/aurora-releases/releases)
2. **Install** on your Aurora OS device:

```bash
sudo /opt/aurora/scripts/update-aurora.sh aurora-X.Y.Z.tar.gz
```

## Release Channels

| Channel | Description | Tags |
|---------|-------------|------|
| **stable** | Production-ready releases | `v5.x.x` |
| **beta** | Pre-release testing | `v5.x.x-beta.x` |

## Verification

All releases are cryptographically signed with RSA-4096.

```bash
openssl dgst -sha256 -verify /etc/aurora/update-key.pub \
  -signature aurora-X.Y.Z.tar.gz.sig aurora-X.Y.Z.tar.gz
```

## System Requirements

- **Hardware:** ASUS ROG Ally
- **OS:** Aurora OS (included in full install)
- **Controllers:** Falcon Player, E1.31/DDP compatible

## Support

- **Website:** [northstaraurora.tech](https://northstaraurora.tech)
- **Email:** customersupport@northstaraurora.tech

---

<sub>NorthStar Aurora Pixel Engine — Proprietary software. All rights reserved.</sub>
