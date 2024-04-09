---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img: .png
title: 'Adaptive Pople basis sets'
authors: 'Danish Khan, Maximillian L. Ach,  O. Anatole von Lilienfeld'
speaker: 
location: 'University of Toronto'
abstract: 'Gaussian Type Orbitals (GTOs) from the Pople basis set family have been among the most widely employed basis functions in quantum chemistry calculations for five decades.
We introduce a machine learning model that improves the STO-3G, 3-21G, 6-31G and 6-31G* basis sets by adapting the basis functions to the local atomic environments prior to the start of Self Consistent Field (SCF) calculations.
This is achieved by scaling the variance of the radial Gaussian functions leading to the atomic orbitals contracting or expanding based on the local chemical environment.
Optimal scaling factors are calculated using the variational principle, i.e. by minimizing the Hartree-Fock (HF) energy, and form the training data for the machine learning (ML) model.
After training on a rather small number of molecules, it is shown that using the basis functions predicted by the model provides more accurate energies, wavefunctions and properties than the default Pople basis sets in up to 99% of tested HF calculations.
'

---
