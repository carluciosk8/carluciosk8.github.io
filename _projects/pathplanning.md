---
title: "PathPlanning / Pathfinding  [2002]"
year: 2002
excerpt: "Bidirectional A* (A star) algorithm implementation"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/pathplanning.png
---

{: .text-justify}

{: .font-size: $type-size-1 }

When I attended Artificial Intelligence discipline, we should choose a problem and present a common and a parallel solution to this problem, implementing it in C using [MPI](https://en.wikipedia.org/wiki/Message_Passing_Interface){:target="_blank"} for parallel programming. I chose the [pathfinding](https://en.wikipedia.org/wiki/Pathfinding){:target="_blank"} problem and proposed to use the [A* (A star)](https://en.wikipedia.org/wiki/A*_search_algorithm){:target="_blank"} algorithm. My parallel solution was to perform a bidirectional search with another task performing the search in the opposite direction until the two searches meet at some point.

<iframe iframe width="720" height="400" src="https://www.youtube.com/embed/qjNmO--SYtE" frameborder="0"></iframe>

<br />

<a href="https://github.com/carluciosk8/pathplanning" target="_blank" title="Source code on GitHub"><i class="fab fa-fw fa-github"></i>Source code available on GitHub</a>
