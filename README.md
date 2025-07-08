# Blackout Facility - Coursera Capstone 🚀

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.x-blueviolet)](https://www.unrealengine.com/)
[![Focus](https://img.shields.io/badge/Focus-Blueprint%20Scripting%20&%20Puzzle%20Design-lightgrey)](https://www.google.com/search?q=game+puzzle+design)
[![Design Type](https://img.shields.io/badge/Design%20Type-First--Person%20Puzzle--Escape-orange)](https://en.wikipedia.org/wiki/Puzzle_video_game)
[![Coursera Certificate](https://img.shields.io/badge/Coursera-Blueprint%20Scripting%20(Completed)-brightgreen?logo=coursera)](<!-- TODO: Add your certificate verification link here -->)
[![Status](https://img.shields.io/badge/Status-Project%20Complete-success)](./)

---

<!--
======================================================================
=== VISUAL SHOWCASE (MAIN VIDEO & HERO IMAGE) ===
======================================================================
-->

<p align="center">
  <!-- TODO: Replace this with your own hero image! A great shot would be the lit-up Central Hub with the active Generator and open Lift Door visible. -->
  <img src="[YOUR HERO IMAGE URL HERE]" alt="Blackout Facility - Hero Image" width="80%"/>
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

This project, **"Blackout Facility,"** was developed by **Fahim Kamal Ahmed** as the capstone assignment for **Course #4: Blueprint Scripting** of the **[Epic Games Game Design Professional Certificate](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)**.

The primary goal was to design and implement a complete, polished game experience driven entirely by a robust, interconnected network of Blueprint systems. The project demonstrates a deep understanding of object-oriented design, event-driven programming, and stateful puzzle mechanics, all while laying the architectural foundation for a more complex stealth game.

---

## 🎯 Overview

**"Blackout Facility"** is a first-person puzzle-escape game built in **Unreal Engine 5**. The player awakens in the dark, abandoned storage room of a multi-story industrial facility. Armed only with a flashlight, they must explore the environment, solve a series of interconnected puzzles to restore power, and navigate a complex office floor to retrieve a valuable objective from the final meeting room. The game emphasizes logical problem-solving and environmental awareness, rewarding players with a dramatic, facility-wide transformation upon completing the main puzzle.

---

## 📜 Game Design Document (GDD)

The entire design philosophy, detailed puzzle flow, gameplay mechanics, and narrative context for "Blackout Facility" are documented in the Game Design Document. This document served as the blueprint for the development process.

<p align="center">
  <!-- TODO: Make sure your GDD pdf is in the repo and update this link if needed! -->
  <a href="./Game Design Document Blackout Facility.pdf" target="_blank">
    <strong>View the Full Game Design Document (PDF)</strong>
  </a>
</p>

---

## ✨ Key Features & Implemented Systems

*   **Universal Interaction System (`BPI_Interactable`):** A clean and efficient interaction system built on a Blueprint Interface. Any object in the world can be made interactable, standardizing how the player engages with the environment.
*   **Advanced Door Mechanics (`BP_Door`):** Doors are complex puzzle elements with multiple states and unlocking mechanisms:
    *   **Key Unlock:** Consumes a key from the player's inventory to permanently unlock.
    *   **Timed Pressure Plate:** Unlocks the door for a limited time, creating a timed challenge.
    *   **Remote Computer Unlock:** Can be unlocked by interacting with a linked `BP_Monitor` terminal.
*   **Automated Lift System (`BP_Lift` & `BP_LiftDoor`):** A fully automated, two-floor elevator system. The lift intelligently communicates with its dedicated doors, closing them before travel and opening them upon arrival for a seamless and immersive transition between floors.
*   **Centralized Power & Light Grid (`BP_PowerGenerator`, `BP_LightController`, `BP_LightSource`):**
    *   The main objective is to find 3 `BP_PowerCell`s to activate the `BP_PowerGenerator`.
    *   Activating the generator triggers a level-wide event dispatcher.
    *   A central `BP_LightController` receives this event and commands all individual `BP_LightSource`s to switch from a dark/flickering state to fully powered on, dramatically changing the environment.
*   **Reactive Electronic Props (`BP_Electronics` Parent Class):** Various props like computer monitors (`BP_Monitor`), keyboards (`BP_Keyboard`), and servers (`BP_Server`) are children of a master `BP_Electronics` class. They all listen for the power-on event and dynamically change their visual state (screens turn on, keys light up, server lights blink to life).
*   **Object-Oriented Architecture:** The project heavily uses parent classes (`BP_CollectibleItem`, `BP_Electronics`) to create a scalable and easy-to-manage hierarchy of game objects, demonstrating clean, object-oriented design principles.

---

## 🗺️ The Player's Journey: A Walkthrough

The game is structured across two distinct floors, each with its own theme and set of challenges.

### Floor 1: The Industrial Zone
The player begins in a dark storage room and must solve a series of non-linear key-and-lock puzzles across four rooms (Storage, Server Room, Office, Weapon Room) to collect three Power Cells. The design offers player agency, with multiple valid paths and a hidden key to reward thorough exploration. The floor culminates in the "Power On" event, a dramatic climax where the entire facility illuminates, granting access to the lift.

### Floor 2: The Corporate Offices
The atmosphere shifts to a clean, corporate environment. The player explores a general office, a break room, and an assistant's office to find a way into the final, locked Meeting Room. This floor features a critical backtracking puzzle, where the player discovers the meeting room's access password is on a now-powered-on computer back in the Server Room on the first floor, forcing them to use their knowledge of the entire facility to progress. The game concludes when the player retrieves the final objective from the Meeting Room.

---

## 🔮 Future Plans: The "Hitman" Evolution

Beyond the course submission, this project was architected as a foundation for a more complex social stealth game, heavily inspired by titles like the *Hitman* series. The goal is to transform this puzzle-escape game into a dynamic, replayable portfolio piece.

*   **NPC Implementation:** The facility will be populated with three types of NPCs: roaming **Security Guards**, **Technicians** on the industrial floor, and **Corporate Employees** on the office floor.
*   **Stealth & Disguise System:** The core gameplay will shift to social stealth. The player will need to avoid guards or find/acquire disguises to blend in and access restricted areas.
*   **Dynamic Objectives:** The final goal will evolve from simply collecting an item to more dynamic scenarios, such as stealing data from a guarded server, or even eliminating a target during the final board meeting.

---

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.x ⚙️
*   **Architecture & Design Patterns:**
    *   **Blueprint Inheritance (Object-Oriented):** Master parent classes for items and electronics.
    *   **Blueprint Interfaces (`BPI_Interactable`):** For a universal interaction system.
    *   **Event Dispatchers:** For efficient, decoupled communication between major systems.
*   **Core Packages Utilized:**
    *   **Unreal Engine First-Person Template:** Used as the base for player character and movement.
    *   **SuperGrid Starter Pack:** Used for rapid prototyping materials and shapes. ([Marketplace Link](https://www.fab.com/listings/a6ab4843-7c8a-47d1-912c-fc1c3553df23))
*   **Unreal Engine Features Used:**
    *   **In-Engine Modeling Tools:** For creating custom static mesh assets.
    *   Blueprint Visual Scripting (Actors, Actor Components).
    *   Custom Trace Channels & Collision.
    *   UMG (for UI prompts).
    *   Material Editor (for dynamic emissive materials).
*   **Version Control:**[ GitHub ](https://github.com/FahimKamal/UE5_MazeEscape)

---

## 📜 Assets & Attributions

*   **Creator (Game Design, Level Design, Blueprint Scripting, 3D Modeling):** Fahim Kamal Ahmed
*   **Custom 3D Models:** All environmental and prop models (chairs, tables, servers, computers, keyboards, cabinets, racks, etc.) were created by the developer from scratch inside Unreal Engine using the built-in Modeling Tools and primitive shapes. This project is a complete blockout/greybox environment built without external modeling software.
*   **Third-Party Assets:**
    *   The final "Crystal" objective is a free asset downloaded from an online source.
    *   This project utilizes the **SuperGrid Starter Pack** for some materials and prototyping shapes.

---

## ⚖️ Licensing

This project ("Blackout Facility" game design, level design, and custom assets) by **Fahim Kamal Ahmed** is licensed under the **MIT License**. Please see the `LICENSE` file for full details. Note that third-party assets are subject to their own licenses.