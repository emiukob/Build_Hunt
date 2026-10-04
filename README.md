<div align="center">

# 🏗️ Build Hunt

### Sort. Load. Build. — A satisfying isometric voxel construction puzzle for mobile.

![Unity](https://img.shields.io/badge/Unity-6-000000?logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=csharp&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![Genre](https://img.shields.io/badge/Genre-Hybrid--Casual%20Puzzle-ff6b8b)
![Status](https://img.shields.io/badge/Status-Closed%20Source-red)

<img src="screenshots/cover.png" alt="Build Hunt cover" width="320">

</div>

---

> [!IMPORTANT]
> **This repository is a showcase page only.** The source code, assets and builds of Build Hunt are **proprietary and are not published here.**
> The game is a commercial-grade project and may be released as a paid title or licensed to a publisher.

---

## 🎮 About the Game

**Build Hunt** is an isometric, hybrid-casual mobile puzzle game. A crew of hard-hatted workers is raising a giant pixel-art sculpture out of colored voxel blocks — and **you run the logistics**.

Pick the right truck, send your workers to haul matching blocks, fill every truck to its number and watch a huge voxel monument grow, block by block, until the build is complete.

Easy to learn in seconds, with enough planning depth to keep every level interesting.

## 📸 Screenshots

<div align="center">

| Core Gameplay | Truck Logistics Queue | Masterpiece Victory |
|:---:|:---:|:---:|
| <img src="screenshots/gameplay.png" width="220" alt="Core Gameplay"> | <img src="screenshots/trucks.png" width="220" alt="Truck Logistics Queue"> | <img src="screenshots/victory.png" width="220" alt="Level Complete Victory"> |

<br>

### 🏛️ 23+ Page Art Gallery Collection
<img src="screenshots/gallery.png" alt="Art Gallery with 130+ Voxel Sculptures" width="340">

*Players unlock and assemble dozens of intricate voxel sculptures across 23+ themed gallery pages.*

</div>

## ✨ Core Features

- 🏛️ **23+ Page Art Gallery** — over 130+ vibrant voxel masterpieces (Apple, Rocket, Burger, Balloon, Cat, and many more) to unlock and construct.
- 🧱 **Voxel sculpture levels** — every level is a grid of colored blocks that together form a larger pixel-art picture.
- 🚚 **Numbered trucks** — each truck targets a specific color and has a fixed capacity that must be filled before it departs.
- 👷 **Worker logistics** — workers automatically carry matching blocks from the board to the selected trucks.
- 🅿️ **Limited truck slots** — only a handful of trucks can be active at once, so choosing the order matters.
- 🔒 **Special truck types** — normal, locked, hidden and linked trucks add layers of strategy as levels progress.
- 🎨 **12-color block palette** with optional per-level custom palettes for exact artist-controlled looks.
- 📳 **Juicy feedback** — particle effects, animated trucks, sound and haptic feedback on key actions.
- 🧩 **Jam detection** — the tray monitors for dead-end states so the player is never silently stuck.

## 🛠️ Technical Highlights

| Area | Details |
|---|---|
| **Engine** | Unity 6, C# |
| **Target** | Android (mobile-first, portrait) |
| **Architecture** | Event-driven design (`EventManager`) decoupling grid, trucks, workers and UI |
| **Performance** | Object pooling for workers and effects, 60 FPS cap with VSync disabled to save battery and heat |
| **Level pipeline** | Data-driven `ScriptableObject` levels — grid size, blocks, truck queue and palette in a single asset |
| **Tooling** | Custom Unity editor tools: level builder, project setup wizard and one-click Android build script |
| **Responsive camera** | Automatically adapts framing to different phone aspect ratios |

### Code Organization (high level)

```
Core      → Game flow, events, visual helpers
Grid      → Block grid & block behaviour
Tray      → Truck slots, truck states, queue logic
Worker    → Worker AI & pooled worker management
Effects   → Board frame, particles, haptics
Audio     → Sound management
UI        → Main menu & in-game UI
Data      → ScriptableObject level definitions
Editor    → Level builder, setup wizard, build automation
```

## 🧰 Built With

- **Unity 6** & **C#**
- AI-assisted pixel / voxel art pipeline
- Custom editor tooling for rapid level creation

## 📅 Status

🚧 **In active development.** Core loop, level pipeline and mobile build are working. Content, polish and monetization design are in progress.

## 📬 Contact

Interested in the game, a publishing deal or a collaboration?

- 📧 **Email:** [emir.bekar@bilgiedu.net](mailto:emir.bekar@bilgiedu.net)
- 💼 **LinkedIn:** [Emir Bekar](https://www.linkedin.com/in/emir-bekar-883410360)
- ▶️ **YouTube:** [@emiukob](https://www.youtube.com/@emiukob)
- 🏝️ **Portfolio:** [emiukob.github.io](https://emiukob.github.io)

## ⚖️ Copyright & License

**© 2026 Emir Bekar. All Rights Reserved.**

Build Hunt, its source code, art, audio, level designs, name and logo are proprietary.
No part of this project may be copied, redistributed, modified, sublicensed or used commercially without prior written permission from the author.
This README and its screenshots are provided for portfolio and promotional purposes only.
