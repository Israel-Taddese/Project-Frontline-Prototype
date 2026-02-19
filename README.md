# Project Frontline – 3D Mobile Strategy Prototype

![Unity](https://img.shields.io/badge/Engine-Unity-000000?logo=unity)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android-blue)
![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Build Target](https://img.shields.io/badge/Target-60%20Day%20Prototype-success)

---

## Vision

Project Frontline is a fast-paced 3D mobile strategy prototype focused on delivering a tight, polished core combat loop optimized for touch devices.

The goal is to validate gameplay feel, performance, and store deployment readiness within 60 days.

This is a **vertical slice prototype**, not a full multiplayer production.

---

## Project Objective

Build a playable, store-deployable 3D strategy prototype including:

- 3D battlefield
- Player-controlled base
- 3 unit types (Melee, Ranged, Tank)
- Enemy AI with state machine behavior
- Combat system with readable feedback
- Resource economy system
- Mobile-first UI & controls
- iOS & Android deployment builds

---

## Tech Stack

**Engine:** Unity 2022/2023 LTS (URP)  
**Language:** C#  
**IDE:** Rider / Visual Studio  
**Version Control:** Git  
**Target Platforms:** iOS + Android  

---

## Core Architecture


### Unit Structure

**Abstract Class:** `Unit`
- Health
- Movement
- Attack()
- TakeDamage()

**Derived Classes:**
- PlayerUnit
- EnemyUnit

---

## AI State Machine

States:
- Idle
- Move
- Attack
- Dead

Transitions are handled via a lightweight state machine architecture for performance and modularity.

---

## Release Roadmap (Playable + Store Deployable)

### Milestone 1 – Core Playable Loop (Weeks 1–2)
- Unity setup with URP mobile profile
- 1 complete map with RTS-style camera
- 3 unit types
- Basic enemy waves
- Win/Lose conditions
- 5–10 minute playable session target

### Milestone 2 – Production Gameplay (Weeks 3–4)
- Resource economy system
- Unit spawning flow
- Combat readability pass (VFX + hit feedback)
- In-game HUD + pause/settings menu
- First full internal playtest build

### Milestone 3 – Mobile Readiness (Weeks 5–6)
- Touch-first controls
- UI scaling for multiple resolutions
- Performance pass (pooling, batching, texture budgets)
- Device matrix testing (low/mid/high Android + iPhone)
- Save/load system + onboarding tutorial

### Milestone 4 – Store Submission Prep (Weeks 7–8)
- iOS signing + TestFlight distribution
- Android signing + Play Console internal test
- App icon, screenshots, store copy
- Privacy policy & data disclosure
- Release Candidate (RC) build + regression pass

---

## Definition of Done (Prototype)

- Playable build on physical iOS and Android devices
- Stable 15-minute session with no blocking bugs
- 60 FPS target on mid-range devices (30 FPS fallback if required)
- Store-ready submission package for TestFlight + Play Internal

---

##  Gameplay Pillars

1. **Immediate Combat Clarity**
   - Player always understands battlefield state.

2. **Fast Session Loop**
   - High-intensity 5–10 minute matches.

3. **Mobile-First Design**
   - Touch optimized
   - Clean UI scaling
   - Performance stable on mid-tier devices

4. **Expandable Architecture**
   - Systems designed for future multiplayer integration.

---

## Production Status

| System              | Status |
|--------------------|--------|
| Project Setup      | ⬜ In Progress |
| Camera System      | ⬜ Pending |
| Unit System        | ⬜ Pending |
| AI System          | ⬜ Pending |
| Combat System      | ⬜ Pending |
| Economy System     | ⬜ Pending |
| UI & Polish        | ⬜ Pending |
| Optimization       | ⬜ Pending |
| Store Submission   | ⬜ Pending |

---

## Performance Targets

- 60 FPS on mid-range device
- < 200 draw calls
- < 300MB RAM usage
- Build size under 300MB

---

## Development Rules

- No feature takes more than 2 days without simplification.
- Code must be modular and documented.
- Commit daily.
- No premature multiplayer implementation.

---

## Versioning Strategy

- v0.1 – Core Playable Loop
- v0.2 – Production Gameplay
- v0.3 – Mobile Optimized
- v0.4 – Release Candidate
- v1.0 – Store Submitted Prototype

---

## Future Expansion

Post-prototype roadmap may include:

- Online multiplayer
- Backend integration (Firebase / PlayFab)
- Live ops systems
- Monetization systems
- Clan system
- Persistent progression

---

## License

MIT License – See LICENSE file for details.

---

## Author

Developed by Israel Taddese  
Unity 3D Mobile Strategy Prototype – 2026
