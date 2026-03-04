---
layout: project
title: Nutcracker Design
description: Statics Mechanical Advantage
course: Statics and Mechanics of Solids
image: "{{ '/assets/images/nutcracker.png' | relative_url }}"
---

## Overview

For a class, we were asked to design our own Nutcracker. This design was to both calculate the machanical advantage of a device through set parameters, but also develop and analyze if intial design concepts were feasible.<br>
Simple geometry assumptions were made for the sake of simplifying the task. <br>

After designing our original nutcracker, we were then tasked with altering the design of our nutcracker to utilize a Linear Actuator in some capacity.<br>

![Project Image]({{ "/assets/images/nutcracker_problem.png" | relative_url }})

## Part A Scope

**Given:** The following parameters
|Macademia Nut Dimensions|Macademia Nut Crack Force|Average Male Grip|
|:---:|:---:|:---:|
|D = 0.75"|222.18kg|50kg|

**Find:** Dimensions for Nutcracker

## Part A Work

**Plan:** <br>
I) Draw rough design of Device with intial dimensional assumptions <br>
II) Generate an Exploded Free Body Diagram of Device (Top Half) <br>
III) Utilize Symmetry to simply math and account for dual force action <br>
IV) Utilize the Sum of Moments about point A to determine ratio of Moment Arms <br>
V) Utilize Trignometric ratios for Arm Lengths <br>

**Solution:** <br>
![Part A Diagram]({{ "/assets/images/nutcracker_ptA_diagram.png" | relative_url }})

![Part A Work]({{ "/assets/images/nutcrackerA_work.png" | relative_url }})
**Reflection:** <br>
When reflecting on my work done above, dimensional analysis resulted in correct units. Further attention to single vs double force input lead to a logical conclusion that a cracker that is gripped would had force applied to the shell on both sides, generating a summed force towards breaking. Finally, verifying dimension ratios later confirmed the size of the device.

## Part B Scope

**Given:** The following parameters
|Macademia Nut Dimensions|Macademia Nut Crack Force|Actuator Dimensions|Actuator Force|
|:---:|:---:|:---:|:---:|
|D = 0.75"|222.18kg|3" Stroke|68.04kg|

**Find:** Dimensions for Actuator Assisted Nutcracker

## Part B Work

**Plan:** <br>
I) Draw rough design of Device with intial dimensional assumptions, altering device for single force input <br>
II) Ratio Force input to Force Needed <br>
III) Utilize this ratio to determine moment arm lengths <br>
IV) Utilize Trignometric ratios for full system dimensions <br>

**Solution:** <br>
![Part B Work]({{ "/assets/images/nutcrackerB_work.png" | relative_url }})
**Reflection:** <br>
When reflecting on my work done above, dimensional analysis resulted in correct units. Further attention to the single vs double force input lead to a logical conclusion that force is only being applied to one side, and that the normal force betweeen the nut and the ground surface does nothing to crack the nut, but to instead prevent it from "sinking into" the ground. Finally, verifying dimension ratios later confirmed the size of the device.

## Discussion

When looking over my two designs as a whole, several questions came to mind about usability/feasability, restraints, and design requirements.<br>

**First, when looking at design A:** the small size of the nutcracker creates a device whose usage is limited in scope, and would fit awkwardly in a hand. The relatively large gap between the grips would cause awkward holding and the inability to optimize grip strength simply due to its wide stature. Some solutions to fixing this, for later consideration, would be to ensure the nut is secured further from joint A, as this would create an overall longer device, but a device more suitable for human use. Overall, the design is largely restrained in usage, being limited to very specific or smaller dimensions of Macademia Nut. It is awkward to hold/use, and the design requirements are met, but are to a minimum.

**Second, when looking at design B:** the shifting of the macademia nut to being further from joint A led to a device that was longer, yet less "tall" when breaking the nut. Working within the restrictions of the max stroke length of the linear actuator, the distance from joint to nut had to become longer. This design, overall, is feasible and has the benefit of having a solid base that the nut is cracked onto. When comparing this design to the design of part A, the dimensions say that part A is more practical, but when comparing Mechanical Advantages, it is clear that design B has a better ratio of Length-Force. Overall, this design is also limited in use because it was design specifically for the requirements of a macademia nut without any flexability, but its design is easier for human use as it does not require an awkward grip width.

**In the end,** when considering true practical application, design B is more user friendly as it allows for all people, regardless of hand size or grip strength, to be able to successfully crack open a macademia nut for a snack.

## Sources

**Grip Strength:** Pratt J, De Vito G, Narici M, Segurado R, Dolan J, Conroy J, Boreham C. Grip strength performance from 9431 participants of the GenoFit study: normative data and associated factors. Geroscience. 2021 Oct. https://pmc.ncbi.nlm.nih.gov/articles/PMC8599604/ <br>
**Macademia Nut Strength and Dimensions:** Schrauf et al. Do capuchin monkeys use weight to select hammer tools, Anim Cogn 11, 413–422 (2008). https://doi.org/10.1007/s10071-007-0131-2<br>
**Actuator**: Progressive Automations. Mini Linear Actuator - Optional Feedback. Model: PA-14-3-150. https://www.progressiveautomations.com/products/pa-14?variant=18277278449731 
