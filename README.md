# Nexus Launcher

**Nexus Launcher** is a premium Minecraft: Java Edition launcher for Android.

It runs Minecraft Java Edition directly on your Android device using a proven open-source engine based on PojavLauncher.

## Features

- Full Minecraft: Java Edition support (legacy + modern versions)
- Java 8 / 17 / 21+ runtime management
- Fabric, Forge, NeoForge, Quilt, LegacyFabric support
- Instance / Profile management
- Mods, Resource Packs, Shader Packs management
- Custom touch controls + keyboard/mouse/controller support
- Microsoft account authentication
- Modern dark navy + blue gradient premium UI (in progress)

## Package

- **Application ID**: `com.nexuslauncher`
- **App Name**: Nexus Launcher

## Building

```bash
./gradlew :app_pojavlauncher:assembleDebug
```

APK output:
```
app_pojavlauncher/build/outputs/apk/debug/app_pojavlauncher-debug.apk
```

## License

This project is based on PojavLauncher and is licensed under **GNU LGPLv3**.
All original engine, rendering and runtime code remains under its original licenses.

See `LICENSE` file and third-party notices for full details.

## Credits

- PojavLauncher Team
- Boardwalk
- GL4ES / MobileGlues / LTW
- LWJGL
- OpenJDK mobile ports
- And the wider open-source Minecraft launcher community

---

**Nexus Launcher** — Built for Android gamers who want a clean, powerful Java Edition experience.
