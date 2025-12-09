# Carve — A Multiplayer 3D Sculpting Game

Carve is a Unity-based 3D sculpting game where creativity meets competition.  
Each round, players are given a random word prompt and must sculpt it within a limited time.  
When time runs out, the sculptures are compared and scored — either by AI or player votes — to determine who carved it best.

---

## Gameplay Overview

1. Join a Lobby — Connect with other players in a shared game session.  
2. Get a Word Prompt — A random object or concept (e.g., "rocket", "apple", "castle").  
3. Start Sculpting — Use voxel-based brushes to shape your model in real-time.  
4. Submit Your Sculpt — When time ends, your work is automatically scored or voted on.  
5. See the Results — Compare sculptures and crown the round's winner.

---

## Features

- 3D Sculpting Tools — Add, remove, or smooth material using intuitive voxel brushes.  
- Random Word Generator — Automatically selects creative prompts each round.  
- Scoring System — Uses AI silhouette comparison or player voting to rate submissions.  
- Multiplayer Lobbies — Create or join rooms using Photon or Unity Netcode.  
- Blender-Ready Assets — Sculpted pieces can be exported for 3D rendering or remixing.  
- Creative Freedom — Every round is unique, and everyone interprets the same word differently.

---

## Tech Stack

| Component       | Technology                                |
|-----------------|---------------------------------------------|
| Game Engine     | Unity (2021.3 LTS or newer)                 |
| Language        | C#                                          |
| Networking      | Photon PUN / Unity Netcode for GameObjects  |
| 3D Assets       | Blender                                     |
| Version Control | Git + GitHub                                |

---

# Development Roadmap (4 Weeks)

A realistic breakdown of development goals spread across four weekly sprints.

---

## Week 1 — Core Sculpting and Single-Player Loop

- Voxel sculpting system (add, remove, smooth).  
- Basic mesh generation.  
- Brush UI (mode and size selection).  
- Word prompt generator.  
- Timer and round lifecycle (start, sculpt, end, lock controls).  
- Single-player sculpting sandbox.

---

## Week 2 — Multiplayer and Sculpt Synchronization

- Networking setup (Photon or Unity Netcode).  
- Create and join lobbies.  
- Player ready states.  
- Shared prompt distribution.  
- Real-time voxel edit synchronization.  
- Multiplayer round timer synced across players.

---

## Week 3 — Scoring, Voting, and UI

- Voting system or AI silhouette scoring.  
- Scoreboard results screen.  
- UI improvements for tools, prompts, timer, and results.  
- Bug fixes and sculpting performance improvements.

---

## Week 4 — Final Polish and Export

- Export sculpt data to Blender-compatible format.  
- Performance optimizations for voxel mesh updates.  
- Final UI pass.  
- Playtesting, debugging, and quality improvements.  
- Prepare playable prototype build.

---

# Agile Methodology

Carve uses a lightweight Scrum workflow suitable for fast game development.

---

## Agile Framework

- Method: Scrum  
- Sprint Length: 1 week  
- Total Sprints: 4  

---

## Roles

- Product Owner (PO): Defines priorities and features.  
- Scrum Master (SM): Removes blockers and maintains workflow.  
- Developer: Implements all features and systems.

---

## Scrum Artifacts

### Product Backlog (High-Level Features)

- Sculpting system  
- Word prompt generator  
- Multiplayer synchronization  
- Voting and scoring  
- Lobby system  
- Exporting  
- UI and UX improvements  
- Audio  
- Optimization  
- Bug fixes  

---

## User Stories

### Sculpting
- As a player, I want to add and remove material so I can sculpt
