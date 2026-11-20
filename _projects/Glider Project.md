---
layout: project
title: Glider Competition
description: Class project to design a glider to fly 20 meters as slowly as possible
technologies: [Fusion 360, xflr5, SOLIDWORKS, Laser Cutting]
image: /assets/images/Glider Final CAD.png
order: 1
---
### Project Description 
This was a class project completed for MAE 3050 Introduction to Aeronautics to design and build a glider. The glider had to be designed to be launchable from a standard spring powered launcher at a height of 5 meters. The goal of the project was to make the glider fly 20 meters as slowly as possible.
<br>
<br>
<br>

---
  
  
### Table of Contents

[Preliminary Analysis:](#preliminary-analysis)

[First Prototype:](#first-prototype)

[Final Results:](#final-results)

---
# Preliminary Analysis


### Initial Plan
Our initial plan was to design the glider so that we could achieve a glide angle that left our glider with 1 meter of height as a factor of saftey when it crossed the finish line to account for effects we couldn't consider in our calculations. We did this since landing before crossing 20 meters would lead to our glider being disqualified so we considered the possibilty of leaving some altitue unused a good trade off. This condition sets our minimum Coefficent of Lift over Coefficent of Drag at a value of 5. ![mh81 diagram]({{ "/assets/images/mh81foil.png" | relative_url }}){: .inline-image-r style="width: 250px"}
{: .indent}


### Foil Analysis

Our initial airfoil analysis in xflr5 consisted of 6 airfoils labled for use in gliders. We estimated our range of reasonable Reynolds numbers to look at for our design to be in the range of 20,000 to 80,000. From this we chose the mh81 airfoil because it was closest to our target Cl/CD of 5 at a Reynolds number of 30,000 while maintaing a small static margin which we believed would allow us to make our horizontal stablizer design smaller increasing our lift.
{: .indent}



Shortly after picking this airfoil we realized that the drag coefficent for this airfoil ![sd7037 diagram]({{ "/assets/images/SD7037.png" | relative_url }}){: .inline-image-r style="width: 250px"} would not include 3d effects such as drag caused by wing tip vortices or parasitic drag from other parts of the glider. This led us to revise our airfoil choice to sd7037 at a Reynolds number of 40,000 which had a higher CD/CL and exhibited gentle stall behavior which would allow our glider to recover more easily in the event of stall.
{: .indent}
 

### Wing and Tail Sizing
To size our wing we first rearanged the eqaution for the lift coeffiecnt to solve for the wing surface area in terms of the weight, lift coefficent, airspeed veloctiy, and density. We were then able to get a surface area of 0.18 m^2 by using an estimated mass of 102 grams, ![Wing Area Equation]({{ "/assets/images/Wing Area equation.png" | relative_url }}){: .inline-image-r style="width: 150px"} the density of air at sea level, our chosen value of the lift coefficent from the graph, and our target velocity from our reynolds number. With our target Reynolds number we were then able to compute a chord and use it to calculate a span and aspect ratio giving us all the dimensions for our wing.
{: .indent}


After sizing the wing we were able to move onto sizing the tail. To size the tail we used sailplane coefficents from Raymer with a CHT of 0.5 and a CVT of 0.02. We also chose the maximum fuselage length of 0.9 meters while sizing our tail. This allowed us to reduce the required surface area for our tails by providing the maximum lever arm which was important to us since we expected the amount of tissue paper we would have to cover our wings was going to be a limiting factor in our design. After plugging these values into our equations to size the tail ![Tail Area Equation]({{ "/assets/images/Tail sizing eqs.png" | relative_url }}){: .inline-image-r style="width: 200px"} we reached a result of 0.0324 m^2 for the horizontal stabilizer and 0.0072 m^2 for our vertical stabilizer for a tail arm of 0.5 meters with aspect ratios of 4 and 1.5 respectivley.
{: .indent}


### Static Margin Calculations
These values were then plugged into static margin equations to calculate the gliders aerodynamic center and to place the gliders center of gravity. After verifying our calculations in xflr5 our initial calculations had placed the center of gravity too far forward leading to a negative static margin at all positive angles of attack after recalculating we moved our center of gravity to 0.08m behind the leading edge of the wing which gave no pitching moment at an angle of attack of 2.5 degrees and a CL/CD of 9.781 which was above our minimum value of 5 we set to ensure the glider crossed the 20 meter mark.
{: .indent}
<div class="image-row">
  <figure>
    <img src="{{ '/assets/images/3d view.png' | relative_url }}" alt="3D View of Glider">
    <figcaption>3D View of Glider</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/images/new cm vs alpha.png' | relative_url }}" alt="Moment coefficient vs AOA">
    <figcaption>Moment Coefficient vs AOA</figcaption>
  </figure>
</div>


---
# First prototype 
![Inital Glider CAD]({{ "/assets/images/InitialGliderCAD.png" | relative_url }}){: .inline-image-r style="width: 300px"}


### CAD  
To begin construction of our first prototype my first step was to create a low detail CAD design so that our group could decide on manufacturing methods and how we planned to assemble the glider. After completing the low detail CAD we decided to laser cut the ribs with a hole for a spar to attach them to the main body of the glider. It was also at this point we chose to use flat plats for our tail as an approximation of a symetric airfoil so we could speed up our manufacturing time allowing us to have an earlier test flight and more time to iterate on our design based off our results.
{: .indent}


### Manufacturing and Assembly
The first step in our manufacturing process was to laser cut the ribs for our wing from sheets of balsa wood. To do this I converted our 3D CAD of the ribs into a 2D DXF file that we then sent to be laser cut. This is also where encountered our first issue. The laser cutter we used had a larger kerf than expected which led to our ribs being loose fitting on our spar. We addressed this issue through wrapping the spots on the spar where we planned to attach the ribs with painters tape. This mostly fixed our fit issue but still didn't ensure that all the ribs were properly aligned. During this process we also broke one of our ribs which caused us to have to leave a gap in the middle of our wing. After attaching the ribs to the spar we then wrapped them in tissue paper giving us our wing which we then attached to the fusselage of the glider. Finally we added modeling clay to the nose to move our center of gravity to our calculated location.
{: .indent}
<div class="image-row-three">
  <figure>
    <img src="{{ '/assets/images/Laser cut ribs.png' | relative_url }}" alt="Laser cut ribs">
    <figcaption>Laser cut ribs</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/images/1st Glider wing.png' | relative_url }}" alt="1st Glider wing">
    <figcaption>Prototype Glider wing during assembly</figcaption>
  </figure>

  <figure>
    <img src="{{ '/assets/images/Glider Prototype.png' | relative_url }}" alt="Glider 1st Prototype">
    <figcaption>Fully assembled first glider prototype</figcaption>
  </figure>
</div>


### Test Flight Results and Design Iterations
During the test flight
{: .indent}

<div style="text-align: center;">
  <video controls width="70%">
    <source src="{{ '/assets/Videos/GliderTestFlight.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support this video.
  </video>
</div>
---
# Final Results