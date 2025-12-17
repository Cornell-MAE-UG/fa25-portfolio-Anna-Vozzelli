---
layout: project
title: Blade Design
description: Wind Turbine Blade Design
technologies: [Fusion 360, ANSYS, Matlab]
image: /assets/images/side-blade.png
---

For my Fluids and Heat Transfer Lab we were asked to design a wind turbine blade in groups of four. We had to choose a value of RPM for our blade to operate at, given a possible range of wind speeds, to generate maximum power. We chose a value of 500 RPM based on previous lab experience. We also chose a NACA 4418 profile for our blade based on its lift to drag ratio and manufacturability.

We designed our blade by optimizing for the ideal angle of attack at every calculated point along the blade, with a resolution of about .6 inches between each point. We made a model of the blade, put the model in ANSYS, and calculated the maximum bending moment to ensure it woud not break.

We tested the blades in Cornell's Big Blue Wind Tunnel. We scanned across all reasonable wind velocities, adjusting the RPM at each measurement via a torque break to ensure our calculated RPM was the most optimal at every point. We then plotted curves of power vs RPM, as shown below. We analyzed our data, and it turns out our maximum power occured closer to 400 RPM, which we will keep in mind should we return to the project.

I made the CAD. I took our NACA 4418 profile and scaled, rotated, and aligned 10 instances of it to give us a decent resolution on our blade. This worked, as you can see in the page image there is no visible artifacting on the blade's model. Once the instances were aligned, I traced a spline along the outer edge at the front and tail and did a rail lift of the initial profile to generate the blade. 


![Power Curves]({{ "assets/images/PowerCruve.png" | relative_url }})