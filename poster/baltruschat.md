---
layout: posterpage
categories: [poster]
posternumber: P59
speaker: Philipp Baltruschat
location: 'University of Hamburg'
title: 'Optimizing Semi-Empirical Methods for Specific Data Sets and Molecular Properties'
authors: 'Philipp Baltruschat, Michael Deffner, Carmen Herrmann'
abstract: [
'Semi-empirical methods like Parameterization Method 6 (PM6) are valued for their
efficiency in computational speed compared to ab initio methods such as Density
Functional Theory (DFT). Using empirical data from diverse molecules, these methods
offer broad applicability but may lack specificity in accuracy for particular chemical
investigations. This research aims to enhance the precision of semi-empirical methods
by refining their parameters to more closely align with specific molecular properties
such as HOMO-LUMO gaps and Mulliken Spin Density, with a particular focus on a
dataset consisting of dicopper complexes [1,2].',
'By utilizing DFT calculations as a benchmark, this study adjusts PM6 parameters to
diminish the discrepancies between semi-empirical predictions and ab initio outcomes.
The adjustment process employs different local and global optimization algorithms like
the Nelder-Mead method or the Basin Hopping algorithm, which are tested for their
efficiency in fine-tuning parameter settings.',
'While this tailored approach significantly improves PM6s performance on targeted
properties, it may alter its efficacy on other attributes not considered in the parameter
adjustment. Notably, the optimization process does not require comprehensive DFT
data across the entire dataset but only a representative subset.',
'This investigation not only advances the understanding of parameter optimization in
semi-empirical methods but also contributes to the broader effort of creating training
sets for machine learning approaches with optimized semi-empirical parameters [3,4].']
references: [
['J. Stewart', 'Journal of Molecular modeling', 2007, 13, 1173-1213],
['F. Bosia, et al.', 'The Journal of Chemical Physics', 2023, 158.5],
['P. O. Dral, O. Anatole von Lilienfeld, and Walter Thiel', 'Journal of chemical theory and computation', 2015, 11.5, 2120-2125],
['T. Fröhlking, et al.', 'The Journal of chemical physics', 2020, 152.23]
]
---
