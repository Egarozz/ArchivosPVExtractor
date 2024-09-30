This is the code for JLINK:
```
 'C:\Program Files (x86)\Java\zulufx17\bin\jlink.exe' --add-modules java.base,java.compiler,java.desktop,java.logging,java.naming,java.security.jgss,java.sql,java.xml,jdk.unsupported,javafx.base,javafx.controls,javafx.graphics,javafx.swing,jdk.crypto.ec --compress 2 --no-header-files --no-man-pages --output ./cjre
```
without jdk.crypto.ec wont work
