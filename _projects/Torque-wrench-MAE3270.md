---
layout: project
title: Torque Wrench Design
description: Class Project with Finite Element Analysis
technologies: [python, Ansys]
image: /assets/images/normal-stress.png
---

## Description
For our final project in Mechancics of Engineering Materials, 
my partner and I designed a torque wrench designed to meet certain
requirements when a 600 lb-in moment is applied to its drive. First,
we hand calculated our expected delfection and stresses, then we 
created a CAD model and ran it through Ansys to obtain the following 
results.

---

#### CAD Files

![CAD Photo 1 ]({{ "/assets/images/CAD.png" | relative_url }})
![CAD Photo 2 ]({{ "/assets/images/CAD-zoom.png" | relative_url }})


These show the dimensions of our design and a rough layout of the geometry used. 

#### Loads and Boundary Conditions

![Loading Schematic]({{ "/assets/images/diagram.jpeg" | relative_url }})

This shows how the pieces of the model were constrained and loaded in Ansys

#### Normal Strain Contours

![strain contour]({{ "/assets/images/normal-strain-contours.png" | relative_url }})

#### Contour Plot of Maximum Principal Stress

![stress contour]({{ "/assets/images/max-principal-stress.png" | relative_url }})
![stress contour]({{ "/assets/images/max-principal-stress-zoom.png" | relative_url }})

#### Results of FEM

Our FEM analysis yielded a 1.64 mv/v output at the gauge (seen in photo as Normal Strain Z-Axis in bottom left), a maximum normal stress of 77323, and a maximum deflection of 0.656 inches

![Strain Gauge]({{ "/assets/images/strain-probe.png" | relative_url }})
![Max Normal]({{ "/assets/images/normal-stress.png" | relative_url }})

#### Torque Wrench Sensitivity

Our sensitivity converts each thousand units of microstrain into 1 mv/V on our strain gauge. This can also be stated as 1 mv/V = 1000 microstrain

#### Strain Gauge Selection

We chose a half bridge strain gauge for out analysis. 

