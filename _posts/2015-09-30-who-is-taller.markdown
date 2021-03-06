---
layout: post
title:  "20150930 - Who is Taller"
date:   2015-09-30 18:52:55
categories: Logic
author: ev3commander
---


Areteem魔法学园每日一题2015年9月30日

Areteem Institute of Witchcraft and Wizardry
Daily Magic Spells September 30, 2015

100名学生身高各不相同。他们排成了一个10x10的方阵。从每行中挑出最高的学生，再从这10个各行最高的学生中选最矮的，称其为甲。然后从每列中挑出最矮的学生，再从这10个每列最矮的学生中选最高的，称其为乙。甲和乙谁高？

100 students, all with distinct heights, stand in a 10x10 array. From each row, choose the tallest student, and among these 10 tallest in their rows, assume student A is the shortest one. Next, from each column, choose the shortest student, and among these 10 shortest in their columns, assume student B is the tallest one. Between A and B, who is taller?

### Solution <button>Show / Hide</button>

<solution>

There are 4 possibilities of A and B in the array.
<br><br>
1. They are on the same row.
<br>
In this case, A > B because A is supposed to be the tallest in the same row.
<br>
<svg width="300" height="300">
  <rect width="300" height="300" style="fill:rgb(255,255,255);stroke-width:3;stroke:rgb(0,0,0)" />
  <line x1="30" y1="0" x2="30" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="60" y1="0" x2="60" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="90" y1="0" x2="90" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="120" y1="0" x2="120" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="180" y1="0" x2="180" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="210" y1="0" x2="210" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="240" y1="0" x2="240" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="270" y1="0" x2="270" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="0" y1="30" x2="300" y2="30" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="60" x2="300" y2="60" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="90" x2="300" y2="90" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="120" x2="300" y2="120" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="150" x2="300" y2="150" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="180" x2="300" y2="180" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="210" x2="300" y2="210" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="240" x2="300" y2="240" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="270" x2="300" y2="270" style="stroke:rgb(0,0,0);stroke-width:2" />
  <text x="70" y="80" fill="red">A</text>
  <text x="220" y="80" fill="blue">B</text>
  <rect x="0" y="60" width="300" height="30" style="fill:rgb(25,25,255);stroke-width:3;stroke:rgb(0,0,0)" fill-opacity="0.2" />
</svg>
<br><br>
2. They are on the same column.
<br>
In this case, A > B because B is supposed to be the shortest in the same column.
<br>
<svg width="300" height="300">
  <rect width="300" height="300" style="fill:rgb(255,255,255);stroke-width:3;stroke:rgb(0,0,0)" />
  <line x1="30" y1="0" x2="30" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="60" y1="0" x2="60" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="90" y1="0" x2="90" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="120" y1="0" x2="120" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="180" y1="0" x2="180" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="210" y1="0" x2="210" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="240" y1="0" x2="240" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="270" y1="0" x2="270" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="0" y1="30" x2="300" y2="30" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="60" x2="300" y2="60" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="90" x2="300" y2="90" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="120" x2="300" y2="120" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="150" x2="300" y2="150" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="180" x2="300" y2="180" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="210" x2="300" y2="210" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="240" x2="300" y2="240" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="270" x2="300" y2="270" style="stroke:rgb(0,0,0);stroke-width:2" />
  <text x="70" y="80" fill="red">A</text>
  <text x="70" y="170" fill="blue">B</text>
  <rect x="60" y="0" width="30" height="300" style="fill:rgb(25,255,255);stroke-width:3;stroke:rgb(0,0,0)" fill-opacity="0.2" />
</svg>
<br><br>
3. They are on different rows and different columns:
<br>
In this case, C is on the same row as A, so A > C. C is on the same column as B, so C > B. Therefore A > C.<br>

<svg width="300" height="300">
  <rect width="300" height="300" style="fill:rgb(255,255,255);stroke-width:3;stroke:rgb(0,0,0)" />
  <line x1="30" y1="0" x2="30" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="60" y1="0" x2="60" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="90" y1="0" x2="90" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="120" y1="0" x2="120" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="150" y1="0" x2="150" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="180" y1="0" x2="180" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="210" y1="0" x2="210" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="240" y1="0" x2="240" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="270" y1="0" x2="270" y2="300" style="stroke:rgb(0,0,0);stroke-width:2" />  
  <line x1="0" y1="30" x2="300" y2="30" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="60" x2="300" y2="60" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="90" x2="300" y2="90" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="120" x2="300" y2="120" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="150" x2="300" y2="150" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="180" x2="300" y2="180" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="210" x2="300" y2="210" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="240" x2="300" y2="240" style="stroke:rgb(0,0,0);stroke-width:2" />
  <line x1="0" y1="270" x2="300" y2="270" style="stroke:rgb(0,0,0);stroke-width:2" />
  <text x="70" y="80" fill="red">A</text>
  <text x="220" y="170" fill="blue">B</text>
  <rect x="0" y="60" width="300" height="30" style="fill:rgb(25,25,255);stroke-width:3;stroke:rgb(0,0,0)" fill-opacity="0.2" />
  <rect x="210" y="0" width="30" height="300" style="fill:rgb(25,255,255);stroke-width:3;stroke:rgb(0,0,0)" fill-opacity="0.2" />
  <text x="220" y="80" fill="green">C</text>
</svg>
<br/><br/>
In the above cases A is the taller one.
<br><br>
4. A and B are actually the same person.
<br>


</solution>
