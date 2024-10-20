---
title: µRISC-II Emulator [2000]
year: 2000
excerpt: "A µRISC-II emulator implemented in C using only logic gates abstractions"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/urisc.png
---

{: .text-justify}

{: .font-size: $type-size-1 }

The traditional assignment of [Computer Architecture](https://en.wikipedia.org/wiki/Computer_architecture){:target="_blank"} discipline of my graduation was to implement a [DLX based](https://en.wikipedia.org/wiki/DLX){:target="_blank"} emulator. We had to implement 4 versions:

1) Functional version. (without restriction in implementation)
2) Functional pipelined version.
3) Logic version. (restricted to use only basic electronic components abstractions in implementation, basically logic gates and muxes)
4) Logic pipelined version.

Besides of these requirements, my version has a improved status screen, showing the assembler mnemonic in execution flowing in the pipeline, pointing also the occurence of forwards and control hazards. Here is a video of the logic pipelined version of the emulator running:

<iframe iframe width="640" height="480" src="https://www.youtube.com/embed/DvyH4xxYavA" frameborder="0"></iframe>

<br />

<a href="https://github.com/carluciosk8/uriscii" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code available on GitHub</a>
