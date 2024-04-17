---
layout: posterpage
categories: [poster]
posternumber: P53
speaker: Konstantin Karandashev
location: 'University of Vienna'
title: 'Evolutionary Monte Carlo optimization in chemical space'
authors: 'Konstantin Karandashev'
link: poster/karandashev
abstract: 'We present a recently proposed [1] Evolutionary Monte Carlo [2] algorithm for solving optimization problems in chemical space. 
The technique is capable of straightforwardly tuning both exploration and exploitation characteristics of an optimization procedure while retaining 
favourable properties of genetic algorithms such as ease of parallelization, no need for initial information on the problem of interest, and stochasticity. 
The method, dubbed MOSAiCS (Metropolis Optimization by Sampling Adaptively in Chemical Space), was tested on problems related to optimizing components 
of battery electrolytes, namely minimizing solvation energy in water or maximizing dipole moment while constraining the HOMO-LUMO gap [1]. 
Optimization over sets of molecular graphs extending QM9 [3,4] and Electrolyte Genome Project (EGP) [5] datasets reliably generated molecular 
candidates with target quantity values matching or (in most cases) better than the ones found in QM9 or EGP. While these optimization results 
sometimes required up to 106 quantum mechanical calculations and were thus only feasible using computationally efficient ab initio approximations 
of properties of interest, in the future the method’s efficiency can be significantly increased using machine learning techniques. Furthermore, 
we explore applying the method beyond property optimization, namely in studying fundamental properties of chemical space [6].'
references: [
['K. Karandashev, J. Weinreich, S. Heinen, D. J. Arismendi Arrieta, G. F. von Rudorff, K. Hermansson, O. A. von Lilienfeld', J. Chem. Theory Comput., 2023, 19, 8861–8870],
['F. Liang, W. H. Wong', Stat. Sin., 2000, 10, 317–342],
['L. Ruddigkeit, R. van Deursen, L. C. Blum, J.-L. Reymond', J. Chem. Inf. Model., 2012, 52, 2864–2875],
['R. Ramakrishnan, P. O. Dral, M. Rupp, O. A. von Lilienfeld', Sci. Data, 2014, 1, 140022],
['X. Qu, A. Jain, N. N. Rajput, L. Cheng, Y. Zhang, S. P. Ong, M. Brafman, E. Maginn, L. A. Curtiss, K. A. Persson', Comput. Mater. Sci., 2015, 103, 56–67],
['J. Weinreich, K. Karandashev, G. F. von Rudorff', preprint available at arXiv:2309.09194]
]
---
