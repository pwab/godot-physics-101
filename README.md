# Godot Physics 101

## TLDR

This is a compilation of physical scenes and simulations for inspection and learning of GodotEngine physics.

## Explanation

Since I started working with game engines, I have been interested in the implemented physical systems. Since I wanted to do 2D simulations, there were only few possibilities at that time (e.g. Box2D). Then I stumbled across the Godot Engine and was immediately convinced of its power. So I did a lot of testing in a lot of simple projects to get a grasp of the underlying mechanics. Now I would like to summarize my knowledge in one project/repository and make it understandable for others. So here we are: Godot Physics 101.

## How it works

When running the project you'll get a welcome screen where you can choose one of the provided scenes. These encapsulate one aspect of Godots capabilities in simulating a physical world. You can start a scene, watch it running (or interacting with it) and read about its foundations in a description sidebar. There are scenes for 2D and 3D physics.

Examples are written for Godot 3.2-beta2. I will soon update to Godot 3.2 as it gets its stable release.

## Overview

- **General**
  - *[Main]* - The main window for choosing the scenes
  - *[Overlay]* - An UI overlay for every scene
  - *[Settings]* - A window to quickly change some settings
  - *[Documentation]* - A quick link to the docs for every concept
- **2D**
  - *[Sandbox2D]* - A sandbox to play with
  - *[Physicsbodies2D]* - Physicsbodies and their concepts
  - *[Gravity2D]* - Gravity and how to change it
- **3D**
  - *[Sandbox3D]* - A sandbox to play with
  - *[Physicsbodies3D]* - Physicsbodies and their concepts
  - *[Gravity3D]* - Gravity and how to change it

## Standing on the shoulder of giants

Here is a list of projects, which I will use as a basis for the compilation of examples:

### Documentations

- [Box2D Manual](http://box2d.org/manual.pdf)
- [Unity Physics Docs](https://docs.unity3d.com/Manual/PhysicsSection.html)
- [Unreal Physics Docs](https://docs.unrealengine.com/en-US/Engine/Physics/index.html)
- [CryEngine Physics Docs](https://docs.cryengine.com/display/CEMANUAL/Physics)

### Examples lists

- [Bullet Physics Examples Explorer](https://github.com/bulletphysics/bullet3/releases)
- [Processing](https://processing.org/examples/)
- [Phaser.io](https://phaser.io/examples/v3/category/physics)
- [LiquidFun](http://google.github.io/liquidfun/)
- [PhyscsJS](http://wellcaffeinated.net/PhysicsJS/)
- [P2.js](https://github.com/schteppe/p2.js#demos)
- [Planck.js](http://piqnt.com/planck.js/)
- [Physijs](https://github.com/chandlerprall/Physijs#examples)
- [Matter.js](https://github.com/liabru/matter-js#demos)
- [Cannon.js](http://schteppe.github.io/cannon.js/)
- [Ammo.js](https://github.com/kripken/ammo.js#demos)
- [Oimo.js Demos](https://github.com/lo-th/Oimo.js#demo) and [Oimo.js Web](http://lo-th.github.io/Oimo.js/#basic)
- [nphysics (2D)](https://www.nphysics.org/demo_all_examples2/) and [nphysics (2D)](https://www.nphysics.org/demo_all_examples3/)

### Learning platforms

- [Leifiphysik](https://www.leifiphysik.de/) (German)

## FAQ

### What is the license?

I have chosen the very permissive MIT license for this project. The icon is CC0 and downloaded from [aiconica](http://aiconica.net/).

### Are the examples mobile ready?

Could be. But I wouldn't bet on it. Just change to GLES2 and try it out.

### Are the examples network ready?

As I'm using the Godot Physics Engine itself and don't care about states I would say: no. But you can try if you want and maybe I sometime add a network example somehow.