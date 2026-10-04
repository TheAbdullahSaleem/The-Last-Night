# The Last Light

> A small atmospheric 3D exploration and puzzle game made with **Blender** and **Godot**.

![Status](https://img.shields.io/badge/status-pre--production-yellow)
![Engine](https://img.shields.io/badge/engine-Godot%203-blue)
![3D](https://img.shields.io/badge/game-3D-purple)
![Made With](https://img.shields.io/badge/made%20with-Blender-orange)

---

## About

**The Last Light** is a first-person 3D exploration and puzzle game set on a small, abandoned island.

The island's lighthouse has stopped working.

The player arrives to investigate and discovers that the lighthouse was abandoned for a reason.

Explore the island, discover clues, solve environmental puzzles, restore the lighthouse, and uncover what happened to the people who lived there.

---

## Main Goal

Reach the top of the lighthouse and restore the light.

To do this, the player will need to:

* Explore the island
* Find useful items
* Discover hidden clues
* Solve environmental puzzles
* Explore abandoned buildings
* Repair broken machinery
* Find a way into the lighthouse
* Discover the island's story

---

## Game World

The initial version will contain:

* Beach
* Dock
* Abandoned cabin
* Small forest
* Rocky areas
* Lighthouse
* Lighthouse machinery room
* Lighthouse tower

The world will remain relatively small and optimized for lower-end hardware.

---

## Art Direction

The game will have a dark and atmospheric visual style.

### Environment

* Weathered wood
* Rusted metal
* Wet rocks
* Fog
* Night-time lighting
* Ocean surrounding the island
* Abandoned structures

### Lighting

The environment will be mostly dark and muted, with the lighthouse acting as the primary source of light.

The goal is to create a strong atmosphere without requiring extremely high-end hardware.

---

## Technology

### Blender

Used for:

* 3D modeling
* UV unwrapping
* Materials
* Texturing
* Environment assets
* Characters
* Animation

### Godot

Used for:

* Player controller
* Camera
* Game logic
* Interaction
* Puzzles
* Lighting
* Audio
* UI
* Scenes
* Final game

---

## Development Philosophy

The project will be built **small first and expanded later**.

The first playable version will contain:

> One small area + player movement + interactive objects + one simple puzzle.

Once that works, new mechanics and areas will be added.

---

## Roadmap

### Phase 1 — Blender

* [ ] Learn basic modeling
* [ ] Create crate
* [ ] Create barrel
* [ ] Create table
* [ ] Create chair
* [ ] Create lantern
* [ ] Create rocks
* [ ] Create basic environment pieces

### Phase 2 — Godot Prototype

* [ ] Create 3D project
* [ ] Create player
* [ ] Add camera
* [ ] Add movement
* [ ] Add jumping
* [ ] Create interaction system
* [ ] Import Blender assets

### Phase 3 — Lighthouse

* [ ] Model lighthouse exterior
* [ ] Model lighthouse interior
* [ ] Create stairs
* [ ] Create lighthouse machinery
* [ ] Create lighthouse light
* [ ] Import lighthouse into Godot

### Phase 4 — Island

* [ ] Create terrain
* [ ] Add beach
* [ ] Add rocks
* [ ] Add trees
* [ ] Add cabin
* [ ] Add dock
* [ ] Add environmental props

### Phase 5 — Gameplay

* [ ] Add keys
* [ ] Add doors
* [ ] Add item interaction
* [ ] Create first puzzle
* [ ] Create lighthouse restoration puzzle
* [ ] Add checkpoints
* [ ] Add save system

### Phase 6 — Atmosphere

* [ ] Ocean
* [ ] Fog
* [ ] Rain
* [ ] Wind
* [ ] Ambient sounds
* [ ] Footsteps
* [ ] Lighthouse sound effects
* [ ] Music

### Phase 7 — Story

* [ ] Write island history
* [ ] Add notes
* [ ] Add environmental storytelling
* [ ] Add mysterious events
* [ ] Create ending

---

## Optimization

The game is being developed on relatively limited hardware, so optimization is an important part of development.

### Blender

* Keep polygon counts reasonable
* Use optimized meshes
* Use normal maps for small details
* Reuse assets where possible
* Avoid unnecessarily large textures
* Create game-ready assets

### Godot

* Use appropriate texture resolutions
* Limit real-time lights
* Optimize physics objects
* Keep scenes reasonably small
* Use LOD where appropriate
* Profile performance regularly

---

## Project Structure

```text
The-Last-Light/
│
├── blender/
│   ├── characters/
│   ├── environment/
│   ├── props/
│   └── source/
│
├── godot/
│   ├── scenes/
│   ├── scripts/
│   ├── assets/
│   ├── audio/
│   └── ui/
│
├── docs/
│
└── README.md
```

---

## Current Status

**Pre-production / Learning**

The project is currently being developed as a learning project for:

**Blender → 3D Game Assets → Godot 3D**

The scope will grow only after each milestone is working.

---

## Final Goal

Create a complete, small 3D game that can be played from beginning to end.

The priority is not size.

The priority is:

**Learn → Build → Test → Optimize → Finish.**

---

## The Last Light

> *The lighthouse hasn't shone for years.*

> *Tonight, someone turned it on.*
