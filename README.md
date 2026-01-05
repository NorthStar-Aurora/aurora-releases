# Aurora Releases

Binary releases for Aurora Console - the touch-first operator console for Aurora Pixel Engine light show management.

## Installation

Download the latest release and run:

```bash
sudo /opt/aurora/scripts/update-aurora.sh aurora-X.Y.Z.tar.gz
```

## Channels

- **stable** - Production releases
- **beta** - Pre-release versions (tagged with `-beta`, `-rc`, etc.)

## Verification

All releases are signed with RSA-4096. Verify with:

```bash
openssl dgst -sha256 -verify /etc/aurora/update-key.pub -signature aurora-X.Y.Z.tar.gz.sig aurora-X.Y.Z.tar.gz
```

## License

Proprietary software. All rights reserved.

