---
layout: post
title: Test Development
description: Validation of new production seals
img: /img/2.jpg
---

Developed two major tests: One for validating a new production seal and another test to validate the strength of a rear spoiler. 

<h3>
	Validation of Production Seal
</h3>

<br/>
I received the test request and then worked with the Reliability team to figure out test parameters. My general work flow for this project was Test Requirement -> Testing Parameters & Failure Criteria -> Prototype test fixture and test samples -> Iterate Design -> Fabricate and Procure Components -> Test Execution -> Test Report
<br/><br/>
The entire cycle from test request to writing the test report was almost 8 months.

Test Requirements:
<ul>
	<li> Cost effective test fixture </li>
	<li> Fast turnaround time for fabrication </li>
	<li> Large sample number, so ease of assembly is needed </li>
	<li> Reflects test boundary conditions well </li>
	<li> Test fixture itself will not affect test results </li>
</ul>
Test Parameters:
<ul>	
	<li> 4 different sealing materials </li>
	<li> 10 Samples for each material and each thermal test </li>
</ul>

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/8350_prototype.png" alt="" title="prototype"/>
	<img class="col two" src="{{ site.baseurl }}/img/8350_cad.JPG" alt="" title="final cad"/>
</div>
<div class="col three caption">
	Left: Small prototype version. Right: Full size test fixture with 10 samples.
</div>

The validation test itself was in the form of a pressure decay test to characterize the performance of the seals as they were proggressively aged. 

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/8350_setup.JPG" alt="" title="Test Setup"/>
</div>

<div class="col three caption">
	Test setup to quantify pressure decay over time
</div>

<br/>
I initially handled the test execution of the phase to develop appropriate methodology to record and log the pressure drop data corresponding with the thermal aging of the material. As some test parameters were different from similar tests done before, I also developed methodology to pinpoint leak areas to document location of leaks. This was important in identifying patterns in failure modes and for troubleshooting assembly issues. After several tests and refining the test procedure, I handed off the rest of the test execution to technicians in the lab who logged the data for the rest of the test. 
<br/>

Throughout the test, I generated documents showing the test progress, as well as an derivation of the failure criteria, in the hopes of improving understanding of pressure decay tests in the team. At the end of the test, I wrote a test report to document my findings and the test setup and procedure. 
<br/>
<br/>

<h3>
	Abuse Test of Rear Spoiler
</h3>

<br/>
I received another test request to validate the strength of the bond between the rear spoiler and the trunk. 

<h4> First Iteration: </h4>
I set up the spoiler (on the trunk) and the actuator on stands and ran the test, where the actuator pushed on the spoiler, attempting to delaminate the bond between the spoiler and the trunk. I also set up cameras and lights around the test setup to record pictorial results at the same time. The trunk buckled before the expected load. Turns out it was because the trunk itself was slipping on the stand.

<h4> Second Iteration: </h4>
I designed and fabricated the mounting structures within 1-2 weeks. The trunk is now mounted onto the stand in the same way that it would be supported on the physical car. This helped immensely with the slipping problem. The peak load is now significantly higher before dropping off at the yield point. 

<h4> Third Iteration </h4>
However, I realised that the spoiler that the actuator is pushing on has a displacement that is different from that of the trunk's. The load cell is in line with the actuator and the actuator is contacting with the spoiler. Hence the the displacement reading = Trunk Displacment + Spoiler Displacement. However, we are also interested in the relative spoiler displacement.

<h4> Fourth Iteration </h4>
<div>
	<span class="col two"> <br/>The LVDT is connected to the trunk and logs the trunk displacement. Hence the relative displacement is computed by taking the total displacement logged by the actuator and subtracting the trunk displacement recorded by the LVDT. The abstract setup is on the right. (The black rectangle is the core that slides along the LVDT and indicates the displacement.)
	<br/><br/>
	I also initiated an extra test for a thermally aged sample that was not on the test request. Running the test on an aged sample would give us additional confidence for the bond strength.
	</span>
	<img class="col one" style="width=50%;" src="{{ site.baseurl }}/img/10897_setup.JPG" alt="" title="Displacement measurement setup"/>
</div>

<br/>
At the end of testing the samples, I compiled a presentation with screenshots from videos recorded during the test (the code to grab screenshots and compile a powerpoint automatically is here:tbu) and post processed the data collected. My findings and test setup and procedure was similarly recorded in a test report. 
<br/><br/>
