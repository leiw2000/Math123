---
layout: post
title:  "20151001 - How Many Squares With Positive Integer Side Lengths"
date:   2015-10-01 18:52:55
categories: NumberTheory
author: ev3commander
---
Areteem魔法学园每日一题2015年10月1日

Areteem Institute of Witchcraft and Wizardry
Daily Magic Spells October 1, 2015

在 8x8 的均匀点阵中，相邻点的距离为1。问：以点阵中的点为顶点且边长为正整数的正方形共有多少个？


In an 8x8 array of evenly spaced points, the distance between adjacent points is 1. Find the number of squares with positive integer side lengths and all vertices belonging to the array.
<br>
<svg width="250" height="250"> 
  <g fill="none" stroke="black" stroke-width="4">
    <path stroke-dasharray="5,25" d="M5 10 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 40 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 70 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 100 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 130 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 160 l215 0"></path>
    <path stroke-dasharray="5,25" d="M5 190 l215 0"></path>      
    <path stroke-dasharray="5,25" d="M5 220 l215 0"></path>          
  </g>
</svg>


### Solution <button>Show / Hide</button>

<solution>

49+36+25+16+9+4+1+2 = 142
<br>
The extra 2 are slant with side = 5. See below:
<br>
<script>var svg = document.createElementNS('http://www.w3.org/2000/svg', 'svg');
svg.setAttribute('width', 300)
svg.setAttribute('height', 300)
//svg.style.background = "PaleGreen";
document.getElementsByTagName("solution")[0].appendChild(svg);
var g = document.createElementNS('http://www.w3.org/2000/svg', 'g');
g.setAttribute('transform', 'translate(32,32)');
svg.appendChild(g);

var output = document.createElement('h1');
output.style.fontSize = "24px";
output.style.margin = '0.5em';
document.getElementsByTagName("solution")[0].appendChild(output);

function point(x, y) {
  var c = document.createElementNS('http://www.w3.org/2000/svg', 'circle');
  c.setAttribute('cx', x * 32);
  c.setAttribute('cy', y * 32);
  c.setAttribute('r', 3)
  g.appendChild(c);
}

var count = 1;
var delay = 0;

function polygon(pArray, color) {
  var p = document.createElementNS('http://www.w3.org/2000/svg', 'polygon');
  var points = '';
  for (var i = 0; i < pArray.length; i++) {
    points += pArray[i][0] * 32 + ', ' + pArray[i][1] * 32 + ' ';
  }
  p.setAttribute('points', points);
  p.setAttribute('fill', 'none');
  p.setAttribute('stroke', 'red')
  p.setAttribute('stroke-width', 4);
  delay += 200;
  setTimeout(function() {
    g.appendChild(p);
    output.innerHTML = count++;
    setTimeout(function() {
      p.setAttribute('stroke', 'blue');
      p.setAttribute('stroke-width', 1);
    }, 200)
  }, delay);
}

for (var i = 0; i < 8; i++) {
  for (var j = 0; j < 8; j++) {
    point(i, j);
  }
}

var p0, p1, p2, p3;
for (var k = 1; k < 8; k++) {
  for (var i = 0; i < 8 - k; i++) {
    for (var j = 0; j < 8 - k; j++) {
      p0 = [i, j];
      p1 = [i + k, j];
      p2 = [i + k, j + k];
      p3 = [i, j + k];
      polygon([p0, p1, p2, p3]);
    }
  }
}

p0 = [3, 0];
p1 = [7, 3];
p2 = [4, 7];
p3 = [0, 4];
polygon([p0, p1, p2, p3]);

p0 = [0, 3];
p1 = [3, 7];
p2 = [7, 4];
p3 = [4, 0];
polygon([p0, p1, p2, p3]);</script>
</solution>
