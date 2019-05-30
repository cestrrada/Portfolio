---
layout: project
title: PAC-MAN
date: December 26, 2017
category: Games

buttons:
  - name: github
    url: https://github.com/cestrrada/PAC-MAN
    color: btn-light
    icon: fab fa-github
  - name: Download (macOS)
    url: https://github.com/estrrada/PAC-MAN/files/1582420/PACMAN-macOS.zip
    color: btn-primary
    icon: fab fa-app-store
  - name: Download (Windows)
    url: https://github.com/estrrada/PAC-MAN/files/1582421/PACMAN-Windows.zip
    color: btn-warning
    icon: fab fa-windows

version: 2.0
featured: pacman/featured.jpg
description: A PAC-MAN clone written in C++ using SFML.
---

### Overview

Guide PAC-MAN through the maze as you consume pellets, chase ghosts, and collect fruits. Consume all the pellets to advance to the next stage. Munch on a Power Pellet to temporarily allow ghosts to be eaten. But be careful—Blinky, Inky, Pinky, and Clyde adapt quickly to survive.

Built using the Simple and Fast Multimedia Library (SFML) and modeled after the original PAC-MAN arcade game, this version attempts to mimic the classic arcade game while adding additional improvements to functionality. Thanks to SFML, cross-platform functionality is built-in, which makes it a breeze to run the code on the operating system of your choice.

#### How to Run
- To run the project on macOS, simply select `PAC-MAN.xcodeproj` and open in XCode.
- To run the project on Windows, select `PAC-MAN.sln` and point your compiler to the appropriate SFML 2.4.2 files.

#### Possible Future Updates
- Implement a Pathfinding Algorithm for the ghosts and use their original AI.
- Represent the world with tiles and load mazes from text files.

#### Credits
- [AnimatedSprite](https://github.com/SFML/SFML/wiki/Source:-AnimatedSprite){:target="_blank"} by Maximilian Wagenbach.
- [Simple Collision Detection for SFML 2](https://github.com/SFML/SFML/wiki/Source:-Simple-Collision-Detection-for-SFML-2){:target="_blank"} by Nick Koirala and ahnonay.