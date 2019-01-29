---
layout: post
title: Blog - Unity Basic Avatar
date: 2019-01-29 01:24:00
description: Demo of a basic Unity Avatar.
category: newbie
published: true
tags: 
- gameplay programming
- general noise
- game programming
- university
- unity
---

<h1> Blog - Unity Basic Avatar </h1>
<br>
In the below video, I cover my implementation of a basic avatar that can move around and jump.

[![Basic Avatar Video](http://img.youtube.com/vi/g5zNsRblmcs/0.jpg)](http://www.youtube.com/watch?v=g5zNsRblmcs "Unity Gameplay Programming - Basic Avatar")

<br>
As part of the assigned task, the avatar and camera should control similarly to Super Mario 3D World.
When looking at Super Mario 3D World for reference, I noted that the camera was fixed. This meant that the player would not move
like they do in typical third-person games, like Super Mario 64. The controls would change relative to the position of the fixed camera.
This is what I aim to do with my avatar. My current implementation works by setting the player's rotation to an absolute value, and the goal is to
instead have it change relative to the camera's perspective.