---
title: "SilentPatch"
game-series: ["crazy-taxi"]
excerpt: "Proper analog controls, fixed crashes with a steering wheel and more."
date: 07-08-2021
order: 0
---

This modification fixes several bugs in the Steam version of Crazy Taxi. While some of the bugs (such as broken analog steering)
already had unofficial fixes in the past, they are shipped as an executable edit and they can have some side effects depending
on the gamepad used. SilentPatch also fixes several other bugs not covered by other fixes, e.g. a crash when booting the game
with steering wheels connected. With this patch, the game is fully playable with a steering wheel (and a shifter), providing a full arcade experience.

## Featured fixes
* Issues with analog steering and pressure sensitive triggers have been fixed. This applies both to XInput and DirectInput controllers.
* A crash when starting the game with specific DirectInput devices (e.g. steering wheels) has been fixed.
* Analog stick deadzones have been refined slightly to improve steering responsiveness and make it feel closer to the Dreamcast release.
* Alt + F4 now works correctly.
* When using the Windowed mode, the window size has been corrected to avoid distorting the image.
* When using the Windowed mode, maximizing is now disallowed by disabling the Maximize button rather than by making it non-functional.
* Restored several missing cheats/hotkeys from the original PC version. These are:
  * Reset Camera (`Shift+Alt+F5`)
  * Cinematic Camera (`Shift+Alt+F6`)
  * First Person Camera (`Shift+Alt+F7`)
  * Show Speedometer (`Shift+Alt+F8`)

## Credits
* Cryoburner - for the original Crazy Taxi Analog Controller Unofficial Fix


{% include setup-instructions.html %}

<a href="https://github.com/CookiePLMonster/SilentPatchCT/releases/latest/download/SilentPatchCT.zip" class="button" role="button">{{ site.theme_settings.download_icon }} Download</a> \\
<a href="https://github.com/CookiePLMonster/SilentPatchCT" class="button github" role="button" target="_blank">{{ site.theme_settings.github_icon }} See source on GitHub</a>