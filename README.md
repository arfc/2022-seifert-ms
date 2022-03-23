# Seifert Master Thesis

## General Concept(s)
Discussion of Serpent2 flow functionality, possible uses, pitfalls, and workarounds. How it differs from batch-wise reprocessing. Discuss usefulness over batchwise (Xe-135 in batchwise is not removed until after depletion, meaning more captures occur by Xe-135 than would have happened if removed continuously).

Use Serpent2 build-in flows and binary restarts to create "piping" where material decays naturally while not in core. How does this differ from MSBR analysis as a single unit geometry analyzed in SaltProc where piping volume is included in core volume? Does it improve result by providing more accuracy to location of DNP decay? Does a smaller "mesh" of materials allow for better results?

## Thesis Sections
- [ ] Abstract
- [ ] Introduction
- [ ] Literature Review
  - [ ] Accounting for material decay in piping
  - [ ] Serpent2 continuous removal
  - [ ] Serpent2 restart scripts
  - [ ] Methods of tracking DNPs in MSRs
    - [ ] GenFOAM?
    - [ ] Moltres?
  - [ ] Batchwise removal methods in Serpent2
  - [ ] SaltProc
  - [ ] MSBR
- [ ] Methods
- [ ] Results
- [ ] Conclusions


## Results to Discuss
- [ ] Explanation of flow functionality
- [ ] Discussion of cyclic flow effects (breaks depletion); workarounds
- [ ] Explanation of why type 1 approximations necessary given removal fraction
- [ ] Type 1 cycle-time-decay approximation
- [ ] Type 1 linear generation approximation
- [ ] Type 2 different approaches and non-physicality
- [ ] Discussion of when each type could be used (pros/cons)


## Results to be Generated
- [ ] Isotope-importance based type 1 MSBR approximation
- [ ] Difference plots along with mass plots for type 1 approximations
- [ ] N-steps for different type 1 approximations
- [ ] Type 1 approximations at different starting positions (BOC vs SS)
- [ ] Implementation of Serpent2 built-in flows in SaltProc
- [ ] Separation of MSBR into core and piping material difference in results
  - [ ] Difference from single-material model
  - [ ] Discuss validty of slug flow approximation (no mixing of materials)
  - [ ] DNP groups SS locations
  - [ ] Difference in neutronic parameters
  - [ ] Mesh refinement analysis (cost vs accuracy)
  - [ ] Analysis of separate parts of the core


## Possible Things to Add
- [ ] Neutronics parameters for different type 1 approximations
- [ ] Comparison of MSBR with SaltProc, subdivided materials, and with CFD
