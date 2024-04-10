---
layout: posterpage
categories: [decision]
posternumber: '?'
speaker: J. Terence Blaskovits
location: [
    'Max-Planck Institute for Polymer Research, Mainz (DE)',
    'Institute of Chemical Sciences and Engineering, Lausanne (CH)']
title: 'Data-driven discovery of molecules with unique excited states for organic electronics'
authors: 'J. Terence Blaskovits, Ruben Laplaza, Luca Schaufelberger, Kjell Jorner,
    Clémence Corminboeuf'
abstract: 'A major bottleneck in the application of machine learning (ML) to organic electronic
materials has been the lack of relevant data. In fact, most developments in ML for
chemistry have focused on few selected datasets – e.g., QM9 and MD17 – and on
ground state properties. While large in size, these datasets lack the compositional
complexity and diversity that are representative of the chemical space required for the
design of new materials with tailored optoelectronic properties. The other side of the
problem is that existing datasets may even contain chemically unrealistic or impossible
compounds.
To address these challenges, we developed a dataset of over 110K experimentally-
reported organic molecules, curated from a crystal structure repository, as well as
protocols to automate the coupling of these molecules together in chemically
meaningful ways.[1] The size and chemical diversity of the dataset enable the training
of extreme gradient boosting regressors for the prediction of molecular excited state
energies with excellent accuracy across the broadest range of known experimental
compound space. These models enable on-the-fly evaluation of excited states in the
screening of over a million potential candidates for singlet fission (SF) - a multiexciton-
generating process that provides a promising route to increase the efficiency of solar
cells through the conversion of one excited singlet state into two triplet states.
The models and dataset are then redeployed in the multiobjective genetic optimization
of SF candidates.[2] We show that calibrated uncertainty in model predictions can be
used to guide the genetic algorithm towards low- or high-uncertainty regions of
chemical space. In the former (exploitative) setup, variations of known SF compounds
are uncovered. In the latter (explorative) mode, altogether new candidates are
generated which display excellent excited state properties for SF but remain
synthetically feasible.'
references: [
    ['J. T. Blaskovits, R. Laplaza, S. Vela, C. Corminboeuf',
    'Adv. Mater.', 2024, 36, 2305602],
    ['L. Schaufelberger, J. T. Blaskovits, R. Laplaza, K. Jorner, C. Corminboeuf', false, 2024, 'Manuscript in preparation', false]
]
---
