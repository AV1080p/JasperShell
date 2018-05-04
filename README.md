# Hacking JasperReports

## Shell.java

compile:

```
/usr/lib/jvm/java-6-openjdk-amd64/bin/javac -Xlint -cp .:jasperreports-5.0.0.jar *.java -d .
```

package:

```
/usr/lib/jvm/java-6-openjdk-amd64/bin/jar cvf shell.jar shell/
```
