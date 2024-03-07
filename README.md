# GOAP
## GOAP NPC Unreal Marketplace Asset repo (UE5.3)
### Repo Creator's Note:
> This Asset is free on [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/goap-npc-goal-oriented-action-planning-for-non-player-characters/). Which was authored by students of [Narratech Laboratories](https://narratech.com/). Copyright belongs to their original authors and their Organization as stated bellow:
```
GOAP NPC: Goal-Oriented Action Planning for Non-Player Characters
Copyright © 2022 Narratech Laboratories
Authors: 
    - Diego Romero-Hombrebueno Santos, 
    - Mario Sánchez Blanco, 
    - José Manuel Sierra Ramos, 
    - Daniel Gil Aguilar and 
    - Federico Peinado
Website: https://narratech.com/project/goap-npc/
```
> Sadly after Engine update 5.0, this plugin is not updated to newer versions anymore. This repo is for those who owns the code-plugin on Unreal Engine Marketplace, but can't use it on newest version of the engine.
>
> - An updated fix has been added from this [commit](https://github.com/Narratech/TFGRomeroSanchezSierra/commit/fbab9e0290e1b253c78481bcb05398681ecd4c98).
> - Updated Engine support : Unreal Engine 5.3
 
### Descriptions
*(Descriptions bellow added from their [marketplace page](https://www.unrealengine.com/marketplace/en-US/product/goap-npc-goal-oriented-action-planning-for-non-player-characters/))*

Unlike traditional approaches which uses complex (and difficult to maintain!) behavior trees or finite state machines, GOAP NPC keeps game characters' behavior simple, efficient and user-friendly.

Here you can watch a [short video](https://www.youtube.com/watch?v=aInzVukXzAg) which showcases an example scenario with different behaviors, and some explanations about how to create your own.

**Goal-Oriented Action Planning (GOAP)** provides a generic and natural way to build Non-Player Characters (NPCs) with Artificial Intelligence (AI). Used in modern commercial games (Shooters, Action RPGs, etc.), it offers smart decision-making with great scalability.

This system allows you to describe the behavior of your intelligent agents using ACTIONS and GOALS. Actions are independent tasks with their own preconditions, costs and effects, while goals are finish conditions for character's PLANS. Thanks to the popular A* heuristic search algorithm, the GOAP system knows which actions to perform in order to achieve certain goals, generating a dynamic plan, without having to define explicit transitions between world states.

This code plugin represents a ready-to-use framework for both development and debugging (in C++ and/or Blueprints) of GOAP NPCs while maintaining optimal performances. We recommend that you watch this [short video](https://youtu.be/L7LDhkfQtpI) to get an idea of how to use the new features provided by this code plugin.

### Technical Details
#### Features:
- Ready-to-use Goal-Oriented Action Planner in a single module.
- Heuristic search using A* algorithm.
- C++/Blueprints compatible framework.
- Customizable Action and Controller Blueprint templates.
- Number of C++ Classes: 6.
- Number of Blueprints: 0.
- Supported Development Platforms: Tested only on Windows 64-bit.
- Supported Target Build Platforms: All of them (Windows 64-bit, Windows 32-bits, MacOS, Linux, HTML 5, Android, iOS...)

### Documentation: 
- GOAP NPC ([Short manual](https://narratech.com/goap-npc/), notes and a version changelist).
- Full [Documentation](https://drive.google.com/file/d/131lMBvNILMxDJUh6yazG3JZJiKjXac1G/view)
- Offline [Docs](./GOAP%20NPC%20Manual.pdf)
- Tutorial Playlist ([Youtube](https://youtube.com/playlist?list=PLMRyVRl3flZ8wKqDkEbnm5Xdpp0M_wOzX&si=VfxLKVCWODSuFfKV))
- Useful Links:
  - [Original Repo](https://github.com/Narratech/GOAP_NPC)
  - [Repo with Update fix commit](https://github.com/Narratech/TFGRomeroSanchezSierra)
  - [Unreal Engine Marketplace](https://www.unrealengine.com/marketplace/en-US/product/goap-npc-goal-oriented-action-planning-for-non-player-characters/)

### Example Project: 
GOAP NPC Demo ([GitHub repository](https://github.com/Narratech/GOAP_NPC_Demo)).