---
layout: default
title: Higher Up
description: Point and click game with an inventory system with a drag and drop feature.
---

The goal of this project is for me to learn to code different game mechanics than the ones in Parkour Leap.

## Game Concept
The player needs to climb up the mountain to escape the flood. They need to pick up items to get past obstacles.

## Player Controller
The game is in first person. The player moves around by clicking and moving the mouse to rotate the locked camera.
![PlayerController](/assets/img/Higher_Up_PlayerController.png)

## Inventory System
The game has a grid with slots. The inventory works by adding items as children of those slots. The items are prefabs with a script that makes them draggable. 
The Item type is specified with Scriptable Objects.
![Inventory_Add_&_Remove_Methods](/assets/img/Higher_Up_Inventory.png)

## Placing Items
The game has inactive GameObjects that are set active when the player has the right item in the tool slot.
![Item_Placement](/assets/img/Higher_Up_ItemPlacement.png)

[Back](./)

