---
layout: project
title: "MAE2250: Open Design Project"
description: Milestone Tracker
technologies: [CAD, Prototyping, Mechanical Design]
image: /assets/images/Gears.png
---

# Project Context
Spotted Lanternfly (SLF) infestations pose a significant threat to grape vineyards by rapidly spreading through large batches of eggs laid on vines and surrounding surfaces. This project explores a tangible, mechanical approach to disrupting that cycle, focusing on developing a realistic and scalable solution within the scope of undergraduate mechanical engineering design. 

--- 
# Project Milestones


## Milestones:
- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report) 

---

# Client Pitch
## The Crusher — Let's crush these SLF!

**Team:** _Vine Vanguard_

**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape  

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

# References

- Krawczyk, G. (n.d.). *What should you do with spotted lanternfly egg masses?* Penn State Extension. https://extension.psu.edu/what-should-you-do-with-spotted-lanternfly-egg-masses
- Pinto, A. F., Eshenaur, B. C., Acevedo, F. E., Calixto, A. A., Centinari, M., & Gómez, M. I. (2025). *Assessing the potential economic impacts of spotted lanternfly (Hemiptera: Fulgoridae) infestations on grape production in New York State.* Journal of Integrated Pest Management, 16(1). https://doi.org/10.1093/jipm/pmae039

---

# Functional Prototype
## Purpose

The purpose of this functional prototype is to be able to test our team's mechanical designs and to determine our success criteria and how to assess them for our final prototype.

## Illustrations of Design Intent
### CAD diagrams of prototype components and functions
image: ![Parts Diagram](/assets/images/Parts.png)
image: ![Assembly Diagram](/assets/images/Assembly.png)

## Design Tests

### Test 1: 
Does the device’s assembly of press-fits remain intact during use?

**How this was tested:**
Completely construct device in accordance with intended assembly, including the insertion of the grid mesh, while noting any times where excessive force was required to connect parts. Firmly shake the device for 10 seconds, in upright and inverted positions. Inspect the entire device for any loosened or detached components.

**Result:**
- *Primary Construction:* The press-fits for the shaft-spiral and housing-funnel connection were securely fastened without excessive force. The tolerances for the connections between the housing top and bottom were inaccurate, and the two could not be press-fit together. Extra adhesion (duct-tape) was required to secure these two components. The mesh was secured easily into the housing groove
- *Post-Shake Test:* No loosened pieces were found in the device. The connected shaft and spiral slid in and out of the housing bottom when inverted.

**Required changes:**
In next prototypes, we will alter the CAD geometries for the housing components so that they securely connect via press-fit. 

### Test 2:
Does the spiral properly rotate without jamming/getting blocked in its motion?

**How this was tested:**
Rotate the device manually through multiple full crushing cycles including before, during, and after the insertion of model egg masses (hydrated Orbeez). Observe whether or not the spiral experiences any resistance, blockage or misalignment during rotation. Testing was conducted over varying loads (no Orbeez, 20-30 Orbeez, 50 Orbeez) to simulate realistic operating conditions.

**Result:**
- *Rotation without Orbeez:* The spiral rotated smoothly, with minimal resistance and no visible wobbling or misalignment of the shaft within the mesh housing.
- *Rotation with Orbeez (during operation):* Rotation became inconsistent once Orbeez were introduced. Some Orbeez became lodged beneath the spiral rather than being carried through the crushing mechanism. This created intermittent resistance and slight jamming. Additionally, it prevented many Orbeez from being fully crushed since there was no resistance between the spiral, the Orbeez, and the mesh.
- *Mesh Interaction:* Due to unforeseen ordering complications, we used a temporary replacement mesh for testing in our lab section. The openings of this replacement were approximately 8mm in diameter, while our partially hydrated Orbeez were about 3mm in diameter. This meant the Orbeez could simply fall through the mesh rather than being crushed against it by the spiral. We tried to rectify this by adding multiple layers of mesh in the housing to create smaller openings, but Orbeez would still fall through. Due to this large mesh opening size, during our prototype testing, Orbeez were not properly supported during rotation, further contributing to slipping and inconsistent contact with the spiral.

