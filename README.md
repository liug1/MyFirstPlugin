# MyFirstPlugin

Drop a **Magma Block** item onto a **Wet Sponge** to dry it into a normal **Sponge**.

## Build (Windows PowerShell)
1. Extract the zip
2. `cd` into the folder that contains `pom.xml`
3. Run:

```powershell
mvn -U clean package
```

The compiled jar will be at:

`target\MyFirstPlugin-1.0-SNAPSHOT.jar`

## Install
Put the jar in your Paper server's `plugins/` folder and restart.
