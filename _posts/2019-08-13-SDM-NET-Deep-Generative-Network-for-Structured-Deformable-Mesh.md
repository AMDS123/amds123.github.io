---
layout: post
title: "SDM-NET: Deep Generative Network for Structured Deformable Mesh"
date: 2019-08-13 07:26:15
categories: arXiv_CV
tags: arXiv_CV Face
author: Lin Gao, Jie Yang, Tong Wu, Yu-Jie Yuan, Hongbo Fu, Yu-Kun Lai, Hao Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce SDM-NET, a deep generative neural network which produces structured deformable meshes. Specifically, the network is trained to generate a spatial arrangement of closed, deformable mesh parts, which respect the global part structure of a shape collection, e.g., chairs, airplanes, etc. Our key observation is that while the overall structure of a 3D shape can be complex, the shape can usually be decomposed into a set of parts, each homeomorphic to a box, and the finer-scale geometry of the part can be recovered by deforming the box. The architecture of SDM-NET is that of a two-level variational autoencoder (VAE). At the part level, a PartVAE learns a deformable model of part geometries. At the structural level, we train a Structured Parts VAE (SP-VAE), which jointly learns the part structure of a shape collection and the part geometries, ensuring a coherence between global shape structure and surface details. Through extensive experiments and comparisons with the state-of-the-art deep generative models of shapes, we demonstrate the superiority of SDM-NET in generating meshes with visual quality, flexible topology, and meaningful structures, which benefit shape interpolation and other subsequently modeling tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04520](http://arxiv.org/abs/1908.04520)

##### PDF
[http://arxiv.org/pdf/1908.04520](http://arxiv.org/pdf/1908.04520)

