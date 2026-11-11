# Gonzalez Damien — Resume Data

## Basics
- Name: Gonzalez Damien
- Pronouns: he / him
- Title: Game Programmer
- Email: gonzalez.damien.kiok@gmail.com

## About Me
I've always had a keen interest in video games and the work that goes into them for as long as I can remember.
Today this curiosity is stronger than ever and every day drives my passion for my work.
I'm constantly pushing myself and trying new things to improve my skills and knowledge in order to try and bring great experiences to people.
I strongly believe making video games is a team effort, and I hope to be able to bring as much to my peers as they could bring to me.
Throughout the years, I have acquired various skills on many tools, ranging from programming language, to engines, to 3D and 2D software.
I'm very passionate about my work in games, and I enjoy working in many different fields of the trade, albeit programming remains my favorite domain to explore.

My favorite game genres include Action RPGs, Strategy RPGs, Sandbox survivals and Tactics games.
During my free time, I enjoy learning about new things, reading mangas and fantasy novels, playing D&D, or trying out my hand at art.

## Skills

| Category | Worked with | Experimented with |
|---|---|---|
| Engines | Unity, Unreal, Godot | |
| Libraries | Flecs, Enet | Raylib, MonoGame, LibGDX |
| Languages | C#, C++, LUA, JS | Odin, Nim, Haxe, Python |
| Software | Blender, 3DsMax, Substance Designer, Photoshop | |
| Source Control | Git, PlasticSCM | |

### Languages Spoken
- 🇫🇷 French — Native
- 🇬🇧 English — Fluent
- 🇪🇸 Spanish — Basics

## Work History

### Midgar Studio — 2024 - 2026
- Role: Lead Programmer (2026)
- Role: Gameplay Programmer (2024 - 2026)
- Worked on Edge Of Memories, a singleplayer Action RPG for PC, PS5 and Xbox, in a studio of around 35 people. Joined as a Gameplay Programmer, then became Lead Programmer in 2026 for the run-up to release.
- Highlights:
  - Gameplay programming in Unreal Engine 5 (C++, Blueprints)
  - Worked with console platform SDKs (PS5, Xbox)

### Cliffdivers Project — 2023 - 2024
- Role: Principal Programmer
- Sole programmer on Cliffdivers, a procedural multiplayer survival adventure for PC built in Godot by a team of 4, with the goal of co-founding a studio. Handled pretty much every technical aspect of the game.
- Highlights:
  - Integrated the Flecs ECS into Godot, with a custom entity renderer
  - Networked entity replication over Enet, interest management and world streaming
  - Data-driven entities, items and recipes in LUA, paving the way for modding
  - Character controller built on an extensive state machine, gameplay tools and UI
  - Followed earlier prototypes (2021) in Unreal Engine 4 / 5: networked character controller, C++ / Blueprint state machine

### Aiko Creative — 2020 - 2022
- Role: Principal Programmer
- Lead programmer on the studio's projects, shipping a VR game, a mobile game, and various B2B games and applications in Unity and Unreal Engine.
- Highlights:
  - Invoiders (VR, Unity): VR character system, weapons, enemy pathing and wave tools for designers, VR UI
  - Aenigma Venatorum (Mobile, Unity): virtual recreations of physical puzzles, progression saves, shaders, UI
  - Aeroport de Paris VR (Unreal): full body tracking for up to 6 trainees in local multiplayer, trainer control panel

### Studio Muybridge — 2019 - 2020
- Role: Programmer
- Worked with hardware interfacing for a racing simulator, and worked on various B2B applications and games

### ETPA School of Game Design — 2016 - 2019
- Role: Student
- Game design studies, including lead programming on student projects such as Redneck Ranch Rumble, a 2-player local party game (Shiva, LUA).

## Portfolio Projects

### Edge Of Memories (2024 - 2026) - PC, PS5, XBOX Game
- Role 2026 Lead Programmer
- Role 2024 > 2026 Gameplay Programmer
- Studio : Midgar Studio
- Team Size : Around 35
- Status: Release 3 Dec, 2026
- Description: A Singleplayer Action RPG.
- Details: 
	- TODO
