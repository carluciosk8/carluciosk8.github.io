---
title: "Mini Artillery Duel"
excerpt: "Another artillery game, written in 10 lines of MSX-BASIC 1.0"
classes: wide
header:
  teaser: /assets/images/miniduel.png
---

## About the Game:

* Mini Artillery Duel is an [Artillery Game](https://en.wikipedia.org/wiki/Artillery_game) written in MSX-BASIC 1.0 for the [10th Anniversary of BASIC 10 Liner Contest](https://gkanold.wixsite.com/homeputerium)

* Like most of the Artillery Games, Mini Artillery Duel has a screen showing a terrain with mountains, valleys and two artillery guns fighting with each other. Player 1 is on the left side and Player 2 is on the right side.

* The game is round based and at each round, the current player adjusts your gun and fire. At the top of Screen, the Game HUD shows the current player, the barrel angle (indicated by letter **B**) and the powder level (indicated by letter **P**).

* At each round, the wind speed changes and the only clue for players is the clouds movement in the sky.

* Use the joysticks to play:
 - 🠉/🠋: Increase/Decrease Powder Level - 🠈/🠊: Increase/Decrease Barrel Angle
 - Hold Button **A** to Fire!

<div id="wmsx" style="text-align: center; margin: 20px auto 0;">
<div id="wmsx-screen" style="box-shadow: 2px 2px 10px rgba(0, 0, 0, .7);"></div>
</div>


**Emulator joysticks configuration**

|:-----------------------:|:-----------------------:|
|      **Player 1:**      |      **Player 2:**      |
|:-----------------------:|:-----------------------:|
|       🠉,🠋,🠈,🠊        | **T**,**F**,**G**,**H** |
|     and **L-CTRL**      |      and **A**          |
|:-----------------------:|:-----------------------:|

<script src="{{ base.url | prepend: site.url }}/assets/js/wmsx.js">
</script>
<script>
    WMSX.MACHINE = "MSX1";
    WMSX.DISKA_URL = "{{ base.url | prepend: site.url }}/assets/misc/miniduel.dsk";
    WMSX.BASIC_RUN = "miniduel.bas";
    WMSX.JOYKEYS_MODE = 2;
</script>
