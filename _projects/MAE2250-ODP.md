---
layout: project
title: "MAE2250 ODP"
description: Open Design Project Prototype for SLF Contamination
image: /assets/images/FP1.png
---

# Project Overview



## Table of Contents
* [1. Client Outline](#1-client-outline)
* [2. Functional Prototype](#2-functional-prototype)


---

## 1. Client Outline

[Back to top](#)

### Wine Grape Post-Harvest Filtration

Clients: Cornell CALS Extension / E&J Gallo Winery / National Grape
Team Name: Trees of Doom

### Spotted Lanternfly Grape Harvest Contamination

Spotted lanterflies (SLF) damage grape vines and also end up in the harvested mixture. SLF
contamination is of critical concern for New York State grape farmers, as federal regulation holds
that more than 0.1% foreign matter in harvested grape batches results in entire 22-ton batches of
harvest being rejected [1]. Contamination is tested in 1000g samples, and SLF weigh 0.5-1.0g each,
the presence of just 1-2 bugs in a batch is potentially detrimental [1]. An initial study found that
on average, 60% of SLF present on vines were picked up by the mechanical harvester, leading to,
on average, 289 SLF per batch—far greater than the allowable amount. The rejection of grape
harvest batches due to foreign matter presence decreases New York state vineyard
yields and profits.

### Proposed Solution: mechanical filter to remove the SLF post-harvest

We propose to use water to separate grapes from SLF based on density (grapes sink, SLF float).
This would be accomplished via a two-sided strainer with a mechanism to remove SLF off the
water’s surface (see Figure 1).

How it would be used:

- Grapes are harvested as per usual
- Harvested grape + juice mixture is run in batches through the mechanical filter, which removes
    any SLF.

Why it’s better than the status quo:

- Attempted filtration is better than no filtration
- Avoids any modifications to the harvesting process and has simple implementation
- Guarantees that once any SLF are removed, they are removed for good (instead of from the
    vines before harvest when they can return).

### Key Risks / Unknowns

- SLF and grapes getting crushed during harvest could affect their densities (and therefore
    buoyancy and filtration).
- Our filter would ideally match the pace of the harvesting process. This introduces design and
    manufacturing complexities and also requires that vineyards have space to house the filter.

### Questions for the Client

1. How crushed are SLF after the grapes have been harvested? Are they mostly intact or are
    they often split into small pieces such as legs and wing fragments?
2. Our idea is based on the assumption that SLF float in water and grapes sink. Is this generally
    true, and is the density of SLF approximately the same across all of their body parts?
3. What is a typical grape/grape juice ratio after the grapes become crushed post-harvest?


### References and Figures

[1] Bekelja, K. and Russo, J. ”MAE 2250 - Spotted Lanternfly Presentation,” Cornell IPM and
New York State Integrated Pest Management, 2026.

![Figure 1: Prototype schematic of the proposed buoyancy-based spotted lanternfly filter.][def]


[def]: /assets/images/ClientOutlineFigure1.png

---

## 2. Functional Prototype

### Design Intent

![Figure 1](fa25-portfolio-rishabhd625/assets/images/FP1.png)
*<center>Figure 1: CAD cross section of full assembly</center>*

Figure 1 above shows a section analysis of the full assembly of our complete design. However, due to time constraints specifically on our 3D printed part, our functional prototype looks slightly different, with an adapted housing created from the initial cylinder to save on time and cost.

![Figure 2](fa25-portfolio-rishabhd625//assets/images/FP2.png)
*<center>Figure 2: CAD of adapted cylinder</center>*

Figure 2 above shows the CAD of the adapted housing that we created for our functional prototype to save on time and 3D printing cost. We removed much of the height of the cylinder, focusing on the function of the rotating base for our prototype. 

![Figure 3](fa25-portfolio-rishabhd625//assets/images/FP3.png)
*<center>Figure 3: Annotated Sketch of Functional Prototype</center>*

Figure 3 shows a sketch of our prototype, with the various components labeled. The main function of the prototype is when the handle is rotated, the base rotates beneath. The handle is threaded onto the shaft, and the bearing supports the shaft radially. The base is press-fit to the shaft through a milled hex connection. The modified cylinder (“housing”) remains fixed during this rotation process, allowing for the grape juice and excess water to be filtered accordingly as the base rotates.

![Figure 4](fa25-portfolio-rishabhd625//assets/images/FP4.png)
*<center>Figure 4: Annotated Sketch of Base Component</center>*

Figure 4 shows a sketch of our base component. There are 3 sections: a solid base, and very fine mesh that only lets liquid through, and a complete opening. The base is able to rotate freely from each side to the other, to perform the sequence needed to remove the SLF. 

The intended sequence model is illustrated in Figure 5, and detailed as follows: 

First pour mixture of grapes grape juice, and SLF over mesh, filtering out the grape juice, which will be collected in a vessel beneath the device. Then, rotate the base such that the surface under the mixture, which now only contains grapes and SLF, is the solid base. Pour water over the grapes and SLF, and then wait several minutes as density properties cause the SLF float to the top while the grapes stay at the bottom. Filter out the SLF manually from the surface of the liquid. Then, rotate the base again such that the mesh base is again under the mixture, causing the water to drain out of the mixture. Last, rotate the base such that the open section is beneath the grapes, allowing the grapes to fall out of the bottom of the container, and be collected in a vessel along with the grape juice.


![Figure 5](fa25-portfolio-rishabhd625//assets/images/FP5.png)
*<center>Figure 5: Filtration sequence, illustrated with blue “grapes” and white “SLF.”</center>*

### Design Tests

1. **Rotation test**

    This test was meant to assess the ability of the handle, shaft, and base components to rotate freely beneath the divider of the cylinder. It was performed by rotating the shaft using the handle and observing the smoothness and ease of motion of the base. Success criteria for this test was that the base would be able to be rotated using a non-strenuous amount of force from a human hand at the handle, and that the mesh would not noticeably interfere with the dividers upon rotation. 

    The results of this test were informative. First, we observed smooth rotation of the base when low to moderate force was applied to the handle, indicating effective tolerancing on the interface between the base and cylinder to limit friction. Second, however, we noticed that the edges of the mesh, particularly the epoxy connections, momentarily jammed rotation when they passed under the dividers. 

    For the next iteration, to resolve this, we plan to create an indentation in the base for the mesh to rest within, allowing the top of the mesh to sit at the same height as the rest of the base and pass under the divider without impeding rotation. 

2. **Water retention test**

    This test was meant to check the seal and water retention of the cylinder and base. It was performed by filling the cylinder with water for 15 minutes and observing leaks in the points of connection in the cylinder (Figure 12).

    The results of this test were also informative. The test showed us that the prototype was very poorly sealed, such that the volume of water drained out within two minutes. However, we noticed that some points of connection were better sealed than others. The diameter of the base was tightly connected with the cylinder; most of the leaking came through the connection points between the dividers and the base. 

    We plan to resolve this issue by better developing a seal system between the dividers and the base. Specifically, we will purchase rubber flaps from McMaster to attach to the bottoms of the dividers, sealing the gap and reducing leakage.  

3. **Weight test**

    This test was performed to test the strength of our base, cylinder, and rotation system in functioning under increased loads. It was performed by adding weights to the base in ~550g increments (Figure 13) and 1) observing any physical deformation in our design, and 2) rotating the handle and making note of ease of rotation. 

    The test provided valuable insight as to how our design functions under increased loads. First, we noticed that as weight was added, the gap between the base and the dividers marginally increased, lowering friction and making rotation occur more smoothly (but also implying increased water leakage). Second, we noticed that if our design is used in such a way where only one out of three sections is filled with mixture at a given time, this unevenly distributed weight will cause the base to tilt down at an angle, greatly inhibiting water retention and structural integrity. Last, we noticed that the numeric limit to functionality of rotation of our cylinder fell at approximately 2.0 kg – any weight beyond this caused greatly angled deflection of the base. 

    These results have important design implications. The first observation, regarding the widening gap between the dividers and the base, indicated that a support system beneath the base is quite necessary — the shaft collar and press fit between the shaft and base is not sufficient to vertically support the load. This was not a surprise or concern, as our design already accounts for placing bolts under the base — we were just not able to incorporate them into this prototype due to tolerancing issues (see Assembly section). The second observation will ideally also be resolved by this solution, as the vertical support provided by the bolts will prevent the observed angled deflection. However, we also plan to explore optimizing our design so that two out of three sections can be filled and filtered simultaneously — which would not only increase efficiency, but help limit the observed angled deflection due to more even distribution of loading.

![Figure 12](fa25-portfolio-rishabhd625//assets/images/FP12.png)
*<center>Figure 12: Water retention testing</center>*

![Figure 13](fa25-portfolio-rishabhd625//assets/images/FP13.png)
*<center>Figure 13: Weights used for weight testing</center>*

### Success Criteria

Since the ultimate goal of our design is to filter out SLF after harvesting grapes, the project will be a success if we are able to put in a batch of harvested mixture to our cylinder and the SLF float in the water so that they can be skimmed off the top. To achieve this, the mixture first drains through the mesh base to conserve the grape juice and then is rotated to the solid base, where water is added so the SLF float and can be removed, and then is rotated once more to the mesh to drain the excess water, finally producing the cleaned grapes.

Success criteria:
1. The cylinder should be able to rotate cleanly while still holding a total of 2 kilograms of water, grapes, and SLF. This rotation should also be sustainable when used repeatedly, so the cylinder should be able to complete at least 2 full rotations for each batch of mixture and a total of 50 cycles (100 rotations) to demonstrate general endurance of the handle and shaft mechanism.
2. The cylinder should be able to hold liquid for at least 15 minutes at a time so that it will not leak for the duration of the filtering process for a batch of the mixture.
3. One batch of mixture (filling one-third of the cylinder with an average weight of 2 kilograms) should be able to go through the entire rotation and filtering process within 3 minutes so that multiple batches can be filtered efficiently.
4. Particles with a density of 500 kg/m3 (SLF) should float to the very top of the cylinder so that they can be skimmed off, while particles with a density of 1100 kg/m3 (grapes) should sink so that they do not interfere with the SLF collection. This is relevant to our exhibit-day presentation of the prototype because we will demonstrate its function using a sample mixture of a liquid containing some particles with lower density and some with higher density, which will simulate the harvest mixture of grapes and SLF. The demonstration will prove the success of our design if we are able to skim the particles with a density of 500 kg/m3 off the top of the liquid.

[Back to top](#)

---
