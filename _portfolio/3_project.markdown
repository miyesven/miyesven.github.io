---
layout: post
title: Robot
description: 
img: /img/3.jpg
---
<h3> Powertrain </h3>

<br/>
<div style="width=100%;">
	<span class="col half"> 
		One of the first things I designed was the powertrain as it was essential for the electrical and software leads to start testing the motors and configuring the PID. Our competition strategy also hinged on how sharply the robot could turn. For sharp turns, I made the trackwidth as small as the physical geometry allowed.
		<br/><br/>
		Due to excessive wear of the key hole between the shaft and the pinion, we eventually made all the gears from delrin instead of MDF from the second chassis onwards. The maintenance of the powertrain dropped to nearly zero occurrences throughout the prototyping and competition duration.
	</span>
	<img class="col half" src="{{ site.baseurl }}/img/robot_powertrain.jpg" alt="" title="first powertrain iteration"/>
</div>

<h3> Chassis </h3>

<div>
	<img class="col three" src="{{ site.baseurl }}/img/robot_chassis.svg" alt="" title="Chassis evolution through three iterations"/>
</div>

<div class="col three caption">
	The evolution of our main chassis, with varying levels of completions.
</div>

<br/>
 I designed and fabricated all components of the robot except for most electrical hardware and the gripper of the arm. 
 <br/>
 Main considerations were:
 <ul>
 	<li> Geometrical restrictions posed by the track (there were gates at the starting point that limited to total size of the robot) 
 	</li>
 	<li> The weight of the robot (as we wanted to hoist the entire robot on the sliding rail above the track) 
 	</li>
 	<li> The placements of electronics with accessibility in mind- for ease of testing and debugging as time was limited. 
 	</li>
 </ul>

 The chassis needed to be structurally sound to provide adequate mounting support for electronics like the main controller board (TINAH), QRDs (for positioning), batteries and so on. The most involved mounting point was that of the zipline hook.

<h3> Zipline Hook </h3>

<br/>
<div>
	<img class="col three" src="{{ site.baseurl }}/img/robot_zipline.jpg" alt="" title="mechanisms of zipline hook"/>
</div>

<div>
	The zipline hook is an additional challenge we imposed on ourselves as most teams sent baskets down on the inclined slide to score points. Instead of sending a basket down, we wanted to hoist the entire robot onto the pipe standing around 19" above the ground.
	<br/><br/>
	It is a pulley system where the pivot pulley is on the underside of the base plate of the chassis, instead of the top as one might expect. As the motor shaft turns, the kevlar braid winds onto the shaft, decreasing the length between the white rail guide and the bottom of the chassis.  Using the slide as the pivot point, the rest of the robot looses contact with the ground and rolls down the slide.
	<br/><br/>
	The zipline was not only tedious to fabricate and to mount, but integrating the entire system with the software presented many new challenges that we would not have expected. 
	<br/><br/>
	For example, when the hook was released, the spring force caused the front wheel of the robot to lift off the ground as the robot tilted back. This causes the QRDs to miss readings and so we had to come up with solutions on the spot to resolve them in a short amount of time. We put masses on the front to reduce the lift-up movement and adjusted the code, such that the lift-offs are taken into consideration.
	<br/><br/>
	However, after some work, the hook was the most reliable system of our robot.
</div>

<div>
	<img class="col three" src="{{ site.baseurl }}/img/robot_sliding.gif" alt="" title="robot hoist up onto zipline and sliding down"/>
</div>

<br/><br/>
-end-

<br/><br/>




