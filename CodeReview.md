---
layout: page
title: Code Review
image: assets/images/ART3code1JPG.JPG
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Code Review</h1>
		</header>

<!-- Content -->
		
<iframe width="1280" height="720" src="https://www.youtube.com/embed/5lt3GDEAQVY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		
<h2 id="content">Code Analysis | Software Design and Engineering</h2>
<p>First things first, we must understand the existing functionalities of this program. Using the eclipse IDE, we are using the Java language to develop a program that creates and/or updates an appointment. We have the following files, Appointment.java, appointmentTest.java and we have appointmentSerivce.java and appointmentserviceTest.java. These files and their matching test files work in conjunction to not only create a program but also test the functionalities of a program. The structure of these files show that the code is implemented correctly and conforms to pertinent standards, as we can see through indentations it is clear to read and doesn’t have identifiers used for multiple purposes and so on. This structure is consistent across all four of our files and there are no uncalled-for procedures and/or unreachable code implemented in our design. When taking a look at our test files, there is not any leftover test routines or anything along those lines; our tests here are designed to test the functionalities of our code, nothing more and nothing less. The way I designed this code and the way all code should be designed is in a modular fashion. Having the ability to replace sections and/or copy sections of this project and implement it into another is important. It is clear that we can do that with the code we have here; a good example of this is the setup portion for the test files, this is a very modular section and because of this, we are able to take this same setup structure and implement it elsewhere if need be. I think the code I have here is about as concise as it can be, I believe if it were any more concise it would be hard to read and not nearly as modular as it currently is.</p>
		
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Code Analysis | Algorithms and Data Structure</h3>
		<p>For category two, Algorithms and data structures we have more Java files that work in conjunction to simulate an operating system utilizing algorithms and data structures to manage all it's components. More specifically, the focus here is about Windows OS and how it goes about managing processes, memory, files, and system resources through algorithms and data structures. This uses six Java files: PageTableEntry, TLBEntry, VM, MakeBACKING_STORE, Frame, and Address. These 6 files allow the user to input a given page size and virtual address and calculate the page number and offset. This is done through algorithms and data structures. While this code may be a little hard to follow at first glace, we can clearly see what is what when following the comments provided; Here we can see what section of the code is doing what and it is very consistent with the code itself. When analyzing the variables here, we can see that all of these variables we are working with, FRAME_Size, or ADDRESS_SIZE are all very self explanatory; Naming is consistent and clear. We can also see that the consistency between the type of variables and the casting of these variables. It is also clear that we do not have any redundant or unused variables; All the of the code we have here is necessary. In terms of arithmetic operations, we can see that this code does indeed avoid comparing floats; It does not utilize floats. Because of this structure, we do not have to worry about the possibility of rounding errors. Considering this code specifically focuses on the translation of virtual memory, we are really only working with a specific set of numbers.</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Code Analysis | Databases</h3>
		<p>We are analyzing a database in form of a CSV file and developing a program that can either create bids, load bids from a .csv file, display all bids, find bids, and remove bids. This program is created using C++ in the Microsoft visual studio IDE. This specific project focuses the implementation of a database through the use of loops, branches and even some defensive programming! Going through our code, we can see that all logic constructs are complete and properly nested. In turn, we obviously have the common cases first in our IF--ELSE statements. We can also see that each case has a proper break therefore we have a default for these case statements, that will inevitably exit our program; Because this is implemented, each case has loop termination conditions.  We can see that our menu/index is implemented before any of the switch cases, this ensures that our index is working and referenced correctly. The statements used in these loops must stay in the loops because it keeps our program from breaking and looping indefinitely upon input. The use of switch cases ultimately allows us to test our user input against the records and file bounds we have in place and because this program utilizes .csv files, we must have some level of defensive programming that ensures our file is valid and this is done through our command line arguments. Due to the fact that this program uses a CSV file, all output files are assigned to memory. "Return 0," at the end of our program is in place to ensure every memory allocation is then deallocated before exiting.</p>
