---
title: "Bicycle Phone Holder Project"
excerpt: "An adjustable, secure phone mount for a bicycle"
header:
  image: /assets/img/PhoneMountPhoto1.JPG
  teaser: /assets/img/PhoneMountPhoto1.JPG
gallery:
  - image_path: assets/img/PhoneMountPhoto1.jpg
  - image_path: assets/img/PhoneMountPhoto2.JPG
  - image_path: assets/img/.png
   
---
# Top Down Modeling
* Top down modeling is an approach to computer aided design that creates components within a single assembly. 
* It can be thought of as a method that designs in place (in situ) which is useful in connecting components within a given context at fine relational detail. 
* While other approaches can achieve similar results, top down modeling is a more efficient way to make quick adjustments to components within an assembly while retaining positions between components.
* In this project, I started by basing the design off of our two fixed constants – the phone and bicycle handlebars. 
* In my first attempt to create a model in context, I failed to ground my base design (the handlebars) and instead used projections which caused downstream issues in component designs. 
* Revising this issue, I grounded the handlebars and used offset planes in the middle to build more effectively within the context of my constants. 
* After making these early changes to the timeline of my design, the rest of the components came together much quicker than the previous attempt. 
* And by building in situ, I was able to use as-built joints to retain original relationships between objects. 

* Additionally, I used parametric modeling to automatically resize necessary objects in relation to the diameter of the handlebars, which may change between bicycles.

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
