---
title: PSYGEN [2009]
year: 2009
excerpt: "PSYGEN - Procedural Synthesis Graphics Engine"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/psygen.png
---

{: .text-justify}

{: .font-size: $type-size-1 }

[Procedural Generation](https://en.wikipedia.org/wiki/Procedural_generation){:target="_blank"} is a very interesting approach to synthesize large variety of textures and 3D models and can help graphic artists to create complex scenes in less time than if they were shaped by hand. Applications that make use of these techniques has been classified into two already known paradigms:

* Data Amplification.
* Lazy Evaluation.

PSYGEN is a graphics engine that I developed as proof of concept of my master's dissertation: to propose a new for procedural synthesis that enables the real time visualization of massive procedural scenes using real time rendering techniques, parallel computing, memory management, and a combination of the two well known procedural synthesis paradigms. This new paradigm is called **Predictive Lazy Amplification**

PSYGEN also presents a scene graph technology that employs the new proposed paradigm, called Blowfish Scene Graph. Experimental results show that in addition to obtaining performance gains through parallelism, PSYGEN can generate and view a procedural scene far greater than the available memory in real time, using only a single PC equipped with a GPU and a multicore processor. These same results would not be possible to be obtained using only the known paradigms.

# Publications related to this work:

* [**“Predictive Lazy Amplification: Synthesis and Rendering of Massive Procedural Scenes in Real Time”**](https://ieeexplore.ieee.org/document/5720334){:target="_blank"}
*C. S. Cordeiro, L. Chaimowicz* – Proceedings of SIBGRAPI 2010.

* Master thesis: **“Predictive Lazy Amplification: Um Novo Paradigma para a Síntese e Visualização de Cenas Procedurais Massivas em Tempo Real” <sup>(Portuguese)</sup>**

<iframe width="560" height="315" src="https://www.youtube.com/embed/qNZ7O2-qyV4" frameborder="0"></iframe>

<br />

<a href="https://github.com/carluciosk8/psygen" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code available on GitHub</a>
