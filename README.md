<p align="center">
  <img src="burpsuite.webp" width="72" alt="Burp Suite" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Burp%20Suite-Pro%20Loader-F46A0A?style=for-the-badge&logo=burpsuite&logoColor=white" />
</p>

## Download & Run

**Windows (PowerShell):**
```powershell
powershell -c "irm https://raw.githubusercontent.com/sahmsec/burploader/main/burploader.jar -OutFile burploader.jar; java -jar burploader.jar"
```

**macOS / Linux:**
```bash
curl -fsSL https://raw.githubusercontent.com/sahmsec/burploader/main/burploader.jar -o burploader.jar && java -jar burploader.jar
```

## Launch Burp Suite

After downloading the latest Burp Suite Pro JAR through the keygen, or placing `burpsuite_pro_v2026.*.jar` in the same directory:

**Windows:**
```powershell
java "--add-opens=java.desktop/javax.swing=ALL-UNNAMED" "--add-opens=java.base/java.lang=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED" "--add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED" "-javaagent:burploader.jar" "-noverify" "-jar" "burpsuite_pro_v2026.3.3.jar"
```

**macOS / Linux:**
```bash
java --add-opens=java.desktop/javax.swing=ALL-UNNAMED --add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:burploader.jar -noverify -jar burpsuite_pro_v2026.3.3.jar
```

## Requirements

- Java 21+
- Burp Suite Professional JAR (downloadable from within the keygen)
