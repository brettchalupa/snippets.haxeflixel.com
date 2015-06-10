---
title: 1-to-1 Collision
concept: Collision
order: 1
tags: [collision]
---
The simplest form of collision is 1-to-1 collision. You call the {% api collide flixel/FlxG collide %} function, optionally setting a callback to trigger when collision happens.

```haxe
// checks if 2 objects collided, and calls the function `callback` if they do
FlxG.collide(objectA, objectB, callback);
```