# Game Priority Manager

A modern, user-friendly application that automatically manages process priorities for your games, helping to optimize performance and reduce stuttering.

![Game Priority Manager](app_icon.png)

## Features

- 🎮 Automatic process priority management for popular games
- ⚡ Real-time process monitoring
- 🎯 Customizable priority settings
- 🕒 Configurable wait time for game detection
- 🎨 Modern, dark-themed user interface
- 🔄 Live process list with priority filtering
- 📝 Custom game process support
- 💾 Persistent settings storage

## Supported Games

The application comes pre-configured with support for:
- Battlefield V (bfv.exe)
- Battlefield 4 (bf4.exe)
- Battlefield 1 (bf1.exe)
- Rainbow Six Siege (RainbowSix.exe, RainbowSix_BE.exe)

You can also add custom game executables through the interface.

## Installation

### From Executable
1. Download the latest release from the [Releases](https://github.com/apkaless/Set_GamePriority/releases) page
2. Run the `GamePriorityManager.exe` file
3. The application will request administrator privileges (required for process priority management)

### From Source
1. Clone the repository:
```bash
git clone https://github.com/apkaless/Set_GamePriority.git
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python setGamePriority.py
```

## Usage

1. Launch the Game Priority Manager
2. Select your game from the dropdown menu or add a custom game executable
3. Choose the desired priority level:
   - High
   - Above Normal
   - Normal
   - Below Normal
   - Idle
4. Set the wait time (how long the app should wait for the game to launch)
5. Click "Start Monitoring"
6. Launch your game
7. The application will automatically detect and set the process priority

## Priority Levels

- **High**: Maximum CPU priority, best for competitive gaming
- **Above Normal**: Elevated priority, good for most games
- **Normal**: Default system priority
- **Below Normal**: Reduced priority
- **Idle**: Lowest priority

## Requirements

- Windows 10 or later
- Python 3.7+ (for source installation)
- Administrator privileges

## Dependencies

- customtkinter
- psutil
- Pillow

## Building from Source

To build the executable:

1. Install PyInstaller:
```bash
pip install pyinstaller
```

2. Run the build script:
```bash
python build_exe.py
```

The executable will be created in the `dist` directory.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- GitHub: [@apkaless](https://github.com/apkaless)

## Acknowledgments

- Thanks to all contributors and users of the application
- Special thanks to the customtkinter library for the modern UI components

## Support

If you encounter any issues or have suggestions, please:
1. Check the [Issues](https://github.com/apkaless/Set_GamePriority/issues) page
2. Create a new issue if your problem hasn't been reported
3. Provide detailed information about your system and the problem you're experiencing

---

Made with ❤️ for gamers 