# Project Frontline – 3D Mobile Strategy Prototype

60-day Unity 3D mobile strategy game prototype inspired by modern RTS titles.

Built with Unity URP targeting iOS and Android.

This repository documents the full development process from foundation setup to mobile deployment.

---

## 🎯 Project Goal

Build a polished, playable 3D strategy prototype including:

- 3D battlefield
- Player-controlled base
- 3 unit types
- Enemy AI system
- Combat mechanics
- Resource economy system
- Mobile optimization pipeline
- iOS & Android builds

This is a vertical slice prototype — not a full multiplayer production.

---

## 🛠 Tech Stack

Engine: Unity 2022/2023 LTS (URP)  
Language: C#  
IDE: Rider / Visual Studio  
Version Control: Git  
Target Platforms: iOS + Android  

---

## 🏗 Core Architecture

GameManager  
├── UnitManager  
├── EconomyManager  
├── CombatManager  
├── UIManager  
├── AudioManager  

### Unit Structure

Abstract Class: `Unit`
- Health
- Movement
- Attack()
- TakeDamage()

Derived Classes:
- PlayerUnit
- EnemyUnit

### AI State Machine

States:
- Idle
- Move
- Attack
- Dead

---

## 📅 60-Day Roadmap

### Phase 1 – Foundation (Week 1)
- Unity setup
- Mobile build pipeline
- Camera system
- Terrain setup
- Base placeholder

### Phase 2 – Unit System (Week 2)
- Unit base class
- NavMesh movement
- 3 playable unit types

### Phase 3 – AI System (Week 3)
- Enemy units
- Patrol logic
- State machine behavior

### Phase 4 – Combat Loop (Week 4)
- Damage system
- Cooldowns
- Health bars
- Win/Lose conditions

### Phase 5 – Economy System (Week 5)
- Resource generation
- Unit cost system
- Spawn logic

### Phase 6 – UI & Polish (Week 6)
- Main menu
- Audio integration
- Visual polish

### Phase 7 – Optimization (Week 7)
- Object pooling
- Draw call reduction
- Mobile performance tuning

### Phase 8 – Deployment (Week 8)
- iOS provisioning
- Android signing
- TestFlight build
- Internal testing

---

## 🎮 Performance Targets

- 60 FPS on mid-range mobile device
- < 200 draw calls
- < 300MB RAM usage
- Build size under 300MB

---

## 📌 Development Rules

- No feature takes more than 2 days without simplification.
- Code must be modular and documented.
- Commit daily.
- No premature multiplayer implementation.

---

## 🚀 Future Expansion

Post-prototype roadmap may include:

- Online multiplayer
- Backend integration (Firebase / PlayFab)
- Live ops system
- Monetization system
- Clan system
- Persistent progression

---

## 📜 License

MIT License – See LICENSE file for details.

---

## 👤 Author

Developed by Israel Taddese  
Unity 3D Mobile Strategy Prototype – 2026
