---
layout: project
title: Client Outline
description: Pitching a mobile crushing and composting system for spotted lanternfly egg masses
technologies: [CAD, Prototyping, Mechanical Design]
image: /assets/images/Gears.png
category: MAE 2250

fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
header-includes:
  - \pagenumbering{gobble}
---

# The Crusher — Let's crush these SLF!

**Team:** _Vine Vanguard_

**Clients:** Cornell CALS Extension / E\&J Gallo Winery / National Grape  

## Problem statement

Vineyard owners across New York State are affected by the rapid proliferation of Spotted Lanternflies (SLF), which lay egg masses directly on grapevines and nearby surfaces. They are trying to reduce SLF reproduction by destroying egg masses before they hatch. Each female SLF lays 30-120 eggs per year, and heavily infested vineyards can have 400 SLF per vine. This means that eggs are being laid exponentially. Current elimination methods such as crushing egg masses one-by-one is ineffective if they are not fully destroyed, and experimental ovicides kill only up to 75% of eggs (Krawczyk). Even a single surviving egg mass can enable SLF persistence, escalating plant damage and contaminated harvests.
  

## Impact
A scalable, systematic method for eliminating large quantities of SLF egg masses is necessary to meaningfully reduce infestations and prevent substantial economic losses for vineyards. Without effective, large-scale intervention, projected losses in the Lake Erie and Finger Lakes regions alone could reach approximately $8.8 million within three years (Gómez, 2025), highlighting the urgent need for proactive and reliable egg-destruction strategies. 

## Proposed direction

### Concept A (primary): Mobile Composting Crusher

**What it is:** 

A mobile crushing and composting unit designed to move through vineyard rows, collect scraped masses, crush and store remains for compost use.  

**How it would be used:**

- Workers scrape egg masses from vines
- Egg masses are deposited into the mobile unit
- Internal crushing mechanisms destroy 100% of input masses
- Crushed material is stored for compost reuse

**Why it’s better than the status quo:**
  
- Handles large quantities of eggs efficiently
- Incorporates multiple contingency crushing mechanisms to ensure full destruction
- Reduces reliance on partially effective chemical ovicides
- Converts biological waste into usable compost material

**End-of-semester proof-of-concept:**

A scaled prototype of the crushing and collecting mechanism, along with basic mobility to drive through vineyard rows.  

### Concepts B: Egg Crusher Attachment 

**What it is:** 

A small, lightweight crushing attachment to integrate with other systems that crush SLF eggs, such as an autonomous drone. 

**How it would be used:**

- Mounted onto a flat surface or compatible device
- Receives scraped egg masses
- Operates in multiple orientations (including inverted)
- Crushes and contains egg remains

**Why it’s better than the status quo:**

- Compact and adaptable
- Integrates into existing vineyard systems
- Enables flexible deployment options for different scales of operation

**End-of-semester proof-of-concept:**

A compact crushing mechanism prototype capable of operating while inverted and mounted to a surface.

## Key risks / unknowns

- Interference with harvesting equipment: the device must not obstruct vineyard operations; we will evaluate footprint and mobility constraints during prototyping.
- Ensuring 100% destruction of egg masses: partial destruction could allow continued infestation; we will test crushing redundancy and containment strategies.
- Assumption that scraping is complete: our design focuses on crushing and disposal; we must confirm that this division aligns with vineyard workflows.

## Questions for the client
1. **Is reincorporating crushed egg waste into the vineyard as compost appealing?**  
   *Decision affected:* Whether to integrate compost storage functionality or prioritize sealed disposal.

2. **What is your actual and ideal egg removal rate (per day and/or per acre)?**  
   *Decision affected:* Determines optimal crushing throughput and speed requirements.

3. **What operational constraints exist during harvest season?**  
   *Decision affected:* Influences mobility size, durability, and interference limitations.

\newpage

# References

- Krawczyk, G. (n.d.). *What should you do with spotted lanternfly egg masses?* Penn State Extension. https://extension.psu.edu/what-should-you-do-with-spotted-lanternfly-egg-masses
- Pinto, A. F., Eshenaur, B. C., Acevedo, F. E., Calixto, A. A., Centinari, M., & Gómez, M. I. (2025). *Assessing the potential economic impacts of spotted lanternfly (Hemiptera: Fulgoridae) infestations on grape production in New York State.* Journal of Integrated Pest Management, 16(1). https://doi.org/10.1093/jipm/pmae039
