---
layout: posterpage
categories: [poster]
posternumber: 'P13'
title: 'Decoding Solid-State NMR Descriptors Using Machine Learning: A Transition Metal Dataset'
authors: 'Magdalena Lederbauer, Zachariah J. Berkson, Merlin Seidel, Yuya Kakiuchi, Jérémy Roudin, Kjell Jorner, Christophe Copéret'
speaker: Magdalena Lederbauer
location: 'Department of Chemistry and Applied Biosciences, ETH Zurich'
abstract: 'Fundamental understanding of structure-reactivity relationships in catalysis requires advanced spectroscopy, like solid-state NMR, where chemical shift tensors (CSTs) 
provide insight into local chemical environments and electronic structures.[1] Current methods rely on advanced computational orbital analysis to connect experimentally accessible 
NMR descriptors of ligand[2] and metal nuclei[3] to orbitals involved in reactivity. Due to the computational expense and time-consuming nature of these measurements, the explored chemical space is limited.
<br><br>
To address these limitations, we developed a comprehensive in silico dataset of 29’000 penta- and hexacoordinated complexes of d0 group(VI) metals (W and Mo) used as precatalysts in olefin conversion processes. 
Each complex was constructed combinatorically[4] from a set of synthetically accessible ligands, optimized using semiempirical methods and subjected to high-level DFT calculations to compute CSTs. 
The dataset was featurized with 125 local and global descriptors including steric and electronic parameters[5]. Through hierarchical clustering, we performed feature selection and tested simple machine learning 
models to probe the mapping of chemical descriptors to spectroscopical properties. Analysis of the dataset yields trends that are consistent with previous case studies and reveal several unexplored trends such as 
the influence of metal 𝝈- and 𝞹-bonding, and the steric bulk of the ligands.
The presented workflow can be adapted to any transition metal complex dataset with a predefined substitution pattern and ligand library. The dataset is designed to support machine learning applications 
in transition metal spectroscopy. It offers an approach to advancing the understanding of the link between spectroscopy and electronic structure across a broad composition space.'
references: [["Christopher P. Gordon, Lukas Lätsch, Christophe Copéret", J. Phys. Chem. Lett. ,2021, 12, 8, 2072–2085],
["Christopher P. Gordon, Christophe Raynaud, Richard A. Andersen, Christophe Copéret, Odile Eisenstein", Acc. Chem. Res. ,2019, 52, 8, 2278–2289],
["Zachariah J. Berkson, Lukas Lätsch, Julius Hillenbrand, Alois Fürstner, Christophe Copéret", J. Am. Chem. Soc. ,2022, 144, 33, 15020–15025],
["Aditya Nandy, Chenru Duan, Michael G. Taylor, Fang Liu, Adam H. Steeves, Heather J. Kulik", Chem. Rev. ,2021, 121, 16, 9927–10000],
["Kjell Jorner, & Lukas Turcani", kjelljorner/morfeus: v0.7.2. Zenodo. ,2022, "https://doi.org/10.5281/zenodo.7017599"]
]
---
