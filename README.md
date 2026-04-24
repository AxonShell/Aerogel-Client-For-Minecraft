# Aerogel Client

Minecraft Client made to be executed anywhere (especially USB Sticks and portable storage types (SSDs and other kinds of drives)

## Features and contents

- 32-Bit System (Soon will be replaced for 64-bit)
- Portable JDK Platform: **jdk-17**
- Mod support: **Fabric Loader 0.19.2**
- Preinstalled performance mods to target better framerates and stable gameplay.
- Low RAM usage (Default 640Mb)
- Recent Versions Supported (1.20.1 Latest as of now)
- Performance Presets such as Balanced and ultra_light

# Compatible platforms:
- Windows 10
- Windows 11

### NOTES:
if the executable does not work, start powershell in the \Client\ directory and execute this command:

***powershell -ExecutionPolicy Bypass -File .\scripts\start-client.ps1 -Profile ultra_light -MinRamMb 256 -MaxRamMb 640***

### KNOWN ISSUES
Crashes has been noticed after installing a ressource pack from a server: this is probably due to minecraft using a very low amount of RAM. unfortunately, when a higher value than 640 is set, such as 1024 or 2048, the game crashes upon starting a world.

We also know that some crashes could happen while playing, this is why we ask players and testers to share thier logs from \Client\logs to the developers.

No minecraft servers is joinable unless they are allowing cracked players. this issue will be fixed soon.

