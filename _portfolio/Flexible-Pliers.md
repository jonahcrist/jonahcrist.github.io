---
title: "Flexible Pliers Project"
excerpt: "A single, multi-material print of usable, flexible pliers"
header:
  image: /assets/img/FlexPliersRender.jpg
  teaser: /assets/img/FlexPliersRender.jpg
gallery:
  - image_path: assets/img/FlexPliersv2.JPG
  - image_path: assets/img/FlexPliersv2.JPG
  - image_path: assets/img/FlexPliersv1.JPG
  - image_path: assets/img/FlexPliersRender.jpg
   
---
# Multimaterial FFF printing
* Multimaterial FFF printing can take many different forms, but generally consists of two or more distinct materials being extruded within the same design.
* There are niche benefits to the combination of materials for a single benefit, such as strategic use of mechanical properties to enable function as in the case of this project. One could imagine other advantages to such a technique, from creating selectively heat resistant areas of a part to frivolous preferences in design.
* Multimaterial printing brings a series of drawbacks compared with standard, single material FFF printing. The necessity of operating multiple extruders requires adjustments in the technical approach. In our case, the multimaterial MakerGear FFF printer simply alternates between which filament is being extruded at a time, taking a turn-based rather than simultaneous approach. This is in contrast to some printers with more complex dual extrusion processes, but the MakerGear retains the full-bed size. An issue encountered by a turn-based approach to dual-extrusion is keeping each extruder "at-ready" when the turn comes for each. To prevent jams or oozing due to cooling or overheating between turns, we implement a block to the side of our main print that allows the extruders to trace a simple object layer by layer, which keeps the extruders fresh and ready.


# Print-in-place parts
*  Print-in-place parts have a broad range of potential applications, from consumer products like sliding puzzles and unfoldable boxes to complex aerospace and nautical machinery.
*  Applications in consumer products are largely limited beyond novelty at this point due to the low cost efficiency and inconsistent quality of 3D printed items when compared with injection molds. But it is not hard to imagine a future where assembly-line efficiency is improved by print-in-place techniques that do not require any later assembly beyond the initial process of formation.
*  In other more complex situations, the niche advantages of print-in-place parts really stand out in terms of their potential. In underwater applications for example, geometries that are printed in place can bring a degree of waterproofing that may be easier achieved than in multi-part assemblies. The flexibility of creating parts in place also has intriguing implications for limited-pack scenarios such as space missions, where each additional item brought carries an extraordinary marginal cost. By potentially allowing for a single printer to be used to create a variety of useful-print-in-place items, there could be significant advantages in the translation of material to parts which could save money by increasing packing density.

# Material combinations
*  PLA and TPU: Polylactic acid (PLA) is a commonly used 3D printing material that is easy to print and rigid in mechanical properties.
*  When combined with thermoplastic polyurethane (TPU), which is flexible and elastic, print-in-place parts with both rigid and flexible components can achieve a balance between strength and flexibility such as in this project.
*  PLA and PVA: Polyvinyl alcohol (PVA) is a water-soluble support material. When combined with PLA, PVA can be used as a support structure around complex parts with intricate moving components and then it is easily dissolved with water afterwards.
*  Other combinations are possible as well, but it is important to carefully research and examine how the materials interact at a chemical level and what unique properties each brings to the multimaterial design, as well as the printing conditions necessary for each.
  
# About the design
* In this project, I was assigned to create a set of usable pliers, leveraging the mechanical properties of different polymers. For flexibility, I used TPU and created a center "flex cube" which can be stretched and compressed to create functional movement. For rigidity, I used PLA which is a hard material that will hold the shape of the handles and wings of the plier assembly. 
* To combine the flexible and rigid components of the part, I needed to create some form of overlap or bond between materials. In this case, I chose to go with a relatively simple perimeter overlap geometry within the CAD design. It only took a few minutes to design within Fusion 360, as the combination required that the flexible TPU cube was partially encased within offsets of the rigid PLA wings and handles.
  
# Elements
* Grips - Allows user to grip and squeeze pliers comfortably
*   Simple design, hollowed out with an offset to minimize print speed
*   Can resize print parameters for different situations, 100mm length was sufficient for comfort in this case
* Wings - Individual pieces that clamp together onto objects of small sizes
*   Clearance is small in this print (10mm) as modelled for use on small resistors
*   Print parameters can be adjusted for more wide-ranging use cases
* Flex Cube - Allowance for deformation to create function of pliers
*   Must be overlapping/interwoven in a geometry with the hard parts of the pliers (i.e. grip and wings)
*   Must be flexible enough to grip at reasonable levels of pressure but strong enough to return to form when released

# Material & fastener choice
* PLA - Hard and easily printable polymer that was readily available in lab
* TPU - Flexible polymer needed for its mechanical properties in the print-place plier design

# Relevant specifications
* Jaw length: Pincers have a contact point of 14mm, with an additional 50-60mm space below in the jaws
* Jaw capacity: Objects with a 0-10mm thickness, with some added functionality from 10-15mm if expanded first

# Print settings
* MakerGear M3
* Default print settings for multimaterial in Digital Fabrication Lab, except:
* Increased TPU print temperature to 245 degrees Celcius after early print jams
* This fixed jams, but caused some oozing and the TPU later failed after making it roughly 60% of the way through the print.
* Consider slightly lower temperature above default of 225 but below 245 degrees Celcius.

# Function
<iframe src="https://giphy.com/embed/Jn1T8XDztY06TFs7zW" width="306" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/Jn1T8XDztY06TFs7zW">via GIPHY</a></p>

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e7d8bfddda576bb10?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

{% include gallery caption="Flexible Pliers Gallery" %}
