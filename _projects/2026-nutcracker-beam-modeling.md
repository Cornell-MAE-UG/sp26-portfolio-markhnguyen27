---
layout: project
title: SP26 Nutcracker Design Part 2 Beam Bending
description: Statics Beam Bending Consideration for Non-Ridged Handles
course: Statics and Mechanics of Solids
image: /assets/images/nutcracker.jpeg
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
  src="{{ '/assets/images/nutcracker_ptA_diagram.png' | relative_url }}" 
  alt="Part A Diagram" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">

<img 
  src="{{ '/assets/images/nutcrackerA_work.png' | relative_url }}" 
  alt="Part A Work" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">

**Reflection:** <br>
TBWRITTEN

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
  src="{{ '/assets/images/nutcrackerB_work.png' | relative_url }}" 
  alt="Part B Work" 
  width="400" 
  height="auto" 
  style="display:block; margin:auto;">

**Reflection:** <br>
TBWRITTEN

## Discussion

When looking over my two designs as a whole, several questions came to mind about usability/feasability, restraints, and design requirements.<br>

**First, when looking at design A:** the small size of the nutcracker creates a device whose usage is limited in scope, and would fit awkwardly in a hand. The relatively large gap between the grips would cause awkward holding and the inability to optimize grip strength simply due to its wide stature. Some solutions to fixing this, for later consideration, would be to ensure the nut is secured further from joint A, as this would create an overall longer device, but a device more suitable for human use. Overall, the design is largely restrained in usage, being limited to very specific or smaller dimensions of Macademia Nut. It is awkward to hold/use, and the design requirements are met, but are to a minimum.

**Second, when looking at design B:** the shifting of the macademia nut to being further from joint A led to a device that was longer, yet less "tall" when breaking the nut. Working within the restrictions of the max stroke length of the linear actuator, the distance from joint to nut had to become longer. This design, overall, is feasible and has the benefit of having a solid base that the nut is cracked onto. When comparing this design to the design of part A, the dimensions say that part A is more practical, but when comparing Mechanical Advantages, it is clear that design B has a better ratio of Length-Force. Overall, this design is also limited in use because it was design specifically for the requirements of a macademia nut without any flexability, but its design is easier for human use as it does not require an awkward grip width.

**In the end,** when considering true practical application, design B is more user friendly as it allows for all people, regardless of hand size or grip strength, to be able to successfully crack open a macademia nut for a snack.

## Sources

**Grip Strength:** Pratt J, De Vito G, Narici M, Segurado R, Dolan J, Conroy J, Boreham C. Grip strength performance from 9431 participants of the GenoFit study: normative data and associated factors. Geroscience. 2021 Oct. https://pmc.ncbi.nlm.nih.gov/articles/PMC8599604/ <br>
**Macademia Nut Strength and Dimensions:** Schrauf et al. Do capuchin monkeys use weight to select hammer tools, Anim Cogn 11, 413–422 (2008). https://doi.org/10.1007/s10071-007-0131-2<br>
**Actuator**: Progressive Automations. Mini Linear Actuator - Optional Feedback. Model: PA-14-3-150. https://www.progressiveautomations.com/products/pa-14?variant=18277278449731 