**Required changes:**
In next prototypes, we will add a guide or mechanical restraint such as little arms attached to the inside columns of the mesh housing to keep the spiral flush against the bottom of the mesh housing. This will prevent eggs from being trapped underneath and remain uncrushed during rotation. Additionally, as we originally planned, we will replace the temporary replacement mesh with much finer mesh to prevent Orbeez from slipping through the openings.

### Test 3:
How efficient is the juicer inspired mechanism at crushing the egg masses? What percentage of eggs come out of the device entirely crushed?

**How this was tested:**
Insert a standardized number of Orbeez (model SLF eggs) into the device. Manually crank the spiral shaft to engage the crushing mechanism for ~30 seconds. Divide the number of eggs that come out intact by the number of eggs inserted into the device. This will give us the percentage of eggs that were not destroyed. Repeat this process for numerous trials and average the percentages.

**Result:** 
As stated in Test 2, the inaccurate sizing for the replacement mesh meant that our trials did not produce crushed Orbeez. However, the trials allowed us to examine the model eggs’ motion throughout the crushing process. 
- *Spiral Design:* We observed that the spiral’s egg-like shape, which tapered out to the diameter of the housing mesh groove then tapered in, allowed Orbeez to accumulate at the housing bottom. The current design had no method to move the settled eggs outside of inverting the device.
- *Mesh Stability:* The interactions between the spiral and the mesh were observed. We suspect that the mesh will not be stable enough in the groove to withstand the lateral load of eggs pushed into it by the spiral at regular operation.

**Required changes:**
To address the accumulation of Orbeez at the housing bottom, the spiral will be redesigned to not taper in towards its base. Adjustments to the mesh will be explored to make it more secure against the eggs pressing against it. Configurations such as a 3D printed cylinder with cutouts for mesh pieces, a 3D printed cylinder with an embedded mesh design, and a solid cylindrical column with internal sandpaper lining may be tested.

## Success Criteria
This project focuses on designing a device attachment that integrates with an existing scraping process to mechanically crush Spotted Lanternfly (SLF) egg masses immediately after removal, ensuring they do not hatch. Success will be evaluated based on effectiveness, processing speed, and appropriate sizing.

### Criteria 1:
Egg Crushing Effectiveness

- **What it assesses:** the ability of our mechanism to completely and reliably crush inserted masses
- **Metric:** ~80% eggs crushed per egg mass
- **How it will be measured:** 
  - Insert a standardized number of Orbeez into the device and run the crushing mechanism for a standardized amount of time.
  - After each trial, count total Orbeez inserted and crushed Orbeez after being run through the mechanism. Calculate (crushed/total) x 100 to get the percentage of eggs crushed.
- **Exhibit-day demonstration:** 
  - Live crushing of Orbeez demo
  - Calculate crushing efficiency in real time for observers

### Criteria 2:
Processing Rate (eggs per second)

- **What it assesses:** speed at which device crushes a desired amount of eggs
- **Metric:** Assume it takes ~10-20 seconds to hand-scrape an SLF egg mass from an uneven surface and insert the masses into the device’s inlet funnel. Since there are approximately 30-50 eggs per egg mass, we’d want to crush the eggs in the same timescale at which they’re being inputted into the mechanism. So, taking the upper limit, we’d hope to crush 50 eggs in 20 seconds, translating to a processing rate of around 2-3 eggs per second.
- **How it will be measured:**
  - Insert 50 Orbeez into the device. Turn the crushing mechanism on for 20 seconds. Count the number of crushed eggs produced and divide by the processing time to calculate the processing rate. Repeat this process for multiple trials and average.
  - Repeat this trial for greater quantities of eggs over a standardized amount of time. Count the number of crushed eggs produced and calculate the processing rate. Compare to the desired 2-3 eggs per second metric.
- **Note:** This would not be tested with our manually controlled prototype, but will be tested when we integrate an electric motor into the device

### Criteria 3:
Device size and weight

- **What it assesses:** practicality for attachment and field use
- **Metric:**
  - For our device to be easily attachable, we’d want to make it small and lightweight
  - Based off sizes of common juicers and electric grinders, as well as accounting for the size of the motor we hope to incorporate into the device, we hope to create a device whose bounding box is less than or equal to 6x6x10 inches
  - The mechanism is intended to be attached to another device’s frame reasonably. Thus we will base the ideal weight on regular handheld devices such as a computer, making the maximum weight to be 4lbs
