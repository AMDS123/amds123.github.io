---
layout: post
title: "Scan2Mesh: From Unstructured Range Scans to 3D Meshes"
date: 2018-11-26 15:54:15
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Angela Dai, Matthias Nießner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Scan2Mesh, a novel data-driven generative approach which transforms an unstructured and potentially incomplete range scan into a structured 3D mesh representation. The main contribution of this work is a generative neural network architecture whose input is a range scan of a 3D object and whose output is an indexed face set conditioned on the input scan. In order to generate a 3D mesh as a set of vertices and face indices, the generative model builds on a series of proxy losses for vertices, edges, and faces. At each stage, we realize a one-to-one discrete mapping between the predicted and ground truth data points with a combination of convolutional- and graph neural network architectures. This enables our algorithm to predict a compact mesh representation similar to those created through manual artist effort using 3D modeling software. Our generated mesh results thus produce sharper, cleaner meshes with a fundamentally different structure from those generated through implicit functions, a first step in bridging the gap towards artist-created CAD models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10464](https://arxiv.org/abs/1811.10464)

##### PDF
[https://arxiv.org/pdf/1811.10464](https://arxiv.org/pdf/1811.10464)

