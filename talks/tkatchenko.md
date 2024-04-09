---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img: .png
title: 'Exploring Chemical Space Directly and Inversely'
authors: 'Alexandre Tkatchenko'
speaker: 
location: 'University of Luxembourg'
abstract: 'Computer-driven molecular design combines the principles of chemistry, physics, and artificial intelligence (AI/ML) to identify novel chemical compounds and materials with desired properties for a specific application. A long-held dream of molecular simulations is to be enable efficient navigation of large chemical spaces, including both compositional and configurational molecular degrees of freedom. In this talk, I will discuss novel insights that AI/ML methods bring when doing direct (https://doi.org/10.1039/D3SC03598K) and inverse (https://arxiv.org/abs/2309.00506) navigation of chemical space of drug-like molecules. First, our analysis reveals that one has a substantial degree of flexibility or “freedom of design” when searching for a single molecule with a desired pair of properties or a set of distinct molecules sharing an array of properties. To explore how this intrinsic flexibility manifests in the molecular design process, we use multi-objective optimization to search for molecules with simultaneously large polarizabilities and HOMO–LUMO gaps; analysis of the resulting Pareto fronts identified non-trivial paths through CCS consisting of sequential structural and/or compositional changes that yield molecules with optimal combinations of these properties. Second, we develop a proof-of-concept implementation that combines a Variational Auto-Encoder (VAE) trained on molecular structures with a property encoder designed to learn the latent representation from a set of QM properties. The result of this joint architecture is a common latent space representation for both structures and properties, which enables property-to-structure mapping for small drug-like molecules contained in the QM7-X dataset. We illustrate the capabilities of our approach by conditional generation of de novo molecular structures with targeted properties, transition path interpolation for chemical reactions as well as insights into property-structure relationships. Our findings thus provide a proof-of-principle demonstration aiming to enable the inverse property-to-structure design in diverse chemical spaces.'

---
