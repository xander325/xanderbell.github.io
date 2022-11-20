---
layout: page
title: Databases
image: assets/images/ART3code1JPG.JPG
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Databases</h1>
		</header>

<!-- Content -->
<h2 id="content"></h2>
<p>This program utilizes a CSV file and imports it into a hash table for our program to search through and remove items from the desired database and we have a dashboard of users to utilize. The goal of this artifact is to showcase databases and my competency with them. In efforts to reach our course outcomes; demonstrating an ability to use well-founded and innovative techniques and demonstrating a security mindset that anticipates adversarial exploits, designs to expose potential vulnerabilities, and mitigate design flaws, I felt this program was most applicable.</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Code Analysis</h3>
<p>We are analyzing a database in form of a CSV file and developing a program that can either create bids, load bids from a .csv file, display all bids, find bids, and remove bids. This program is created using C++ in the Microsoft visual studio IDE. This specific project focuses the implementation of a database through the use of loops, branches and even some defensive programming! Going through our code, we can see that all logic constructs are complete and properly nested. In turn, we obviously have the common cases first in our IF--ELSE statements. We can also see that each case has a proper break therefore we have a default for these case statements, that will inevitably exit our program; Because this is implemented, each case has loop termination conditions.  We can see that our menu/index is implemented before any of the switch cases, this ensures that our index is working and referenced correctly.</p>
<div class="12u$ 12u$(medium)"><span class="image fit"><img src="assets/images/ART3code2.JPG" alt="" /></span></div>
</div>
	<div class="6u$ 12u$(small)">
		<h3></h3>
<p>he statements used in these loops must stay in the loops because it keeps our program from breaking and looping indefinitely upon input. The use of switch cases ultimately allows us to test our user input against the records and file bounds we have in place and because this program utilizes .csv files, we must have some level of defensive programming that ensures our file is valid and this is done through our command line arguments. Due to the fact that this program uses a CSV file, all output files are assigned to memory. "Return 0," at the end of our program is in place to ensure every memory allocation is then deallocated before exiting.</p>
<div class="12u$ 12u$(small)"><span class="image fit"><img src="assets/images/ART3test2.JPG" alt="" /></span></div>
	</div>
	<!-- Break -->
	<div class="6u 12u$(small)">
		<h3>Enhancements</h3>
		<p> The enhancements I have made here have revealed my abilities with software development as I have not only fixed the program and got it running from its original state but I have also implemented a fail-safe for the remove function, confirming with the user before removing a file.

I decided it would be best to remain using hash tables and take a different approach to my enhancements. Ultimately, I was able to meet those same desired outcomes with the approach of implementing a user inputted a bid id search and a user inputted removal of record via bid ID.
</p>
	</div>
	<div class="6u 12u$(small)">
		<h3>Outcomes/Reflections</h3>
		<p>

It was helpful to circle back and work with databases and it was a nice refresher!
</p>
       </div>
</div>

<hr class="major" />
		
<!-- Buttons -->
<h4></h4>
<ul class="actions vertical">
	<li><a href="https://bitbucket.org/xanderbell/cs499_art3/src/master/" class="button fit">Bitbucket Repository Link</a></li>
	<li><a href="https://xander325.github.io/xanderbell.github.io/artifact_two.html" class="button special fit">Back Home</a></li>
	</ul>
</div>
