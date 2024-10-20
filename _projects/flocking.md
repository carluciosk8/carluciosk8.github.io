---
title: Flocking [2006]
year: 2006
excerpt: "Flocking algorithm implemented in C++ and OpenGL 2.0"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/flocking.png
---

{: .text-justify}

{: .font-size: $type-size-1 }

This is my implementation of the seminal paper [Flocks, herds and schools: A distributed behavioral model (from Craig Reynolds)](https://dl.acm.org/doi/10.1145/37401.37406){:target="_blank"} that I made for a computer graphics assignement. The requirements were:
- 3D world.
- Simple illumination.
- A controllable boid acting as a leader.
- Four cameras:
  1) Behind the flock
  2) Beside the flock,
  3) Behind the leader boid
  4) Fixed on some point and looking to the flock center.
  
In addition to that, I implemented some extra features like: 
- Fractal landscapes.
- Fog.
- Pause.
- Animated boids.
- Controls to tweak my flocking algorithm constants.

During the runtime, the user can tweak the various parameters until satisfied with the results, as can be seen in the following video:

<iframe iframe width="560" height="315" src="https://www.youtube.com/embed/9_JgACAmQ6A" frameborder="0"></iframe>

<br />

<a href="https://github.com/carluciosk8/flocking" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code available on GitHub</a>