- **How it will be measured:**
  - After creating our next prototypes, physically measure the size of device using rulers or calipers
  - Measure the weight of the device using a scale

---

# Client Report
## The Egg Crusher: A Scalable Solution for Spotted Lanternfly Egg Management

### Problem Statement & Context: 
Vineyard owners across New York State are affected by the rapid spread of Spotted Lanternflies (SLF), whose presence in the Lake Erie and Finger Lakes regions alone could have projected losses reaching approximately $8.8 million within three years [1]. A single SLF egg mass contains 30–50 eggs, and populations can spread rapidly across large areas of vineyard land. To effectively address this spread, reduce proliferation, and prevent these economic losses from spreading to other parts of the nation, these invasive insects should be targeted while in their egg stage.Destroying eggs prevents the flies from maturing into reproductive adults, reducing the number of SLF that will lay future egg masses and limiting their exponential population growth. Our team focused on developing a mechanical solution for large-scale egg mass destruction that can be deployed at the vineyard level.
Current elimination methods are not suitable for addressing large-scale SLF populations. Manually crushing individual egg masses is time-consuming and inconsistent. Submersion into rubbing alcohol requires constant refilling and storage capacity. Experimental oil ovicides are only effective on 75% of eggs [2]. Additional consideration must be given to the consequences of ineffective elimination, as even one surviving egg mass can enable SLF persistence, escalating plant damage and contaminated harvests.
There is a need for a systematic method for eliminating large quantities of SLF egg masses that can be integrated into existing collection workflows. This method must be consistently effective, practical for real-world use, while minimizing storage, disposal, and labor demands on vineyard operations during implementation.

### Final Prototype and Application:
We developed a device that mechanically crushes eggs, utilizing a juicer-inspired crushing mechanism.

**How it works:**
- Eggs masses enter the mesh cylinder chamber through an inlet funnel.
- A rotating spiral, driven by an electric motor, transports the egg masses downward while simultaneously pressing the eggs against the mesh cylinder, where the crushing occurs.
- A sweeper attached to the rotating spiral pushes crushed eggs towards a hole in the bottom of the mesh housing, falling out of the device through an outlet funnel.

This device will be deployed in the field alongside the given collection method that best suits the vineyard's needs, such as a manual scraper or an autonomous scraping robot. The device is modular, such that its method of accepting and ejecting egg masses can be easily changed.

### Conclusion and Recommendation:
We would recommend the continued research and development of the Egg Crusher for applications in vineyards. The device in its current form is a successful proof of concept for a scalable, efficient, and practical egg extermination method, demonstrating basic mechanical motion. Its ~80% crushing efficiency is on par with current methods, without the drawbacks of consistent maintenance or manual labor. Additionally, its 100% efficiency for ejecting crushed eggs of a standardized diameter suggests the crushed eggs can be re-incorporated into the ecosystem as a compost ingredient if desired by the vineyard owners.

**We would suggest three primary redesigns in future phases of this project:**
1. *Spiral and sweeper geometry.* Pitch angle, spiral diameter, and other features can be optimized to improve crushing efficiency and properly push the crushed eggs towards the outlet funnel.
2. *Compactness.* The system can be scaled down to reduce weight and improve portability, making it easier to deploy in the field alongside a collection device.
3. *Contingency mechanisms.* Incorporating multiple built-in crushing mechanisms arranged in a linear series can improve crushing efficiency, as eggs not crushed by the first spiral will be crushed by the second crushing mechanism right below.

