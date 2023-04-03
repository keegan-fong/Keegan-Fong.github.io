---
title: "Microfluidic Device"
excerpt: "Big results from a tiny device"
header:
  image: /assets/img/microfluidic2.jpg
  teaser: /assets/img/microfluidic2.jpg
  
---


## Background

Microfluidic devices are tiny devices with small flow channels that have been widely used in biomedical diagnostics, drug development, and the food and chemical industries. These devices are advantageous due to their high surface-to-volume ratio, but low Reynolds numbers in the channels limit the efficiency of diffusive mixing. To address this issue, microfluidic mixing schemes have been developed to achieve thorough and rapid mixing of multiple samples in microscale devices. There are two categories of mixers: active mixers, which use an external energy force to perturb the samples, and passive mixers, which increase the contact area and contact time of the species samples through specially-designed microchannel configurations. Passive mixing devices can mix samples within 55-300 ms, making them well-suited for high-throughput applications. Efficient mixing schemes are essential for increasing the throughput of microfluidic systems and realizing the concept of lab-on-a-chip systems.


## Zigzag Research
For this project, myself and a partner sought to create an effective microfluidic device utilizing innovative manufacturing techniques. In doing background research on microfluidic devices, the paper "Microfluidic Mixing: A Review'' by Lee, Chang, Wang, and Fu was discovered to provide useful information on the design of the devices. Based on the promising results presented in the paper, the decision was made to implement zigzag microchannels in our microfluidic mixing device. In the study, the authors investigated the effect of the periodic step value on the mixing efficiency in a zigzag microchannel with a Y inlet junction. The paper also investigated the most efficient ratio of length and thickness of the individual zigzags under both high Reynolds and low Reynolds number scenarios. They found that for low Reynolds number flows, the most efficient zigzag configuration resulted in a mixing efficiency of 83.8%. For higher Reynolds numbers, there was an optimal zigzag geometry that resulted in a mixing efficiency of up to 98.6%. With all of this in mind, we decided to implement the ideal zigzag microchannels in our microfluidic mixing device to enhance the mixing efficiency. 

## Printing

To create our microfluidic device, a mold must be created so that an appropriate material can be shaped. This is where innovative manufacturing techniques come into play. Vat polymerization (VPP) is a type of 3D printing technique that has gained popularity in the fabrication of microfluidic devices due to its high resolution and ability to create complex geometries. One of the key advantages of vat polymerization is the ability to produce parts with a resolution down to a few microns, which is critical in microfluidics where feature sizes are typically in the sub-millimeter range. Additionally, vat polymerization allows for the fabrication of devices with smooth surfaces, which can minimize frictional losses and improve flow dynamics within microfluidic channels. This is important in microfluidic systems, where flow resistance is a key factor in determining the efficiency and performance of the device. Overall, the high resolution, smooth surface finish, and versatility of vat polymerization make it an ideal choice for the fabrication of microfluidic devices. By leveraging the unique capabilities of this technology, we can create highly functional and efficient microfluidic devices that are tailored to meet the specific needs of our application.

For the purposes of this project, VPP will be used to manufacture a mold which can be used to create a singular component which will function as our microfluidic device. 

## Design
Utilizing the design ratio of 8:1 length to thickness ratio, which emulates the ratio found to be most efficient by the paper, our design should be a quality mixer under low Reynolds number flows. There were considerations of making multiple offshoot channels consisting of zigzags to maximize mixing. However, the plate that our microfluidic device will sit on has design parameters of 75 mm x 25 mm. With such a large plate, it was determined that a singular channel would provide the best, simplest, and most streamlined design. The singular zigzag channel on our microfluidic device contains over 50 individual zigzags and it is believed that it will effectively mix when fluid is passed through. 2 mm round posts were implemented on the design to create inlet and outlet holes in the mold. The CAD model of the mold can be seen below.

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee4b2ab1210fc7ad9?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Results 
<img src="/assets/img/microfluidic2.jpg" alt="VPP printed device mold" style="width:120px;"/>
After the mold was successfully created using VPP technology, it was prepared such that PDMS (polydimethylsiloxane) could be casted. In this preparation, smudging and improper touching of the applied film may have induced problems for the casting process. The mold was placed in a vacuum and PDMS was applied in the mold. 




