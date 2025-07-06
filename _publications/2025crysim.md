---
title: "CRYSIM: Prediction of Symmetric Structures of Large Crystals with GPU-based Ising Machines"
collection: publications
permalink: /publication/2025crysim
excerpt: 'Authors: Chen Liang, Diptesh Das, Jiang Guo, Ryo Tamura, **Zetian Mao**, Koji Tsuda'
date: 2025-04-09
venue: 'Arxiv'
---

# DOI

[https://https://https://arxiv.org/abs/2504.06878](https://https://arxiv.org/abs/2504.06878)

# Abstract

Solving black-box optimization problems with Ising machines is increasingly common in materials science. However, their application to crystal structure prediction (CSP) is still ineffective due to symmetry agnostic encoding of atomic coordinates. We introduce CRYSIM, an algorithm that encodes the space group, the Wyckoff positions combination, and coordinates of independent atomic sites as separate variables. This encoding reduces the search space substantially by exploiting the symmetry in space groups. When CRYSIM is interfaced to Fixstars Amplify, a GPU-based Ising machine, its prediction performance was competitive with CALYPSO and Bayesian optimization for crystals containing more than 150 atoms in a unit cell. Although it is not realistic to interface CRYSIM to current small-scale quantum devices, it has the potential to become the standard CSP algorithm in the coming quantum age.