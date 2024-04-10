---
layout: posterpage
categories: [poster]
posternumber: 'P14'
title: 'MoINN: A Neural Network for Identifying and Utilizing Chemical Moieties in Molecular Data'
authors: 'Jonas Lederer, Michael Gastegger, Kristof T. Schütt, Michael Kampffmeyer, Klaus-Robert Müller,  Oliver T. Unke'
speaker: Jonas Lederer 
location: 'Berlin Institute of Technology (TU Berlin)'
abstract: 'Message-passing neural networks (MPNNs) as a framework for learning atomic representations, has become increasingly powerful regarding the prediction of electronic properties. Here, we introduce a method to automatically identify chemical moieties (molecular building blocks) from such representations, enabling a variety of applications beyond property prediction, which otherwise rely on expert knowledge. Beyond the data-driven design of molecular fingerprints, the versatility of our approach is demonstrated by enabling the selection of representative entries in chemical databases, the automatic construction of coarse-grained force fields, as well as the identification of reaction coordinates.'
abstractfigure: lederer.png
figuretext: 'Methodology of MoINN. First, atomic feature representations (red and blue bars) are learned. Next, MoINN constructs type assignment vectors (pink and orange bars) based on these features. Each entry represents the probability of an atom to be assigned to a specific type of moiety (atoms are colored according to the highest atom-to-type affinity). Based on these assignments and the proximity of atoms, MoINN divides molecules into individual moieties.'
references: [ [Lederer, Jonas, et al. "Automatic identification of chemical moieties.", Physical Chemistry Chemical Physics 25.38, (2023): 26370-26379]
]
---
