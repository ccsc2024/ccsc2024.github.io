---
layout: talkpage
categories: [speedtalk]
talknumber: 'D1.10'
talktime: '21.05.2024, 17:00 – 17:15'
speaker: Kimberly J. Daas
location: 'Vrije Universiteit Amsterdam (NL)'
title: 'The Next Generation of Møller-Plesset Adiabatic Connection Functionals for Non-Covalant Interactions'
authors: 'Kimberly J. Daas, Heng Zhao, Elias Polak, Paola Gori-Giorgi, Stefan Vuckovic'
abstract: 'Non-covalent interactions (NCIs) play a crucial role in biology, chemistry, material science, and everything in between. 
To improve pure quantum chemical simulations of NCIs, we constructed accurate models via an interpolation along the Møller-Plesset adiabatic connection (MP AC) [1]. 
These interpolations approximate the correlation energy, by recovering MP2 at small coupling strengths and the correct large-coupling strength expansion of the MP AC, 
recently shown to be a functional of the Hartree-Fock density [2][3]. Our models are size consistent for fragments with non-degenerate ground states, have the same cost
as double hybrids and require no dispersion corrections to capture NCIs accurately. These interpolations greatly reduced large MP2 errors for typical &pi;-stacking complexes 
(e.g., benzene-pyridine dimers) and for large molecular systems. They were also competitive with state-of-the-art dispersion enhanced functionals and can even significantly 
outperform them for a variety of NCIs. Here, we present the next generation of the MPAC functionals where we use spin scaling and regularization techniques to not only further 
increase the accuracy of the functionals but also make them scale the same as hybrids [4]. Other strategies such as local interpolations, giving the functions more information 
without significantly increasing the computational cost, and machine learning, by either finding the optimal parameters or finding better interpolation forms, are used to further 
improve the accuracy of the functionals and increase the transferability to different non-covalent interactions and other energy differences.'
references: [
    [
        'T. J. Daas, E. Fabiano, F. Della Sala, P. Gori-Giorgi, S. Vuckovic',
        J. Phys. Chem. Lett., 2021, 12, 4867-4875 
    ],
    [
        'T. J. Daas, J. Grossi, S. Vuckovic, Z. Musslimani, D. Kooi, M. Seidl, K. Giesbertz, P. Gori-Giorgi',
        The Journal of Chemical Physics, 2020, 153, false
    ],
    [
        'M. Seidl, S. Giarrusso, S. Vuckovic, E. Fabiano, P. Gori-Giorgi',
        The Journal of Chemical Physics, 2018, 149, false
    ],
    [
        'K. J. Daas; D. P. Kooi; N. C. Peters; E. Fabiano; F. Della Sala; P. Gori-Giorgi; S. Vuckovic',
        The Journal of Physical Chemistry Letters, 2023, 14, 8448–8459
    ]
]
---