- Images: 
	- TODO
- Videos:
	- TODO
- Technical Information:
  - Engine: Unreal Engine 5
  - Languages used: C++, Blueprints
  - Worked with consoles Platforms SDKs ( PS5 , XBOX )
- Notes: 
	- TODO


### Cliffdivers (2023) — PC Game
- Role: Lead Programmer
- Studio: Unnamed
- Team Size: 4 people
- Status: Unreleased
- Duration: 12 months
- Description: A procedural multiplayer survival adventure game.
- Details: I worked full time on this project for all of 2023, with the end goal of co-founding a studio.
  I left the team at the beginning of 2024 for personal reasons, but the project was a lot of fun to work on and I learned a lot while working on it.
  I was the sole programmer on the team, and handled pretty much every technical aspect of it.
  The game features an open, vertical, procedural world explorable in multiplayer. The players have many tools available to help them traverse the atypical world.
  The goal of the game is to go down further and further down in an unexplored abyss and uncover its mysteries and history.
  At the time of me leaving, most of the underlying engine was functional (world streaming, networking) and gameplay mechanics were starting to get implemented.
  The game uses a data-driven approach to a lot of things: Entity declaration, Items declaration, Character controller configuration, among other things.
  This was done to help development time and later on help bring modding support to the game.
- Images:
  - https://i.imgur.com/0nxpdVD.jpeg
  - https://i.imgur.com/Ds65GJc.jpeg
  - https://i.imgur.com/aQVLQDP.jpeg
- Videos:
  - https://www.youtube.com/embed/F-_Bv38gP9U (showcase)
  - https://www.youtube.com/embed/5X1Ran8f5z4 (one year progress)
- Technical Information:
  - Engine: Godot
  - Responsible for the entirety of the programming
  - Languages used: C#, LUA, C++, GDScript
