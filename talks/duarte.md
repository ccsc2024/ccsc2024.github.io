---
layout: talkpage
categories: [keynote]
talknumber: D2.01
talktime: '22.05.2024, 09:00 – 09:45'
speaker: Prof. Fernanda Duarte
img: 'fernanda_duarte.png'
location: 'Department of Chemistry · University of Oxford · 12 Mansfield Road, Oxford, OX1 3TA UK'
title: 'Modelling Chemical Reactions in Solution with Machine Learning Potentials – Balancing Efficiency and Accuracy'
authors: 'Hanwen Zhang, Veronika Juraskova, Fernanda Duarte'
abstract: [
"Efficient and accurate modelling of chemical reactions in the condensed phase represents one of the ‘grand challenges’ in computational chemistry. While characterizing reaction energy pathways has become routine, exploring these processes while accounting for solvent and dynamics effects remains a time-consuming and non-systematic endeavour. Solvent effects, in particular, significantly impact reaction rates, selectivity, and the reaction mechanism itself.",
"In this talk, I will discuss our ongoing efforts to model reactions in solution using machine learning potentials (MLPs) as efficient surrogates for traditional ab initio methods. [1-3] Our approach, implemented in the mlp-train package (https://github.com/duartegroup/mlp-train), integrates electronic structure methods, different MLP architectures, and active learning to generate the training sets on the fly and train MLPs in low data regime. Through illustrative examples using the Atomic Cluster Expansion (ACE) framework [4] and its message-passing neural network variant (MACE) [5-6] we demonstrate that this approach facilitates the creation of data-efficient training sets that adequately sample the chemical space to achieve the required accuracy while maintaining significantly low computational costs. Furthermore, we combine this strategy with enhanced sampling techniques, such as metadynamics, to explore the energy landscape during the training phase, which is particularly challenging when investigating reactive processes. We discuss the influence of descriptors and models, training strategy, and ground truth method, as well as different metrics to evaluate the performance and accuracy of the generated MLPs for different organic chemical reactions."
]
references: [
['T. A. Young, T. Johnston-Wood, V. Deringer, F. Duarte', 'Chem. Sci.', 2021, 12, 10944],
['T. A. Young, T. Johnston-Wood, H. Zhang, F. Duarte', 'Phys. Chem. Chem. Phys.', 2022, 24, 20820],
['H. Zhang, V. Juraskova, F. Duarte', 'ChemRxiv', 2023],
['R. Drautz', 'Phys. Rev. B', 2019, 99, 014104],
['D. P. Kovács, C. van der Oord, J. Kucera, A. E. A. Allen, D. J. Cole, C. Ortner, G. Csányi', 'J. Chem. Theory Comput.', 2021, 17, 7696],
['I. Batatia, D. P. Kovács, G. N. C. Simm, C. Ortner, G. Csanyi', 'Adv. Neural Inf. Process. Syst.', 2022, 35, 11423]
]
---
