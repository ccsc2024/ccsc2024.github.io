---
layout: posterpage
categories: [poster]
posternumber: P55
speaker: Manuel Schmitt
location: 'University Heidelberg'
title: 'Predicting Lewis Acidity - Machine Learning the Fluoride Ion Affinity of p-Block-Atom-Based Molecules'
authors: 'Manuel Schmitt, Andreas Albers, Lukas M. Sigmund, Shree Sowndarya S. V., Philipp Erdmann, Robert S. Paton, Lutz Greb'
abstract: "Lewis acids are omnipresent in all branches of chemistry and the strength of a Lewis acid in its thermodynamic sense (global Lewis acidity) is often 
approached by calculating its fluoride ion affinity (FIA) with quantum chemistry.[1,2] 
Here, we present FIA49k, an extensive FIA dataset with 48,986 data points calculated at the RI-DSD-BLYP-D3(BJ)/def2-QZVPP//PBEh-3c level of theory, 
including 13 different p-block atoms as the fluoride accepting site. The FIA49k dataset was used to train FIA-GNN, two message-passing graph neural 
networks,[3] which predict gas and solution phase FIA values of molecules excluded from training with a mean absolute error of 14 kJ mol<sup>−1</sup> (r<sup>2</sup>=0.93) 
from the SMILES string of the Lewis acid as the only input. The level of accuracy is notable, given the wide energetic range of 750 kJ mol<sup>−1</sup> spanned 
by FIA49k. The model's value and weaknesses were evaluated and demonstrated with four case studies. FIA-GNN and the FIA49k dataset can be reached via 
a free web app (www.grebgroup.de/fia-gnn)."
abstractfigure: [{'figure': 'schmitt.png', 'caption': ''}]
references: [
['K. O. Christe, D. A. Dixon, D. McLemore, W. W. Wilson, J. A. Sheehy, J. A. Boatz', J. Fluorine Chem., 2000, 101, 151],
['P. Erdmann, J. Leitner, J. Schwarz, L. Greb', ChemPhysChem, 2020, 21, 987],
['P. C. St. John, C. Phillips, T. W. Kemper, A. N. Wilson, Y. Guan, M. F. Crowley, M. R. Nimlos, R. E. Larsen', J. Chem. Phys., 2019, 150, 234111]
]
---
