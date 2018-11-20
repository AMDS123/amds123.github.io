---
layout: post
title: "Topology-Aware Non-Rigid Point Cloud Registration"
date: 2018-11-16 20:08:47
categories: arXiv_CV
tags: arXiv_CV Regularization GAN Detection
author: Konstantinos Zampogiannis, Cornelia Fermuller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce a non-rigid registration pipeline for pairs of unorganized point clouds that may be topologically different. Standard warp field estimation algorithms, even under robust, discontinuity-preserving regularization, tend to produce erratic motion estimates on boundaries associated with `close-to-open' topology changes. We overcome this limitation by exploiting backward motion: in the opposite motion direction, a `close-to-open' event becomes `open-to-close', which is by default handled correctly. At the core of our approach lies a general, topology-agnostic warp field estimation algorithm, similar to those employed in recently introduced dynamic reconstruction systems from RGB-D input. We improve motion estimation on boundaries associated with topology changes in an efficient post-processing phase. Based on both forward and (inverted) backward warp hypotheses, we explicitly detect regions of the deformed geometry that undergo topological changes by means of local deformation criteria and broadly classify them as `contacts' or `separations'. Subsequently, the two motion hypotheses are seamlessly blended on a local basis, according to the type and proximity of detected events. Our method achieves state-of-the-art motion estimation accuracy on the MPI Sintel dataset. Experiments on a custom dataset with topological event annotations demonstrate the effectiveness of our pipeline in estimating motion on event boundaries, as well as promising performance in explicit topological event detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07014](http://arxiv.org/abs/1811.07014)

##### PDF
[http://arxiv.org/pdf/1811.07014](http://arxiv.org/pdf/1811.07014)

