# 🌱 Cultivation - Advanced Farming Addon for Slimefun

[![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.6-brightgreen.svg)](https://www.spigotmc.org/)
[![Slimefun](https://img.shields.io/badge/Slimefun4-RC--37-blue.svg)](https://github.com/Slimefun/Slimefun4)
[![Java Version](https://img.shields.io/badge/Java-21-orange.svg)](https://www.java.com/)

A Slimefun4 addon that adds a plethora of magical and non-magical flora to Minecraft, featuring an advanced breeding system, custom trees, and a fully-featured kitchen system. Using Minecraft's Display Entities, plants and blocks are displayed like you've never seen before.

---

## 🚀 Features

### 🌾 Cultivation Plants
- **90 unique plants** to discover through breeding
- **Advanced breeding system** with genetic traits (10/10/10 max stats)
- **Three stats**: Growth Speed, Drop Amount, and Breed Strength
- **Cross-breeding mechanics** - combine plants to create new varieties
- **Crop stick system** - required for growth and breeding
- **Leveling system** - improve your plants over time
- Resource generation for vanilla Minecraft items

### 🌳 Cultivation Trees
- **Beautiful custom-built trees** with unique designs
- **Fruit-bearing** - pluck ripe fruits directly from trees
- **20% sapling drop** from leaves for replanting
- **Multiple tree varieties** including Oak, Birch, Cherry, Mangrove, and more
- Purchase saplings from Fletching Villagers

### 🌿 Cultivation Bushes
- **Simple resource production** - no breeding or leveling required
- **Foodstuff generation** for kitchen recipes
- **Multiple bush varieties** producing different ingredients
- Purchase bushes from Farmer Villagers

### 🏭 Garden Cloche
- **Automated plant production** system
- **Slimefun Cargo compatible** for full automation
- **Networks integration** for advanced setups
- Slower than manual harvesting but runs constantly

### 🍳 The Kitchen System
- **7 processing machines**:
  - Chopping Board
  - Slicer
  - Boiler
  - Blender
  - Grinder
  - Fryer
  - Masher
- **2 cooking machines**:
  - Oven (Cooking/Baking)
  - Finishing Station
- **Custom food effects** lasting 10 minutes
- **Hundreds of recipes** using Cultivation and vanilla foods
- **Unique one-off effects** for special foods

### 📚 Discovery System
- **Wandering Traders** sell breeding hint documents
- **Unlock system** tracks discovered plants
- **Progressive gameplay** - discover combinations yourself

---

## 📋 Requirements

### Server
- **Minecraft**: 1.20.6
- **Server Software**: Spigot or Paper 1.20.6
- **Java**: 21 or higher
- **Slimefun4**: RC-37 or newer

---
## 📦 Installation

### For Server Administrators

1. **Install Slimefun4**
   - Download from [Slimefun4 Builds](https://blob.build/project/Slimefun4)
   - Place in `/plugins/` folder

2. **Install Cultivation**
   - Download the latest `.jar` from [releases](https://github.com/Sefiraat/Cultivation/releases)
   - Place in `/plugins/` folder

3. **Restart Server**
   ```bash
   stop
   # Wait for complete shutdown
   # Start server again
   ```

4. **Verify Installation**
   - Check console for `[Cultivation] has been enabled!`
   - Open Slimefun guide in-game
   - Look for Cultivation categories

---

## 📖 Documentation

For a complete guide to Cultivation, visit the [Documentation Pages](https://sefiraat.dev)

---

## 🎮 Getting Started

### Basic Plant Breeding

1. **Craft Crop Sticks** from the Slimefun guide
2. **Place crop sticks** on farmland
3. **Plant your first seeds** (available in Slimefun guide)
4. **Wait for growth** - plants will grow over time
5. **Double crop stick** adjacent plants to enable breeding
6. **Discover new plants** through cross-breeding

### Using the Kitchen

1. **Harvest produce** from plants, bushes, or trees
2. **Process ingredients** using kitchen machines
3. **Combine by-products** in the Oven or Finishing Station
4. **Enjoy custom effects** from your cooked meals

---

## 🛠️ Development

### Building from Source

```bash
git clone https://github.com/Sefiraat/Cultivation.git
cd Cultivation
mvn clean package
```

The compiled `.jar` will be in the `target/` folder.

### Requirements
- Java 21 JDK
- Maven 3.6+
- Git

---

## 🙏 Credits & Thanks

### Special Thanks
- **SlimefunAddonCommunity** - Guinea pig testers
- **MCTantrum** (B, Decoy, and Oddish) - Extensive testing and feedback
- **GentlemanCheesy** - Custom skull designs from Netheopoiesis
- **[Minecraft-Heads.com](https://minecraft-heads.com/)** - Permission to use custom player heads


### Original Authors
- **Sefiraat** - Original creator and lead developer
- **J3fftw** - Contributor
- **JustAHuman** - Contributor

---

## 📄 License

This project is licensed under the **GPL-3.0 License** - see the [LICENSE](LICENSE) file for details.

---

## 🐛 Bug Reports & Suggestions

Found a bug or have a suggestion? Please open an issue on the [GitHub Issues](https://github.com/Sefiraat/Cultivation/issues) page.

---

## 📸 Screenshots

<p align="center">
<img width="500" src="https://user-images.githubusercontent.com/20646323/231161480-7b6bd303-cec9-4555-aa40-5c502aaa031b.png"><br>
<em>Cultivation Logo</em>
</p>

<p align="center">
<img width="1047" alt="Cultivation Plants Display" src="https://user-images.githubusercontent.com/20646323/231163325-3749560b-f998-4399-8a60-a4bb5c0b6fcd.png"><br>
<em>Plants displayed using Display Entities</em>
</p>

<p align="center">
<img width="1355" alt="Plant Breeding System" src="https://user-images.githubusercontent.com/20646323/231164447-be56b8b1-cc92-486d-a2ec-97cec27a438d.png"><br>
<em>Advanced plant breeding mechanics</em>
</p>

<p align="center">
<img height="300" alt="Garden Cloche" src="https://user-images.githubusercontent.com/20646323/231168642-9208af2b-d40a-4d75-8da8-c8deeed1703e.png"><br>
<em>Automated Garden Cloche</em>
</p>

<p align="center">
<img width="1195" alt="Cultivation Bushes" src="https://user-images.githubusercontent.com/20646323/231167783-0367929f-be68-476c-8637-de68267b3ed1.png"><br>
<em>Various bush types</em>
</p>

<p align="center">
<img width="1108" alt="Cultivation Trees" src="https://user-images.githubusercontent.com/20646323/231168164-fa57deee-e4fb-4463-9439-56b729cd4229.png"><br>
<em>Custom-built fruit trees</em>
</p>

<p align="center">
<img width="1391" alt="Kitchen System" src="https://user-images.githubusercontent.com/20646323/231169938-c94116a1-2064-4cb1-85e8-2ecd14b6d61e.png"><br>
<em>Complete kitchen processing system</em>
</p>
