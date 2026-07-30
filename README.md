<p align="center">
  <img src="burp-icon.svg" width="64" alt="Burp Suite" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Burp%20Suite-Pro%20Loader-F46A0A?style=for-the-badge&logo=burpsuite&logoColor=white" />
</p>

## Download & Run

```powershell
# PowerShell one-liner download
Invoke-WebRequest -Uri "https://github.com/sahmsec/burploader/releases/latest/download/burploader.jar" -OutFile "burploader.jar"

# Run
java -jar burploader.jar
```

## Launch Burp Suite

After downloading the latest Burp Suite Pro JAR through the keygen, or placing `burpsuite_pro_v2026.*.jar` in the same directory:

```bash
# Windows
java "--add-opens=java.desktop/javax.swing=ALL-UNNAMED" "--add-opens=java.base/java.lang=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED" "-javaagent:burploader.jar" "-noverify" "-jar" "burpsuite_pro_v2026.3.3.jar"
```

```bash
# macOS / Linux
java --add-opens=java.desktop/javax.swing=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:burploader.jar -noverify -jar burpsuite_pro_v2026.3.3.jar
```

## Requirements

- Java 21+
- Burp Suite Professional JAR (downloadable from within the keygen)
