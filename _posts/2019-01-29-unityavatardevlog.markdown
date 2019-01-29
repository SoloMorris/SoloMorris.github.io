---
layout: post
title: Blog - Unity Basic Avatar
date: 2019-01-29 01:24:00
description: Demo of a basic Unity Avatar.
category: newbie
published: true
tags: 
- gameplay programming
- game programming
- university
- unity
---

<h1> Blog - Unity Basic Avatar </h1>
<br>
In the below video, I cover my implementation of a basic avatar that can move around and jump.

[![Basic Avatar Video](http://img.youtube.com/vi/g5zNsRblmcs/0.jpg)](http://www.youtube.com/watch?v=g5zNsRblmcs "Unity Gameplay Programming - Basic Avatar")

<br>
As part of the task I was given, the avatar and camera should control similarly to Super Mario 3D World.
When I was looking at Super Mario 3D World for reference, I noted that the camera was fixed. This meant that the player would not move
like they do in typical third-person games such as Super Mario 64. The controls change relative to the position of the fixed camera.
This is what I aim to do with my avatar. My current implementation works by setting the player's rotation to an absolute value, and the goal is to
instead have it change relative to the camera's perspective. 
The main issue with how movement currently works is that there isn't a turning animation - it is more responsive but probably won't be 
visually appealing to all players. I'll be taking another look at it in the future by adding a few frames of rotation.

The jump, as it is now, is barely functional. When the animation plays it halts forward momentum 
(due to how movement is currently implemented, the player only moves via the current animation)
so the player can't normally jump in any direction. There is a "bug" of sorts where inputting a direction and jumping 
at the same time will cancel the jumping animation, while still sending the player into the air so they can jump across platforms, as seen in the video.
As it is now the jump should definitely be reimplemented and is a high priority for the future of this project.

Next week I'll be implementing a collectible into the game!