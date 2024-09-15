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
The traditional assignment of computer organization discipline during my graduation was to implement a DLX based µRISC-II emulator using only basic electronic components abstractions, basically logic gates and muxes. My version has a status screen that was more improved than the most common, showing the assembler mnemonic in execution. There is also a pipelined version of the emulator where the status screen shows the instructions flowing in the pipeline, showing also the occurence of forwards and control hazards. Here is a video of the pipelined version of the emulator running:

<iframe iframe width="640" height="480" src="https://www.youtube.com/embed/DvyH4xxYavA" frameborder="0"></iframe>

Source code on GitHub: <https://github.com/carluciosk8/uriscii>
