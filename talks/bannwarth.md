---
layout: talkpage
categories: [comms]
talknumber: 'D4.05'
talktime: '24.05.2024, 12:00 – 12:30'
speaker: Christoph Bannwarth
location: 'Aachen University'
title: 'MolBar: A Molecular Identifier for Inorganic and Organic
Molecules with Full Support of Stereoisomerism'
authors: 'Nils van Staalduinen, Christoph Bannwarth'
abstract: 'When a new molecular structure is to be registered to a chemical structure database,
a duplicate check is essential to ensure the integrity of the database. Existing
identifiers like SMILES and InChI have limitations when it comes to inorganic
compounds or those with non-central stereochemistry.
To address this limitation, we introduce a novel chemical identifier called the
Molecular Barcode (MolBar), which can uniquely identify a molecule based on its
Cartesian coordinates. In this approach, fragments are conceptualized using a
specialized force field and characterized by physically inspired matrices derived
solely from atomic positions. The resulting permutation-invariant representation is
constructed from the eigenvalue spectra, providing comprehensive information on
both bonding and stereochemistry. Hence, MolBar encompasses a wider spectrum
of chiral types, including axial and planar chirality, offering a unified description
applicable to both organic and inorganic chemistry alike.
The robustness of MolBar is demonstrated through duplication and permutation
invariance tests on the Molecule3D dataset of 3.9 million molecules. A Python
implementation is available as open source and is also listed on PyPI for broader
accessibility. The intended use is for duplicate removal in molecular database as well as unique molecule identification in chemical space exploration.'
abstractfigure: [{'figure': 'bannwarth.png', 'caption': 'Workflow to generate the unique MolBar identifier from Cartesian coordinates as
input. The final identifier is a concatenation of rounded eigenvalue spectra of different
matrices describing the topology, as well as relative and absolute configuration.'}]
references: [
    [
        'N. van Staalduinen, C. Bannwarth', ChemRxiv, 2024, false, 'DOI 10.26434/chemrxiv-2024-k40v5'
    ],
    [
        '<a href="https://git.rwth-aachen.de/bannwarthlab/molbar">https://git.rwth-aachen.de/bannwarthlab/molbar</a> (last accessed 03.04.2024)'
    ]
]
---
