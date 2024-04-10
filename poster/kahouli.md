---
layout: posterpage
categories: [decision]
posternumber: '?'
title: 'Molecular Relaxation by Reverse Diffusion with Time
Step Prediction'
authors: 'Khaled Kahouli, Stefaan Simon Pierre Hessmann, Klaus-Robert Müller, Shinichi Nakajima, Stefan Gugler, Niklas Wolf Andreas Gebauer'
speaker: 
location: ['Technische Universität Berlin','Berlin Institute for the Foundations of Learning and Data']
abstract: 'Molecular relaxation, finding the equilibrium state of a non-equilibrium structure, is an
essential component of computational chemistry to understand reactivity. Classical
force field methods often rely on insufficient local energy minimization, while neural
network force field models require large labeled datasets encompassing both
equilibrium and non-equilibrium structures. As a remedy, we propose MoreRed,
molecular relaxation by reverse diffusion, a novel purely statistical approach where
non-equilibrium structures are seen as noisy instances of the corresponding
equilibrium structures. To enable the denoising of arbitrarily noisy inputs using a
diffusion model, we further introduce a novel diffusion time step predictor. Notably,
MoreRed learns a simpler pseudo potential energy surface instead of the complex
physical potential energy surface. It is trained on a significantly smaller and therefore
computationally cheaper dataset consisting of solely unlabeled equilibrium
structures, avoiding the computation of non-equilibrium structures altogether. We
compare MoreRed favourably to classical force fields, equivariant neural network
force fields, trained on a large dataset of equilibrium and non-equilibrium data, as
well as a semi-empirical tight-binding model. We compare the root-mean-square
deviation between the found equilibrium structures and the reference equilibrium
structures as well as the energy minimum computed for each of them.'
---
