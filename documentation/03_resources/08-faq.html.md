```
title: "FAQ"
```

### Do I have to learn Flixel (AS3) before HaxeFlixel?
No, you have to learn HaxeFlixel to use HaxeFlixel, although previous experience with the AS3 version will help.

### Do I have to learn ActionScript before Haxe?
No, although previous experience will help.

### Do I have to learn OpenFL to use HaxeFlixel?
No, HaxeFlixel abstracts it completely.

### Are there any video tutorials?
Yes. [This series](https://www.youtube.com/watch?v=LpKvSPwHOP8&list=PLi0ypjD5PcV9xdjycW0hYi_HD297012tE) covers everything from installation to prototyping a platformer.

### I found I bug, where to report?
On the [official GitHub repository](https://github.com/HaxeFlixel/flixel/issues).

### Is HTML5 supported?
Almost, it still is in development.

### Will next-gen consoles be supported?
Maybe. It's out of scope of HaxeFlixel, it all depends of OpenFL.

### My sounds are lagging!?
On some platforms you need to manually cache sounds: `FlxG.sound.cache("sound");` or `flixel.system.FlxAssets.cacheSounds();` to do all at once.

### My player falls off-screen after walking a certain distance!
Collisions are limited to the area defined by `FlxG.worldBounds`. For example in platformers where this area needs to be larger, you need to adjust it manually.

### Can I make 3D games with HaxeFlixel?
No, the framework is limited to 2D graphics.
