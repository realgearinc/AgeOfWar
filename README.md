# AgeOfWar

A Clash of Clans-inspired mobile strategy game framework originally developed in **C++** using **Cocos2dx** and **Android Studio**. This project is **Work in Progress** and has been **ported to Unity** for future development.

## Project Status

⚠️ **WORK IN PROGRESS** - This project is in early stages of development. Features and APIs are subject to change.

📦 **NOTE:** This project has been **ported to Unity** for enhanced cross-platform capabilities and faster development iteration.

## Overview

AgeOfWar is a framework for building a tile-based strategy game with grid management, resource systems, and multiplayer elements. It aims to provide a solid foundation for tower-defense and base-building mechanics similar to popular mobile strategy games.

## Tech Stack

- **Original Language:** C++
- **Original Engine:** Cocos2dx
- **Current Engine:** Unity (ported)
- **Platform:** Android, iOS (cross-platform via Unity)
- **Build System:** Android Studio (legacy) / Unity Editor (current)

## Features Implemented

### Core Systems
- ✅ **Grid Framework** - Tile-based grid system for game world management
- ✅ **Tile Generator** - Dynamic tile generation and placement
- ✅ **Touch Detection** - Nearest tile position calculation based on user input
- ✅ **Input Handling** - Grid-based coordinate detection from touch events

### Planned Features (Not Yet Implemented)
- 🔄 Building placement and upgrades
- 🔄 Resource management system
- 🔄 Combat mechanics
- 🔄 Player progression and levels
- 🔄 Multiplayer networking
- 🔄 UI/UX enhancements
- 🔄 Sound and visual effects

## Project Structure

```
AgeOfWar/
├── src/          # C++ source files (legacy)
├── assets/       # Game assets (sprites, textures)
├── build/        # Build output
└── README.md     # This file
```

## Getting Started

### Prerequisites

- Android Studio (for legacy C++ builds)
- Unity Engine (for current development)
- NDK (for C++ compilation)
- Cocos2dx game engine installed and configured (legacy)

### Building (Legacy - C++ Version)

1. Clone the repository
   ```bash
   git clone https://github.com/realgearinc/AgeOfWar.git
   ```

2. Open the project in Android Studio

3. Build and run on an Android device or emulator

### Building (Current - Unity Version)

Please refer to the Unity branch/repository for the current development version.

## Screenshots

![AgeOfWar Gameplay](https://i.postimg.cc/sV6qfxWv/Screenshot-20220920-193630-Age-of-War.jpg)

## Known Limitations

- Early stage development with incomplete features
- Limited optimization
- API stability not guaranteed
- Legacy C++ version is Android-only

## Contributing

Contributions are welcome! If you'd like to help with development, please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

[Add your license information here]

## Roadmap

- [ ] Complete base building system
- [ ] Implement resource management
- [ ] Add combat mechanics
- [ ] Multiplayer synchronization
- [ ] Performance optimization
- [ ] UI polish and refinement
- [ ] Cross-platform deployment (iOS & Android)

## Contact & Support

For questions, suggestions, or bug reports, please open an [Issue](https://github.com/realgearinc/AgeOfWar/issues) on GitHub.

---

**Last Updated:** June 2026  
**Version:** 0.1 (Early Development)  
**Note:** This repository contains the legacy C++ version. The project has been ported to Unity for ongoing development.