### Testing and Results:
Using hydrated Orbeez as model SLF eggs due to their comparable size and material properties as well as their uniformity, we were able to test:
1. *The dependence of the quantity of inputted eggs on machine efficiency.*
We wanted to determine if the system had an optimal loading range. Results showed that efficiency decreases as quantity increases beyond the optimal operating load. Trials with 50 eggs produced a crushing efficiency range of 72-92% with an average crushing efficiency of 82%. With trials of 100 eggs, the crushing efficiency dropped to a range of 64-78% with an average crushing efficiency of 72%. This indicates that overcrowding inside the chamber restricts motion and reduces effective processing, limiting throughput at higher loads. However, it does also indicate that the device is suitable for crushing one egg mass at a time which contains anywhere from 30-50 eggs.
2. *The dependence of operation time on machine efficiency.*
We wanted to determine whether longer runtime improves performance. Across both 90 second and 3 minute trials with 100 eggs, results showed minimal or no improvement over time. Crushing efficiency remained within similar ranges of 64-78% with an average crushing efficiency of 72% for 90 seconds and 65-78% with an average crushing efficiency of 71% for 3 minutes. This suggests that the system reached a steady-state operating condition quickly which means that extending the operating time of the system does not significantly enhance crushing performance once equilibrium is reached. This indicates that our device can limit the amount of energy used as increasing the operating time does not increase the crushing efficiency.
3. *The system failure rate.*
Finally, we evaluated the system failure rate which we defined as eggs that made it through the device uncrushed. Across all trials, with our standard Orbeez model egg size of ⅛”, no uncrushed eggs were observed indicating a 0% failure rate under these standardized conditions. In the cases where an uncrushed Orbeez made it through the device, the Orbeez tended to be less hydrated and smaller measuring closer to 1/16” rather than ⅛”.

**Key Outcomes:**
- Optimal performance occurs at lower to moderate input quantities as the 50-100 eggs range shows diminishing returns as the load increases
- Time is not a limiting factor after initial steady-state is reached, 90 seconds seems to be sufficient
- System reliability is high, with effectively complete crushing under tested conditions

### Prototype and Testing Details:
Our design draws inspiration from juicer systems, where material is guided through a rotating spiral and compressed against an abrasive mesh surface. Similarly, our device crushes input SLF egg masses by forcing them downward through a rotating central spiral against a fixed mesh barrier. This approach prioritizes compactness, portability, and compatibility with future system integration.
Following initial mock-ups to determine overall dimensions and structural layout, we developed multiple iterative prototypes to address challenges in spiral alignment, clearance tolerances, and material flow. The final functional prototype is shown in the figure below, which illustrates the full system architecture and component interactions.

### Component Specifications and Assembly:
image: ![CAD Diagram](/assets/images/CAD.png)
The final prototype consists of nine 3D-printed PLA components fabricated using the Rapid Prototyping Lab, integrated with purchased mechanical and electrical components. The central crushing mechanism utilizes a McMaster 6409K17 compact DC gearmotor (12V DC, 26 rpm, 320 in-oz torque) to drive a custom-designed spiral shaft assembly. The crushing chamber features a cylindrical mesh housing that secures a 304 stainless steel mesh cylinder (20x20 mesh, 0.034" openings) flush against the rotating spiral. For enhanced filtration, a secondary fine mesh layer (270x270 mesh, 0.0023" openings) provides additional crushing precision. The spiral geometry was iteratively optimized through multiple prototypes to achieve proper clearance tolerances and material flow characteristics. Assembly is achieved through M3 x 25mm Phillips head screws (McMaster 99461A948) that secure the mesh housing to the motor housing, while the motor itself is mounted with dedicated bolts. A toggle switch (SPST-NO, 6A rating, McMaster 7343K184) provides simple on/off control. The modular design allows for easy disassembly for maintenance or component replacement. Material flow follows a consistent path: egg masses enter through the inlet funnel, are transported downward by the spiral while being compressed against the mesh barrier, and crushed material exits via the sweeper-directed outlet funnel. The entire assembly weighs approximately 2.5 pounds and measures roughly 12 inches in height, making it suitable for field deployment alongside existing collection workflows.

### References
[1] A. F. Pinto, B. C. Eshenaur, F. E. Acevedo, A. A. Calixto, M. Centinari, and M. I. Gómez, "Assessing the potential economic impacts of spotted lanternfly (Hemiptera: Fulgoridae) infestations on grape production in New York State," Journal of Integrated Pest Management, vol. 16, no. 1, 2025. [Online]. Available: https://doi.org/10.1093/jipm/pmae039
[2] G. Krawczyk, "What should you do with spotted lanternfly egg masses?" Penn State Extension. [Online]. Available: https://extension.psu.edu/what-should-you-do-with-spotted-lanternfly-egg-masses
