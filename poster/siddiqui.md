---
layout: talkpage
categories: []
talknumber: '?'
talktime: '?'
img:
title: 'Enhancing Organic Solar Cell Development: Leveraging Chemical Variational Autoencoders and Self-Prepared Datasets for Inverse Design of Donor-Acceptor Molecules'
authors: 'Hamza Siddiqui, Tahsin Usmani'
speaker: 
location: 'Integral University, Lucknow'
abstract: 'In this study, we introduce a novel inverse design model based on the chemical variational autoencoder (VAE)[1], designed to generate chemical structures (x) of Donors and 
Acceptors with desired properties (y) derived from quantitative structure–property relationships obtained via rdkit and Mordred descriptors. Our methodology utilizes a self-prepared 
dataset gathered from literature sources for training purposes. Within this framework, an encoder is employed to convert simplified molecular input line entry system (SMILES) strings 
into SELFIES format, and subsequently into latent variables (z). Conversely, a decoder is utilized to map z back to SELFIES strings, which are then converted back to SMILES representations.
The reconstruction loss function used in training the chemical variational autoencoder integrates constraints computed within the loss function, utilizing standard rdkit and Mordred descriptors 
on respective descriptors that exhibit high SHAP values. These descriptors are identified through a random forest (RF) classification model, employed to categorize the dataset into high 
efficiency and low efficiency donor: acceptor pairs. Consequently, newly generated donor and acceptor molecules are penalized proportionally to the deviation of their respective values 
falling outside the desired range.
During training, the chemical VAE learns to minimize the combined loss, which encompasses both the traditional reconstruction loss and the penalty for violating the descriptor constraints. 
In the event of a generated molecule violating the molecular weight constraint, an additional mechanism is employed, involving the addition or removal of functional groups to modify the 
molecule and bring it within the desired range. This approach affords control over the properties of the generated molecules. Our findings validate the efficacy of chemical variational 
autoencoders and SELFIES in generating donor: acceptor molecules within specified descriptor ranges and specific fingerprints, thus facilitating the development of high-efficiency organic solar cells.'
references: [["R. Gómez-Bombarelli et al.", "“Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules,” ACS Cent. Sci., vol. 4, no. 2, pp. 268–276", 2018, "doi: 10.1021/acscentsci.7b00572"]
]
---
