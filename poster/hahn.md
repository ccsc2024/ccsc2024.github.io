---
layout: posterpage
categories: [poster]
posternumber: 'P06'
speaker: Eduard Hahn
location: 'University of Hamburg (DE)'
title: 'Machine Learning Exchange Spin Coupling -
Building problem-tailored Descriptors'
authors: 'Eduard Hahn, Michael Deffner, Jonny Proppe, Carmen Herrmann'
abstract: [
    'Exchange coupling between unpaired electrons plays a crucial role in determining the
magnetic properties of molecules, e.g., dinuclear copper(II) complexes, deciding their
usability as molecular magnets in fields such as molecular spintronics or quantum
technologies [1].',
    'Problem-tailored machine learning models based on Gaussian process regression
have proven capable of predicting the strength of the exchange spin coupling,
expressed via the Heisenberg exchange coupling constant J and calculated using an
efficient Green&#8217;s-function approach, within subsets of dinuclear copper complexes.
Training the machine learning models requires only a fraction of the computational
cost and produces accuracies close to the reference calculations obtained by utilizing
density-functional theory (DFT) [2,3].',
    'However, more complex datasets (which better represent the relevant chemical space
of dinuclear copper complexes) reveal significant shortcomings of previous
approaches regarding machine learning algorithm and descriptor choice.
Examining the performance of machine learning models trained on increasingly
complex datasets pinpoints the limitations of previously used low dimensional,
problem-tailored descriptors and allows for systematic improvements while retaining
low dimensionality and feature interpretability.',
    'In particular, encoding the influence of outer ligands remains challenging due to their
different structural as well as electronic effects on the coupling constant [4].
Simple solutions such as one-hot encoding (including selected element or ligand
specifications) leads to decent performance improvements, highlighting the
importance of proper feature selection, but does not adequately translate the unique
properties of the many possible ligands.'
]
references: [
    [
        'E. Coronado',
        Nat. Rev. Mater. 2020, 5, 87-104
    ],
    [
        'T. Steenbock, J. Tasche, A. Lichtenstein, C. Herrmann',
        J. Chem. Theory Comput., 2015, 11, 5651-5664
    ],
    [
        'P. Bahlke, N. Mogos, J. Proppe, C. Herrmann',
        J. Phys. Chem. A 2020, 124, 42, 8708-8723
    ],
    [
        'A. Rodríguez-Fortea, P. Alemany, S. Alvarez, E. Ruiz',
        Inorg. Chem. 2002, 41, 14, 3769-3778
    ]
]
---
