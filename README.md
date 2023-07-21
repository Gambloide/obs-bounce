# OBS-Bounce

OBS script to bounce a scene item around, DVD logo style or throw & bounce with physics.

Forked from https://github.com/insin/obs-bounce to fix the hotkey not working as a toggle.

I have no experience with lua or the OBS bindings used.
I just understood that the issue caused by the hotkey event triggering twice, once when you press down the key and once again when it is released, causing the toggle not to work like a toggle.

A sideeffect is that the `Toggle` button in the UI needs to be pressed twice to trigger the toggle. 

# Bad Quality Demo

https://user-images.githubusercontent.com/5939852/222574678-87263ea0-bbb9-4941-8833-73b3af84b8e2.mp4

# Usage

Download [the latest version](https://github.com/Gambloide/obs-bounce/archive/refs/tags/1.5.zip), extract the downloaded zip, then:

1. In OBS, make sure the scene with the source you want to move (e.g. your cam) is active.
2. In OBS, open Tools > Scripts in the menu bar at the top.
3. Click on the "+" button on the bottom left of the windows that opened.
4. Select the "bounce.lua" file and click "Open".
5. In the drop down menu which opened on the right, select the source you want to move.
6. Click toggle and it should start moving.

You can set-up a hotkey to toggle the animation without having to open this window:

1. In OBS, open File > Settings > Hotkeys you will find a "Toggle Bounce" entry. If you can't find it, type "bounce" in the "Filter" bar at the top of the settings.
2. Click in the input field next to "Toggle Bounce", then press the hotkey or key combination you want to use to toggle the animation.

# License Information

Copyright (c) 2023 Jonny Buchanan, Sebastian M. Reuter

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice (including the next paragraph) shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
