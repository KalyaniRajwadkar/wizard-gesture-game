# wizard-gesture-game
Gesture-controlled 3D wizard game built with Python, Ursina, OpenCV and MediaPipe
<img width="1774" height="887" alt="706ffb99-d340-4cd7-84ff-7a19b0b870e9" src="https://github.com/user-attachments/assets/500e1302-0d86-409c-81f7-949edfac7cd7" />
<img width="1536" height="1024" alt="eed1a829-0256-4ee3-b70b-734f83bd0b70" src="https://github.com/user-attachments/assets/45d3b817-a1c3-4443-924a-f793bbbde88e" />


# 🧙 Wizard Gesture-Based 3D Game

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Ursina](https://img.shields.io/badge/Ursina-Engine-green)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-red)
![MediaPipe](https://img.shields.io/badge/MediaPipe-HandTracking-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 🌟 Overview

A real-time gesture-controlled 3D fantasy game built with Python.

Players cast spells using real hand gestures detected through webcam tracking powered by MediaPipe.

No buttons.
No hotkeys.
Your hands become your magic.

---

# 🎮 Gameplay Preview

![Gameplay](assets/images/gameplay.png)

---

# ✨ Features

- Real-Time Hand Tracking
- Gesture Recognition
- Fire Magic
- Ice Magic
- Lightning Magic
- Wind Magic
- Dark Magic
- Healing Magic
- Enemy AI
- Spell Casting System
- XP & Leveling
- Boss Battles
- Inventory System
- Future Multiplayer Support

---

# ✋ Hand Tracking

![Hand Tracking](assets/images/hand_tracking.png)

MediaPipe detects hand landmarks and converts gestures into spell commands.

Examples:

✊ = Arcane Shield

✋ = Fire Nova

✌️ = Thunder Bolt

---

# 🪄 Magic System

## 🔥 Fire Magic

![Fireball](assets/images/fireball.png)

| Spell | Damage |
|---------|---------|
| Fire Nova | 25 |
| Inferno Blast | 40 |
| Flame Orb | 30 |
| Solar Strike | 50 |
| Meteor Fall | 100 |

---

## ⚡ Lightning Magic

![Lightning](assets/images/lightning.png)

| Spell | Damage |
|---------|---------|
| Thunder Bolt | 35 |
| Storm Chain | 45 |
| Sky Wrath | 80 |
| Electric Wave | 30 |
| Plasma Surge | 55 |

---

## 🛡️ Defense Magic



| Spell | Effect |
|---------|---------|
| Arcane Shield | Protection |
| Crystal Dome | Area Shield |
| Mirror Barrier | Reflect Damage |
| Guardian Wall | Magic Wall |
| Time Bubble | Slow Enemies |

---

## ❄️ Ice Magic

| Spell | Effect |
|---------|---------|
| Frost Shot | Freeze |
| Ice Prison | Trap |
| Glacier Spear | Ice Damage |
| Snow Burst | Area Freeze |
| Absolute Zero | Ultimate |

---

## 🌑 Dark Magic

| Spell | Effect |
|---------|---------|
| Shadow Bind | Root Enemy |
| Void Sphere | Black Hole |
| Soul Drain | Life Steal |
| Phantom Strike | Teleport |
| Nightmare Curse | Fear |

---

## ✨ Healing Magic

| Spell | Effect |
|---------|---------|
| Healing Light | Heal |
| Nature Blessing | Group Heal |
| Rejuvenation | Regeneration |
| Divine Pulse | Mana Restore |
| Phoenix Grace | Ultimate Heal |

---

# 🎯 Gesture Mapping

```python
SPELLS = {
    "fist": "Arcane Shield",
    "open_palm": "Fire Nova",
    "two_fingers": "Thunder Bolt",
    "swipe_left": "Electric Wave",
    "swipe_right": "Plasma Surge",
    "circle": "Tornado Spin",
    "heart": "Healing Light",
    "both_hands": "Meteor Fall"
}
```

# 🧠 Architecture

![Architecture](assets/images/architecture.png)

```text
Camera Input
      ↓
MediaPipe
      ↓
Hand Detection
      ↓
Gesture Recognition
      ↓
Spell Engine
      ↓
Ursina Engine
      ↓
3D World
```

# 📂 Project Structure

```text
wizard-gesture-game/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── src/
│   ├── main.py
│   ├── hand_tracker.py
│   ├── gesture_detector.py
│   ├── player.py
│   ├── enemy.py
│   ├── spells.py
│   └── game_manager.py
│
├── assets/
│   ├── images/
│   ├── sounds/
│   ├── models/
│   └── textures/
│
├── docs/
│   ├── architecture.md
│   ├── roadmap.md
│   └── GDD.pdf
│
└── screenshots/
```

# 📦 Installation

```bash
python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt
```

# 📦 requirements.txt

```txt
ursina
mediapipe
opencv-python
numpy
```

# 🚀 Run

```bash
python src/main.py
```

# 🛠️ Step-by-Step Development Guide

## Phase 1

- Setup Python
- Create Virtual Environment
- Install Dependencies

## Phase 2

- Camera System
- Open Webcam
- Read Frames

Success:
Camera feed visible.

## Phase 3

- MediaPipe Hand Tracking
- Detect Landmarks

Success:
Hand skeleton visible.

## Phase 4

- Gesture Recognition

Supported:

✊ Shield

✋ Fireball

✌️ Lightning

Success:
Detected spell printed.

## Phase 5

- Build 3D Arena using Ursina

Success:
3D world visible.

## Phase 6

- Player Movement

Success:
Player can move.

## Phase 7

- Spell Casting

Success:
Gesture triggers spell.

## Phase 8

- Enemy System

Success:
Enemy spawns.

## Phase 9

- Combat System

Success:
Enemy takes damage.

## Phase 10

- UI System

Features:

- Health Bar
- Mana Bar
- XP Bar

## Phase 11

- XP & Leveling

## Phase 12

- Boss Battles

## Phase 13

- Inventory

## Phase 14

- Skill Tree

## Phase 15

- Sound System

## Phase 16

- Save Game

## Phase 17

- Multiplayer

## Phase 18

- Open World Expansion

---

# 🎨 Asset Creation Guide

## Images Folder

```text
assets/images/
```

Required:

```text
banner.png
gameplay.png
hand_tracking.png
fireball.png
shield.png
lightning.png
architecture.png
wizard_ui.png
roadmap.png
```

## Banner Prompt

```text
Epic fantasy wizard standing in a dark magical arena,
blue magical energy,
fireball in one hand,
lightning in the other,
cinematic lighting,
AAA game artwork,
8k
```

## Gameplay Prompt

```text
Fantasy wizard battle,
fireball attack,
enemy monster,
3D environment,
game screenshot,
health bars,
cinematic camera
```

## Hand Tracking Prompt

```text
Computer vision hand tracking,
mediapipe landmarks,
webcam interface,
AI gesture recognition
```

## Fireball Prompt

```text
Huge magical fireball,
fantasy VFX,
transparent background
```

## Shield Prompt

```text
Blue magical shield,
energy barrier,
fantasy spell,
transparent background
```

## Lightning Prompt

```text
Lightning spell effect,
electric energy,
transparent background
```

---

# 🔊 Sound Assets

Folder:

```text
assets/sounds/
```

Required:

```text
fireball.wav
lightning.wav
shield.wav
ambient.wav
boss.wav
victory.wav
```

---

# 🧙 Models

Folder:

```text
assets/models/
```

Required:

```text
wizard.glb
enemy.glb
wand.glb
boss.glb
portal.glb
```

---

# 📈 Roadmap

## Version 1

- Hand Tracking
- Gesture Recognition

## Version 2

- Spell Casting

## Version 3

- Enemy AI

## Version 4

- Boss Battles

## Version 5

- Inventory

## Version 6

- Multiplayer

## Version 7

- Open World Academy

---

# 🔮 Future Features

- Voice Spells
- Wand Tracking
- Quest System
- PvP Arena
- Guild System
- VR Mode
- AR Mode
- AI Bosses

---

# 🤝 Contributing

Pull requests are welcome.

---

# 📜 License

MIT License

---

# ⭐ Support

If you like this project, please give it a star.

Made with ❤️ using Python, Ursina, OpenCV and MediaPipe.
