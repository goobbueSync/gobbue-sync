# Goobbue Sync - FFXIV Character Synchronization Plugin

[![Version](https://img.shields.io/badge/version-1.11.0-blue.svg)](https://github.com/Penumbra-Sync/client)
[![Dalamud API](https://img.shields.io/badge/Dalamud%20API-13-green.svg)](https://github.com/goatcorp/Dalamud)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

> **"Let others see you as you see yourself!"**

Goobbue Sync is a powerful Dalamud plugin for Final Fantasy XIV that enables real-time synchronization of character customizations, mods, and appearance data across the FFXIV community. This plugin allows other players to see your character exactly as you see them, including all Penumbra mods, Glamourer states, and customizations.

## 🌟 Features

### Core Functionality
- **Real-time Character Synchronization**: Share your character's appearance with other Goobbue Sync users
- **Mod Compatibility**: Full support for Penumbra mods, Glamourer states, and other appearance modifications
- **Cross-World Support**: Connect with players across different worlds and data centers
- **Performance Optimized**: Efficient file caching and compression for smooth gameplay

### Advanced Features
- **Syncshells**: Create or join private groups for synchronized character sharing
- **Character Data Hub**: Manage and share character poses, expressions, and animations
- **Nearby Poses**: Automatically sync with nearby players using the plugin
- **GPose Together**: Synchronize character states during group photo sessions
- **Profile Management**: Create and manage multiple character profiles
- **Permission System**: Control who can see your character and when

### Plugin Integration
- **Penumbra**: Full mod synchronization support
- **Glamourer**: State and customization sharing
- **Customize**: Character appearance modifications
- **Heels**: Height adjustment synchronization
- **Honorific**: Title and honorific sharing
- **Moodles**: Mood and expression synchronization
- **Pet Names**: Companion naming synchronization
- **Brio**: Additional character data support

## 📋 Requirements

### Essential Requirements
- **Final Fantasy XIV** (any version)
- **Dalamud** (API Level 13)
- **Penumbra** (for mod synchronization)
- **Glamourer** (for state synchronization)

### Recommended Plugins
- **Customize**: For character appearance modifications
- **Heels**: For height adjustment features
- **Honorific**: For title synchronization
- **Moodles**: For mood/expression sharing
- **Pet Names**: For companion naming features
- **Brio**: For additional character data support

## 🚀 Installation

### Method 1: Dalamud Repository (Recommended)
1. Open Dalamud Plugin Installer
2. Add repository: `https://raw.githubusercontent.com/n0way02/goobbue-sync-repo/refs/heads/master/plogonmaster.json`
3. Search for "Goobbue Sync" and install

### Method 2: Manual Installation
1. Download the latest release from [GitHub Releases](https://github.com/n0way02/goobbue-sync/releases)
2. Extract the ZIP file to your Dalamud plugins folder
3. Restart Dalamud

## ⚙️ Configuration

### Initial Setup
1. **Plugin Installation**: Ensure Penumbra and Glamourer are installed and active
2. **First Launch**: The plugin will guide you through initial configuration
3. **Server Connection**: Connect to a Goobbue Sync server or create your own
4. **Character Setup**: Configure your character profile and synchronization settings

### Key Settings
- **Compression**: Enable file compression for better performance
- **Cache Management**: Configure file caching and cleanup
- **Privacy Controls**: Set who can see your character
- **Performance**: Adjust synchronization frequency and quality

## 🔧 Usage

### Basic Synchronization
1. **Pair with Players**: Connect with other Goobbue Sync users
2. **Automatic Sync**: Your character appearance automatically syncs with paired players
3. **Real-time Updates**: Changes to your character are reflected immediately

### Advanced Features
- **Syncshells**: Create private groups for synchronized sharing
- **Character Data Hub**: Share poses, expressions, and animations
- **Profile Management**: Switch between different character configurations
- **Permission Management**: Control access to your character data

### Commands
- `/goobbue` - Open the main plugin interface
- `/goobbue sync` - Quick synchronization commands
- `/goobbue profile` - Profile management commands

## 🌐 Server Setup

### Self-Hosting
The plugin can connect to custom Goobbue Sync servers. See the [server documentation](../server-main/README-DEPLOY.md) for deployment instructions.

### Public Servers
Connect to community-run servers or create your own for private use.

## 🛠️ Development

### Building from Source
```bash
git clone https://github.com/n0way02/goobbue-sync.git
cd goobbue-sync/client-main
dotnet build
```

### Requirements
- .NET 9.0 SDK
- Visual Studio 2022 or later
- Dalamud Development Environment

### Project Structure
- **MareSynchronos/**: Main plugin implementation
- **MareAPI/**: API client and data models
- **Services/**: Core functionality services
- **UI/**: User interface components
- **Interop/**: Plugin integration layer

## 📱 User Interface

### Main Interface
- **Compact UI**: Minimal interface for basic operations
- **Settings UI**: Comprehensive configuration options
- **Character Data Hub**: Advanced character sharing features
- **Profile Management**: Character profile editing and management

### Key Windows
- **Intro UI**: Initial setup and configuration
- **Settings**: Plugin configuration and preferences
- **Syncshell Management**: Group creation and management
- **Character Profiles**: Profile editing and sharing

## 🔒 Privacy & Security

### Data Protection
- **Local Processing**: Character data is processed locally
- **Encrypted Communication**: Secure server communication
- **Permission Controls**: Granular control over data sharing
- **Blocking System**: Block unwanted users from seeing your character

### Privacy Features
- **Selective Sharing**: Choose what character data to share
- **Temporary Permissions**: Grant temporary access to specific users
- **Anonymous Mode**: Hide your identity while sharing character data

## 🐛 Troubleshooting

### Common Issues
1. **Plugin Not Working**: Ensure Penumbra and Glamourer are active
2. **Sync Issues**: Check server connection and permissions
3. **Performance Problems**: Adjust compression and cache settings
4. **Mod Conflicts**: Verify mod compatibility and load order

### Getting Help
- **Discord**: Join the [Mare Synchronos Discord]()
- **GitHub Issues**: Report bugs and request features
- **Documentation**: Check the wiki for detailed guides

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **n0way02**: Main developer and project maintainer
- **Penumbra Team**: For the excellent modding framework
- **Glamourer Team**: For character state management
- **Dalamud Team**: For the plugin framework
- **FFXIV Community**: For testing and feedback

## 🔗 Links

- **GitHub Repository**: [https://github.com/n0way02/goobbue-sync](https://github.com/n0way02/goobbue-sync)
- **Dalamud Repository**: [https://raw.githubusercontent.com/Penumbra-Sync/repo/main/plogonmaster.json](https://raw.githubusercontent.com/n0way02/goobbue-sync-repo/refs/heads/master/plogonmaster.json)
- **Discord Server**: [https://discord.gg/5HVveFefcB]()
- **Releases**: [https://github.com/n0way02/goobbue-sync/releases](https://github.com/n0way02/goobbue-sync/releases)

---

**Note**: This plugin requires active Penumbra and Glamourer installations to function properly. Make sure both plugins are up to date and properly configured before using Goobbue Sync.
