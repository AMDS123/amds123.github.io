---
layout: post
title: "DEMEA: Deep Mesh Autoencoders for Non-Rigidly Deforming Objects"
date: 2019-05-24 15:35:37
categories: arXiv_CV
tags: arXiv_CV Face Tracking CNN
author: Edgar Tretschk, Ayush Tewari, Michael Zollh&#xf6;fer, Vladislav Golyanik, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
Mesh autoencoders are commonly used for dimensionality reduction, sampling and mesh modeling. We propose a general-purpose DEep MEsh Autoencoder (DEMEA) which adds a novel embedded deformation layer to a graph-convolutional mesh autoencoder. The embedded deformation layer (EDL) is a differentiable deformable geometric proxy which explicitly models point displacements of non-rigid deformations in a lower dimensional space and serves as a local rigidity regularizer. DEMEA decouples the parameterization of the deformation from the final mesh resolution since the deformation is defined over a lower dimensional embedded deformation graph. We perform a large-scale study on four different datasets of deformable objects. Reasoning about the local rigidity of meshes using EDL allows us to achieve higher-quality results for highly deformable objects, compared to directly regressing vertex positions. We demonstrate multiple applications of DEMEA, including non-rigid 3D reconstruction from depth and shading cues, non-rigid surface tracking, as well as the transfer of deformations over different meshes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10290](http://arxiv.org/abs/1905.10290)

##### PDF
[http://arxiv.org/pdf/1905.10290](http://arxiv.org/pdf/1905.10290)

