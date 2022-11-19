---
layout: post
title: Algorithms and Data Structures
description:
image: assets/images/ART2code1.JPG
nav-menu: true
---


In this artifact, we have five Java files that all work in conjunction to run our main file, VM.java and this file utilizes a text file of virtual addresses and converts it to its physical addresses and values to ultimately simulate the algorithms and data structures an operating system go through.

This specific artifact showcases the complexity of data structures and algorithms; Because this focuses on how an operating system goes about converting virtual memory to physical memory, I saw an opportunity to add a tool for analyzation purposes, a runtime counter. With my improvements, we can see how long each conversion takes for the computer to process, in nanoseconds. This really puts into perspective the speed and efficiencies of a computer when dealing with different algorithms and data structures.

I feel as though I really did well with the enhancements here; Albeit, my enhancements were small, I believe they made sense and they truly make this artifact much more useful. I know initially when I set the goal for this I was a bit intimidated but it turned out well and I am really happy with no only the simplicity of my addition but the usability of it!

This code was something we were provided in IT-165 and made very small edits too if my memory severs me right. We may have not done anything and just ran it as is to get an idea how a computer converts virtual memory to physical memory. So, with that being said getting it to run correctly was tedious but once I began playing around with enhancements, I was able to figure it out pretty quickly!

Professor comments: For the final portfolio clean up more and make sure you comment a bit more with intent and decision for the overall functionality of each Java file in the header as well as inline so any programmer can hop in and edit. You talk about that you met outcomes, but you have to identify and then articulate which outcomes of the five and how you met one or more of those with each category enhancement. Sound work and with a few small updates, you are ready.

This header for example needs to be modified!

/**

VM.java *
Virtual Memory address translation. *
Given an input parameter, this program extracts
the page number and offset. Then reading the byte in
the file BACKING_STORE residing at that position. *
Usage:
java VM 
 *
@author Gagne, Galvin, Silberschatz
Operating System Concepts with Java - Eighth Edition
Copyright John Wiley & Sons - 2010.
