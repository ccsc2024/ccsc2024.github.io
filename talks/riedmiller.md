---
layout: talkpage
categories: [speedtalk]
talknumber: 'D1.09'
talktime: '21.05.2024, 16:45 – 17:00'
title: 'KIMMDY - Kinetic Monte Carlo Molecular Dynamics'
authors: 'Kai Riedmiller, Jannik Buhr, Eric Hartmann, Frauke Gräter'
speaker: Kai Riedmiller
location: 'Heidelberg University'
abstract: 'Molecular Dynamics (MD) simulations are an established and reliable way to gain insight into molecular systems. However, they do not allow for reactions to occur during the simulation. Alternative methods are often limited to much smaller system sizes compared to MD. Density Functional Theory (DFT) becomes impractical for systems exceeding a few dozen atoms. Reactive force fields also fall short of matching the efficiency of highly-optimized MD simulations.
KIMMDY is a novel approach that maintains the speed of MD, while incorporating reactions into the simulation via a kinetic Monte Carlo (KMC) approach.
We run standard MD using GROMACS, check with KMC for possible reactions, and change the topology of the systems accordingly on the fly, in a completely automated manner. Multiple reaction steps can be performed, with MD steps in between, without any need for user intervention in between.
We support arbitrary reactions, as long as reaction rates can be obtained in some way for the reaction of interest. While this would have been a major challenge in the past, machine learning (ML) models can now be trained to predict reaction rates based on a finite set of DFT-calculated rates.
KIMMDY is designed as an extensible framework that supports new reactions through a plugin system. Out of the box, we support hydrogen atom transfer (HAT) reactions, and homolysis to simulate the rupture of a (bio-)polymer under force. [1,2]
As the result of a reaction might not be contained in the standard force-field, KIMMDY supports on-the-fly reparametrization powered by a ML model called GRAPPA. [3] Through GRAPPA, accurate parameters for novel residues can be obtained, with better accuracy compared to a general force field.
With KIMMDY, we hope to provide an easy to use, extensible platform for reactive MD simulations. KIMMDY is Open-Source software available through GitHub. [4]'
references: [ ["Riedmiller, K.; Reiser, P.; Bobkova, E.; Maltsev, K.; Gryn’ova, G.; Friederich, P.; Gräter", F. Substituting Density Functional Theory in Reaction Barrier Calculations for Hydrogen Atom Transfer in Proteins. Chem. Sci. ,2024, 15, 2518–2527],
["Rennekamp, B.; Kutzki, F.; Obarska-Kosinska, A.; Zapp, C.; Gräter", F. Hybrid Kinetic Monte Carlo/Molecular Dynamics Simulations of Bond Scissions in Proteins. J. Chem. Theory Computat. ,2020, 16, 553-563],
[GRAPPA,"", 2024, https://github.com/hits-mbm-dev/grappa],
[KIMMDY,"", 2024, https://github.com/hits-mbm-dev/kimmdy]
]
---
