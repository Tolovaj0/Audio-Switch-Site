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
On first launch, select the two audio output devices you want to switch between.
After configuration:
- 🖱️ Left-click the tray icon to switch
- 🖱️ Right-click for additional options
	- **Switch device** 
- **Settings** 		→ change the configured devices
- **Start with Windows** 	→ enable or disable automatic startup
- **Exit** 			→ close Audio-Switch
	
## Requirements
- Windows 11 or Windows 10
- x64

The published version is distributed as a self-contained application, so users do not need to install .NET separately (Hence large file size...).

## Configuration
Audio-Switch stores the selected device IDs and icon preferences in the user's application data directory.

## Building from source
Clone the repository and open the project in VS Code or another .NET-compatible editor.
```powershell
dotnet restore
dotnet build
dotnet run

## Download
	https://github.com/Tolovaj0/Audio-Switch/releases/download/Release-1.1/AudioSwitch.exe
## Support:Buy Me a Coffee
	https://ko-fi.com/tolovaj0
## License
	MIT  [link to the LICENSE file](https://github.com/Tolovaj0/Audio-Switch?tab=MIT-1-ov-file#)

