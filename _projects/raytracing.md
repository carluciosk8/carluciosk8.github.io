---
title: Ray Tracing [2006]
year: 2006
excerpt: "Very simple parallel raytracer with some procedural textures"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/rt-cellular.png
gallery:
  - url: /assets/images/academy/rt-test1.png
    image_path: /assets/images/academy/rt-test1.png
    alt: "rt-test1 alt"
    title: "rt-test1 title"
  - url: /assets/images/academy/rt-test2.png
    image_path: /assets/images/academy/rt-test2.png
    alt: "rt-test2 alt"
    title: "rt-test2 title"
  - url: /assets/images/academy/rt-cellular.png
    image_path: /assets/images/academy/rt-cellular.png
    alt: "rt-cellular alt"
    title: "rt-cellular title"
  - url: /assets/images/academy/rt-marble.png
    image_path: /assets/images/academy/rt-marble.png
    alt: "rt-marble alt"
    title: "rt-marble title"
---

{: .text-justify}

{: .font-size: $type-size-1 }

This simple parallel raytracer is another Computer Graphics assignment. I personally found it very interesting to develop this project, because I had the opportunity to implement some extra features like procedural textures ([Perlin noise](https://en.wikipedia.org/wiki/Perlin_noise){:target="_blank"} based and [Worley noise](https://en.wikipedia.org/wiki/Worley_noise){:target="_blank"} based). Here are some images generated from my raytracer.

{% include gallery  layout="half"  id="gallery" caption="Some test images rendered with the raytracer" %}

<br />

<a href="https://github.com/carluciosk8/raytracer" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code available on GitHub</a>
