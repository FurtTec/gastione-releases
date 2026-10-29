# Gastione releases

Download page for the **Gastione** Android app: the cheapest gas near you in Puerto Rico, with prices reported by drivers.

- **Download:** [latest release](../../releases/latest) (`Gastione.apk`)
- **Website:** https://gastione.com
- **Questions or privacy requests:** support@gastione.com

This repository only holds the app's installable files (APKs) and release notes. It has no source code.

## Install

1. Download `Gastione.apk` on your Android phone.
2. Open it. Android will ask you to allow installing apps from this source; allow it for the browser or file manager you used.
3. Open Gastione. It asks for your location while the app is open, to show nearby stations.

Requires Android on a 64-bit (arm64) phone. Free, with no account.

## Check the file

Each release lists the file's SHA-256. To compare it with your download:

```
sha256sum Gastione.apk        # Linux
shasum -a 256 Gastione.apk    # macOS
certutil -hashfile Gastione.apk SHA256    # Windows
```

## Privacy

Privacy policy and terms: https://gastione.com/privacy/ and https://gastione.com/terms/
