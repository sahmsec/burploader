<p align="center">
  <img src="burpsuite.webp" width="72" alt="Burp Suite" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Burp%20Suite-Pro%20Loader-F46A0A?style=for-the-badge&logo=burpsuite&logoColor=white" />
</p>

## Download

Replace `$DOWNLOAD_URL` with the actual JAR download link.

**Windows (PowerShell):**
```powershell
powershell -c "irm $DOWNLOAD_URL -OutFile burploader.jar"
```

**macOS / Linux:**
```bash
curl -fsSL $DOWNLOAD_URL -o burploader.jar
```

## Download & Run

**Windows (PowerShell):**
```powershell
powershell -c "irm $DOWNLOAD_URL -OutFile burploader.jar; java -jar burploader.jar"
```

**macOS / Linux:**
```bash
curl -fsSL $DOWNLOAD_URL -o burploader.jar && java -jar burploader.jar
```

## Requirements

| | Version |
|---|---|
| **Minimum JDK** | 21 |
| **Recommended** | 22 or 23 |

> For best stability, use a JDK that is 1–2 versions behind the latest release (e.g., if JDK 26 is out, use JDK 24 or 25). Brand-new JDK releases may have compatibility quirks with Swing or the loader agent. JDK 21 is the long-term support (LTS) baseline.
