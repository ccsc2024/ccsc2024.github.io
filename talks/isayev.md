---
layout: talkpage
categories: [invited]
talknumber: D2.03
talktime: '22.05.2024, 11:00 – 11:30'
speaker: Prof. Olexandr Isayev
img: isayev.png
location: 'Department of Chemistry, Carnegie Mellon University, Pittsburgh PA'
title: 'Scaling Molecular Modelling to Millions of Reactions with AIMNet2 Neural Network Potential'
authors: Dylan M. Anstine, Roman Zubatiuk and Olexandr Isayev
abstract: [
'Developments in high-throughput experimentation, automated chemistry platforms, and chemical generative models have created an urgent need to rapidly predict reaction outcomes so that synthetic planning and evaluations of degradability can match the emerging pace of molecule/material discovery. Machine-learned interatomic potentials (MLIPs), whereby potential energy surface representations are learned from datasets of first-principles calculations, present an attractive opportunity to overcome the expensive and/or time-consuming tasks required to characterize and refine reactions experimentally or with quantum chemistry models.',
'In this talk, I will introduce two models, RxnAIMNet and AIMNet2-Pd, that illustrate how MLIPs can be used to predict the thermodynamics and kinetics of general organic reactions and carbon-carbon cross-couplings that are catalyzed by Pd organometallic complexes. By learning from a newly constructed and exhaustive dataset of ~10 million molecular conformers, RxnAIMNet is shown to reliably perform minimum energy pathway searches, transition state optimization, and intrinsic reaction coordinate calculations, leading to predicted activation barriers within ~2 kcal/mol of reference range-separated hybrid density functional theory (DFT) calculations. To meet the needs of high-throughput reaction characterization, we introduce a method for batched nudged elastic band calculations, which allows RxnAIMNet to identify ~350,000 minimum energy pathways daily on a single medium-end GPU.'
]
references: [
['D. Anstine, R. Zubatyuk, O. Isayev', 'ChemRxiv', 2023, 'https://doi.org/10.26434/chemrxiv-2023-296ch'],
]
---
