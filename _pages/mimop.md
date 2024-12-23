---
title: "Modelling Ice-shelf Melting and ice-Ocean Processes"
permalink: /mimop/
author_profile: false
---

<img src="/images/logo20marie20curie20actions.jpg" alt="drawing" width="350" align="right">
The MIMOP project aims to answer the question:  
__How quickly do ice shelves melt ?__  
and received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie
Sklodowska-Curie grant agreement 793450.

## News

I moved from the British Antarctic Survey to the Université de Lyon on Setpember 1st 2020, but I will keep working on this project for the foreseeable future. **Do not hesitate to reach out** if you want to work on MIMOP or a related topic as I'd be more than happy to accomodate your interests in the general field of **polar oceanography**. The more the merrier!

## Background

Most of the ice of our planet is stored in Antarctica (see figure below, credit: ESA). But it is a fragile place. As temperatures rise both in the atmosphere and the oceans, grounded ice and floating ice on and around the Antarctic continent are melting increasingly rapidly. Snow falls, which used to balance melting, haven't picked up the pace. As a result, more and more ice is being transformed into southern ocean water and one should expect sea levels to rise in the 21st century much faster than we humans ever witnessed. 

<center><img src="/images/Antarctica_in_3D_credit_esa_lowres.png" align="top" width="400"/></center>

## Goal

The Antarctic Ice Sheet (AIS) is mostly grounded but some of it is floating. We call the ice chunks attached to the grounded ice but floating above sea water **ice shelves**. Ice shelves are a critical component of the AIS. The thicker they are, the more they oppose the gravitational flow of ice from the Antarctic centre to the margins. Recent observations show that **ice shelves are melting and thinning increasingly rapidly**, which opens the door to faster flows of the AIS into the southern ocean. So, yes, the polar regions are changing. But **can we predict how quickly this change is going to take place?**  

<center><img src="/images/mimop_cavity_physics_scheme.png" alt="drawing" width="600"/></center>  

Figure (a) above is a schematic of an ice-shelf cavity. An ice-shelf cavity can be quite large. It can cover an horizontal area up to 1000,000 square kilometers, the ice-shelf can be up to 1 kilometer thick, and the water column can be 1 kilometer deep. The water inside an ice-shelf cavity is ventilated to compensate for the input of subglacial water drained from below the AIS and the inflow of open-ocean water pushed poleward by the winds. Modelling and understanding, let alone predicting, the circulation of water in an ice-shelf cavity is a formidably complicated task. Fortunately, the scientific community is throwing a lot of manpower, computing time and ship time at this problem, such that we may be able to reduce uncertainties in sea-level rise forecasts over the next few years... or decades.  

The role of MIMOP in this is to **develop high-fidelity models of the ice melting dynamics**. We're not attempting to reproduce everything that's going on in the cavity (Figure (a)), but rather what's going on near the ice-water interface (Figure (b)). We resolve turbulent motions explicitly and track the movement of the ice-water interface. We use the **phase-field method** to simultaneously solve for the fluid dynamics and diffusion of heat in the solid. As a result, we can detect the generation of topography at the ice-water interface and assess whether or not this topography can affect the overall efficiency of heat fluxes from the ocean to the ice and ultimately the mean melt rates.

## Results

Our paper *Improved phase-field models of melting and dissolution in multi-component flows* is now published in Proceedings of the Royal Society A. This work, led by Eric Hester, shows how to derive the phase-field equations in order to minimize errors coming from the finite thickness of the diffuse fluid-solid interface. Go check out the official publication [https://royalsocietypublishing.org/doi/10.1098/rspa.2020.0508](here)! 

We have submitted our revision on *Topography generation by melting and freezing in a turbulent shear flow* to the Journal of Fluid Mechanics. This work shows an application of the phase-field method to study the interaction of a three-dimensional turbulent boundary layer flow with an ice block... and topographical features spontaneously emerge (see figure below)! Stay tuned for more updates or go check out the arXiv preprint [https://arxiv.org/abs/2004.09879](here). 

<center><img src="/images/graphical_abstract.jpg" alt="drawing" width="500"/></center>

We have submitted our paper *Aspect ratio affects iceberg melting* to Physical Review Fluids. This work, led by Eric Hester, combines laboratory experiments and numerical simulations that use the phase-field method of an ice block melting in a flume to demonstrate the importance of aspect ratio on mean melt rates (see figure below). The preprint is already available on [https://arxiv.org/abs/2009.10281](arXiv). Let us know what you think!

<center><img src="/images/eric_prf_dns.png" alt="drawing" width="500"/></center>

## Perspectives



## Collaborators
- [Eric Hester](https://www.maths.usyd.edu.au/u/erich/) (University of Sydney, Sydney)
- [Benjamin Favier](https://sites.google.com/site/bfavierhome/) (IRPHE, Marseille)
- [John Taylor](http://www.damtp.cam.ac.uk/user/jrt51/) (DAMTP, Cambridge)
- [Adrian Jenkins](https://www.northumbria.ac.uk/about-us/our-staff/j/adrian-jenkins/) (Northumbria University, Newcastle) 
- [Paul Holland](https://www.bas.ac.uk/profile/pahol/) (DAMTP) (BAS, Cambridge)
