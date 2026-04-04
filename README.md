# Nekomancer

> A multiplayer game developed with Unreal Engine 5 in collaboration with Robin Hasenbach, featuring networked gameplay, character abilities, and rich visual design.

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-0E1128?logo=unrealengine&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=c%2B%2B&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

## Overview

A multiplayer game developed with Unreal Engine 5 in collaboration with Robin Hasenbach, featuring networked gameplay, character abilities, and rich visual design.

Built with **Unreal Engine** and **C++**, demonstrating professional game development patterns: the Actor-Component model, Unreal's reflection system (UPROPERTY/UFUNCTION), Blueprint interoperability, and optimized gameplay systems.

## Features

- Unreal Engine gameplay framework (GameMode, GameState, PlayerController)
- Custom C++ Actor and Component classes
- Blueprint-C++ interoperability
- Physics and collision systems
- Optimized asset loading

## Technologies Used

| Technology | Details |
|------------|---------|
| Unreal Engine | 4.x / 5.x |
| C++ | Modern C++17 |
| Blueprints | Visual scripting |
| Chaos Physics | Physics simulation |

## Screenshots / Demo

![Screenshot 1](https://raw.githubusercontent.com/khaled71612000/Nekomancer/HEAD/Plugins/Character_Kitty/Resources/Icon128.png)

![Screenshot 2](https://raw.githubusercontent.com/khaled71612000/Nekomancer/HEAD/Plugins/Character_Lich/Resources/Icon128.png)

![Screenshot 3](https://raw.githubusercontent.com/khaled71612000/Nekomancer/HEAD/Plugins/Level_Meadows/Resources/Icon128.png)

![Screenshot 4](https://raw.githubusercontent.com/khaled71612000/Nekomancer/HEAD/Plugins/VFX_SnakingProjectile/Resources/Icon128.png)

![Screenshot 5](https://raw.githubusercontent.com/khaled71612000/Nekomancer/HEAD/Plugins/WaveSurvival/Resources/Icon128.png)

## Getting Started

### Prerequisites

- [Unreal Engine](https://www.unrealengine.com/en-US/download) 4.x or 5.x
- Visual Studio 2019 or 2022 with **Desktop development with C++**
- Git LFS

### Installation

```bash
git lfs install
git clone https://github.com/khaled71612000/Nekomancer.git
cd Nekomancer
```

1. Right-click `.uproject` → **Generate Visual Studio project files**
2. Open `.sln` in Visual Studio
3. Set config: **Development Editor | Win64**
4. Build (Ctrl+Shift+B) then launch the editor

## Project Structure

```
Nekomancer/
├── Source/                  # C++ source files
  └── (source files)
├── Content/                 # Assets, blueprints, levels
├── Config/                  # Project settings
└── Nekomancer.uproject
```

## License

[MIT License](LICENSE)
