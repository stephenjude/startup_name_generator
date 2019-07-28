# Startup Name Generator App

A mobile app built druing our GDG Onitsha flutter study jam.

### Gradle setup For Android

Download gradle 4.6 or higher.

Update line 72 of gradlew.bat file in the project.

```
set CLASSPATH=path\to\gradle-4.6\lib\gradle-launcher-4.6.jar
```

Update line 75 of gradlew.bat file in the project.

```
"%JAVA_EXE%" %DEFAULT_JVM_OPTS% %JAVA_OPTS% %GRADLE_OPTS% "-Dorg.gradle.appname=%APP_BASE_NAME%" -classpath "%CLASSPATH%" org.gradle.launcher.GradleMain %CMD_LINE_ARGS%
```

### Run the app

Start your emulator or connect your mobile device.

Run this command.

```bash
cd path/to/your/project

flutter run
```

## Getting Started

A few resources to get you started if you are new to Flutter:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
