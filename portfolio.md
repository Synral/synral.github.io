---
layout: page
title: Portfolio
subtitle: Past projects and experiences
---
# [Earth's Light](https://hamraj-rai.itch.io/earths-light)
![Earth's Light Title Screen](https://img.itch.zone/aW1hZ2UvOTc0MTIzLzczMjM0NDEucG5n/347x500/yRgepC.png)

>Earth's Light is a cooperative action-adventure game following the story of four animals and their journey to save their ecosystems, protect their homes, and heal the planet. Fight off garbage monsters plaguing the wetlands, the invasive plants enrapturing the forest, water spirits flooding the plains, and the mechanical chipper robots destroying the arctic.

A project in collaboration with the Toronto Zoo as a member of Sedna Games, a group of students from Ontario Tech University. Features two complete levels (Wetlands and Arctic) and functions as a prototype proof of design developed over a year (09/2020 ~ 09/2021).

Over the course of the project, our group of seven collaborated over Discord and planned our timeline using Jira. We would undergo daily scrums to check for progress on our weekly tasks, and hold a larger meeting every week to assign new tasks and deal with merging on our repository hosted on Github (using Github Desktop). Every week our project lead would meet with a member on the Toronto Zoo team to convey our progress as well as receive feedback on elements they may wish to see within the game.

As the gameplay programmer of this project, I handled most of the front-end programming related to gameplay and dealt with some user interface elements. Here are some elements I programmed:
- Movement (Jumping/Double Jumping, Dashing/Air Dashing, Basic Movement)
- Combat (Light/Heavy Attacks and Combos, Ground Slam, Combat Abilities, Death, Revive, Damage Calculations, Character Swapping, Combat Waves/Zones)
- Quick Time Events (Button Mash, Circular Button Rotations, Sequential Button Input, Time Sensitive Input)
- Camera (Third Person Camera, Cinematic Shots, Splitscreen, Cinemachine)
- Pickups (Health, Datapads)
- Enemy AI - Wetlands (Flinger, Splitter, Trashzilla, Flying Trash Bug, Trashmon)
- Local Lobby (Joining/Disconnecting Controllers)

Character input was done through Unity's Input System (input action maps) while camera work was done using Cinemachine. Besides these things, I also implemented the checkpoint system, achievement system for the tutorial using delegates, and the UI related to player portraits, health bar, combat skill icons and cooldown, text pop-up when picking up datapads, and character swap wheel UI. Furthermore, I implemented the character and Wetland enemy models and animations into the game, hooking them up so that they work in game and dabbled in visual effects/post processing using Unity's shader graphs to enhance the graphics of the game.

Other programmers on the team handled the backend programming which involved setting up networking, packet sending of game data across up to four players, allowing people to join or create lobbies, as well as handled merging on the repository. Besides that, Anthony worked together with me on certain aspects of quick time events, enemy AI, and bugfixing while Daniel Presas worked on menus, particularly the pause and title screen menus and their navigations.

The two artists split the work between themselves, with one doing general 2D asset work (title screens, icons, UI elements) and 3D modelling of the player and enemy models while the other handled the creation of all animations related to the 3D models. I communicated with the two regarding any assets I needed as well as asked for changes to best align animations and user interface elements in a player friendly manner.

The project manager, Hamraj, guided us through our project timeline as well as handled level design and creation, creating the models and textures of landscapes and any props necessary such as trees, plants, grass, water shaders, icebergs, etc. He also worked together with Carter to design the game and create the game design document in an easy to understand manner so that I could reference it for anything I needed to implement. Working together with the two, I placed the QTEs, combat encounters, cinematic shots, checkpoints, datapads, and tutorial prompts.

In addition to some of the above, Carter handled the creation of all sound effects and soundtracks within the game and worked with Anthony to figure out how to use FMOD to implement sounds. I worked with Carter

# [Primordial](https://promethaes.itch.io/primordial)
[![Primordial](http://img.youtube.com/vi/iZOTqHBXW2M/0.jpg)](https://www.youtube.com/watch?v=iZOTqHBXW2M)