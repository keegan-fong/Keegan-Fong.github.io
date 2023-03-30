---
title: "Microfluidic Device"
excerpt: "Zigzagging to get the perfect mixture"
header:
  image: /assets/img/pliers2.jpg
  teaser: /assets/img/pliers2.jpg
  
---


## Background

Microfluidic devices are tiny devices with small flow channels that have been widely used in biomedical diagnostics, drug development, and the food and chemical industries. These devices are advantageous due to their high surface-to-volume ratio, but low Reynolds numbers in the channels limit the efficiency of diffusive mixing. To address this issue, microfluidic mixing schemes have been developed to achieve thorough and rapid mixing of multiple samples in microscale devices. Two categories of mixers have been proposed: active mixers, which use an external energy force to perturb the samples, and passive mixers, which increase the contact area and contact time of the species samples through specially-designed microchannel configurations. Passive mixing devices can mix samples within 55-300 ms, making them well-suited for high-throughput applications. Efficient mixing schemes are essential for increasing the throughput of microfluidic systems and realizing the concept of lab-on-a-chip systems.


## Multimaterial Printing
Because of the way that pliers function, an elastic component is necessary to maintain the starting orientation of the tool while also providing the opportunity to compress the pinching end. However, the entire pliers cannot be made of an elastic material; to maintain its structural integrity, have high durability against wear, and for easier application of force, the arms and the pinching heads of the pliers should be made of a more rigid material. These considerations are a challenge to traditional standard 3D printers, which can only print one type of plastic at a time. Additionally, printing of multiple components with separate printers incur additional costs in manufacturing, add complexity in development, and remove the convenience of creating tools that can be immediately used once removed off the print bed. 

These challenges can be overcome, however, with the usage of multimaterial printing.  Multimaterial machines allow for two different types of material to be laid down in one continuous print, providing the opportunity for the creation of print-in-place items which do not require post-processing or additional assembly. By designing the pliers to be print-in-place, the tools will be available for immediate use once completely printed. A multimaterial printer will allow for the elastic components of the pliers to be printed in the flexible 95A TPU, and the rigid components to be printed with standard PLA. 

## Design

Standard commercially available pliers, such as the ones seen below, were analyzed before developing the custom-designed pliers.

<img src="/assets/img/pliers.jpeg" alt="pliers" style="width:200px;"/>

It was determined that emulating the force translation mechanism of these pliers would provide the best final product. In designing the arms of the pliers, mechanical advantage and comfort of the user were the highest priority. The arm consists of a 70 mm long handle which then transitions into an overhanging crossing bar. The crossing bar connects to the gripping end, which is 50 mm long and provides extended reach. The final design employs the usage of two arms, the other arm being a mirrored version of the first one. To create a pivot point, a cylindrical pin is slotted through the crossing bars; when overlaid, there is a gap between crossing bars in order to allow for clear movement of the arms. 

These components are all intended to be composed of rigid material; however, in their current design, there would be no mechanism to return the pliers to an open position. Therefore, a flexible component is necessary to maintain an open orientation when no force is applied on the arms. In the first iteration of the design, narrow slots were cut into the interior sides of the arms near the front face of the pliers, to allow for a flexible mesh of 3 mm thickness to connect the handles. The TPU failed to print properly for this first iteration, as seen below. 

<img src="/assets/img/design1.jpg" alt="failed first print" style="width:120px;"/>

User error contributed to several failed prints. The next pliers printed were scaled down to minimize creation time, and to determine design proof of concept. However, because of this scaling down the pin connecting the two arms failed. The print can be seen in the photo below.

<img src="/assets/img/design3.jpg" alt="failed second print" style="width:90px;"/>

A successful print was completed with the initial design, the black model seen below. However, the mesh was proven to be too thick, as it did not bend and prevented the user from properly squeezing the pliers. As a result, the mesh was reduced to a thickness of 1 mm, as seen in the red model below. However, there were flaws with this design as well. Although bending properly, the 1 mm mesh was placed closer to the front face of the pliers and thus disproportionately applied force to the front of the pliers.

<img src="/assets/img/design4.jpg" alt="problems with mesh" style="width:275px;"/>

With these considerations, two meshes were implemented into what ultimately became the final design, with one mesh placed near the front face and one near the back face of the pliers. After printing successfully, this final design proved to return the arms to open position, providing sufficient resistance to squeezing while evenly distributing the force applied by the user’s hands. 

<img src="/assets/img/finaldesign2.jpg" alt="successful design" style="width:275px;"/>

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee4b2ab1210fc7ad9?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Results 
The pliers were tested against 12 other designed models. The test consisted of using the pliers to pick up the 3 mm pellets and place them in a container, one at a time. Pliers were judged by the amount of pellets successfully moved in 45 seconds. In this test, these designed pliers placed 3rd, picking up 21 pellets in the allocated time. 

## Print Settings
### General Settings:
Bed Temperature: 60 degrees Celsius

PLA extruder temperature: 215 degrees Celsius

### Specific TPU settings:
Extruder Temperature: 235 degrees Celsius

Maximum speed: 25 mm/s

Retraction Speed: 15 mm/s