- Notes:
  - Integrated [Flecs](https://www.flecs.dev/flecs/) on top of Godot engine (ECS)
  - Built a network entity replication system on top of [Enet](http://enet.bespin.org/) (creation, deletion, state change)
  - Built a custom renderer system to render entities efficiently
  - Used a data-driven approach to declare entities, items, crafting recipes, using the LUA scripting language
  - Built a basic network interest manager and world streaming system
  - Built a custom entity spawning system on top of [VoxelTools](https://github.com/Zylann/godot_voxel)
  - Built an extensive state machine system for the character controller
  - Implemented the character controller and various gameplay tools
  - UI programming

### Invoiders (2020 - 2021) — VR Game
- Role: Lead Programmer
- Studio: Aiko Creative
- Team Size: 8 people
- Status: Available
- Duration: 12 months
- Description: A virtual reality Tower Defense / Shooter for the Meta Quest 1 / 2, and Oculus Rift S.
  The player plays as a space prisoner, sent to fight hordes of enemies invading various planets and defend the settlements.
  The player has access to an arsenal of weapons with various upgrades and can call offensive towers from orbit onto the battlefield.
- Video: https://www.youtube.com/embed/0nrZXLiCtr4
- Technical Information:
  - Engine: Unity
  - Language used: C#
  - Platforms: [Android](https://www.meta.com/fr-fr/experiences/3807370422692379/), [PC](https://www.meta.com/fr-fr/experiences/pcvr/4434572513250824/)
- Notes:
  - Responsible for programming the character system in VR
  - Developed various weapons useable in VR (Bow, Revolver, Machine Gun, Unreleased weapons)
  - Built custom tools to help with enemy pathing and wave management for designers
  - Developed the towers' various interactions
  - VR UI programming

### Cliffdivers Prototypes (2021) — Game Prototype
- Role: Lead Programmer
- Studio: Unnamed
- Team Size: 4 people
- Status: Internal
- Duration: 8 months
- Description: Various prototypes for Cliffdivers before entering production. Worked on during free time.
- Videos:
  - https://www.youtube.com/embed/QQgfagbYPiA
  - https://www.youtube.com/embed/d4EYT-giCxo (trailer proto)
- Technical Information:
  - Engine: Unreal Engine 4 and 5
  - Languages used: C++, Blueprints
- Notes:
  - Prototyped a character controller, network replicated using Unreal Network System
  - C++ / Blueprint Hybrid state machine
  - Setup of a custom entity renderer based on [Flecs](https://www.flecs.dev/flecs/)

### Aenigma Venatorum (2021 - 2022) — Mobile Game
- Role: Lead Programmer
- Studio: Aiko Creative
- Team Size: 6 people
- Status: Released
- Duration: 12 months
- Description: 3D Puzzle Mobile game. Recreation of existing physical puzzles, at the demand of [NKD Puzzle](https://nkd-puzzle.com/blog/)
- Video: https://www.youtube.com/embed/WIWIGfebQOE
- Technical Information:
  - Engine: Unity
  - Language used: C#
  - Platforms: [Android](https://play.google.com/store/apps/details?id=com.NKDPuzzle.AenigmaVenatorumFull&hl=fr&gl=US), [IOS](https://apps.apple.com/fr/app/aenigma-venatorum-integral/id1628758670)
- Notes:
  - Recreated physical puzzles virtually
  - UI programming
  - Save system for puzzle progression
  - Shaders programming
  - Virtual Drawing Pad with save system

### Aeroport de Paris VR (2019) — Training Tool
- Role: Lead Programmer
- Studio: Aiko Creative
- Team Size: 4 people
- Status: Shipped
- Duration: 8 months
- Description: Virtual Reality Training tool for the Paris Charles de Gaulle Airport.
  Supports up to 6 trainees in local multiplayer with full body tracking using the Vive Pro.
- Video: https://www.youtube.com/embed/S7qoEEaUn5I
- Technical Information:
  - Engine: Unreal Engine 4
  - Languages used: Blueprint
- Notes:
  - Responsible for programming the character system in VR
  - Developed a full body tracking system
  - Local multiplayer with full body tracking animations replication
  - External control from a control panel for trainer

## Other Projects

### Don Random — GMTK Jam 2022 — Game Jam
- Role: Lead Programmer
- Studio: Personal
- Team Size: 4 people
- Status: Available
- Duration: 48 hours
- Description: Short Tactics Game on the theme of "Roll of the Dice", developed for the GMTK Jam 2022.
- Links:
  - Itch.io embed: https://itch.io/embed/1623397 (https://kiiok.itch.io/don-random)
- Technical Information:
  - Engine: Unity
  - Language used: C#
  - Platform: WebGL
- Notes:
  - Enemies AI
  - Dice rolling system
  - UI programming
  - Assets integration in engine

### Redneck Ranch Rumble — Student Game
- Role: Lead Programmer
- Studio: Student Project
- Team Size: 2 people
- Status: Available
- Duration: 2 months
- Description: 2 Player local party game where each player must score the highest by grabbing and throwing farm animals into a moving truck.
- Links:
  - Itch.io embed: https://itch.io/embed/423375 (https://kiiok.itch.io/redneck-ranch-rumble)
  - Video: https://www.youtube.com/embed/wAa_CHVZX4E
- Technical Information:
  - Engine: Shiva
  - Language used: LUA
  - Platform: Windows
- Notes:
  - Done most of the programming

### Mekastasis — Dev Tool
- Description: Personal project. First foray into making custom tools in Unity.
  A simple finite state machine configuration in the editor.
- Links:
  - Itch.io embed: https://itch.io/embed/446434 (https://kiiok.itch.io/mekastasis — Unmaintained)
  - Image: https://img.itch.zone/aW1hZ2UvNDQ2NDM0LzIyNTM5NDMucG5n/original/IOeBSz.png
- Technical Information:
  - Engine: Unity
  - Language used: C#
