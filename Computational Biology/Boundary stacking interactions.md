# Boundary stacking interactions 

**Jan 21, 2024**

This is a reading about [Boundary stacking interactions enable cross-TAD enhancer–promoter communication during limb development](https://www.nature.com/articles/s41588-023-01641-2) that published in **Nature Genetics** in Jan 18, 2024. 

### 1. Question that the paper trying to solve

Enhancer-promoter interaction for TAD border bypass

- how one structural aspect influences another in the very same molecule: cannot be resolved by Hi-C or other bulk methods

### 2. Studying approach 

a) Data selection

- they specifically focused on one locus *Pitx1* and its enhancer *Pen*
- they compared between forelimb vs. hindlimb 
- they use ORCA data (optical reconstruction of chromatin architecture) to characterize the conformations of the *Pitx1* locus on single chromosomes
- ORCA has single-molecule resolution

b) Specifically - three hypothesis

- Hypothesie 1 (Merge): TADs merge in a subset of traces: stochastic release of boundary factors
- Hypothesie 2 (Stack): TADs remain intact, but their boundaries stack together, allowing boundary-proximal enhancer and promoter to meet 
- Hypothesie 3 (Other): Enhancer promoter interaction without TADs merging or stacking

c) Computational approach 

- quantitative criteria of each observed trace is best described as Merge, Stack or other
- relative risk score 

d) Modeling 

- physical polymer model: studying molecular mechanisms of forming stack information 
- minimal model: extrusion blockers were equally spaced

### 3. Findings 

a) General sections 
- Border bypass: Stack is the most plausible mechanism in hindlimb-enriched interactions. Merge and Other didn't show much difference. 
- Stack locations: aggregate in the geometric center of the domain --> a stripe pattern 
- Molecular mechanisms 
- global trend of E-P interactions by border stacking 

b) Key findings 

- The study supports a model where neighboring boundaries are stacked due to loop extrusion, allowing boundary-proximal cis-elements to contact each other.
- Increasing boundary strengths, somewhat counter-intuitively, facilitate border bypass, enabling enhancer-promoter interactions across TAD borders.
- This work revises the understanding of TAD borders' function in both facilitating and preventing cis-regulatory interactions and helps distinguish between border-crossing and border-respecting enhancer–promoter pairs.

### 4. Additional 

- Data source: [FANTOM5 project](https://fantom.gsc.riken.jp/5/) contains a Transcribed Enhancer Atlas with E-P pairs across diverse human cell types 
