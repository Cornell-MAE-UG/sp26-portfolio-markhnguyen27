---
layout: project
title: SP26 Nutcracker Design Part 2 Beam Bending
description: Statics Beam Bending Consideration for Non-Ridged Handles
course: Statics and Mechanics of Solids
image: /assets/images/Beam_Bending.png
technologies: Goodnotes
---


## Overview

For a class, we were asked to design our own nutcracker. This design was intended to both calculate the mechanical advantage through set parameters and develop and analyze initial design concepts for feasibility.

Simple geometry assumptions were made for simplicity.
Material selected was Stainless Steel as a kitchen appliance standard.

After designing our original nutcracker, we were then tasked with altering the design to utilize a linear actuator in some capacity.
<img 
  src="{{ '/assets/images/Nutcracker_AID.png' | relative_url }}" 
  alt="Nutcracker Actuator Initial Design" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">

From my original design with the actuator, a new challenge was assigned, to consider the handle leveraged as now a bending beam instead of a ridged bar

## Part 2 A Scope

**Given:** The Previous Actuator Design and the Following Information

|Macademia Nut Dimensions|Macademia Nut Crack Force|Average Male Grip|Stainless Steel E|
|:---:|:---:|:---:|:---:|
|D = 0.75"|222.18kg|50kg|200GPa|

<br>

**Find:** The location of Maximum Elastic Deflection in the Handles, and solve for any relevant information to be used in dimension calculations

## Part 2 Work

**Plan:** <br>
I) Draw rough design of Device with intial dimensional assumptions <br>
II) Generate an Exploded Free Body Diagram of Device (Top Half) with Actuator Force <br>
III) Model FBD as a Pinned End, Roller at Nut, and Overhang with Force by Actuator <br>
IV) Logically Deduce location of Maximum deflection <br>

**Solution:** <br>
<img 
  src="{{ '/assets/images/NutcrackerPT2A.png' | relative_url }}" 
  alt="Part A Diagram" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">

**Reflection:** <br>
When reflecting on my work done above, the model I chose does well to represent the actuator nutcracker design as no bending would occur between the nut and the hinge, while all the bending would occur after. This model also results in the logical conclusion that the most deflection occurs at the free end of the actuator force, where it will bend from the "roller" or nut location.

## Part 2 B Scope

**Given:** The following parameters

|Macademia Nut Dimensions|Macademia Nut Crack Force|Average Male Grip|Stainless Steel E|
|:---:|:---:|:---:|:---:|
|D = 0.75"|222.18kg|50kg|200GPa|

<br>

**Find:** A "beam" design (CS & Material) s.t. the vertical elastic deflection is < 2% of its length and as mass-efficient as possible.

## Part B Work

**Plan:** <br>
I) Calculate all reactions and Dimensions <br>
II) Utilizing known equation for Overhang, plug in reactions <br>
III) Plug in Material Properties to solve for Minimum I value s.t. ymax is 2% of L <br>
IV) Determine the most mass-efficient Beam Structure (Wide Flanged Beam) <br>
V) Utilizing the Calculated Moment of Inertia (I), use equation for Wide Flanged Beam <br>
VI) Using assumption of dimensional ratios, solve for the dimensions of the Beam <br>
VII) Generate final design with dimensions <br>

**Solution:** <br>

<img 
  src="{{ '/assets/images/NutcrackerPT2B1.png' | relative_url }}" 
  alt="Part B Work" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">
  
<img 
  src="{{ '/assets/images/NutcrackerPT2B2.png' | relative_url }}" 
  alt="Part B Work" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">
  
**Reflection:** <br>
When reflecting on my work done above, dimensional analysis resulted in correct units. Further attention to the magnitude of the dimensions lead me to contemplate the accuracy of my work, but the recognition of a high Youngs Modulus addressed my concerns regarding the size of the I-Beam. Finally, wide flanged I-Beams are traditionally the most mass efficient to high Moment of Inertia cross section, so utilizing it in the design makes the most sense.

## Final Design of Actuator Nutcracker
<img 
  src="{{ '/assets/images/NutcrackerPT2FD.png' | relative_url }}" 
  alt="Part B Work" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">
  
## Discussion

When looking over my design as a whole, one main question came to mind about the logicallity of my design<br>

**First, when looking at the Final Design Above:** the small size of the Cross Section of the "beam" used seemed irrational, but then I took into consideration the large Youngs Modulus of Stainless Steel, the sizing became more practical. Additionally, the thin beam overall makes sense as this is the Minimum viable structure that fullfills the nutcracker requirements. It does not have any "Factor of Safety" as it is the most efficient design I created under perfect hypothetical conditions.

**In the end,** when considering true practical application of my Nutcracker device, mathematically I would work under perfect conditions, but constant usage would eventually wear down the material, causing failure by beam bending. In a hypothetical world, however, it does remain the minimum viable product for project success.

## Sources

**Grip Strength:** Pratt J, De Vito G, Narici M, Segurado R, Dolan J, Conroy J, Boreham C. Grip strength performance from 9431 participants of the GenoFit study: normative data and associated factors. Geroscience. 2021 Oct. https://pmc.ncbi.nlm.nih.gov/articles/PMC8599604/ <br>
**Macademia Nut Strength and Dimensions:** Schrauf et al. Do capuchin monkeys use weight to select hammer tools, Anim Cogn 11, 413–422 (2008). https://doi.org/10.1007/s10071-007-0131-2<br>
**Actuator**: Progressive Automations. Mini Linear Actuator - Optional Feedback. Model: PA-14-3-150. https://www.progressiveautomations.com/products/pa-14?variant=18277278449731 
