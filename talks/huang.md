---
layout: talkpage
categories: [comms]
talknumber: D1.12
talktime: '21.05.2024, 17:30 – 18:00'
speaker: Bing Huang
authors: Bing Huang
img: 
location: 'College of Chemistry and Molecular Sciences, Wuhan University, Wuhan, 430072'
title: 'Approaching Exact Quantum Chemistry through Data-Driven Multi-scale and Multi-fidelity
Machine Learning Models'
abstract: 'Accuracy and efficiency are two challenging aspects to reconcile in quantum chemical computations. Even
for small molecules, the computational cost for approaching or achieving exact solutions in quantum
chemistry is prohibitively high. In recent years, the emergence of Machine Learning (ML) methods has
provided a promising avenue to overcome this challenge[1-3], yet ML methods struggle to evade the curse
imposed by scaling relationships[4]: obtaining more accurate results often requires adding more training
samples (which significantly increases the cost of dataset construction and training). A more severe issue is
that the precision of the training data for ML models determines the upper limit of prediction accuracy[5].
Therefore, to achieve absolute high precision (relative to experimental observations), a large amount of
high-precision training data is needed, which is currently quite scarce. Herein, I would talk about a
multi-level machine learning model[5,7] based on molecular fragments[6] and multi-fidelity molecular
datasets, employing combinatorial mathematics and kernel methods, to approach exact solutions in
quantum chemistry at minimal computational cost, thus fundamentally reconciling the contradiction
between accuracy and efficiency. A distinctive feature of this model is the use of novel combination of
datasets with different levels of precision: high-precision calculations (e.g., quantum Monte Carlo method)
are performed only for the smallest molecular fragments, while larger molecular fragments are treated with
increasingly more inexpensive methods (e.g., PBE/cc-pVTZ). Essentially, this model exploits the locality
of atoms in molecules and the error cancellation mechanism widely exploited in quantum chemistry (as in
composite methods like G2), which can be realized by combinatorial mathematics methods. Extensive
numerical results demonstrate that this model can effectively approach exact solutions in quantum
chemistry for medium-sized organic molecules (containing approximately nine or more non-hydrogen
atoms). Once corresponding systematic big data can be established, this model is expected to achieve
efficient and high-precision quantum chemical property predictions universally (i.e., for any compound
system), thus greatly expanding the application scope of traditional quantum chemical computations and
enabling direct correlation or comparison with experimental data.'
references: [
['B. Huang, O. A. von Lilienfeld', Chem. Rev., 2021, 121(16), 10001],
['B. Huang, G. F. von Rudorff, O. A. von Lilienfeld', Science, 2023, 381(6654), 170],
['F. A. Faber, L. Hutchison, B. Huang, J. Gilmer, S. S. Schoenholz, G. E. Dahl, O. Vinyals, S. Kearnes,
P. F. Riley, O. A. von Lilienfeld', J. Chem. Theory Comput., 2017, 13(11), 5255],
['B. Huang, O. A. von Lilienfeld', J. Chem. Phys., 2016, 145(16), 161102],
['B. Huang, O. A. von Lilienfeld, J. T. Krogel, A. Benali', J. Chem. Theory Comput., 2023, 19(6), 1711],
['B. Huang, O. A. von Lilienfeld', Nat. Chem., 2020, 12(10), 945],
['P. Zaspel, B. Huang, H. Harbrecht, O. A. von Lilienfeld', J. Chem. Theory Comput., 2019, 15(3), 1546]
]
---
