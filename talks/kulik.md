---
layout: talkpage
categories: [keynote]
talknumber: D1.02
talktime: '21.05.2024, 11:00 – 11:45'
speaker: Prof. Heather Kulik
authors: Prof. Heather Kulik
img: heather_kulik.png
location: 'Department of Chemical Engineering and Department of Chemistry, Massachusetts
Institute of Technology, Cambridge, MA 02139'
title: 'Machine Learning for Open Shell Transition Metal
Complex and Metal-Organic Framework Discovery'
abstract: ['I will discuss our efforts to use machine learning (ML) to accelerate the computational tailoring
and design of open shell transition metal homogeneous catalysts as well as metal-organic
framework (MOF) materials for catalysis and gas separations/storage. One limitation in a
challenging materials space such as open shell transition metal chemistry present in the open
metal sites of many homogeneous catalysts and most catalytically active MOFs is that ML
models and ML-accelerated high-throughput screening traditionally rely on density functional
theory (DFT) for data generation, but DFT is both computationally demanding and prone to
errors that limit its accuracy in predicting new MOFs.',
'In the realm of MOFs, I will describe how we have curated a dataset of thousands of
MOFs[1,2] that have been experimentally synthesized and used this data to train ML models
to predict experimentally reported measures of stability. These models predict experimental
thermal stability and activation stability, which would be extremely difficult to predict using
computational modeling. I will describe how we have leveraged these models to then screen
for mechanically stable materials as well as stable catalysts in the direct conversion of
methane to methanol[3]. I will also describe how we have used these models to accelerate
the discovery of novel stable MOFs, creating a dataset of transition metal complexes enriched
with stability and diversity 1-2 orders of magnitude beyond what is typically included in most
hypothetical MOF datasets[4].',
'In the realm of open shell homogeneous catalysis, I will describe our efforts to
accelerate the discovery of single site catalysts and materials with machine learning[5,6].
Despite decades of effort, no earth-abundant homogeneous catalysts have been discovered
that can selectively catalyze the partial oxidation of methane to methanol. In open shell
transition metal catalysis, we show how conventionally used scaling relations are easily
disrupted, motivating the development of independent ML models to predict multiple reaction
energies that can be independently optimized[7]. We have used our open-source toolkit
molSimplify to accelerate the discovery of candidate catalysts with ML. We exploit active
learning to optimize methane activation and methanol release calculated with ML-accelerated
DFT in a space of 16M candidate catalysts including novel macrocycles[6]. I will demonstrate
how this approach accelerates the discovery of new design principles by at least a few orders
of magnitude, leading to conclusions that are often unexpected[6].']
references: [
    [
        'A. Nandy, C. Duan, and H. J. Kulik',
        J. Am. Chem. Soc., 2021, 143, 17535-17547
    ],
    [
        'A. Nandy, G. G. Terrones, N. Arunachalam, C. Duan, D. W. Kastner, and H. J. Kulik',
        Scientific Data, 2022, 9, 74
    ],
    [
        'H. Adamji, A. Nandy, I. Kevlishvili, Y. Roman-Leshkov, and H. J. Kulik',
        J. Am. Chem. Soc., 2023, 145, 14365–14378
    ],
    [
        'A. Nandy, et al.',
        Matter, 2023, 6, 1585-1603
    ],
    [
        'A. Nandy, et al.',
        ACS Catalysis, 2019, 9, 8243-8255
    ],
    [
        'A. Nandy, C. Duan, C. Goffinet, and H. J. Kulik',
        JACS Au, 2022, 2, 1200-1213
    ],
    [
        'A. Nandy and H. J. Kulik',
        ACS Catalysis, 2020, 10, 15033-15047
    ]
]
abstractfigure: false
---
