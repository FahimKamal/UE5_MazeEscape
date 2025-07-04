# Blackout Facility - Coursera Capstone (Project In Development) 🚀

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.x-blueviolet)](https://www.unrealengine.com/)
[![Focus](https://img.shields.io/badge/Focus-Blueprint%20Scripting%20&%20Puzzle%20Design-lightgrey)](https://www.google.com/search?q=game+puzzle+design)
[![Design Type](https://img.shields.io/badge/Design%20Type-First--Person%20Puzzle--Escape-orange)](https://en.wikipedia.org/wiki/Puzzle_video_game)
[![Coursera Certificate](https://img.shields.io/badge/Coursera-Blueprint%20Scripting%20(In%20Progress)-0056D2?logo=coursera)](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow)](./)

---

<!--
======================================================================
=== VISUAL SHOWCASE (MAIN VIDEO & HERO IMAGE) ===
======================================================================
-->

<p align="center">
  <!-- TODO: Replace this with your own hero image! -->
  <img src="[YOUR HERO IMAGE URL HERE - e.g., A dramatic shot of the dark facility with your flashlight on]" alt="Blackout Facility - Hero Image" width="80%"/>
  <br>
  <em>A representative hero image of the "Blackout Facility" escape room.</em>
</p>

<p>
  <br>
  <!-- TODO: Replace this with a link to YOUR playtesting video once recorded! -->
  <em>Playtesting Video of the "Blackout Facility" prototype.</em>
  <a href="[YOUR YOUTUBE VIDEO URL HERE]" target="_blank">
    Watch the Gameplay Showcase on YouTube.
  </a>
</p>

---

## 🎓 Project Context & Motivation

This project, **"Blackout Facility,"** is being developed by **Fahim Kamal Ahmed** as the capstone assignment for **Course #4: Blueprint Scripting** of the **[Epic Games Game Design Professional Certificate](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)** offered on Coursera.

The project is being built from the ground up using the standard Unreal Engine First-Person template to focus entirely on the application of Blueprint scripting principles. The primary goal is to translate the conceptual Game Design Document (GDD) into a fully playable, interactive, and logical puzzle-escape game. The focus is on implementing core gameplay mechanics, event-driven programming, and robust interaction systems—all built exclusively with Blueprints. This repository documents the development process and will showcase the completed game.

---

## 🎯 Overview

**"Blackout Facility"** is a first-person puzzle-escape game built in **Unreal Engine 5**. The player awakens in a dark, two-story industrial complex without memory. They must explore, solve environmental puzzles, manage a simple inventory of key items, restore power to the facility, and navigate a logical sequence of challenges to find the exit.

The game is designed around a **first-person perspective** to enhance immersion and the feeling of isolation. The core experience is a loop of **Observe, Solve, and Progress**, challenging the player's logic and spatial awareness. This project aims to be a complete, self-contained game experience that demonstrates a strong command of Blueprint scripting for gameplay creation.

---

## 📜 Game Design Document (GDD)

The entire design philosophy, detailed puzzle flow, gameplay mechanics, and narrative context for "Blackout Facility" are documented in the Game Design Document. This document serves as the blueprint for the development process.

<p align="center">
  <!-- TODO: Make sure your GDD pdf is in the repo and update this link if needed! -->
  <a href="./Game Design Document Blackout Facility.pdf" target="_blank">
    <strong>View the Full Game Design Document (PDF)</strong>
  </a>
</p>

---

## 🗺️ Level Map Overview

Below is the conceptual map that guides the construction of the "Blackout Facility," illustrating the two floors, key rooms, and the intended player path.

<p align="center">
  <!-- TODO: Replace this with your own map image! You can screenshot it from your GDD. -->
  <img src="[YOUR LEVEL MAP IMAGE URL HERE]" alt="Blackout Facility Level Map" width="75%"/>
  <br>
  <em>Top-down conceptual map of the two-floor facility.</em>
</p>

---

## ✨ Key Goals & Features (To Be Achieved with Blueprints)

*   🔩 **Robust Interaction System:** A flexible, interface-driven system (`BPI_Interact`) allows the player to seamlessly interact with any puzzle element in the world.
*   🔑 **"Keychain" Inventory System:** A lightweight actor component (`AC_InventorySystem`) manages puzzle-critical items without needing a complex UI, enabling automatic key-and-lock mechanics.
*   🔦 **Dynamic Player Abilities:** Core mechanics like a toggleable flashlight, crouching, and sprinting are implemented on the player character.
*   💡 **Environmental State Changes:** A major, level-wide lighting shift occurs when the player solves the generator puzzle, transforming the gameplay environment from dark and suspenseful to bright and clinical.
*   🧩 **Diverse Puzzle Mechanics:** The game will feature a variety of puzzles built with Blueprints, directly reflecting the course content:
    *   **Physics-Based:** Pushing objects to reveal paths.
    *   **Triggers:** Hidden pressure plates that alter the environment.
    *   **Item Placement:** Using collected "Fusion Cores" to power a machine.
    *   **Timed Events:** A door that stays open for a limited time.
    *   **Sequence Puzzles:** Levers that must be pulled in a specific order.
*   📄 **GDD Adherence:** The gameplay systems and level flow from the GDD are to be fully translated into a playable, interactive 3D game.
*   🖥️ **Minimalist UI/HUD:** Contextual interaction prompts and temporary item notifications (`UMG Widgets`) provide necessary feedback without cluttering the screen.
*   📦 **Complete Game Loop:** The project will be a complete, packaged game with a start menu, a win condition, and a clear beginning and end.

---

## 📜 Certificate of Completion - Blueprint Scripting

<!-- TODO: Once you complete the course, replace the placeholder image and update the links! -->
This section will showcase the certificate earned upon successful completion of the "Blueprint Scripting" course.

<p align="center">
  <img src="[YOUR CERTIFICATE IMAGE URL HERE]" alt="Certificate for Blueprint Scripting" width="70%"/>
  <br>
  <em>Certificate of Completion - Blueprint Scripting.</em>
  <br>
  <a href="[YOUR COURSERA VERIFICATION URL HERE]" target="_blank">
    <strong>Verify Certificate</strong>
  </a>
</p>

---

## 📸 Development Screenshots (In-Progress)

<!-- TODO: As you build the level, add screenshots here! -->
<p align="center">
  <img src="[URL for Screenshot 1 - e.g., The dark maintenance room]" alt="Floor 1 View" width="45%"/>
  <img src="[URL for Screenshot 2 - e.g., The generator room before activation]" alt="Generator Room" width="45%"/>
  <br/>
  <img src="[URL for Screenshot 3 - e.g., The lit-up logic floor]" alt="Floor 2 View" width="45%"/>
  <img src="[URL for Screenshot 4 - e.g., The lever puzzle]" alt="Lever Puzzle" width="45%"/>
</p>

---

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.x ⚙️
*   **Core Assets Utilized:**
    *   **Unreal Engine First-Person Template:** Used as the base for player character and movement.
    *   **No external assets:** All puzzle logic and gameplay systems are built from scratch with Blueprints.
*   **Unreal Engine Features Used:**
    *   Blueprint Visual Scripting (Actors, Actor Components, Game Mode)
    *   Blueprint Interfaces (for interaction)
    *   Event-Driven Programming & Timers
    *   Line Traces (for interaction detection)
    *   UMG (Unreal Motion Graphics) for HUD and Widgets
    *   Physics Actors & Collision (Triggers)
    *   Basic Lighting & Level Design Tools
    *   Project Packaging/Build System
*   **Design Document:** [Game Design Document (GDD) for "Blackout Facility"](./Game Design Document Blackout Facility.pdf)
*   **Course:** [Blueprint Scripting](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate) (Epic Games / Coursera)
*   **Version Control:** GitHub ([YOUR GITHUB REPO URL HERE])
*   **Documentation:** Markdown (for this README)

---

## 📊 Project Status (As of July 4, 2025)

*   ✅ **Project Definition & Foundation:** Scope defined in the GDD. Project initialized using the UE First-Person Template.
*   ⏳ **Implement Core Player Mechanics:** Flashlight, Crouch, Sprint functionality.
*   ⏳ **Build Core Gameplay Systems:**
    *   `BPI_Interact` Interface.
    *   `AC_InventorySystem` Component.
*   🔲 **Greybox & Implement Floor 1:**
    *   Blockout layout for Rooms 1-A, 1-B, 1-C, 1-D.
    *   Implement Maintenance Key & Door puzzle.
    *   Implement Hidden Pressure Plate puzzle.
    *   Implement Timed Door puzzle.
    *   Implement Generator & Fusion Core puzzle.
*   🔲 **Greybox & Implement Floor 2:**
    *   Blockout layout for Rooms 2-A, 2-B, 2-C, 2-D.
    *   Implement Lever Sequence puzzle.
    *   Implement crouch/platforming puzzle.
    *   Implement final pressure plate puzzle.
    *   Implement the final "Escape Beacon" win condition.
*   🔲 **UI & Menus:** Create Main Menu and Pause Menu.
*   🔲 **Audio Pass:** Add placeholder sound effects for key interactions.
*   🔲 **Playtesting & Iteration:** Test for bugs, puzzle clarity, and game flow.
*   🔲 **Finalize Project:** Create packaged build, record gameplay video, and submit.
*   🔲 **Receive Course Certificate:** Complete the course.

---

## 🌱 Learning & Development Focus

This project is designed to build and demonstrate proficiency in:

*   **Blueprint Scripting Fundamentals:** Mastering the creation and use of variables, functions, macros, and flow control.
*   **Event-Driven & Object-Oriented Principles:** Creating self-contained, reusable Blueprints that communicate effectively.
*   **Robust Interaction Design:** Building a scalable interaction system using Blueprint Interfaces.
*   **Gameplay Systems Architecture:** Designing and implementing core systems like an inventory and stateful puzzles.
*   **Problem Solving:** Translating GDD requirements into functional, logical code within the Blueprint system.
*   **UI/UX Implementation:** Using UMG to provide essential player feedback.
*   **Full Project Lifecycle:** Taking a game from a design document through development, testing, and final packaging.

---

## 🔮 Future Plans (Post-Course Development for Portfolio Enhancement)

Once the course requirements are met, this project could be enhanced for a portfolio:

*   🎨 **Art Pass:** Replace the greybox assets with a cohesive set of industrial or sci-fi environment assets to give the facility a distinct visual identity.
*   📖 **Narrative Deepening:** Add environmental storytelling elements like notes, audio logs, or computer terminals that reveal the backstory of the facility.
*   🧩 **Puzzle Complexity:** Introduce more complex logic puzzles, perhaps involving combining items or multi-stage sequences.
*   🎧 **Audio Polish:** Implement a full sound-scape with ambient background loops, distinct footstep sounds, and higher-quality SFX.
*   ⚙️ **Refine Systems:** Add features like a more detailed options menu or controller support.

---

## 📜 Assets & Attributions

*   **Course:** This project is an assignment for the "Blueprint Scripting" course by Epic Games on Coursera.
*   **Core Assets Utilized in this Project:**
    *   **Unreal Engine First-Person Template:** Provided by Epic Games, Inc., and subject to the Unreal Engine EULA.
*   **Creator (Game Design, Level Design, Blueprint Scripting):** Fahim Kamal Ahmed

---

## ⚖️ Licensing

This project ("Blackout Facility" game design, level design, and its specific assembly of assets) by **Fahim Kamal Ahmed** is licensed under the **MIT License**. Please see the `LICENSE` file in this repository for the full license text.