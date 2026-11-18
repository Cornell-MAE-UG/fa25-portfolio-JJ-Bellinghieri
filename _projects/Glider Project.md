---
layout: project
title: Glider Competition
description: Class project to design a glider to fly 20 meters as slowly as possible
technologies: [Fusion 360, xflr5, SOLIDWORKS]
image: /assets/images/Glider Final CAD.png
order: 1
---
### Project Description 
This was a class project completed for MAE 3050 Introduction to Aeronautics to design and build a glider. The glider had to be designed to be launchable from a standard spring powered launcher at a height of 5 meters. The goal of the project was to make the glider fly 20 meters as slowly as possible.
<br>
<br>
<br>

### Initial Plan
Our initial plan was to design the glider so that we could achieve a glide angle that left our glider with 1 meter of height as a factor of saftey when it crossed the finish line to account for effects we couldn't consider in our calculations. We did this since landing before crossing 20 meters would lead to our glider being disqualified so we considered the possibilty of leaving some altitue unused a good trade off. This condition sets our minimum Coefficent of Lift over Coefficent of Drag at a value of 5.


### Foil Analysis
![mh81 diagram]({{ "/assets/images/mh81foil.png" | relative_url }}){: .inline-image-r style="width: 450px"}
Our initial airfoil analysis in xflr5 consisted of 6 airfoils labled for use in gliders. We estimated our range of reasonable Reynolds numbers to look at for our design to be in the range of 20,000 to 80,000. From this we chose the mh81 airfoil because it was closest to our target Cl/CD of 5 at a Reynolds number of 30,000 while maintaing a small static margin which we believed would allow us to make our horizontal stablizer design smaller increasing our lift.
<br>
<br>
<br>
![sd7037 diagram]({{ "/assets/images/SD7037.png" | relative_url }}){: .inline-image-r style="width: 450px"}Shortly after picking this airfoil we realized that the drag coefficent for this airfoil would not include 3d effects such as drag caused by wing tip vortices or parasitic drag from other parts of the glider. This led us to revise our airfoil choice to sd7037 which had a higher CD/CL and exhibited gentle stall behavior which would allow our glider to recover more easily in the event of stall.