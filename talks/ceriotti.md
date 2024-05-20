---
layout: talkpage
categories: [keynote]
talknumber: D3.01
talktime: '23.05.2024, 09:00 – 09:45'
speaker: Prof. Michele Ceriotti
img: michele_ceriotti.png
location: 'Laboratory of Computational Science and Modeling (COSMO), Institute of Materials, EPFL'
title: 'Hic sunt dracones - Uncertainty quantification for trustworthy exploration of chemical space'
abstract: 'Machine learning has greatly accelerated the search of new chemical compounds,
and extended the range of systems that can be studied, promising an accuracy
comparable with that of the first-principles reference they are fitted against. Given the
interpolative nature of machine-learning models, it is crucial to be able to determine
how reliable are the predictions of simulations that rely on them, as well as to
understand the physical underpinnings - if any - for the successes and failures of
different frameworks.
<br><br>
I will discuss a few examples of how understanding the mathematical structure of ML
models help to use them to interpret the outcome of atomistic simulations, in terms of
familiar concepts such as locality, range and body order of interactions. Then, I will
give a brief overview of the different approaches that are available to obtain a
quantitative measure of the uncertainty in a machine-learning prediction, and discuss
in particular an inexpensive and reliable scheme based on an ensemble of models.
[1-3] Crucially, these "calibrated committee models" estimate not only the accuracy
of individual predictions, but also of the final properties resulting from complicated
workflows based on molecular dynamics and statistical sampling techniques.'
references: [
['G. Imbalzano, Y. Zhuang, V. Kapil, K. Rossi, E. A. Engel, F. Grasselli, and M. Ceriotti', 'J. Chem. Phys.', 2021, 154(7), 074102],
['M. Kellner, M. Ceriotti', arXiv, 2024, 2402.16621],
['F. Bigi, S. Chong, F. Grasselli, M. Ceriotti', arXiv, 2024, 2403.02251]
]
abstractfigure: ['figure': 'ceriotti.png', 'caption': 'Schematic representation of error estimation with uncertainty propagation using a
shallow-ensemble model']
---
