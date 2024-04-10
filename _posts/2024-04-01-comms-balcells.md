---
layout: default
link: talks/balcells
categories: [comms]
talknumber: 'D2.04'
talktime: '22.05.2024, 11:30 – 12:00'
speaker: David Balcells
location: 'University of Oslo'
title: 'Generative Machine Learning in the Transition Metal Compound Space'
authors: 'David Balcells'
abstract: 'In this talk, I will give a brief overview of the research done in my group on the field of
machine learning (ML) applied to transition metal complexes (TMCs). I will start with
our initial work on predicting the energy barrier of the elementary steps involved in
homogeneous catalysis[1], followed by our interest on generalizing ML approaches
with tmQM[2], an 86K dataset of TMCs built from CSD data and semi-empirical
quantum calculations, which we thereafter expanded with graph representations
based on DFT and NBO[3]. After this short summary, I will introduce our recent work
on evolutionary learning, including the tmQMg-L ligand library and the PL-MOGA
algorithm[4]. The tmQMg-L library contains 30K diverse and synthesizable ligands with
defined charges and metal coordination modes. The PL-MOGA is a genetic algorithm
allowing for the multiobjective optimization of TMCs within selected regions of the
Pareto front, with fine control over both aim and scope; [Fig. 1]. Used together, these
tools allowed for the exploration and exploitation of vast chemical spaces containing
billions of TMCs. If time allows, I will present our current efforts in coupling the
PL-MOGA to other generative models based on deep graph learning.'
abstractfigure: [{'figure': 'balcells.png', 'caption': 'Pareto front multiobjective optimization with fine control over aim and scope using the PL-MOGA algorithm with the tmQMg-L ligand library[4].'}]
references: [
     ['Friederich, P.; Gomes, G. d. P.; De Bin, R.; Aspuru-Guzik, A.; Balcells, D.',
     'Chem. Sci. 2020', 11, 4584–4601],
     ['Balcells, D.; Skjelstad, B. J.',
     'Chem. Inf. Model.', 2020, 60, 6135–6146],
     ['Kneiding, H.; Lukin, R.; Lang, L.; Reine, S.; Pedersen, T. B.; De Bin, R.; Balcells, D.',
     'Digital Discovery', 2023, 2, 618–633],
     ['Kneiding, H.; Nova, A. Balcells, D.', 'Nat. Comput. Sci.', 2024, 4, accepted],
]
---
