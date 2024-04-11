---
layout: default
link: talks/stuyver
categories: [comms]
talknumber: D2.11
talktime: '22.05.2024, 17:30 – 18:00'
title: 'Hybrid computational workflows for reaction
screening & discovery'
authors: 'Thijs Stuyver, Javier Emilio Alfonso-Ramos'
speaker: Prof. Thijs Stuyver 
location: 'Ecole Nationale Supérieure de Chimie de Paris, Université PSL'
abstract: 'Recent advances in machine learning (ML) and computational chemistry have opened
the door to the development of hybrid computational workflows for reaction screening
and discovery (Fig. 1).[1],[2],[3] In this talk, I will highlight some recent work from our research
group in this field. Specifically, I will discuss how we combined automated reaction
profile computation with graph neural networks to screen a chemical space of over 5M
[3+2] cycloaddition reactions for bioorthogonal click potential, resulting in the
identification of over 100.000 plausible click reaction of interest.[4] Furthermore, I will
talk about how existing quantum chemical descriptor datasets can be repurposed to
construct informative representations for downstream reactivity predictions, enabling
extremely data-efficient ML-workflows.2b The latter point will be illustrated for hydrogen
atom transfer reactions, where we were able to make informative predictions on
datasets as small as a few hundred data points, or even smaller, with our approach.
In the final part of my presentation, I will focus on our efforts on the training data
generation side, by showcasing our recently developed tool for automated transition
state (TS) localization, TS-tools.[6] TS-tools is a Python package that enables transition
state searches at xTB or DFT level-of-theory from a reaction SMILES input. On a
benchmarking dataset of mono- and bimolecular reaction pathways, TS-tools reaches
an excellent success rate of 95% already at xTB level of theory. For tri-/multi-molecular
pathways – typically not benchmarked when developing new TS search methods, yet
common in various chemical processes, cf. solvent-, auto- and enzyme catalysis – TS-
tools retains its abilities, though a DFT treatment becomes essential in many cases.'
abstractfigure: [{'figure': 'stuyver.png', 'caption': 'An overview of a typical workflow associated with machine learning accelerated computational screening.'}]
references: [["B. Meyer, et al.", Chem. Sci. ,2018, 9, 7069-7077], 
["S. Heinen, G. Falk von Rudorff, O.
A. Von Lilienfeld", J. Chem. Phys. ,2021, 155, 064105],
["N. Casetti, et al.", Chem. Eur. J. ,2023,
29, e202301957],
["T. Stuyver, C. W. Coley", Chem. Eur. J. ,2023, e202300387], 
["J. Alfonso-Ramos, R.
Neeser, T. Stuyver", ChemRxiv. ,2023, doi:10.26434/chemrxiv-2023-2n281], 
["T. Stuyver",
ChemRxiv. ,2024, doi:10.26434/chemrxiv-2024-st2tr]   
]
---
