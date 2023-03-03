---
title: "Print-in-Place Pliers"
excerpt: "Pliers are just fancy chopsticks."
header:
  image: /assets/img/IMG_9224.jpg
  teaser: /assets/img/IMG_9224.jpg
gallery:
  - image_path: assets/img/IMG_9224.jpg
  - image_path: assets/img/finaldesign.jpg
  - image_path: assets/img/design1.jpg
   
---
I am literally working on this at this very moment.


# Background

3D printing provides an easy and cost-effective method to create useful objects which can function just as well as commercially available products. This project attempted to test the capabilities of 3D printed products, with the goal of creating a custom-designed tool which functions the same as the traditional pliers that one might find at a hardware store. 

Pliers operate off basic translation of force; when a user squeezes the two arms of the tool, the pinching end of the mechanism closes together. This is useful when it is necessary to pick up objects, squeeze two items together, or apply a pinching force on an object. For this project, our designed pliers needed to grip and release small plastic pellets, roughly 3 millimeters in diameter; successfully being able to accomplish this goal would reasonably demonstrate the plier’s ability to provide a mechanical advantage. My designed pliers would be put in competition with 12 other sets of pliers, to determine which design provided the most efficient and greatest ability to pick up the pellets in a designated time frame. 

# Multimaterial Printing
Because of the way that pliers function, an elastic component is necessary to maintain the starting orientation of the tool while also providing the opportunity to compress the pinching end. However, the entire pliers cannot be made of an elastic material; to maintain its structural integrity, have high durability against wear, and for easier application of force, the arms and the pinching heads of the pliers should be made of a more rigid material. These considerations are a challenge to traditional standard 3D printers, which can only print one type of plastic at a time. Additionally, printing of multiple components with separate printers incur additional costs in manufacturing, add complexity in development, and remove the convenience of creating tools that can be immediately used once removed off the print bed. 

These challenges can be overcome, however, with the usage of multimaterial printing.  Multimaterial machines allow for two different types of material to be laid down in one continuous print, providing the opportunity for the creation of print-in-place items which do not require post-processing or additional assembly. By designing the pliers to be print-in-place, the tools will be available for immediate use once completely printed. A multimaterial printer will allow for the elastic components of the pliers to be printed in the flexible 95A TPU, and the rigid components to be printed with standard PLA. 

# Design

Standard commercially available pliers, such as the ones seen below, were analyzed before developing the custom-designed pliers.

<img src="/assets/img/pliers.jpeg" alt="pliers" style="width:200px;"/>

It was determined that emulating the force translation mechanism of these pliers would provide the best final product. In designing the arms of the pliers, mechanical advantage and comfort of the user were the highest priority. The arm consists of a 70 mm long handle which then transitions into an overhanging crossing bar. The crossing bar connects to the gripping end, which is 50 mm long and provides extended reach. The final design employs the usage of two arms, the other arm being a mirrored version of the first one. To create a pivot point, a cylindrical pin is slotted through the crossing bars; when overlaid, there is a gap between crossing bars in order to allow for clear movement of the arms. 

These components are all intended to be composed of rigid material; however, in their current design, there would be no mechanism to return the pliers to an open position. Therefore, a flexible component is necessary to maintain an open orientation when no force is applied on the arms. In the first iteration of the design, narrow slots were cut into the interior sides of the arms near the front face of the pliers, to allow for a flexible mesh of 3 mm thickness to connect the handles. The TPU failed to print properly for this first iteration, as seen below. 

<img src="/assets/img/design1.jpg" alt="failed first print" style="width:200px;"/>

User error contributed to several failed prints. The next pliers printed were scaled down to minimize creation time, and to determine design proof of concept. However, because of this scaling down the pin connecting the two arms failed, as seen in the print below

<img src="/assets/img/design3.jpg" alt="failed second print" style="width:200px;"/>

A successful print was completed with the initial design, the black model seen below. However, the mesh was proven to be too thick, as it did not bend and prevented the user from properly squeezing the pliers. As a result, the mesh was reduced to a thickness of 1 mm, as seen in the red model below. However, there were flaws with this design as well. Although bending properly, the 1 mm mesh was placed closer to the front face of the pliers and thus disproportionately applied force to the front of the pliers.

<img src="/assets/img/design4.jpg" alt="problems with mesh" style="width:200px;"/>

With these considerations, two meshes were implemented into what ultimately became the final design, with one mesh placed near the front face and one near the back face of the pliers. After printing successfully, this final design proved to return the arms to open position, providing sufficient resistance to squeezing while evenly distributing the force applied by the user’s hands. 

<img src="/assets/img/finaldesign.jpg" alt="successful design" style="width:200px;"/>



# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH35dfcQT936092f0e432a92c466ad2224e2?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>
{% include gallery caption="Print-in-place Pliers" %}
