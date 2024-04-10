---
layout: posterpage
categories: [poster]
posternumber: P04
speaker: Yuri Cho
location: 'École Polytechnique Fédérale de Lausanne (EPFL), Lausanne (CH)'
title: 'Automated Prediction of Ground State Spin for Transition Metal Complexes
and Benchmarking Physics-based Representations'
authors: 'Yuri Cho, Ruben Laplaz, Sergi Velad,
Yannick Calvino Alonso, Ksenia Briling, Clémence Corminboeuf'
abstract: 'Exploiting crystallographic data repositories for large-scale quantum chemical computations
requires rapid and accurate retrieval of all the necessary information (molecular structure, charge,
and spin state) directly from crystal structures. Here, we develop a general approach to predict the
ground state spin of transition metal complexes, complementing our prior work on determining
metal oxidation states and bond order within the <cite>cell2mol</cite> software. Starting from a previously
curated database extracted with <cite>cell2mol</cite> [1], we construct the TM-GSspin dataset, which contains
2,032 mononuclear first row transition metal complexes and their computed ground state spins.
TM-GSspin dataset is analyzed to identify correlations between the structural and electronic
features of the complexes and their ground state spins. Leveraging this knowledge, we build a
rule-based empirical model as well as interpretative statistical models that assign the ground state
spin of transition metal complexes, with a high accuracy of 97%. Our approach provides a practical
way to determine the ground state spin of transition metal complexes directly from the crystal
structure without additional computations, thus enabling the automated use of crystallographic
data for large-scale computations. Moreover, we utilize our diverse dataset to benchmark the
performance of various physics-based representations [2] in predicting the molecular properties of
transition metal complexes.'
abstractfigure: [{'figure': 'cho.png', 'caption': 'General workflow of predicting ground state spin of transition metal complexes.'}]
references: [
    ['Vela, S., Laplaza, R., Cho, Y., Corminboeuf, C.',
    'npj Comput. Mater.', 2022, 8, 188],
    ['Musil, F., Grisafi, A., Bartók, A. P., Ortner, C., Csányi, G., Ceriotti',
    'M. Chem. Rev.', 2021, 121, 9759]
]
---
