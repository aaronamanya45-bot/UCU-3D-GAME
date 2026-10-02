# UCUCollector — A 3D Campus Collectible Game

## 📖 Project Overview

**UCUCollector** is a 3D collectible game set on the campus of **Uganda Christian University (UCU), Mukono**. The player explores a simplified 3D recreation of the campus, searching for hidden collectibles placed at real campus landmarks. The game is being built in **Unity** as a university project.

### 🎯 Core Gameplay
- Player walks around the UCU campus in first-person (WASD + Mouse).
- 5 collectibles are hidden at real campus landmarks.
- Touching a collectible adds to the player's score and makes the item disappear.
- Collecting all 5 triggers a "You Win!" message.

---

## 🏫 Campus Landmarks Used

These locations were identified from a satellite view of UCU Mukono and will each hold one collectible:

| # | Landmark | Position on Map |
|---|----------|----------------|
| 1 | UCU Fountain ("path to ucu fountain") | Bottom center |
| 2 | UCU Counseling Department | Center-right |
| 3 | UCU Safe Drinking Water Faucet | Top center |
| 4 | Bishop Tucker Road | Left side |
| 5 | Bishop Tucker Building / Foods area | Top left |

---

## 🛠️ Tools & Setup

| Item | Version / Detail |
|------|-----------------|
| **Game Engine** | Unity 6.6 (6000.6.4f1) |
| **Unity Hub** | Latest |
| **IDE** | Microsoft Visual Studio Community 2026 |
| **Render Pipeline** | Universal Render Pipeline (URP) |
| **Project Name** | UCUCollector |
| **Template** | Universal 3D |

---

## 📂 Project Progress Log

### ✅ Completed
- [x] Installed Unity Hub and Unity 6.6 Editor
- [x] Installed Visual Studio Community 2026 (for C# scripting)
- [x] Created the Unity project `UCUCollector` using the Universal 3D template
- [x] Verified the Editor opens with the default SampleScene
- [x] Created the ground plane (the campus floor)

### 🚧 In Progress
- [ ] Scale the ground plane to (5, 1, 5)
- [ ] Block out the first buildings using Cubes:
  - `CounselingBuilding` — Pos (10, 1, 0), Scale (4, 2, 6)
  - `BishopTuckerBuilding` — Pos (-10, 1.5, 5), Scale (5, 3, 8)
- [ ] Create the fountain using a Cylinder:
  - `UCUFountain` — Pos (0, 0.5, -10), Scale (3, 0.5, 3)

### ⏳ Not Started
- [ ] Player character with first-person controller
- [ ] Collectible objects (5 total) with trigger colliders
- [ ] Pickup script + scoring system
- [ ] UI (score display, win screen)
- [ ] Menu and audio
- [ ] Polish and final build

---

## 🗺️ Planned Level Layout (Greybox)

Based on the UCU Mukono satellite view, the level is laid out as follows:
