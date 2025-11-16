# Save the Axolotl — Your First 2D Game (Xogot & Godot Tutorial)

Save the Axolotl is a friendly, beginner-focused project that teaches the basics of the Godot game engine while using the Xogot editor. It's a complete, adapted version of the classic Godot tutorial "Your First 2D Game" (also known as "Dodge the Creeps") with a new theme and assets: your goal is to protect the Xogot mascot — a cute little axolotl — from predators coming from all directions.

This repository contains the finished project used in the Xogot tutorial "Your First 2D Game" so you can open, explore, and run the completed example, or follow the tutorial to build it step-by-step.

- Project: xogot-projects/your-first-2d-game
- Tutorial name: Save the Axolotl (adaptation of "Dodge the Creeps")

---

## What you'll learn

- Godot scene system and nodes (2D)
- Scripting with GDScript (game logic, input, spawning)
- Basic physics and collision detection
- UI basics (score, game over)
- Asset setup (sprites, animations, audio)
- Workflow using the Xogot editor

This project is intended for beginners or anyone who wants a guided introduction to building a small 2D game in Godot, but it does expect some programming familiarity.

---

## Preview

![Preview](https://github.com/user-attachments/assets/da10ec70-5745-4f14-b730-2b402c6a86b2)

---

## Requirements

- Xogot editor (to follow the Xogot-specific tutorial steps and editor workflow).
- This was designed for iPad and is built to run with Xogot, but can load in Godot desktop.

---

## Quick start

1. Clone the repository
   - HTTPS: git clone https://github.com/xogot-projects/your-first-2d-game.git
   - SSH: git clone git@github.com:xogot-projects/your-first-2d-game.git

2. Open the project
   - Using Xogot: Open Xogot → Open Project → select this repository folder.
   - Using Godot: Open Godot → Import or Open (select the project.godot or project.godot4 file as appropriate).

3. Run the game
   - Open the main scene `res://scenes/Main.tscn` and press Play.
   - If the project has a project-wide main scene configured, pressing Play in the Godot editor will launch it.

---

## Controls

- Keyboard: Arrow keys or WASD to move the Axolotl (player).
- Mouse / Touch: (If supported) Touch or click to move, depending on input implementation.
- The game uses simple input so you can test with keyboard on desktop.

(Adjust control notes if the implementation differs — check `scripts/player.gd` or similar.)

---

## Project structure (high level)

- assets/ — sprites, audio, and other media used by the project
- scenes/ — Godot scenes (player, enemy, main, UI)
- scripts/ — GDScript files implementing game logic
- ui/ — UI elements (score display, menus)
- project.godot or project.godot4 — Godot project file

Open these folders in the editor to explore how the tutorial organizes scenes and code.

---

## How this differs from the original tutorial

- Theme: "Dodge the Creeps" → "Save the Axolotl" with Xogot mascot and custom sprites.
- Example assets and names have been updated to reflect the Xogot branding and the axolotl character.
- The core gameplay and learning goals remain the same: spawning enemies, moving a player, detecting collisions, and tracking score.

---

## Tips for learning

- Step through the scenes and open scripts to read how each piece of functionality is implemented.
- Run the game, then pause and inspect node properties at runtime to see how values change.
- Try modifying parameters (spawn rate, enemy speed, player speed) to observe gameplay differences.
- If you get stuck, compare the scene tree and script files to the corresponding steps in the Xogot tutorial.

---

## Troubleshooting

- If sprites or audio are missing: make sure `assets/` folder contents weren't altered or moved.
- If the game doesn't run: verify you're opening the correct Godot project file and using a compatible Godot version.
- If using Xogot — ensure your Xogot installation is up-to-date

---

Thanks for checking out Save the Axolotl! Open the project in Xogot or Godot and start exploring — it's a great way to learn how small games are structured and built.
