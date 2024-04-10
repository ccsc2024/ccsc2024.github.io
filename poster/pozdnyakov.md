---
layout: posterpage
categories: [decision]
posternumber: '?'
title: 'Merits of unconstrained atomistic machine learning'
authors: 'Sergey Pozdnyakov, Michele Ceriotti'
speaker: Sergey Pozdnyakov
location: 'Ecole Polytechnique Fédérale de Lausanne'
abstract: 'In the last decade, methods incorporating rotational symmetry into their functional form have dominated the field of atomistic machine learning. Two main considerations have driven this design choice. Firstly, it was widely believed that rotational symmetry, when intrinsically built into a machine learning architecture, plays the role of necessary inductive bias, thus being crucial for a model’s performance and generalizability. Secondly, rigorous rotational invariance might be necessary for atomistic simulations such as molecular dynamics to avoid subtle artifacts. In this talk, I will challenge the first belief by presenting an unconstrained model, Point Edge Transformer (PET), which is not rotationally invariant and instead relies on rotational augmentations during fitting. As Figure and Table 1 show, PET not only achieves state-of-the-art performance on multiple benchmark datasets of molecules and solids but also improves faster with the increase of the training data compared to other methods. To address the second consideration, we introduce a general symmetrization method that a-posteriori enforces rigorous rotational equivariance for any backbone architecture, which might even be superfluous given how accurate PET’s learned rotational equivariance is. In the final part, I will present a few general considerations of why unconstrained architectures are likely more efficient, especially in the data-rich regime, which might explain PET’s excellent and often superior performance and more favorable scaling laws. These include: (i) in contrast to the equivariant world, each shallow layer of an unconstrained architecture is provably and trivially a universal approximator; (ii) there is no need in the expensive SO(3) algebra, which allows to achieve an unlimited angular resolution inexpensively and favors the computational efficiency overall.'
abstractfigure: [{'figure': 'pozdnyakov.png',
'caption': 'Comparison of the accuracy of PET and current state-of-the-art models for the COLL, MnO, HM21, HEA and CH4 data sets. In Table energy errors are given in meV/atom, force errors in meV/Å. y0 and yS indicate unsymmetrized and symmetrized models, respectively. References match the ones of Ref[1].  In addition, it is worth noting that PET outperforms Nequip on the liquid water dataset, see Ref[1].'
}]
references: [["Sergey Pozdnyakov, & Michele Ceriotti","",2023. Smooth, exact rotational symmetrization for deep learning on point clouds. In Thirty-seventh Conference on Neural Information Processing Systems] 
]
---
