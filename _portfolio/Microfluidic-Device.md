---
title: "Microfluidic Device Project"
excerpt: "A microfluidic mixing device casted in a 3D printed mold"
header:
  image: /assets/img/MFDrender.jpg
  teaser: /assets/img/MFDrender.jpg
gallery:
  - image_path: assets/img/MFDcast.JPG
  - image_path: assets/img/MFDmold.JPG
  - image_path: assets/img/MFDfail.JPG
  - image_path: assets/img/MFDrender.jpg
   
---
# Description of the microfluidic device and its applications
* The microfluidic device we created is meant for precision mixing of fluids.
* It takes the form of a casted polydimethylsiloxane (PDMS) shape created from a vat photopolymerization (VPP) printed mold, and the shape is later bonded to a glass slide for ease of examination with a microscope.
* Our class used the following definition for microfluidic devices, from George Whitesides:
* "Microfluidics are the science and technology of systems that process or manipulate small (10^-9 to 10^-18 L) amounts of fluids, using channels with dimensions of tens to hundreds of micrometers”
* As you can imagine, there are many applications and extensions of research with microfluidic devices, especially within chemistry and biomedical research. Specifically, they are used for chemical reactions, testing for compounds, and separation of fluids. The incredible results possible with at small scale with microfluidic devices brings advantages in resource utilization, portability, and parallel or simultaneous processing of tests.
* For further reading, this [research paper](https://pubs.rsc.org/en/content/articlelanding/2021/lc/d1lc00744k) is what our project is based on.

# How our microfluidic device was designed
* We designed our microfluidic device as a simple proof of concept.
* As a team of two people from non-biomedical backgrounds, we wanted to learn about the process of creating molds for microfluidic mixing by starting with a simple, large channel design rather than attempting to optimize mixing in our first attempt.
* In testing for basic functionality, we avoided pushing boundaries of feature size and effectiveness of mixing and conceptualized a design that met required specifications while incorporating a little bit of flair in addition to the standard mixing channels.

# How were the dimensions and the shapes of the channels determined?
* The dimensions of the channels were chosen to be the maximum, or near maximum, size that would fit within the mold size given while still restricting the fluids to a single pathway. 
* The central shape of the design was an idea Jack and I had to combine both of our first initials to create a script “JJ” pattern, preempted and followed by some simple angular geometries to provoke mixing between fluids.
* The hope of this strategy was to create a basic, fun device that would help us gain experience with an entirely unfamiliar subject area and to see the potential of further convergence and optimization in our design parameters.

# Why vat photopolymerization was chosen to produce mold?
* Vat photopolymerization (VPP) was chosen as our additive manufacturing technique as it is the most effective technology at producing fine detail in results.
* By using VPP to print our mold, we are able to achieve incredible small feature sizes with smooth textured interfaces that are necessary when working at the microscopic level as is the case with microfluidic devices. 

# What is the main drawback of this technique (hint: parylene)?
* One downside of this approach is the inherent toxicity of VPP due to the resin used.
* The photoinitiators and monomers will leach into the materials used inside of the mold due to the tendency of them to leech, which creates faulty and unusable microfluidic devices.
* There are some ways to address the resin toxicity problem, but each has their weaknesses.
* It has been proposed [in this research paper](https://pubs.acs.org/doi/10.1021/acs.analchem.0c04944) that curing resin prints at very high temperatures can sufficiently rid the resin of interfering qualities, but in practice, we were unable to achieve this without significant, irreparable warpage to the molds.
* Instead, we choose to use a parylene coating on our molds which creates a safety layers between the resin and the PDMA used within the mold to create a microfluidic device. The availability of a parylene coating machine, though, creates a scalability concern that is a major roadblock to extensions of this strategy elsewhere. The machine we are able to rent at Vanderbilt costs roughly $50,000.
* In addition, our first attempt with the parylene coating machine in this project also failed to properly coat the resin printed mold, leaving the PDMS stuck inside and ruining our cast (failure pictured in gallery below).
* Due to the cost and apparent inconsistency of results, Dr. David Florian has expressed some interest in experimenting with a lower cost polyurethane coating strategy to address this, but there are concerns in the physical interference of the polyurethane coating when dealing with mixing channels of incredibly small feature sizes.

# Instructions for how to go from the 3D printed mold to the final device
* Print and cure mold
* Parylene device
* Cast PDMS
* Plasma bond glass slide


# YouTube Video

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e9099bb1016f0b22f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

{% include gallery caption="Flexible Pliers Gallery" %}

