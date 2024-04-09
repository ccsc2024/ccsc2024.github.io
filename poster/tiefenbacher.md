---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img:
title: 'Excited state ML/MM dynamics with electrostatic embedding'
authors: 'Maximilian Xaver Tiefenbacher, Brigitta Bachmair, Sebastian Mai, Johannes Dietschreit, Julia Westermayr'
speaker: 
location: 'University of Vienna'
abstract: 'Quantum mechanics/molecular mechanics (QM/MM) simulations have become a
well-established approach for treating large systems by partitioning them into a region of chemical interest described with a QM-level of theory while the significantly cheaper MM is used for the rest of the system. 
Recently, to overcome the inherent bottleneck of using costly QM, machine learning (ML) models have been developed for performing analogous ML/MM simulations [1,2].
In this work we present an extension of the neural network FieldSchNet [2], which can describe the interactions between the ML region and the surrounding system by means of electrostatic embedding. 
This is achieved by including the external electric field (created by the partial charges of the MM-atoms) as a descriptor to the neural
network in addition to the coordinates and atomic numbers.
The extension called FieldSchNarc is based on the SchNarc [3] approach and makes it possible to describe not only the ground state but also non-adiabatic effects in an ML/MM setting. FieldSchNarc enables fewest-switches surface
hopping dynamics using the established SHARC (surface hopping including
arbitrary couplings) program package [4].
The efficacy of this architecture is demonstrated by applying it to
furan in water.'
references: [ ["E. Cignoni, L. Cupellini, and B. Mennucci", J. Chem. Theory Comput. ,2024, 19, 965–977],
["M. Gastegger, K. T. Schütt and K. R. Müller", Chem. Sci. ,2021, 12, 11473-11483],
["J. Westermayr, M. Gastegger, and P. Marquetand", J. Phys. Chem. Lett. ,2020, 11, 3828–3834],
["S. Mai, D. Avagliano, M. Heindl, P. Marquetand, M.F.S.J. Menger, M. Oppel, F. Plasser, S. Polonius, M. Ruckenbauer, Y. Shu, D.G. Truhlar, L. Zhang, P. Zobel, L. González", https://sharc-md.org/. ,2023]
]
---
