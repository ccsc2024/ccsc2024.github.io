---
layout: posterpage
categories: [digidemo]
posternumber: 'DD05'
speaker: 'Joscha Hoche and Marcel Müller'
location: ['Merck KGaA, Darmstadt, Germany', 'Mulliken Center for Theoretical Chemistry, University of Bonn, Germany']
title: 'Catalyzing Discovery: Bayesian Back End (BayBE)
as a general-purpose toolbox for Bayesian Design of
Experiments in real-world campaigns'
authors: 'J. Hoche, M. Müller, M. Fitzner, A. Hopp, A. Lee, A. Šošić and J. G. Brandenburg'
abstract: [
'The Bayesian Back End (BayBE) is a versatile, open-source software package [1] designed
to streamline and optimize the design of experiments (DoE) process. BayBE offers a
comprehensive suite of tools tailored for real-world experimental campaigns, particularly in the
chemical and materials sciences. Key features include custom parameter encodings to
incorporate domain knowledge, built-in chemical encodings, and the flexibility to integrate
custom surrogate models for specialized problems like active learning.',
'A standout capability of BayBE is its implementation of transfer learning, enabling the
integration of data from multiple related campaigns to accelerate optimization. This multi-
context Bayesian optimization approach has demonstrated significant performance
enhancements in various test cases, including reaction conditions for direct arylation.[2] and
anti-correlated benchmark functions. Preliminary results suggest that strategically sub-
sampling source data can further improve optimization efficiency.',
'BayBE is built on a robust, fully typed and hypothesis-tested code base, ensuring reliability
and ease of use. It includes comprehensive backtesting utilities to facilitate benchmarking and
identification of optimal settings. All objects within BayBE are fully de-/serializable, making it
easy to store results in databases or integrate with wrappers such as APIs.'
]
abstractfigure: [{'figure': 'hoche.png', 'caption': 'Outcomes of Bayesian Optimization with various molecular encodings from BayBE [1],
demonstrating enhanced efficiency in identifying optima˚l conditions for imidazole direct
arylation [2] with complex encodings over simpler ones with fewer iterations.'}]
references: [
    [
        'M. Fitzner, A. Šošić, A. Hopp, et al.', 'unpublished 2024', 'github.com/emdgroup/baybe'
    ],
    [
    'B.J. Shields, J. Stevens, J. Li, et al.', 'Nature', '2021', 590, 89–96
    ]
]
---
