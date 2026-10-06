# Audio-Switch-Site

# Audio-Switch

Simple Windows 11 tray utility for quickly switching between TWO audio output devices – speakers, headphones, monitors, soundbars and other playback devices.

🌐 Website: audio-switch.com

## Features
- 🔊 Switch between two configured audio output devices
- 🎧 Configurable icon for each device
- ✅ 🔢 Tray icon and number indicator in icon show which device is currently active
- Optional start with Windows
- Simple device configuration
- Remembers your selected devices and settings
- Built with C# and Windows Forms

## Usage
On first launch, select the two audio output devices you want to switch between. After that:

- 🖱️ **Left-click** the tray icon to switch devices
- 🖱️ **Right-click** for more options:
  - **Switch device**
  - **Settings** – change the configured devices and icons
  - **Start with Windows** – enable or disable automatic startup
  - **Exit** – close Audio-Switch

> Windows 11 hides new tray icons behind the **^** arrow. Drag the icon onto the taskbar to keep it always visible.

## Requirements
- Windows 11 or Windows 10
- x64

## Download
Get `AudioSwitch.exe` from the [latest release](https://github.com/Tolovaj0/Audio-Switch/releases/latest).

**Windows x64 · Portable · No installer.** It is self-contained, so you don't need to install .NET (this is the reason for large file size ~150MB).

### "Windows protected your PC" warning
The executable is **not code-signed**, so Windows SmartScreen may warn you the first time you run it. Click **More info → Run anyway**.
To verify the download, compare its SHA-256 checksum:
```powershell
Get-FileHash .\AudioSwitch.exe -Algorithm SHA256
```

## Configuration
Audio-Switch stores the selected device IDs and icon preferences in the user's application data directory.

## Building from source
Clone the repository and open the project in VS Code or another .NET-compatible editor.
```powershell
dotnet restore
dotnet build
dotnet run
```

## Support
Audio-Switch is free. If it saves you some clicks, you can support it:
☕ [Buy Me a Coffee on Ko-fi](https://ko-fi.com/tolovaj0)

## License
Released under the [MIT License](LICENSE).


