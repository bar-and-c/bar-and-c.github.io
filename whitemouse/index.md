---
layout: page
title: WhiteMouse
permalink: /whitemouse/
---


WhiteMouse was developed at work, in 2010, to be used as a demo application for OS X. It is basically a Mac 
OS X version of the Windows demo application that hosted [Penball](/penball/), minus the game 
and without spline interpolation for rendering the pen strokes. It lets the user draw 
to a full screen canvas, as well as use the pen for mouse emulation. The mouse emulation is better 
suited for whiteboard projection than for usage with a sheet of paper, but it is possible with paper 
as well, as seen in the film (the pen transmits coordinates when hovering right above the paper). 
Actually, I have used it quite a few times for drawing in Gimp.

In a later version than presented in the film, I added a third mode: drawing to a full screen transparent 
window – very useful for annotating stuff on the screen. 

This movie gives a short demonstration of the two modes of the application, drawing and mouse emulation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/ck4zKqnBhoo" frameborder="0" allowfullscreen></iframe>

The application itself is written in Objective-C, and it is based on a library I wrote for handling 
Bluetooth HID data in OS X, the data coming from streaming pens. The library, written in C, is an 
OS X Framework that parses the data from the Bluetooth HID pens. It was developed at the company, to 
be used as example code, but found its way into many applications: to test the pens’ compatibility and 
performance with Mac OS X, for demo purposes, and some written solely for my pleasure, at my spare time.
