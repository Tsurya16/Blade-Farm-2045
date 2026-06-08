# Blade Farm 2045

A 2D farming simulation game built in Unity where players manage crops, explore different areas, and progress through multiple days of gameplay.

Link ddownload APK: https://drive.google.com/file/d/1wov29QfT1S8RB6hA0mdxuCy4k0I0FFEV/view?usp=sharing

## 🎮 Game Overview

Blade Farm 2045 is an immersive farming simulation where players cultivate crops, manage resources, and experience a story-driven adventure across multiple days. The game features a complete farming ecosystem with growth cycles, inventory management, and scene transitions.

## ✨ Key Features

### 🌱 Advanced Farming System

-   **Multiple Crop Types**: Grow tomatoes, rice, cucumbers, and cabbage
-   **5-Phase Growth Cycle**: Each crop progresses through seeding, 4 growth phases, and harvest
-   **Realistic Growth Mechanics**: Crops persist and continue growing between game sessions
-   **Tile-Based Farming**: Plow tiles, plant seeds, and harvest crops on a grid system

### 🎒 Comprehensive Inventory System

-   **Dual Inventory Setup**: Backpack for storage and toolbar for quick access
-   **Drag & Drop Interface**: Intuitive item management
-   **Persistent Data**: Inventory saves between scenes and game sessions
-   **Item Categories**: Tools, seeds, crops, and collectibles

### 🏃‍♂️ Player Systems

-   **Stamina Management**: Actions consume stamina that regenerates over time
-   **Tool Usage**: Hoe for plowing, seeds for planting, hands for harvesting
-   **Movement & Interaction**: Smooth character movement with object interaction

### 🎬 Cutscene System

-   **Dialog System**: Text animation with pagination support
-   **Skip Functionality**: Players can skip cutscenes to jump to next day
-   **Story Integration**: Narrative elements woven into gameplay

### 🌅 Day/Night Cycle

-   **Multi-Day Progression**: Game spans 7 days with unique content
-   **Sleep Mechanics**: Use beds to transition between days
-   **Video Transitions**: Smooth transitions with sleep animations
-   **Scene Management**: Automatic scene loading and data persistence

### 💾 Save System

-   **Automatic Saving**: Game state saves on scene transitions
-   **Persistent Crops**: Planted crops maintain growth state between sessions
-   **Inventory Persistence**: Items and quantities preserved across gameplay
-   **Scene Data**: Each area maintains its own tile and object states

## 🛠️ Technical Architecture

### Core Systems

-   **TileManager**: Handles crop growth, tile states, and farming mechanics
-   **SceneTransitionManager**: Manages day transitions and scene loading
-   **InventoryManager**: Controls item storage and UI interactions
-   **StaminaManager**: Tracks and regenerates player energy
-   **CutsceneController**: Manages story sequences and dialog

### Save Data Structure

```csharp
- GameSaveData
  ├── Tile data by scene (crop states, growth phases)
  ├── Inventory data (backpack + toolbar)
  └── Current day progression
```

### Supported Platforms

-   **Unity Version**: 2021.3.45f1
-   **Target Platforms**: PC (Windows), with potential for mobile adaptation
-   **Rendering**: Universal Render Pipeline (URP)

## 🎯 Gameplay Loop

1. **Morning**: Wake up in your bed, plan your farming activities
2. **Farming**: Plow fields, plant seeds, water and tend crops
3. **Exploration**: Move between different areas and scenes
4. **Harvesting**: Collect mature crops for resources
5. **Evening**: Rest in bed to advance to the next day
6. **Progression**: Watch crops grow and story unfold over 7 days

## 🌾 Crop System Details

### Growth Phases

Each crop follows this progression:

1. **Seeding** (Day 0) - Just planted
2. **Phase 1** (Day 1) - Initial sprouting
3. **Phase 2** (Day 2) - Early growth
4. **Phase 3** (Day 3) - Mid development
5. **Phase 4** (Day 4) - Pre-harvest
6. **Harvest** (Day 5+) - Ready for collection

### Supported Crops

-   **Tomatoes**: High-value crop with longer growth cycle
-   **Rice**: Staple crop for consistent harvests
-   **Cucumbers**: Fast-growing vegetable
-   **Cabbage**: Leafy green with moderate growth time

## 🎨 Art & UI

### Visual Style

-   **2D Pixel Art**: Charming retro-inspired graphics
-   **Tile-Based World**: Clean, organized farming areas
-   **Animated Sprites**: Character and crop animations
-   **UI Elements**: Custom inventory, stamina, and dialog interfaces

### User Interface

-   **Inventory Grid**: Visual item management
-   **Stamina Bar**: Real-time energy tracking
-   **Dialog System**: Story text with skip options
-   **Scene Transitions**: Smooth video-based day changes

## 🔧 Setup & Installation

### Prerequisites

-   Unity 2021.3.45f1 or newer
-   TextMeshPro package
-   Universal Render Pipeline

### Getting Started

1. Clone the repository
2. Open project in Unity
3. Ensure all required packages are installed
4. Load the main scene to start playing
5. Use WASD for movement, E for interactions

## 🎮 Controls

-   **WASD**: Character movement
-   **E**: Interact with objects (beds, crops, etc.)
-   **Mouse**: Inventory management (drag & drop)
-   **Escape**: Skip cutscenes (when available)

## 📁 Project Structure

```
Assets/
├── Scripts/
│   ├── Player.cs              # Player controller and inventory
│   ├── TileManager.cs         # Farming system management
│   ├── SceneTransitionManager.cs # Day/scene transitions
│   ├── InventoryManager.cs    # Item and storage system
│   ├── StaminaManager.cs      # Energy system
│   ├── Bed.cs                # Sleep interaction
│   ├── SaveSystem.cs          # Data persistence
│   └── UI/                    # User interface scripts
├── Cutscene/
│   └── CutsceneController.cs  # Story and dialog system
├── Sprites/                   # Game artwork and UI
├── Scenes/                    # Game levels (Day1-Day7)
└── Prefabs/                   # Reusable game objects
```

## 🚀 Future Enhancements

-   **Weather System**: Rain affects crop growth
-   **Market System**: Sell crops for currency
-   **Tool Upgrades**: Improved farming equipment
-   **Animal Husbandry**: Livestock management
-   **Multiplayer Support**: Cooperative farming
-   **Seasonal Events**: Special crops and activities

## 🤝 Contributing

This is a personal project, but feedback and suggestions are welcome! Feel free to:

-   Report bugs or issues
-   Suggest new features
-   Share gameplay feedback
-   Contribute art or assets

## 📜 License

This project uses various assets with their respective licenses:

-   **TextMeshPro Fonts**: SIL Open Font License
-   **UI Assets**: ElvGames Free Inventory Pack
-   **Code**: Custom implementation

## 👨‍💻 Developer

Created as a learning project to explore Unity game development, farming simulation mechanics, and comprehensive save systems.

---

_Experience the peaceful joy of farming in Blade Farm 2045 - where every seed planted is a step toward a bountiful future!_ 🌱
