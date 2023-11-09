---
title: "Flexible Pliers Project"
excerpt: "A single, multi-material print of usable, flexible pliers"
header:
  image: /assets/img/FlexPliersRender1.png
  teaser: /assets/img/FlexPliersRender1.png
gallery:
  - image_path: assets/img/FlexPliersPhoto1.JPG
  - image_path: assets/img/FlexPliersPhoto2.JPG
  - image_path: assets/img/FlexPliersRender1.png
   
---
# Multimaterial FFF Printing
* Multimaterial FFF printing can take many different forms, but generally consists of two or more distinct materials being extruded within the same design.
* There are niche benefits to the combination of materials for a single benefit, such as strategic use of mechanical properties to enable function as in the case of this project. One could imagine other advantages to such a technique, from creating selectively heat resistant areas of a part to frivolous preferences in design.
* While there are benefits, multimaterial printing brings a series of drawbacks compared with standard, single material FFF printing. The necessity of operating multiple extruders requires adjustments in the technical approach. In our case, the multimaterial MakerGear FFF printer simply alternates between which filament is being extruded at a time, taking a turn-based rather than simultaneous approach. This is in contrast to some printers with more complex dual extrusion processes, but the MakerGear retains the full-bed size. An issue encountered by a turn-based approach to dual-extrusion is keeping each extruder "at-ready" when the turn comes for each. To prevent jams or oozing due to cooling or overheating between turns, we implement a block to the side of our main print that allows the extruders to trace a simple object layer by layer, which keeps the extruders fresh and ready.
* In this project, I was assigned to create a set of usable pliers, leveraging the mechanical properties of different polymers. For flexibility, I used TPU and created a center "flex cube" which can be stretched and compressed to create functional movement. For rigidity, I used PLA which is a hard material that will hold the shape of the handles and wings of the plier assembly. 
* To combine the flexible and rigid components of the part, I needed to create some form of overlap or bond between materials. In this case, I chose to go with a relatively simple perimeter overlap geometry within the CAD design. It only took a few minutes to design within Fusion 360, as the combination required that the flexible TPU cube was partially encased within offsets of the rigid PLA wings and handles.
* R

* A

# Design Rationale

# Theory of design:
* A phone bike mount should be secure as any issues in the mount of a phone can present major safety risks to the user when riding on the road
* The phone must fit tightly and rotate in strict movement patterns that would not be inadvertently triggered by use of the bicycle. But the specifications still require that the mount allows for degrees of freedom between portrait and landscape mode.

# Design Elements
* Grip - Adjusts to varying tightnesses and handlebar sizes. 
*   Secured with an M5 Allen key
*   Bolts come through the bottom of the grip toward the heat set insert in the top grip to appear less clunky on the bike
*   Offsets for bolt heads to hide seamlessly in the black enclosure of the grip
* Wings - Adjusts to varying phone models and cases
*   Left and right adjust independently
*   Hand tie must be sufficient securely for ease of adjustment
* Baseplate - Axis of rotation between orientations
*   Must be tightened as it relies on threading and friction of baseplate to grip
*   Must limit spins in a single direction as it is a thread which can be undone

# Material & fastener choice
* Within the options presented by the digital fabrication lab, acrylonitrile butadiene styrene (ABS) is most suitable for the design theory of the phone mount as it has a good balance of properties in its durability to the suboptimal conditions of outdoor use (such as heat) and its impact resistance.
* Though thermoplastic polyurethane (TPU) would also offer some interesting qualities as a non-deformable, highly heat resistant material, it does not allow for the placement of heat set inserts. Heat set inserts are key to the design theory of my phone mount as they allow for high levels of security and adjustment in combination with M5 bolts.
* As a result, I chose ABS for my phone mount design. It uses heat set inserts with M5 bolts, is highly impact resistant, and performs better in outdoor conditions comparable to our other options in the lab such as PLA. 
* One concern in the long term use of my ABS phone mount is exposure to UV rays, which may cause some layer separation and fading of the matte black finish over time. This could be prevented in a future design with a more complex material that includes some sort of UV protection.

# Assembly instructions
* First, secure the top and bottom sections of the grip assembly to the handlebar. Use an M5 Allen key and four 20mm M5 bolts. Adjust the viewing angle to the proper alignment for your riding position on the bicycle.
* Next, take the base plate and hand tie a ridged head 10-12mm M5 bolt to the center hole, in the middle of the circular divot offset. Tighten as much as possible.
* Attach the first wing of the phone clamp to the baseplate, using a 20mm M5 bolt. This side can either be hand tied or fixed with an Allen key, as only one side is needed to be hand-adjustable for removal and placing of phone in clamp.
* Place your phone, with case, against the baseplate and hook into the first wing which should now be bolted in.
* Hook in the second wing of the clamp around the phone and begin attaching it to the baseplate, using a 20mm M5 bolt. This side should be hand tied and left somewhat looser than the dominant side of the clamp. Still, there should be no doubt of the security of the clamp so be sure to tighten the M5 bolts to that extent.
* Test the security of the assembled phone mount to make sure the grip is tight against the handlebars and the phone’s rotation on the baseplate is tight against the grip assembly. 
* Repeat as needed. It is recommended to keep a small M5 Allen key on your person in a bike pouch in case of any incident out on the road causing a need for adjustment of grip.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6e687bf4df5af6701e?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

---

{% include gallery caption="Phone Mount Gallery" %}
