# pln-r14del-md

## Research Question
What biological problem or mechanism were you investigating?
We investigated how the R14del mutation in phospholamban (PLN) affects the structural stability and regulatory function of PLN pentamers in cardiac muscle cells.

Why is it important?
PLN regulates SERCA, the calcium pump responsible for cardiac muscle relaxation. The R14del mutation is linked to dilated cardiomyopathy and heart failure, causing a superinhibitory effect on SERCA that is only partially reversible by phosphorylation. Understanding its structural and dynamic effects can clarify the molecular basis of disease and inform therapeutic strategies

.

## Methods

    Simulation Software: NAMD (all-atom molecular dynamics)

    Visualization & Analysis Tools: VMD, Python (MDAnalysis, NumPy, pandas), R (tidyverse, ggplot2), HOLE

    System Setup: Protein-lipid bilayer systems were built in CHARMM-GUI using experimental PLN pentamer structures (wild-type and R14del mutant) embedded in a DOPC membrane with TIP3P water and 0.15 M KCl.

    Simulation Parameters: 1000 ns per replicate, 310 K.

    Analyses Conducted:

        RMSD – global stability

        Helix tilt – orientation of transmembrane helices

        Pore radius profiles – structural geometry of the pentamer pore

        Secondary structure – backbone conformational changes over time

## Key Findings (general audience)

    R14del pentamers showed reduced structural flexibility compared to wild-type, suggesting increased stability.

    The mutation altered helix tilt and pore geometry in ways that could strengthen SERCA inhibition.

    Secondary structure analyses indicated localized changes near the mutation site without complete unfolding of helices.

    These differences support experimental evidence that R14del stabilizes pentamers, possibly limiting dynamic regulatory switching and contributing to chronic SERCA inhibition
