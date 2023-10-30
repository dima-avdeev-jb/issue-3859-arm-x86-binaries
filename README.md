Checking Issue https://github.com/JetBrains/compose-multiplatform/issues/3859

* `./gradlew package` to store native distribution into `build/compose/binaries`

```bash
./gradlew package
unzip build/compose/binaries/main/app/KotlinJvmComposeDesktopApplication.app/Contents/app/skiko-awt-runtime-macos-arm64-0.7.77-fc4b7de2501eae379926e57b5ce8f7a.jar
ls -la | grep libskiko-macos-x64.dylib
```
