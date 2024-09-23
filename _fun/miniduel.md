---
title: "Mini Artillery Duel"
year: 2020
layout: single
excerpt: "Another artillery game, written in 10 lines of MSX-BASIC 1.0"
classes: wide
header:
  teaser: /assets/images/miniduel.png
sidebar:
  nav: fun
---

##  Play it online now:

* Use the joysticks to play:
  * &#x1F81D;/&#x1F81F;: Increase/Decrease Powder Level - &#x1F81C;/&#x1F81E;: Increase/Decrease Barrel Angle
  * Hold Button **A** to Fire!

<div id="wmsx" style="text-align: center; margin: 0 auto 0 auto; horizontal-align:middle;">
  <div id="keys">
    <table style="text-align: center; margin: 0 auto 0 auto; horizontal-align:middle; display: initial;">
      <thead>
        <tr>
          <th style="text-align: center;" class="header" colspan="2">Joystick Configuration for Emulator:</th>
        </tr>
        <tr>
          <th style="text-align: center;" class="header" markdown="span">**Player 1:**</th>
          <th style="text-align: center;" class="header" markdown="span">Player 2:</th>
        </tr>
      </thead>
      <tr>
        <td style="text-align: center;" markdown="span">&#x1F81D;, &#x1F81F;, &#x1F81C;, &#x1F81E; and **SPACE**</td>
        <td style="text-align: center;" markdown="span">**T**, **G**, **F**, **H** and **A**</td>
      </tr>
    </table>
  </div>
  <div id="wmsx-screen" style="box-shadow: 2px 2px 10px rgba(0, 0, 0, .7);"></div>
</div>

<script src="{{ base.url | prepend: site.url }}/assets/js/wmsx.js">
</script>
<script>
    WMSX.MACHINE = "MSX1";
    WMSX.DISKA_URL = "{{ base.url | prepend: site.url }}/assets/misc/miniduel.dsk";
    WMSX.BASIC_RUN = "miniduel.bas";
    WMSX.JOYKEYS_MODE = 2;
</script>

## About the Game:

* Mini Artillery Duel is an [Artillery Game](https://en.wikipedia.org/wiki/Artillery_game){:target="_blank"} written in [MSX-BASIC 1.0](https://en.wikipedia.org/wiki/MSX_BASIC){:target="_blank"} for the [10th Anniversary of BASIC 10 Liner Contest](https://gkanold.wixsite.com/homeputerium){:target="_blank"}

* Like most of the Artillery Games, Mini Artillery Duel has a screen showing a terrain with mountains, valleys and two artillery guns fighting with each other. Player 1 is on the left side and Player 2 is on the right side.

* The game is round based and at each round, the current player adjusts your gun and fires. At the top of Screen, the Game HUD shows the current player, the barrel angle (indicated by letter **B**) and the powder level (indicated by letter **P**).

* At each round, the wind speed changes and the only clue for players is the clouds movement in the sky.

* One hit to die!!!

## Main Game Features:

* Graphics try to look like the ColecoVision version of [Artillery Duel](https://www.youtube.com/watch?v=pbw9qYPxxvQ)

* Random generated playfield terrain and background.

* Destructible playfield terrain.

* Animated cannon movement using "vector balls".

* Sound FX for bomb movement and explosions.

## Observations:

* The random terrain routine is heavy on processing, after load and run, the game spends about 40 seconds to start drawing, please be patient (if you are spending time reading these texts, probably the game is running and ready to play)

* To list the source code, you can break pressing CTRL+Break in your keyboard. If the game stops and you dont see any characters on emulator screen, type "screen 0" and press enter to reset the characters to its original. Alternatively you can view the source online in pure MSX-BASIC [here](https://github.com/carluciosk8/msx-basic/blob/master/ten-liners/miniduel.bas){:target="_blank"}, and in [NestorPreTer](https://www.konamiman.com/msx/msx-e.html#nestorpreter){:target="_blank"} [here](https://github.com/carluciosk8/msx-basic/blob/master/ten-liners/miniduel.npr){:target="_blank"}

* You can grab a disk image with the game [here]({{ base.url | prepend: site.url }}/assets/misc/miniduel.dsk)
