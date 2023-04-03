---
title: "Microfluidic Device"
excerpt: "Big results from a tiny device"
header:
  image: /assets/img/microfluidic2.jpg
  teaser: /assets/img/microfluidic2.jpg
  
---


## Background

Microfluidic devices are tiny devices with small flow channels that have been widely used in biomedical diagnostics, drug development, and the food and chemical industries. These devices are advantageous due to their high surface-to-volume ratio, but low Reynolds numbers in the channels limit the efficiency of diffusive mixing. To address this issue, microfluidic mixing schemes have been developed to achieve thorough and rapid mixing of multiple samples in microscale devices. There are two categories of mixers: active mixers, which use an external energy force to perturb the samples, and passive mixers, which increase the contact area and contact time of the species samples through specially-designed microchannel configurations. Passive mixing devices can mix samples within 55-300 ms, making them well-suited for high-throughput applications. Efficient mixing schemes are essential for increasing the throughput of microfluidic systems and realizing the concept of lab-on-a-chip systems.


## Zigzag Design
The decision to implement zigzag microchannels in our microfluidic mixing device was based on the promising results presented in the paper by Mengeaud et al. In this study, the authors investigated the effect of the periodic step value on the mixing efficiency in a zigzag microchannel with a Y inlet junction. They found that for low Reynolds number flows, the most efficient zigzag configuration had a periodic step value of 800 μm, resulting in a mixing efficiency of 83.8%. For higher Reynolds numbers, there was an optimal zigzag geometry that resulted in a mixing efficiency of up to 98.6%.
Additionally, the paper by Hong et al. presented a passive micromixer with a modified Tesla structure that also achieved excellent mixing performance at higher flow rates. However, at lower flow rates, the mixer was constrained to the diffusive mixing regime, resulting in limited mixing performance.

Therefore, we decided to implement zigzag microchannels in our microfluidic mixing device to enhance the mixing efficiency, particularly at low Reynolds number flows. By using the Coanda effect to guide the fluid streams to collide with one another, we aim to achieve a thorough and rapid mixing of multiple samples in microscale devices. We will investigate the effect of the periodic step value on the mixing efficiency in our experiments, and aim to optimize the zigzag geometry to achieve the highest mixing efficiency possible. With this approach, we hope to contribute to the development of efficient microfluidic mixing schemes, which are essential for increasing the throughput of microfluidic systems and realizing the concept of micro-total-analysis systems and lab-on-a-chip systems.

## Printing Method

Vat polymerization is a type of 3D printing technique that has gained popularity in the fabrication of microfluidic devices due to its high resolution and ability to create complex geometries. One of the key advantages of vat polymerization is the ability to produce parts with a resolution down to a few microns, which is critical in microfluidics where feature sizes are typically in the sub-millimeter range.
Additionally, vat polymerization allows for the fabrication of devices with smooth surfaces, which can minimize frictional losses and improve flow dynamics within microfluidic channels. This is important in microfluidic systems, where flow resistance is a key factor in determining the efficiency and performance of the device.
Furthermore, vat polymerization is a highly versatile technique that can be used to print a wide range of materials, including both rigid and flexible polymers. This allows for the fabrication of microfluidic devices with a wide range of mechanical properties, which can be tailored to specific applications.
Overall, the high resolution, smooth surface finish, and versatility of vat polymerization make it an ideal choice for the fabrication of microfluidic devices. By leveraging the unique capabilities of this technology, we can create highly functional and efficient microfluidic devices that are tailored to meet the specific needs of our application.


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






