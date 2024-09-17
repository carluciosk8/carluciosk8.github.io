---
title: "Atlantis for MSX"
year: 2021
layout: single
excerpt: "Atlantis for MSX"
classes: wide
header:
  teaser: /assets/images/hobby/atlantis.png
sidebar:
  nav: hobby
---

A game published in Gold Disk #4, the coverdisk of [Clube MSX Magazine 14](https://www.clubemsx.com.br/produto/revista-clube-msx-14-en/). The game is a clone of the classic for Atari 2600.

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
