---
layout: talkpage
categories: [comms]
talknumber: D2.10
talktime: '22.05.2024, 17:00 – 17:30'
title: 'Spicy – A Functional Computational Framework for Multilayer Fragment Methods'
authors: 'Phillip Seeber, Sebastian Seidenath, Stefanie Gräfe'
speaker: Phillip Seeber 
location: 'Friedrich Schiller University Jena'
abstract: 'Modern ab initio methods provide unprecedented accuracy for a variety of chemical problems. However, their steep scaling with system size often limits their applicability to relatively small molecules. Even though the rise of linear scaling ab initio methods allows their application to systems with thousands of atoms, important aspects remain unsolved. First, a suitable computational method for both the desired physical property and the type of chemical system needs to be chosen. Not all of them arelinearly scalable. Second, the crossover, where linear scaling methods become more efficient than their conventional counterparts, can arise at already too high computational costs to study dynamic phenomena.
In this contribution, we present our program Spicy, a computational framework for multilayer fragment methods. Combining the concepts of multilayer methods, where each layer is treated at a different, suitable level of theory, and fragment methods, breaking down large systems into smaller parts and combining their results, Spicy implements the multilayer fragment combination range (ML-FCR) formalism. Without altering the underlying computational methods, a flexible partitioning of the system and assignment of suitable methods to each fragment is possible, enabling a tailored and efficient treatment of systems with chemically diverse components.
An important advantage of fragment methods is their inherit ability to utilise network-based parallelism and distribute calculations over many computer nodes. Currently, the individual components for heavily parallel calculations are being developed and implemented in Spicy, namely a Nix-inspired content addressable storage to manage persistent data, a scheduling system based in MPI for distributed quantum and molecular mechanical calculations, as well as an interface to the DBCSR library for distributed block sparse array computations, enabling efficient response tensor and wave function transformations.'
references: [["P. Seeber, S. Seidenath, J. Steinmetzer, S. Gräfe", WIREs Comp. Mol. Science. ,2022, 13.3, e1644]
    
]
---
