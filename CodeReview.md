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
		
<h2 id="content">Code Review Narrative</h2>
<p> </p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Code Analysis | Software design and engineering</h3>
		<p> First things first, we must understand the existing functionalities of this program. Using the eclipse IDE, we are using the java language to develop a program that creates and/or updates an appointment. We have the following files, Appointment.java, appointmenttest.java and we have appointmentserivce.java and appointmentserviceTest.java. These files and their matching test files work in conjunction to not only create a program but also test the functionalities of a program. The structure of these files show that the code is implemented correctly and conforms to pertinent standards, as we can see through indentations, clear to read, doesn’t have identifiers used for multiple purposes and so on. This structure is consistent across all four of our files and there are no uncalled-for procedures and/or unreachable code implemented in our design. When taking a look at our test files, there is not any leftover test routines or anything along those lines; our tests here are designed to test the functionalities of our code, nothing more and nothing less. The way I designed this code and the way all code should be designed is in a modular fashion. Having the ability to replace sections and/or copy sections of this project and implement it into another is important. It is clear that we can do that with the code we have here; a good example of this is the setup portion for the test files, this is a very modular section and because of this, we are able to take this same setup structure and implement it elsewhere if need be. I think the code I have here is about as concise as it can be, I believe if it were any more concise it would be hard to read and not nearly as modular as it currently is; it is also about as efficient as it can be to my knowledge. We can also see in appointment.java and appointmentserivce.java, we use symbolics for constants and string constants, all our “final private byte” variables and the “final private List”  are examples of symbolic constants.</p>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Code Analysis | Algorithms and data structure</h3>
		<p>For category two, Algorithms and data structure we have some java files that work in conjunction to simulate an operating systems utilizing algorithms and data structures to manage all its components. More specifically, the focus here about Windows OS and how it goes about managing processes, memory, files, and system resources through algorithms and data structures. This uses six java files, PageTableEntry, TLBEntry, VM, MakeBACKING_STORE, Frame, and Address. These 6 files allo the user to input a given page size and virtual address and calculate the page number and offset. This is done through algorithms and data structures! While this code may be a little hard to follow at first glace, we can clearly see what is what when following the comments provided. Here we can see what section of the code is doing what and it is very consistent with the code itself. When analyzing the variable here, we can see that all of these variables we are working with, FRAME_Size, or ADDRESS_SIZE are all very self explanatory; naming is consistent and clear. We can also see that the consistency between the type of variables and the casting of these variables. It is also clear that we do not have any redundant or unused variables, all the of the code we have here is necessary.(VM.java and MakeBACKING_STORE.java) In terms of arithmetic operations, we can see that this code does indeed avoid comparing floats; it actually doesn’t even utilize floats. Because of this structure, we do not have to worry about the possibility of rounding errors.Considering this code specifically focuses on the translation of virtual memory, we are really only working with a specific set of number;  therefore the concern of adding or subtraction numbers with different magnitudes is negligible. Also, because of the variables and integers we are working with, the need to test divisors for zero or noise is not really needed here.</p>
	</div>
	<!-- Break -->
	<div class="4u 12u$(medium)">
		<h3>Code Analysis | Databases</h3>
		<p>We are analyzing a database in form of a .csv file and developing a program that can either create bids, load bids from a .csv file, display all bids, find bids, and remove bids. This program is created using C++ in the Microsoft visual studio IDE. This specific project focuses the implementation of a database through the use of loops, branches and even some defensive programming! Going through our code here, we can see that all logic constructs are complete and properly nested. In turn, we obviously have the common cases first In our IF- -ELSE statements   We can also see that each case has a proper break therefore we have a default for these case statements, that will inevitably exit our program. Because this is implemented, we have loop termination conditions, each case does.  We can see that our menu/index is implemented before any of the switch cases, this ensures that our index is working and referenced correctly. The statements used in these loops must stay in the loops because it keeps our program from breaking and looping indefinitely upon input.  Because of the design of this code, we do not have to worry about the manipulation of the index variable or using it upon exiting the loop. This is untimely because this utilizes switch cases. The use of switch cases ultimately allows us to test our user input against the records and file bounds we have in place.Because this program utilizes .csv files, we must have some level of defensive programming that ensures our file is valid and this is done through our command line arguments. Due to the fact that this program uses a .csv file, all output files are indeed assigned to memory and because of this each statement provided the correct data operated. Return 0; at the end of our program is in place to ensure every memory allocation is then deallocated before exiting. To my knowledge, we do not have any timeouts but we do have error traps in the event that an undesirable input is given, this is done through our if/else statements! We can see that our program attempts to check for the existence of the required .csv file before attempting to access, although if it does not exist, it does not seem to stop the program from attempting to access which may prove to be an issue. Because we are returning memory to zero at the end of our program, we are leaving things in their original state upon termination which is the desire for this specific project.</p>
	
