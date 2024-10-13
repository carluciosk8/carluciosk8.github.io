---
title: "Atlantis for MSX"
year: 2021
layout: single
excerpt: "A Clone of the classic Atari 2600 game Atlantis"
classes: wide
header:
  teaser: /assets/images/fun/atlantis.png
sidebar:
  nav: fun
---

##  Play it online now:

<div id="wmsx" style="text-align: center; margin: 0 auto 0 auto; horizontal-align:middle;">
  <div id="keys">
    <table style="text-align: center; margin: 0 auto 0 auto; horizontal-align:middle; display: initial;">
      <thead>
        <tr>
          <th style="text-align: center;" class="header" colspan="2">Joystick Configuration for Emulator:</th>
        </tr>
        <tr>
          <th style="text-align: center;" class="header" markdown="span">**Player 1:**</th>
        </tr>
      </thead>
      <tr>
        <td style="text-align: center;" markdown="span">&#x1F81D;, &#x1F81F;, &#x1F81C;, &#x1F81E; and **SPACE**</td>
      </tr>
    </table>
  </div>
  <div id="wmsx-screen" style="box-shadow: 2px 2px 10px rgba(0, 0, 0, .7);"></div>
</div>

<script src="{{ base.url | prepend: site.url }}/assets/js/wmsx.js">
</script>
<script>
    WMSX.MACHINE = "MSX1";
    WMSX.CARTRIDGE1_URL = "{{ base.url | prepend: site.url }}/assets/misc/atlantis.rom";
</script>

## About the Game:

This is a clone of the classic [Atari 2600 Atlantis](https://en.wikipedia.org/wiki/Atlantis_(video_game)){:target="_blank"} released by [Imagic](https://en.wikipedia.org/wiki/Imagic){:target="_blank"} in 1982. I created this game to be published by [Clube MSX Magazine](https://www.clubemsx.com.br){:target="_blank"} and it was released in Gold Disk #4, the coverdisk of the [issue 14](https://www.clubemsx.com.br/produto/revista-clube-msx-14-en/){:target="_blank"}.

It was developed in C language using [SDCC](https://sdcc.sourceforge.net){:target="_blank"} and the [ubox MSX lib](https://www.usebox.net/jjm/ubox-msx-lib/){:target="_blank"}. For writing code I used VS Code and for debbuging I used [Emulicious](https://emulicious.net){:target="_blank"} alongside with the [debugger extension for VS Code](https://marketplace.visualstudio.com/items?itemName=emulicious.emulicious-debugger){:target="_blank"}

<br />

<a href="https://github.com/carluciosk8/atlantis" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code and ROM available on GitHub</a>
