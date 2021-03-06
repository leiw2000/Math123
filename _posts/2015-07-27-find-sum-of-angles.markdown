---
layout: post
title:  "20150727 - Find Sum of Angles in Squares"
date:   2015-07-27 18:52:55
categories: Geometry Trigonometry
author: ev3commander
---

Three squares are drawn below. Find the sum of angle 1 and angle 2 in degrees.

<svg width="350" height="150">
  <rect x="10" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="110" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="210" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <line x1="10" y1="110" x2="310" y2="10" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="110" y1="110" x2="310" y2="10" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <text x="45" y="108" fill="red">1</text>
  <text x="140" y="108" fill="red">2</text>
</svg>


### Solution <button>Show / Hide</button>

<solution>
In the diagram, angle 2'=angle 2, and the green triangle is an isosceles right triangle, thus the desired sum of angles is 45 degrees.
<br><br>
<svg width="350" height="300">
  <rect x="10" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="110" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="210" y="10" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="10" y="110" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="110" y="110" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>
  <rect x="210" y="110" width="100" height="100" style="fill:none;stroke:blue;stroke-width:1"/>

  <line x1="10" y1="110" x2="310" y2="10" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="110" y1="110" x2="310" y2="10" style="stroke:rgb(255,0,0);stroke-width:1"/>
  <line x1="10" y1="110" x2="210" y2="210" style="stroke:rgb(0,255,0);stroke-width:1"/>
  <line x1="210" y1="210" x2="310" y2="10" style="stroke:rgb(0,255,0);stroke-width:1"/>

  <text x="45" y="108" fill="red">1</text>
  <text x="140" y="108" fill="red">2</text>
  <text x="45" y="125" fill="green">2'</text>
</svg>
</solution>

