# ⬡ Hex Grid Turn-Based Game

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,6,21&height=210&section=header&text=Hex%20Grid%20Turn-Based%20Game&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Strategy%20on%20Every%20Hex%2C%20Victory%20on%20Every%20Turn&descAlignY=56&descSize=18" width="100%"/>

<br/>

[![Version](https://img.shields.io/badge/version-2.6.0-3C096C?style=for-the-badge&logo=semanticrelease&logoColor=white)](https://github.com)
[![Engine](https://img.shields.io/badge/Godot%204%20%7C%20Unity%20%7C%20Web-5A189A?style=for-the-badge&logo=godotengine&logoColor=white)](https://github.com)
[![License](https://img.shields.io/badge/license-MIT-7B2CBF?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Grid](https://img.shields.io/badge/grid-hexagonal-9D4EDD?style=for-the-badge&logo=hexo&logoColor=white)](https://github.com)

<br/>

### 🎲 A complete turn-based strategy game built on a hexagonal grid

*⬡ Hex Movement • ⚔️ Tactical Combat • 🧠 Smart AI • 🎨 Clean UI*

<br/>

<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/🎮_PLAY_DEMO-3C096C?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=280548" alt="Play Demo" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-5A189A?style=for-the-badge&logo=github&logoColor=white&labelColor=3D0F6A" alt="Get Source" height="45"/>
</a>
&nbsp;&nbsp;
<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/📚_DOCS-7B2CBF?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=551E85" alt="Docs" height="45"/>
</a>

</div>

<img width="1920" height="1080" alt="VanarisTactics" src="https://github.com/user-attachments/assets/421b3e23-8366-414a-97f2-4e9f53cc7e16" />


<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌟 About

**Hex Grid Turn-Based Game** is a **complete, playable strategy game** built around a hexagonal grid — the classic battlefield layout of legends like *Civilization*, *Battle for Wesnoth*, and *Heroes of Might & Magic*.

Everything works: hex pathfinding, unit movement ranges, tactical combat, terrain effects, turn management, and a capable AI opponent. It's ready to play, ready to learn from, and ready to build on.

> 💡 **Perfect for:** Strategy game fans, aspiring game devs, students learning pathfinding & AI, and anyone who wants a solid hex-grid foundation.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Key Features

<div align="center">

| ⬡ **Hex Grid** | 🧭 **Pathfinding** | ⚔️ **Tactical Combat** |
|:---:|:---:|:---:|
| Axial coords, neighbors<br/>& distance | A* over hex<br/>movement costs | Attack ranges,<br/>flanking & cover |

| 🎲 **Turn System** | 🧠 **AI Opponent** | 🎨 **Clean UI** |
|:---:|:---:|:---:|
| Initiative order &<br/>action points | Multi-step plan,<br/>heuristic evaluation | Highlights, tooltips<br/>& unit panels |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🏆 Why This Project

<div align="center">

| 💎 **Advantage** | 📝 **Description** |
|:---|:---|
| ⬡ **Correct Hex Math** | Axial coordinates, correct neighbors, real hex distance — no approximation |
| 🧭 **Real Pathfinding** | A* tuned for hex grids with terrain cost and movement limits |
| ⚔️ **Deep Combat** | Flanking bonuses, cover, ranged vs melee, and status effects |
| 🧠 **Non-Trivial AI** | Evaluates threats, positions units, and plans multi-step moves |
| 🎨 **Polished Presentation** | Movement highlights, animated attacks, damage popups |
| 🧩 **Extendable** | Clear ECS-style structure for adding new units and abilities |

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎬 Game Preview

<div align="center">

```ascii
╔══════════════════════════════════════════════════╗
║  ⬡  Hex Grid Turn-Based  v2.6.0                  ║
╠══════════════════════════════════════════════════╣
║  Turn 4 — Player Phase          ⏳ Time: 00:42   ║
║                                                  ║
║        ⬡ ⬡ ⬡ ⬡ ⬡ ⬡ ⬡                           ║
║       ⬡ ⬡ 🔵 ⬡ ⬡ ⬡ ⬡ ⬡                          ║
║      ⬡ ⬡ ⬡ ⬡ ⬡ 🟢 ⬡ ⬡ ⬡                         ║
║     ⬡ ⬡ 🟢 ⬡ ⬡ ⬡ ⬡ 🔴 ⬡ ⬡                        ║
║      ⬡ ⬡ ⬡ ⬡ ⬡ ⬡ ⬡ 🔴 ⬡                         ║
║       ⬡ ⬡ ⬡ 🏰 ⬡ ⬡ ⬡ ⬡                          ║
║        ⬡ ⬡ ⬡ ⬡ ⬡ ⬡ ⬡                           ║
║                                                  ║
║  🔵 Archer   HP 18/20  AP 2/2  Range 3           ║
║  🟢 Knight   HP 22/25  AP 1/2  Move 3            ║
║  🔴 Enemy    HP 15/20  AP 2/2                    ║
║                                                  ║
║  🎯 Selected: Archer   [ Move ] [ Attack ] [ End]║
║  💡 Hint: 🟢 Knight can flank the red unit        ║
╚══════════════════════════════════════════════════╝
```

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧩 Project Structure

```
⬡ hex-grid-turn-based-game/
├── 🎯 src/
│   ├── grid/                  # Hex grid math & rendering
│   │   ├── hex.gd
│   │   ├── coords.gd
│   │   └── renderer.gd
│   ├── pathfinding/           # A* over hexes
│   ├── combat/                # Damage, range, cover
│   ├── units/                 # Unit types & stats
│   ├── turns/                 # Turn & action system
│   ├── ai/                    # Opponent logic
│   └── ui/                    # HUD & panels
├── 🎨 assets/                 # Sprites & effects
├── 🧪 tests/                  # Grid & AI tests
└── 📖 docs/                   # Setup & extension guide
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

![Godot](https://img.shields.io/badge/Godot_4-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![A-Star](https://img.shields.io/badge/A*_Pathfinding-3C096C?style=for-the-badge&logo=algorithm&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🤝 Community

Found a pathfinding bug? Want to add new units, factions or abilities?

<div align="center">

<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/💬_Join_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="35"/>
</a>
<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/🐞_Report_Issue-3C096C?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>
<a href="https://share.google/OQPzBa2BMUCd0dYZe">
  <img src="https://img.shields.io/badge/⭐_Star_Repo-9D4EDD?style=for-the-badge&logo=github&logoColor=white" height="35"/>
</a>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

### ⬡ Made with 🎲 by the Hex Grid Team

*If this project inspired your next strategy game — star the repo!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=14,6,21&height=120&section=footer" width="100%"/>

</div>
