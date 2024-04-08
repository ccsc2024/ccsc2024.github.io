---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
speaker: Eric Hartmann
img: hartmann.png
location: [
    HITS gGmbH (DE),
    Heidelberg University (DE)
]
title: 'On-the-fly reparametrization for hybrid MD/MC simulations in KIMMDY'
authors: 'Eric Hartmann, Kai Riedmiller, Jannik Buhr, Frauke Gräter'
abstract: [
    'In Molecular Dynamics (MD), standard force fields inherently lack the capacity for
simulating chemical reactions. Among many other methods such as QM/MM, hybrid
MD/MC simulations can be used for reactive systems[1]. With such a setup, changes
within the molecular system require an adjustment of force field parameters to
accurately reflect the current system state.',
    'Here, we present how the open-source framework KIMMDY[2] handles on-the-fly
reparametrization after reactions. This parametrization strategy allows for automated
consecutive MD simulations of reactive systems within a KIMMDY run.',
    'From a MD engine perspective, the molecule parameters as well as its coordinates
need to be adapted to continue simulating from the product state. Addressing this,
we’ve designed reaction steps in KIMMDY. To accommodate changes in parameters,
the system’s connectivity can be adjusted through bond breaking and forming steps,
followed by reparametrization with GRAPPA[3]. Additionally, for adjustments of
coordinates, KIMMDY features a "place atom" step, allowing for the repositioning of
atoms. This is complemented by a relaxation MD step, which may include slow
growth parameter transitions to smoothly integrate parameter changes, ensuring the
system reaches its intended state without artifacts. Different reaction scenarios are
explored to highlight the expressivity of KIMMDY reaction steps.'
]
references: [
    [
        'Rennekamp, B.; Kutzki, F.; Obarska-Kosinska, A.; Zapp, C.; Gräter, F.',
        J. Chem. Theory Computat., 2020, 16, 553-563
        'Hybrid Kinetic Monte Carlo/Molecular Dynamics Simulations of Bond Scissions in Proteins'
    ],
    [
        KIMMDY, false, 2024, false, '<a href="https://github.com/hits-mbm-dev/kimmdy">https://github.com/hits-mbm-dev/kimmdy</a>'
        ],
    [
        GRAPPA, false, 2024, false, <a href="https://github.com/hits-mbm-dev/grappa">https://github.com/hits-mbm-dev/grappa</a>
        ]
]
---
