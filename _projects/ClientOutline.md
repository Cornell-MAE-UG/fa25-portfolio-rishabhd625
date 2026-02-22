---
layout: project
title: Client Outline
description: Advanced CAD Project

---

# Wine Grape Post-Harvest Filtration

Clients: Cornell CALS Extension / E&J Gallo Winery / National Grape
Team Name: Trees of Doom

# Spotted Lanternfly Grape Harvest Contamination

Spotted lanterflies (SLF) damage grape vines and also end up in the harvested mixture. SLF
contamination is of critical concern for New York State grape farmers, as federal regulation holds
that more than 0.1% foreign matter in harvested grape batches results in entire 22-ton batches of
harvest being rejected [1]. Contamination is tested in 1000g samples, and SLF weigh 0.5-1.0g each,
the presence of just 1-2 bugs in a batch is potentially detrimental [1]. An initial study found that
on average, 60% of SLF present on vines were picked up by the mechanical harvester, leading to,
on average, 289 SLF per batch—far greater than the allowable amount. The rejection of grape
harvest batches due to foreign matter presence decreases New York state vineyard
yields and profits.

# Proposed Solution: mechanical filter to remove the SLF post-harvest

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

# Key Risks / Unknowns

- SLF and grapes getting crushed during harvest could affect their densities (and therefore
    buoyancy and filtration).
- Our filter would ideally match the pace of the harvesting process. This introduces design and
    manufacturing complexities and also requires that vineyards have space to house the filter.

# Questions for the Client

1. How crushed are SLF after the grapes have been harvested? Are they mostly intact or are
    they often split into small pieces such as legs and wing fragments?
2. Our idea is based on the assumption that SLF float in water and grapes sink. Is this generally
    true, and is the density of SLF approximately the same across all of their body parts?
3. What is a typical grape/grape juice ratio after the grapes become crushed post-harvest?


# References and Figures

[1] Bekelja, K. and Russo, J. ”MAE 2250 - Spotted Lanternfly Presentation,” Cornell IPM and
New York State Integrated Pest Management, 2026.

![Figure 1: Prototype schematic of the proposed buoyancy-based spotted lanternfly filter.][def]


[def]: /assets/images/ClientOutlineFigure1.png