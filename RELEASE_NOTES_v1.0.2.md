# Release v1.0.2

## 🎉 What's New

### Switch Entity Support
- **NEW**: Each activity is now automatically created as a switch entity
- Entity ID format: `switch.activity_name` (e.g., `switch.watch_tv`)
- Perfect for use in Home Assistant automations and scenes
- More intuitive than using remote services

### Documentation Improvements
- Added comprehensive automation examples for switch entities
- Added FAQ about physical key press detection
- Added helper button automation examples
- Improved bilingual documentation (English & Chinese)

### Bug Fixes
- Fixed manifest.json repository URLs
- Improved README structure and clarity

## 📚 Documentation

Full documentation available at: https://github.com/yomonpet/ha-sofabaton-hub

## 🔧 Installation

### Via HACS (Recommended)
1. Open HACS in Home Assistant
2. Click on "Integrations"
3. Search for "Sofabaton Hub"
4. Click "Install"
5. Restart Home Assistant

### Manual Installation
1. Download `sofabaton_hub.zip` from this release
2. Extract to `config/custom_components/`
3. Restart Home Assistant

## ⚙️ Requirements

- Home Assistant 2023.1.0 or newer
- MQTT broker (Mosquitto recommended)
- Sofabaton X2 Hub (NOT compatible with X1s)

## 🆕 For New Users

This integration provides:
- 🔍 Automatic discovery via mDNS/Zeroconf
- 🎮 Activity control with switch entities
- 🔑 Complete key management (assigned, macro, favorite keys)
- 📱 Beautiful custom Lovelace cards
- 🔄 Real-time MQTT-based updates
- 🌐 Bilingual support (English & Chinese)

## 📝 Changelog

### Added
- Switch entity platform for activity control
- Comprehensive automation examples in README
- FAQ section about key press detection
- Helper button automation examples

### Changed
- Updated manifest.json repository URLs
- Improved README structure
- Enhanced documentation clarity

### Fixed
- Repository URL consistency across all files

## 🐛 Known Issues

- Physical key press detection is not supported (limitation of Sofabaton Hub API)
- Use helper buttons as a workaround for automation triggers

## 🙏 Acknowledgments

Thanks to all users who provided feedback and suggestions!

## 📞 Support

- 🐛 Report issues: https://github.com/yomonpet/ha-sofabaton-hub/issues
- 💬 Discussions: https://github.com/yomonpet/ha-sofabaton-hub/discussions
- 📖 Documentation: https://github.com/yomonpet/ha-sofabaton-hub

---

**Full Changelog**: https://github.com/yomonpet/ha-sofabaton-hub/compare/v1.0.1...v1.0.2

