---
layout: talkpage
categories: [invited]
talknumber: D2.05
talktime: '22.05.2024, 14:00 – 14:30'
speaker: Prof. Paul Popelier
authors: 'Paul L.A. Popelier, M. Brown, M. Burn, L. Cabrera, G. Hawe, B. Isamura, M. Nosratjoo, B. Symons and M. Vincent'
img: popelier.png
location: Department of Chemistry, University of Manchester, M13 9PL Manchester, Britain (UK)
title: 'FFLUX'
abstract: 'We pioneered[1] the use of Gaussian Process Regression (which we regrettably called “kriging” with hindsight) in the design of atomic potentials. Contrary to efforts of other research groups, we started first with the machine learning (ML) of accurate electrostatics (e.g. for all 20 amino acids[2]). It is manifest to work with multipole moments if only nuclear sites are used. Next followed accurate ML predictions of the atomic energies. At the heart of this method are quantum topological atoms[3], such that a single partitioning method provides all atomic properties. Note, that unlike in alternative approaches, the ML does not partition the total system into atomic quantities. This approach[4] is now called FFLUX.
Sustained in-house software development led to the ML training program FEREBUS[5] supported by ICHOR[6] and the molecular dynamics program DL_FFLUX, which is an offspring of DL_POLY. Adaptive sampling (which the establishment calls active learning) combined with a AIMD-based sample set produces models with fewer training point than neural network do for small molecules[7]. Improved training now tackles molecules (e.g. paracetamol) up to ~30 atoms[8]. The recent parallellisation[9] of DL_FFLUX enables the simulation of condensed matter, whether molecular crystals[10] or liquid water[11], all with high-rank polarisable electrostatics. The next major step will be to link models in order to describe oligopeptides and later even proteins. Meanwhile, innovative ML techniques are being introduced[12]  to improve the prediction errors.'
abstractfigure: [{'figure': 'popelier.pnd', 'caption': ' '}]
references: [
['C. M. Handley, G. I. Hawe,D. B. Kell, P. L. A. Popelier', PCCP, 2009, 11, 6365],
['T. L. Fletcher, P. L. A. Popelier', J.Chem.Theor.Comput., 2016, 12, 2742],
['R. Bader', 'Atoms in Molecules. A Quantum Theory. Oxford Univ. Press', 1990],
['P. L. A. Popelier', Int.J.Quant.Chem., 2015, 115, 1005],
['M. J. Burn, P. L. A. Popelier', Digital Discovery, 2023, 2, 152],
['M. J. Burn, P. L. A. Popelier', Materials Advances, 2022, 3, 8729],
['M. J. Burn, P. L. A. Popelier', J.Chem.Phys., 2020, 153, 054111],
['M. J. Burn, P. L. A. Popelier', J.Chem.Theory Comp., 2023, 19, 1370],
['B. C. B. Symons, M. K. Bane, P. L. A. Popelier', J. Chem. Theor. Comp., 2021, 17, 7043],
['M. L. Brown, J. M. Skelton, P. L. A. Popelier', J. Chem. Theor. Comp., 2023, 19, 7946],
['B. C. Symons, P. L. A. Popelier', J.Chem.Theory Comp., 2022, 18 5577],
['B. K. Isamura, P. L. A. Popelier', Artificial Intelligence Chemistry, 2023, 1, 100021]
]
---
