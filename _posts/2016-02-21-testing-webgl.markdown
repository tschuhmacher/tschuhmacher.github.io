---
layout: post
title:  "Testing WebGL"
date:   2016-02-21 16:12:00 +0100
categories: awesome webgl
---
Hi y'all!

This my first kramdown test using webgl in the post
*exciting*

<canvas id="myCanvas" width="200" height="100" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML5 canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.arc(95,50,40,0,2*Math.PI);
ctx.stroke();
</script>

Good luck!
