---
layout: project
title: MAE 2250 SLF Sorter
description: This was a class project completed to address the issues posed by SLF. My group chose to takcle the challenges faced by SLF during the grape harvesting process through the design of an inline sorting system.
technologies: [Fusion 360, Machining]


fontsize: 11pt
geometry: margin=1in
papersize: letter
pagestyle: empty
mainfont: Times New Roman
header-includes:
  - \usepackage{sectsty}
  - \sectionfont{\fontsize{14}{16}\selectfont}  # H1
  - \subsectionfont{\fontsize{12}{14}\selectfont} # H2
  - \usepackage{setspace}
  - \setstretch{1.15}

---

**Client(s):** Cornell CALS Extension / E\&J Gallo Winery / National Grape

---
### Project Description

This was a class project completed to address the issues posed by SLF. My group chose to takcle the challenges faced by SLF during the grape harvesting process through the design of an inline sorting system.

### Table of Contents

[Project Proposal:](#project-proposal)

[First Prototype:](#first-prototype)

[Client report:](#client-report)

# Project Proposal:



## Problem Statement

Mechanical grape harvesters and grape growers working with clients like Cornell CALS Extension, E&J Gallo Winery, and the National Grape Association are trying to remove Spotted Lanternflies (SLF) from grapes during harvest in conveyor systems on mechanical harvesters, but SLF get collected with grapes, but more than 1–2 SLF per 1000g can trigger contamination concerns, leading to rejected loads.Current post-harvest washing or manual sorting removes only up to ~50% of SLF and reduces usable yield, making these methods ineffective at commercial throughput. The challenge is designing an inline solution that removes SLF without bruising grapes, slowing harvest, or requiring major harvester redesign, all while handling a harvest stream of crushed fruit, stems, juice, and debris.


## Impact
Growers and processors lose economic value when contaminated loads are downgraded or discarded. A reliable inline separator would preserve yield, reduce labor-intensive inspection, and allow uninterrupted harvest at commercial speed.
If this problem is successfully addressed, the likelihood of SLF contamination would be reduced, there would be an increase in production, and it would also be less disruptive to the ecosystems since it would be performed post-harvest.


## Proposed direction:


### Primary Concept: SLF Inline Sorter

**What it is:**  
 One potential prototype we have discussed is a conveyor belt that utilizes pneumatic and physical sorting to remove SLF from the grape mass that is collected by a mechanical grape harvester. The sorting system would consist of:
- Motor-driven roller with bristles attached for preliminary sorting
- Compressed air system to expel leftover SLF 
- Vacuum suction system to collect expelled SLF


**How it would be used:**
- Based on an estimated adult spotting lanternfly mass of about 0.2-0.3 grams, an air jet velocity of 5-10m/s would generate enough force to dislodge the insect. 
- Once the grape mass falls into the grape harvester and onto a conveyor belt, compressed air is blown from one side and a vacuum is sucked from the other side to remove any flies that move through.
- There are varying levels of compressed air as the grapes move through the conveyor to get flies that may be adhering to grapes or heavier. 


**Why it’s better than the status quo:**
- More specialized toward SLF than the current MOG (materials other than grapes) systems

**End-of-semester proof-of-concept:**  
Test conveyor belt with an effective sorting system attached to the conveyor

## Key risks / unknowns

- Our solution only mitigates the problem, but doesn’t handle the harmful effects SLF have on the vitality/productivity of grape vines. Could lead to reduced yields from harvests.
- Volumetric flow rate of grapes on the conveyor belt.  If this is too high, it will be very hard to sort bugs underneath large amounts of grapes. Also, a challenge if grapes/bugs get smushed together.
- May not have the right to modify the harvester


## Questions for the client

1. Are there any sanitation or cleaning requirements for inline equipment?
   *Decision affected:*
2. What level of grape loss or displacement is acceptable?
   *Decision affected:*
3. Is it easy for current harvesters to be retrofitted, or would a new harvest have to be created? 
   *Decision affected:*
4. What is the maximum upfront cost per harvester that would be acceptable?
   *Decision affected:*

## Figure

![Figure 1: Proposed inline pneumatic sorting system]({{ "assets/images/sorter.png" | relative_url }}){ width=0.5\textwidth }
Proposed inline pneumatic sorting system

---
# First Prototype

## Contents

1.  Overview
2.  Parts List and Specifications
    -   2.1 Shaft
    -   2.2 Brush
    -   2.3 Drill
    -   2.4 Conveyor Simulation Components
    -   2.5 Assembly Sketches and Photos
3.  Assembly Instructions
4.  Design Tests
5.  Success Criteria

------------------------------------------------------------------------

## 1 Overview

This report documents the design, assembly, and testing of our
functional prototype for mechanically removing spotted lanternfly (SLF)
models from grape clusters. The prototype includes a rotating brush
mounted on a shaft powered by a drill and a manually simulated conveyor
system.

------------------------------------------------------------------------

## 2 Parts List and Specifications

### 2.1 Shaft

-   McMaster Code: 8920K231
-   Unit Cost: $9.77
-   Length: 1 ft
-   Length Tolerance: -0.005" to 0"
-   Diameter: 1"
-   Diameter Tolerance: -0.002" to 0"
-   Material: Low-Carbon Steel, Grade 1018
-   Shape: Rod and Disc
-   Yield Strength: 54,000 psi
-   Fabrication: Cold Worked
-   Hardness: Rockwell B70
-   Heat Treatable: Yes
-   Certificate: Material Certificate with Traceable Lot Number
-   Specifications Met: ASTM A108
-   Straightness Tolerance: Not Rated
-   Coefficient of Thermal Expansion: 7.1 × 10^-6
-   Elongation: 15%
-   Material Composition:
    -   C 0.13--0.20%
    -   Mn 0.30--0.90%
    -   P 0.04% max
    -   Si 0.15--0.30%
    -   S 0.50% max
    -   Fe remainder
-   Additional Specifications: SDS, RoHS, REACH, DFARS
-   Country of Origin: USA
-   Fabrication Notes: Machined 1.75 in from one end to 0.48 in diameter
    to fit inside drill chuck

------------------------------------------------------------------------

### 2.2 Brush

-   McMaster Code: 7442T11
-   Unit Cost: $8.95
-   Brush Length: 1 ft
-   Bristle Material: Polyester Plastic
-   Backing Material: Stainless Steel
-   Bristle Dimensions: 3/16" W × 7/32" H
-   Overall Diameter: 1"
-   Bristle Diameter: 0.008"
-   Color: White
-   Max Temperature: 200°F
-   Compliance: FDA 21 CFR 177.1660

------------------------------------------------------------------------

### 2.3 Drill

-   Model: Dewalt Drill
-   Source: Taylor Design Studio

------------------------------------------------------------------------

### 2.4 Conveyor Simulation Components

-   Cardboard Piece
    -   Simulates conveyor surface
-   Wooden Boards
    -   Support frame
-   Zip Ties
    -   Secure components
-   Glue
    -   Temporary bonding

------------------------------------------------------------------------

### 2.5 Assembly Sketches and Photos

-   Figure 1: Annotated sketch of prototype. Arrows indicate brush
    rotation and conveyor motion.
-   Figure 2: Photo of assembled prototype showing brush, shaft, and
    conveyor simulation.

------------------------------------------------------------------------

## 3 Assembly Instructions

### 3.1 Step 1: Shaft Preparation

1.  Cut 1 ft low-carbon steel rod.
2.  Machine 1.75 in from one end to 0.48 in diameter using lathe.
3.  Deburr and clean the shaft.

### 3.2 Step 2: Brush Mounting

1.  Cut the stock strip brush into three equal-length sections.
2.  Position sections evenly along shaft.
3.  Secure with zip ties.
4.  Apply glue to prevent axial movement.
5.  Ensure alignment.

### 3.3 Step 3: Drill Interface

1.  Insert shaft into drill chuck.
2.  Tighten chuck.

### 3.4 Step 4: Shaft Mount

1.  Drill 1-inch hole in wooden board.
2.  Offset center 1 inch from top.
3.  Secure board perpendicular to base.

### 3.5 Step 5: Conveyor Simulation Setup

1.  Place cardboard under brush.
2.  Install partition.

### 3.6 Step 6: Collection Trough

1.  Place box behind brush.

### 3.7 Step 7: System Integration

1.  Place grape clusters on conveyor.
2.  Operate drill at 450--500 RPM.
3.  Slide cardboard manually.

-   Figure 3: Functional connections
-   Figure 4: Annotated prototype components

------------------------------------------------------------------------

## 4 Design Tests

### 4.1 Test 1: Brush Rotation Speed

-   Tested: 450, 500, 550, 600, 650 RPM\
-   Results:
    -   450 RPM: 6/7 removed
    -   500 RPM: 3/7 removed
    -   550 RPM: 3/7 removed
    -   600 RPM: 1/7 removed
    -   650 RPM: 1/7 removed
-   Conclusion: Optimal ~500 RPM

------------------------------------------------------------------------

### 4.2 Test 2: Brush Bristle Coverage

-   Left: 5/7
-   Center: 7/7
-   Right: 4/7
-   Issue: Edge gaps

------------------------------------------------------------------------

### 4.3 Test 3: Conveyor Simulation Stability

-   6/10 stable
-   4/10 lost grapes
-   Issue: lack of support

------------------------------------------------------------------------

### 4.4 Test 4: SLF Removal Efficiency

-   Average: 72%
-   Range: 65--78%
-   No grape damage

------------------------------------------------------------------------

### 4.5 Test 5: Assembly Repeatability and Stability

-   Average assembly time: 9 minutes
-   No shaft slippage
-   Minor zip tie shifting
-   Slight conveyor flexing

------------------------------------------------------------------------

## 5 Success Criteria

-   SLF Removal Efficiency: ≥90%
-   Grape Integrity: No visible damage
-   Assembly Time: <10 minutes
-   Conveyor Speed: 0.5--1 in/sec
-   Brush Speed: 450--500 RPM

---
# client Report

![Final Prototype]({{"assets/images/Bill_of_materials.png" | relative_url }})

## 1. Context and Problem Statement
Mechanical grape harvesting operates at industrial scales of approximately 2–3 tons per hour but unintentionally collects Spotted Lanternflies (SLF) along with harvested grapes. Even low contamination levels
(approximately 1–2 insects per 1000g) can result in rejected loads due to quality control and regulatory
concerns.

Existing mitigation strategies such as manual sorting and post-harvest washing are not compatible with
commercial throughput requirements. These approaches introduce significant processing delays, increase
labor demand, and are incompatible with continuous harvesting operations.

### 1.1 Design objective
Develop a mechanical system for removing SLF during harvesting that preserves throughput and minimizes
grape damage, and is compatible with both standalone operation and retrofit integration with existing
conveyor-based harvesting systems.

## 2. Final Prototype and Application
A modular inline separation system was developed, integrating mechanical agitation and pneumatic separation
to remove SLF during conveyor transport.

### 2.1 System Architecture
• Conveyor transport system for continuous material flow
• Directed airflow subsystem for insect separation
• Rotary brush subsystem for mechanical agitation of grape clusters
As grapes travel along the conveyor, they pass beneath a rotating brush that dislodges attached insects. A
directed airflow system then separates SLF based on their lower mass and higher aerodynamic sensitivity
relative to grapes. Grapes continue to the collection trough while the SLF are diverted into a separate
containment bin.

## 3. Conclusion and Recommendations
The prototype demonstrates that inline mechanical and pneumatic separation can effectively reduce SLF
contamination without interrupting throughput or damaging grapes.

### 3.1 Recommendation
• Proceed with iterative development and scaled validation.

### 3.2 Recommended Next Steps:
• Improve brush uniformity to ensure consistent contact across full conveyor width
• Replace ad hoc airflow source with engineered compressed air manifold (target 5–10 m/s)
• Integrate vacuum-based capture to prevent re-entrainment of dislodged insects
• Conduct testing under higher throughput conditions representative of commercial harvesters
The system demonstrates sufficient performance to justify further development toward field-scale validation,
with improvements focused on consistency and scalability.

## 4. Testing and Results
Experimental testing was conducted using fresh grapes and representative SLF models to evaluate separation
performance and fruit integrity.

### 4.1 Key Performance Outcomes:
• Average SLF removal efficiency: 72%
• Observed variation in removal efficiency: 57–100% across conveyor width
• Optimal operating condition: ∼500 RPM brush speed with high conveyor velocity and maximum airflow
• Grape integrity: no significant observable damage under tested conditions
Performance variation was primarily attributed to non-uniform brush contact across the conveyor width,
indicating a need for improved mechanical consistency.

## 5. Prototype and Assembly Details
The prototype was constructed as a simplified conveyor-based system designed to replicate industrial
harvesting flow.
### 5.1 Structural Frame
• Wooden base structure with supporting side walls
• Central alignment for conveyor integration
### 5.2 Conveyor System
• Cardboard rollers mounted on wooden dowels
• Paper-based belt reinforced with wax paper for durability
• Manual actuation via 3D-printed end knobs
### 5.3 Rotary Brush Subsystem
• Machined shaft driven by handheld drill
• Bristles mounted using custom 3D-printed shaft rings
• Epoxy bonding used to prevent relative motion and improve stability
### 5.4 Airflow Subsystem
• Hair dryer used as a surrogate for compressed air system during testing
• Positioned downstream of brush for immediate insect removal
### 5.5 Collection System
• Primary collection bin for grapes at conveyor exit
• Secondary side-mounted bin for SLF capture
### 5.6 Design Iterations
• Replaced geared conveyor concept due to jamming and misalignment
• Improved brush fixation to eliminate independent rotation
• Adjusted brush height and alignment to optimize contact consistency

## 6 Bill of Materials 

![Bill of Materials]({{ "assets/images/Bill_of_materials.png" | relative_url }})

### 6.1 Structural Components
• Wooden base boards (2) – TDS
• Wooden side walls (4) – TDS
### 6.2 Conveyor System
• Cardboard rollers (2) – TDS
• Wooden dowels (2) – TDS
• Paper conveyor belt with wax-paper coating – TDS
• 3D-printed drive knobs (4) – RPL
### 6.3 Brush System
• Machined steel shaft – McMaster-Carr
• Bristle material (brush segments) – McMaster-Carr
• 3D-printed shaft mounting rings – RPL
• Epoxy adhesive – TDS
• Handheld drill (drive source) – Amazon
### 6.4 Airflow System
• Hair dryer (temporary airflow generation unit) – Dyson (self-funded; not charged to project budget)
### 6.5 Collection System
• 3D-printed SLF collection bin – RPL
• Wooden mounting supports – TDS
### 6.6 Miscellaneous Materials
• Hot glue adhesive – TDS
• Fasteners and general mounting hardware – TDS
• Paper SLF test models – TDS
• Grapes (experimental validation material) – Mac’s Cafe

## References
- evokeAG. “Harvest Optimisation Technology to Remove Matter Other than Grape (MOG).” YouTube, 26 July 2021, https://www.youtube.com/watch?v=JEM50O9d-M8. 
- Kurtural, S. Kaan. Mechanical Harvesting – Tools of the Trade. Department of Viticulture and Enology, University of California, Davis, https://wineserver.ucdavis.edu/sites/g/files/dgvnsk2676/files/inline-files/MechanicalHarvest_tools_tradeSKK.pdf. 
- WECO Sorting – “The Science of Optical Sorting,” A Duravant Company. “WECO TomatoTek II Sorter in Slow Motion.” YouTube, 14 Apr. 2022, https://www.youtube.com/watch?v=iSd4RgrFOtg.