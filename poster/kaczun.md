---
layout: posterpage
categories: [poster]
posternumber: P52
speaker: T. Kaczun
location: 'Interdisciplinary Center for Scientific Computing (IWR), Universität Heidelberg, 69120 Heidelberg'
title: 'Enabling OF-DFT with Machine Learning? A novel ansatz for data generation'
authors: 'T. Kaczun, R. Remme, M. Scheurer, F. Hamprecht, A. Dreuw'
link: poster/kaczun
abstract: [
'Orbital-free density functional theory (OF-DFT) holds the promise to compute ground
state molecular properties at minimal cost. Despite this, decades of research did not
yield a kinetic energy functional with sufficient accuracy for general use in
computational chemistry.[1]',
'Previously several ML models have been published that are able to predict the kinetic
energy density and kinetic potential of Kohn-Sham ground state densities.[2,3]
However no ML kinetic energy functional with sufficient generality for meaningful
molecular calculation has been reported so far. A major computational obstacle is that
it is insufficient to precisely predict the relevant quantities for the ground state only;
instead it is necessary to estimate them accurately for all intermediate densities during
a calculation.[3] Unfortunately, though, the kinetic potential can only be calculated from
KS-DFT solutions.',
'As a consequence of this inverse DFT can be leveraged to calculate the external
potential of those intermediate densities. This allows the calculation of the kinetic
potential for those densities. Furthermore, we propose to overcome this limitation by
not just training on standard KS-DFT ground states but also on ground states from
perturbed external potentials. The novel equivariant network KineticNet has been
trained accordingly and achieves OF-DFT calculations for two electron systems.'
]
references: [
['R. G. Parr, W. Yang', Annual review of physical chemistry, 1995, 46, 701–728],
['K. Ryczko, S. J. Wetzel, et al.', Journal of Chemical Theory and Computation, 2022, 18, 1122–1128],
['M. Fujinamia, R. Kageyamaa, et al.', Chemical Physics Letters, 2020, 748, 137358]
]
---
