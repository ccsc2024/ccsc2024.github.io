---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img: .png
title: 'Reliable machine learning form sparse data in high dimension with additive kernel based methods'
authors: 'Sergei Manzhos, Manabu Ihara'
speaker: 
location: 'Tokyo Institute of Technology'
abstract: 'Machine learning (ML) has become popular for the construction of interatomic potentials, DFT functionals, and to predict materials properties from descriptors of chemical composition and structure. In these applications, the ML problems are typically of regression type (or can be cast as such), and kernel regressions and neural networks (NN) are most widely used types of methods. These methods have high expressive power but require more data than physically motivated approaches and suffer from lack of insight. I high-dimensional (D) settings, sampling is bound to be sparse, and this cannot be helped by adding more data (the ’curse of dimensionality’). NNs suffer from a large and growing with D number of nonlinear parameters, which causes high CPU cost and overfitting. Kernel methods, being effectively linear regressions with nonlinear basis functions, appear then particularly appealing as combining high expressive power and stability [1]. We will demonstrate how in high D and with sparse data, kernel regressions lose their superior expressive power and become equivalent to low-order polynomial fits [2], and the property of locality of commonly used Matern type kernels (which are used for this property) is lost [3]. Finding optimal hyperparameters in this regime also becomes difficult [4]. We will show that these problems can be effectively addressed by using orders of coupling expansions achieved by using additive kernels [5–8]. This approach also helps generate insight while preserving the generality of the methods. Additive kernels also allow obtaining an NN type representation without nonlinear optimization and with optimal neuron activation functions [9,10]. We wills show examples from ML for interatomic potentials, materials informatics [11] and kinetic energy functionals [7,12].'
references: [["Manzhos, S.; Tsuda, S.; Ihara, M.", Phys. Chem. Chem. Phys. ,2023, 25, 1546–1555],
["Manzhos, S.; Ihara, M.", J. Chem. Phys. ,2024, 160, 021101],
["Manzhos, S.; Ihara, M.", J. Chem. Phys. ,2023, 158, 044111],
["Manzhos, S.; Ihara, M.", J. Math. Chem. ,2023, 61, 7–20],
["Manzhos, S.; Carrington, T.; Ihara, M.", Artificial Intelligence Chemistry ,2023, 1, 100008],
["Manzhos, S.; Sasaki, E.; Ihara, M.", Mach. Learn.: Sci. Technol. ,2022, 3, 01LT02],
["Ren, O.; Boussaidi, M.A.; Voytsekhovsky, D.; Ihara, M.; Manzhos, S.", Comput. Phys. Commun. ,2022, 271, 108220],
["Boussaidi, M.A.; Ren, O.; Voytsekhovsky, D.; Manzhos, S.", J. Phys. Chem. A ,2020, 124, 7598–7607],
["Manzhos, S.; Ihara, M.", J. Phys. Chem. A ,2023, 127, 7823–7835],
["Manzhos, S.; Ihara", M. Artificial Intelligence Chemistry ,2023, 1, 100013],
["Nukunudompanich, M. et al", MRS Adv. ,2024, "doi:10.1557/s43580-023-00749-1"],
["Manzhos, S.; Lüder, J.; Ihara, M.", J. Chem. Phys. ,2023, 159, 234115]


    
]
---
