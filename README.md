# Crystal Chronicles - Final Fantasy Clone

## 🎮 Play Now!

**[▶ Play Crystal Chronicles Live!](https://imrope2-boop.github.io/crystal-chronicles-ff-clone/)**

A fully playable Final Fantasy-style RPG built with pure HTML5 Canvas — no dependencies, no build tools needed!

---

## ✨ Features

- **4 Unique Characters**: Warrior, Black Mage, White Mage, and Thief
- **Turn-Based Combat**: Classic JRPG battle system with menus
- **23 Spells**: Fire/Fira/Firaga, Blizzard/Blizzara/Blizzaga, Thunder/Thundara/Thundaga, Cure/Cura/Curaga, Quake, Meteor, Drain, Bio, Holy, Shell, Protect, Haste, Esuna, Life
- **15 Enemy Types**: Including 5 Boss Monsters (Lich, Marilith, Kraken, Tiamat, Chaos)
- **Explorable World Map**: 20×15 tile grid with grass, forests, water, mountains, desert, roads, snow
- **5 Towns with Shops**: Buy potions, ethers, elixirs, phoenix downs, and more
- **Item System**: Full inventory with 8 item types, purchasable/usable in battle
- **Level Up System**: Gain EXP from battles, level up, learn new spells, stat growth
- **Menu System**: Status, Items, Magic, and Save screens
- **Save/Load**: Browser localStorage save system
- **Pixel Art Style**: Everything drawn with HTML5 Canvas 2D API
- **Boss Battles**: Triggered at dungeons and caves on the world map
- **Particle Effects**: Visual spell/attack animations
- **Beautiful Title Screen**: Animated crystals, stars, and gold logo

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| Arrow Keys | Move on world map / Navigate menus |
| Z / Enter / Space | Confirm / Select |
| X / Escape | Cancel / Back |
| M / I | Open field menu |

### Battle Controls
- **Arrow Keys** — navigate action menu, select targets
- **Z/Enter** — confirm selection
- **X/Esc** — go back

---

## 🗺️ World Map

The world contains:
- **5 Towns** — Cornelia, Pravoka, Elfheim, Crescent Lake, Melmond
- **2 Caves** — Ice Cave, Marsh Cave
- **1 Dungeon** — Chaos Shrine (final boss area!)
- **Random Encounters** — different enemy tables for grass, forest, caves, and dungeons

---

## 👾 Characters

| Character | Class | Role |
|-----------|-------|------|
| WARRIOR | Warrior | Physical tank, high HP/DEF/STR |
| MAGE | Black Mage | Magic damage, elemental spells |
| HEALER | White Mage | Healing, buffs, revival magic |
| THIEF | Thief | Fast physical attacker |

---

## 🧙 Spell System

Spells are learned automatically on level up. Each spell costs MP to cast.

- **Fire/Fira/Firaga** — Fire elemental damage (single target)
- **Blizzard/Blizzara/Blizzaga** — Ice elemental damage
- **Thunder/Thundara/Thundaga** — Lightning damage
- **Quake** — Earth magic hits ALL enemies
- **Meteor** — Massive non-elemental hits ALL enemies
- **Cure/Cura/Curaga** — Restore HP to one ally
- **Drain** — Steal HP from enemy
- **Life** — Revive a fallen ally
- **Esuna** — Cure all status effects

---

## 💻 Technical Details

- **Pure HTML5 Canvas** — no libraries, no frameworks
- **Single file** — everything in `index.html`
- **~50KB** — runs instantly in any modern browser
- **60fps game loop** with `requestAnimationFrame`
- **Pixel art rendering** with `image-rendering: pixelated`

---

## 🚀 Run Locally

Just open `index.html` in any modern browser — no server required!

```bash
git clone https://github.com/imrope2-boop/crystal-chronicles-ff-clone.git
cd crystal-chronicles-ff-clone
# Open index.html in your browser
```

---

*Built as a tribute to the classic Final Fantasy series. All original code.*
