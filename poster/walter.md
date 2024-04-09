---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img:
title: 'Navigating Chemical Space: An Active Learning Strategy Using Multi-Level Coarse-Graining'
authors: 'Luis Walter and Tristan Bereau'
speaker: 
location: 'Heidelberg University'
abstract: 'The chemical compound space is vast and therefore challenging to explore. To navigate this space, conventional methods directly screen extensive compound libraries. 
However, the size of the library or the resources available for screening limit this strategy. We explore a different approach to chemical space exploration using a multi-level coarse-graining method. 
Our method is based on the idea that transferable coarse-grained models can compress chemical space into different resolutions. Each level of coarse-graining represents the same region of chemical 
space but with varying levels of detail and therefore different numbers of total possible molecules. To discover target compounds, we first use an autoencoder to transform the discrete molecular space 
into a continuous latent space. We thus generate one latent space representation for each level of resolution. Within these latent spaces, we run a multi-level Bayesian optimization-based active learning cycle.
In contrast to most multi-fidelity Bayesian optimization studies, we explore this approach for varying resolutions rather than varying runtime and accuracy. For the active learning cycle, we use molecular dynamics
simulations to calculate binding free energies for the coarse-grained compounds. We use lower fidelity levels for the chemical space exploration and higher fidelity levels for the exploitation phase of our compound 
optimization. We investigate challenges related to latent space structure and the efficiency of the multi-fidelity approach.'
---
