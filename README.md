# Blackout Facility - Coursera Capstone (Project Complete & Certified!) 🏆

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.5.4-blueviolet)](https://www.unrealengine.com/)
[![Focus](https://img.shields.io/badge/Focus-Blueprint%20Scripting%20&%20Puzzle%20Design-lightgrey)](https://www.google.com/search?q=puzzle+game+design)
[![Design Type](https://img.shields.io/badge/Design%20Type-First--Person%20Puzzle--Escape-orange)](https://en.wikipedia.org/wiki/Puzzle_video_game)
[![Coursera Certificate](https://img.shields.io/badge/Coursera-Blueprint%20Scripting%20(Certified)-0056D2?logo=coursera)](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)
[![Status](https://img.shields.io/badge/Status-Project%20Complete%20&%20Certified-success)](./)

---

<!--
======================================================================
=== VISUAL SHOWCASE (MAIN VIDEO & HERO IMAGE) ===
======================================================================
-->

<p align="center">
  <img src="https://github.com/user-attachments/assets/3405319c-a441-49cf-91dd-64fb418caff2" alt="Blackout Facility - Hero Image" width="80%"/>
  <br>
  <em>A representative hero image of the completed "Blackout Facility."</em>
</p>

<p>
  <br>
  <em>Playtesting Video of the completed "Blackout Facility" game.</em>
  <!-- TODO: Replace this with a link to YOUR playtesting video once recorded! -->
  <a href="https://youtu.be/P9MyNKpGvYM?si=p5N358MyeFH3Fjp5" target="_blank">
    Watch the Full Gameplay Showcase on YouTube.
  </a>
</p>

---

## 🎓 Project Context & Motivation

This project, **"Blackout Facility,"** was developed by **Fahim Kamal Ahmed** as the successfully completed capstone assignment for the **[Blueprint Scripting](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)** course. This is the fourth course in the **[Epic Games Game Design Professional Certificate](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)** offered on Coursera, for which the certificate has now been earned.

The development focused on building a complete game from the ground up, emphasizing a deep understanding of Blueprint visual scripting. The project was initiated using the **Unreal Engine First-Person Template** and the **SuperGrid Starter Pack** to establish a solid foundation, allowing the core effort to be directed toward designing and implementing a network of complex, interconnected gameplay systems and creating all environmental assets from scratch within the engine.

The primary achievement was translating the conceptual Game Design Document (GDD) into a fully playable, feature-complete puzzle-escape game that showcases robust architecture and a compelling, multi-layered puzzle flow.

---

## 🎯 Overview

**"Blackout Facility"** is a completed first-person puzzle-escape game built in **Unreal Engine 5**. The player awakens in a dark, abandoned industrial complex and must explore a two-story facility, solve environmental puzzles, restore power, and navigate a series of logical challenges to retrieve a final objective.

Development utilized the standard first-person character controller, with a heavy focus on creating all puzzle logic and interactive systems exclusively with Blueprints. All environmental and prop assets were custom-modeled inside Unreal Engine to create a cohesive greybox aesthetic. This completed project establishes a full gameplay loop from start to finish, built on a well-architected and scalable foundation.

---

## 📜 Game Design Document (GDD)

The entire design philosophy, detailed puzzle flow, gameplay mechanics, and narrative context for "Blackout Facility" are documented in the Game Design Document. This document served as the blueprint for the development process.

<p align="center">
  <!-- TODO: Make sure your GDD pdf is in the repo and update this link if needed! -->
  <a href="./GDD - Blackout Facility.pdf" target="_blank"> 
    <strong>View the Full Game Design Document (PDF)</strong>
  </a>
</p>

---

## 🗺️ Level Map Overview

Below are the conceptual maps that guided the construction of each floor in the "Blackout Facility."

<p align="center">
  <img src="https://github.com/user-attachments/assets/80f77504-e7a5-494c-a717-92791f98c37e" alt="Floor 1 Map" width="75%"/>
  <br>
  <em>Top-down conceptual map of Floor 1: The Industrial Zone.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6799bb9b-e1eb-4a1c-ad85-4a999ac8f82d" alt="Floor 2 Map" width="75%"/>
  <br>
  <em>Top-down conceptual map of Floor 2: The Corporate Offices.</em>
</p>

---

## ✨ Key Goals & Features (Achieved in Project)

*   **Complex Interconnected Systems:** All major gameplay elements are linked. Activating the Power Generator uses Event Dispatchers to trigger a chain reaction, simultaneously activating the central Light Controller, unlocking the Lift, and powering on all electronic props across the entire facility.
*   **Object-Oriented Blueprint Architecture:** The project is built on a clean foundation of parent classes (`BP_Electronics`, `BP_CollectibleItem`) and a universal `BPI_Interactable` Blueprint Interface, demonstrating a professional, scalable, and organized approach to development.
*   **Multi-Stage Puzzle Design:** The game features advanced puzzle mechanics, including a non-linear key-and-lock system on Floor 1 and a major backtracking puzzle on Floor 2 that requires the player to revisit a previous area in a new world state.
*   **Custom In-Engine Asset Creation:** All environmental and prop assets (desks, chairs, servers, monitors, racks, etc.) were modeled from scratch using Unreal Engine's built-in Modeling Tools, demonstrating self-sufficiency and deep engine knowledge.
*   **Dynamic Interactive Elements:** Implemented highly functional systems including doors with multiple unlock states (key, timed pressure plate, remote computer), and a fully automated, state-aware elevator system.
*   **Atmospheric Transformation:** A key feature is the dramatic environmental shift from an oppressive, dark, and tense atmosphere to a brightly lit, clean, and fully revealed facility, providing a powerful sense of progression and reward.
*   **GDD to Completion Pipeline:** The project successfully translated a detailed Game Design Document into a feature-complete, playable game that was packaged and submitted for the course.

---

## 📜 Certificate of Completion - Blueprint Scripting

I am proud to have successfully completed the "Blueprint Scripting" course and earned my certificate!

<p align="center">
  <img src="https://github.com/user-attachments/assets/4a1838da-5a43-410f-a786-5687214586b2" alt="Certificate for Blueprint Scripting" width="70%"/>
  <br>
  <em>Certificate of Completion - Blueprint Scripting.</em>
  <br>
  <a href="https://coursera.org/verify/O1VRBB9UFBXR" target="_blank">
    <strong>Verify Certificate</strong>
  </a>
</p>

---

## 📸 Development Screenshots (Completed Project)

<p align="center">
  <img src="https://github.com/user-attachments/assets/b44c2bf1-9038-4375-85f5-a1dac829a075" alt="Storage Room Screenshot" width="80%"/>
  <br/>
  <img src="https://github.com/user-attachments/assets/a27fe258-21d8-4da3-a433-f61e6fe3b083" alt="'Power On' Event Screenshot" width="45%"/>
  <img src="https://github.com/user-attachments/assets/8cbfa87c-a41e-4f9e-88b2-4b846312a190" width="45%"/>
  <br/>
  <img src="https://github.com/user-attachments/assets/d4733694-f613-4bd3-b218-c690e9cbbf94" alt="Automated Elevator Screenshot" width="45%"/>
  <img src="https://github.com/user-attachments/assets/06179296-eaab-4dec-bcf2-c49c6619bab7" alt="Final Objective Screenshot" width="45%"/>
  <br/>
  <img src="https://github.com/user-attachments/assets/25114f5f-c645-46bc-b55b-7060f6c4958d" alt="Automated Elevator Screenshot" width="45%"/>
  <img src="https://github.com/user-attachments/assets/2ca03b77-4771-42ab-b25b-2f514f1fe5f0" alt="Final Objective Screenshot" width="45%"/>
  <br/>
</p>

---

## 💻 Technology Stack

*   **Engine:** Unreal Engine 5.5.4 ⚙️
*   **Core Packages Utilized:**
    *   **Unreal Engine First-Person Template:** Used as the base for player character and movement.
    *   **SuperGrid Starter Pack:** Used for rapid prototyping materials and shapes. ([Marketplace Link](https://www.fab.com/listings/a6ab4843-7c8a-47d1-912c-fc1c3553df23))
*   **Unreal Engine Features Used:**
    *   Blueprint Visual Scripting (Actors, Actor Components, Game Mode)
    *   **In-Engine Modeling Tools** (for all custom environmental assets)
    *   Blueprint Inheritance & Blueprint Interfaces
    *   Event Dispatchers
    *   Custom Trace Channels
    *   UMG (for UI prompts)
    *   Material Editor (for dynamic emissive materials)
    *   Project Packaging/Build System
*   **Design Document:** [Game Design Document (GDD) for "Blackout Facility"](./Game Design Document Blackout Facility.pdf)
*   **Course:** [Blueprint Scripting](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate) (Epic Games / Coursera)
*   **Version Control:**[ GitHub ](https://github.com/FahimKamal/UE5_MazeEscape)

---

## 📊 Project Status (As of July 10, 2025)

*   ✅ **Project Definition & GDD:** Scope defined, GDD drafted and finalized.
*   ✅ **Architectural Foundation:** All parent classes and interfaces (Interaction, Collectible, Electronics) implemented.
*   ✅ **Core Systems Implementation:** All major gameplay systems (Doors, Lift, Power/Light Grid) are complete and functional.
*   ✅ **Level Blockout & Implementation:** Floor 1 and Floor 2 are fully built and populated with their respective puzzles and assets.
*   ✅ **Full Gameplay Loop:** The game is playable from the starting room to the final objective collection.
*   ✅ **Playtesting & Iteration:** Final playtesting complete to ensure puzzle flow and system stability.
*   ✅ **Finalize Project Build:** A packaged build of the project was created.
*   ✅ **Video Showcase:** Gameplay showcase video recorded and uploaded.
*   ✅ **Course Project Submitted:** All required materials submitted for course evaluation.
*   ✅ **Received Course Certificate (July 10, 2025):** Successfully completed the course and earned the certificate.
*   ---
*   🎯 **Next Steps:** Further develop this project into a more complete portfolio piece by enhancing details and adding gameplay systems (see "Future Plans").

---

## 🌱 Learning & Development Focus

This project successfully demonstrated proficiency in:

*   **Advanced Blueprinting:** Architecting and scripting a network of complex, interconnected, and stateful gameplay systems from scratch.
*   **Object-Oriented Design:** Creating a clean, scalable, and maintainable project using a well-defined hierarchy of parent classes and interfaces.
*   **Full-Cycle Game Design:** Taking a concept from a detailed GDD through system design, level implementation, playtesting, and final packaging.
*   **In-Engine Asset Creation:** Modeling a complete library of cohesive environmental and prop assets using Unreal Engine's built-in tools.
*   **Systemic & Puzzle Design:** Crafting a multi-layered puzzle experience that relies on player deduction and a holistic understanding of the game world.

---

## 🔮 Future Plans (Post-Course Development for Portfolio Enhancement)

Now that the course requirements are met, the plan is to further develop this "Blackout Facility" into a more polished and comprehensive portfolio piece, evolving it into a social stealth game.

*   🤖 **NPC Implementation:** Populate the facility with roaming Security Guards, Technicians, and Corporate Employees.
*   🎭 **Stealth & Disguise System:** Introduce a core mechanic where the player must acquire disguises to blend in and access restricted areas without alerting guards.
*   🎯 **Dynamic Objectives:** Evolve the end-goal from collecting an item to more complex scenarios like stealing data from a guarded server, or even eliminating a target during the final board meeting.
*   🎨 **Visual & Audio Polish:** (Long-term) Replace blockout assets with final art, improve lighting and post-processing, and implement a full sound design.

---

## 📜 Assets & Attributions

*   **Course:** This project is an assignment for the **[Blueprint Scripting](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)** course by Epic Games on Coursera.
*   **Creator (Game Design, Level Design, Blueprint Scripting, 3D Modeling):** Fahim Kamal Ahmed
*   **Custom 3D Models:** All environmental and prop models (chairs, tables, servers, computers, keyboards, cabinets, racks, etc.) were created by the developer from scratch inside Unreal Engine using the built-in Modeling Tools and primitive shapes.
*   **Third-Party Assets:**
    *   The **SuperGrid Starter Pack** was used for some base materials and prototyping shapes.
    *   The final "Crystal" objective is a free asset downloaded from an online source.
    *   The project was built upon the standard **Unreal Engine First-Person Template**.

---

## ⚖️ Licensing

This project ("Blackout Facility" game design, level design, and custom assets) by **Fahim Kamal Ahmed** is licensed under the **MIT License**. Please see the `LICENSE` file for full details. Note that third-party assets are subject to their own licenses.
