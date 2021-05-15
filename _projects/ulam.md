---
title: Ulam Spiral
excerpt: "Ulam Spiral"
layout: single
classes: wide
sidebar:
  nav: projects
header:
  teaser: /assets/images/ulam.png
---

{: .text-justify}
This assignment of algorithms project and analysis discipline has a very simple source code. The challenge here was to derive a O(1) complexity solution for the points of squared spiral from where the prime numbers are assigned to build the Ulam Spiral.

My solution (x,y) to the point n is:

{: .text-left}
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
$$
\begin{align}
& b = \lfloor \sqrt{n} \rfloor \\
& h = \lfloor{\frac{b + 1}{2}}\rfloor \\
& d = n - b^{2} + (b\ \ \textrm{mod}\ \ 2) \\
& dx =
\begin{cases}
    2h & \textrm{if}\ d > 2h \\
    d & \textrm{otherwise}
\end{cases} \\
& dy =
\begin{cases}
    d - 2h & \textrm{if}\ d > 2h \\
    0 & \textrm{otherwise}
\end{cases} \\
& s = -1^{b\ \ \textrm{mod}\ \ 2} \\
& x = s (dx - h) \\
& y = s (dy - h) \\
\end{align}
$$

{: .text-justify}
Here is a video of the program running for n=999:

<iframe iframe width="512" height="512" src="https://www.youtube.com/embed/eCQwUr_cVT0" frameborder="0"></iframe>
