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
<p>This program utilizes a CSV file and imports the file into a hash table for our program to search through and remove items from. The user utilizes a dashboard to access and edit the database.</p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Code Analysis</h3>
<p>We are analyzing a database in form of a CSV file and have developed a program that can either  load bids from a CSV file, display bids, find bids, and/or remove bids. This program is created using C++ in the Microsoft Visual Studio IDE. This specific project focuses the implementation of a database through the use of loops, branches and even some defensive programming! Going through our code, we can see that all logic constructs are complete and properly nested. In turn, we obviously have the common cases first in our IF--ELSE statements. We can also see that each case has a proper break therefore we have a default for these case statements, that will inevitably exit our program; Because this is implemented, each case has loop termination conditions.  We can see that our menu/index is implemented before any of the switch cases, this ensures that our index is working and referenced correctly.</p>
<p>The statements used in these loops must stay in the loops because it keeps our program from breaking and looping indefinitely upon input. The use of switch cases ultimately allows us to test our user input against the records and file bounds we have in place and because this program utilizes CSV files, we must have some level of defensive programming that ensures our file is valid and this is done through our command line arguments.</p>
		<div class="12u$ 12u$(medium)"><span class="image fit"><img src="assets/images/ART3term5.JPG" alt="" /></span></div>
</div>
	<div class="6u$ 12u$(small)">
		<h3></h3>
<div class="12u$ 12u$(medium)"><span class="image fit"><img src="assets/images/ART3_code.JPG" alt="" /></span></div>
<div class="12u$ 12u$(medium)"><span class="image fit"><img src="assets/images/ART3term6.JPG" alt="" /></span></div>
	</div>
	<!-- Break -->
	<div class="6u 12u$(small)">
		<h3>Enhancements</h3>
<p> I made several enhancments here as the program was not working intially; Once I got it working I was able to make a descion on enhancements. After experiementing with binary trees, I decided it would be best to remain using hash tables. Ultimately, I was able to meet the desired outcomes by taking the approach of implementing a user inputted a bid id search function and a user inputted removal of record via bid ID. I also added a feature requiring user confirmation before the removal of a record.
</p>
	</div>
	<div class="6u 12u$(small)">
		<h3>Outcomes/Reflections</h3>
<p>In efforts to reach our course outcomes; demonstrating an ability to use well-founded and innovative techniques and demonstrating a security mindset that anticipates adversarial exploits, designs to expose potential vulnerabilities, and mitigate design flaws, I felt this program was most applicable. I was also able to demonstrate innovative techniques through my enhancements while also following industry-standard designs. 
</p>
       </div>
</div>

<hr class="major" />
		
<!-- Buttons -->
<h4></h4>
<ul class="actions vertical">
	<li><a href="https://bitbucket.org/xanderlbell/artifact_3_enhanced/src/master/" class="button fit">Bitbucket Repository Link (Enhanced Files)</a></li>
	<li><a href="https://bitbucket.org/xanderlbell/artifact_3_orginal/src/master/" class="button fit">Bitbucket Repository Link (Orginal Files)</a></li>
	<li><a href="https://xander325.github.io/xanderbell.github.io/artifact_two.html" class="button special fit">Next</a></li>
	</ul>
</div>
