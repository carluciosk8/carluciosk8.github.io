---
title: PSYGEN
excerpt: "PSYGEN - Procedural Synthesis Graphics Engine"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/psygen.png
---

{: .text-justify}
Procedural techniques are a very interesting approach to synthesize large variety of textures and 3D models and can help graphic artists to create complex scenes in less time than if they were shaped by hand. Applications that make use of these techniques has been classified into two already known paradigms: data amplification and lazy evaluation.

PSYGEN is a graphics engine that i developed as proof of concept of my master's dissertation. His main objective was to propose a new paradigm for procedural synthesis that enables the real time visualization of massive procedural scenes using real time rendering techniques, parallel computing, memory management, and a combination of the two well known procedural synthesis paradigms. PSYGEN also presents a scene graph technology that employs the new proposed paradigm. Experimental results show that in addition to obtaining performance gains through parallelism, PSYGEN can generate and view a procedural scene far greater than the available memory in real time, using only a single PC equipped with a GPU and a multicore processor. These same results would not be possible to be obtained using only the known paradigms.

<iframe width="560" height="315" src="https://www.youtube.com/embed/qNZ7O2-qyV4" frameborder="0"></iframe>
