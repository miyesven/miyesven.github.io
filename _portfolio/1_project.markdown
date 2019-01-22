---
layout: post
title: Planetary Gearbox
description: Designed a speed reducer gearbox and accompanying test fixture
img: /img/1.jpg
---

The existing test fixture to test the ultimate torsional strength of half shafts does not have the necessary torque necessary to run the test. A gearbox was needed to increase the torque such that a safety margin could be attained at peak loads during the test. The new test fixture also had the additional capability to be Model 3/S/X compatible.

<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/planet_testfix.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	The test fixture setup in CATIA, complete with test components and constrained gearbox.
</div>

<br/>
Before starting on the design, I asked for quotes from various companies to verify the cost effectiveness of the project. Although we dont have the all the components necessary to product a quote for a custom gearbox, but I floated my ideas to some experienced engineers in the team and they gave me a generic quote from their previous experiences. The result was that the custom gearbox seemed to be a significantly better option than the two alternatives.

<table>
	<tr>
		<th> New Rotary Actuator </th>
		<th> Off the Shelf Gearbox </th>
		<th> Custom Gearbox </th>
	</tr>
	<tr>
		<td> >$40,000 </td>
		<td> $16 000 - $32 000 </td>
		<td> $16 000 - $20 000 </td>
	</tr>
	<tr>
		<td> Long Waiting Time </td>
		<td> Long Waiting Time </td>
		<td> Customizable </td>
	</tr>
	<tr>
		<td> Very expensive </td>
		<td> Clumsy fit for our purpose </td>
		<td> Light, good fit for intended use </td>
	</tr>
</table>		

<br/>
Developed the relevant requirements and specifications for the gearbox below based on test requirements :
<br/>

<table>
	<tr>
		<th> Requirement </th>
		<th> Value </th>
		<th> Resulting Specifications </th>
		<th> Value </th>
	</tr>
	<tr>
		<td> Minimum Torque Needed </td>
		<td> 10kN </td>
		<td> Gear Ratio </td>
		<td> 1:3.5 </td>
	</tr>
	<tr>
		<td> Minimum Rotation Angle Needed </td>
		<td> 70 degrees </td>
		<td> Maximum Rotation Angle Allowed </td>
		<td> 80 degrees </td>
	</tr>
	<tr>
		<td> Safety </td>
		<td> - </td>
		<td> Minimum Safety Factor of Components </td>
		<td> 2.5 </td>
	</tr>
</table>

<br/>
In the process, I have also considered using both spur gears and helical gears. 
<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/planet_spur.png" alt="" title="spur gear concept"/>
	<div class="col one"> Spur gears were too bulky for the torque load that was required. Helical gears were too expensive, plus the weight savings were not significant over the spur gear option.
		<br/><br/>
		<span style="font-size:12px;color:#bdbdbd;"> Spur gear concept CAD on the left. </span>
	</div>
</div>

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/planet_cross.png" alt="" title="gearbox cross section"/>
	<img class="col two" src="{{ site.baseurl }}/img/planet_side.png" alt="" title="gearbox side view"/>
</div>

<div class="caption">
	<span class="col one"> 4 Planets, 1 Sun, 1 Ring </span>
	<span class="col two"> Left side (larger spline): Output, Right Side: Input </span>
</div>

<br/>
A planetary gearset was the most ideal as this configuration:
<ul>
	<li> Allowed for in-line operation with existing actuator </li>
	<li> Most compact and elegant packaging, easy to pickup and setup </li>
	<li> Allowed for the highest safety factors as contact and bending stresses are shared by the planet gear teeth </li>
</ul>

<br/>
Below are the features of the gearbox:
<ol>
	<li> Rapid Disassembly </li>
	<li> Easy Assembly </li>
	<li> Easy to mount on fixture </li>
	<li> More parts but smaller package than a spur gear configuration </li>
	<li> Bearings are fully preloaded </li>
	<li> Reduced cantilevered loads </li>
	<li> Shaft seals to keep grease in </li>
</ol>

<img style="width:85%; height:100%;" src="{{ site.baseurl }}/img/planet_features.JPG" alt="" title="cross section across gearbox"/>
<div class="col three caption">
	Labelled approximate positions of mechanical features in the gearbox
</div>

<br/>
Overall, I spent 2 months, with other projects on my radar, on developing, designing and producing engineering drawings for this project. Prior to the project, I spend about a week familiarising myself with CATIA's features and product tree organisation. I knew I would be making several iterations of the design, so I was mindful of keeping the product tree neat and reasonably parametrized.
<br/><br/>

-end-

<br/><br/>