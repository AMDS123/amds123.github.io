---
layout: post
title: "TextureNet: Consistent Local Parametrizations for Learning from High-Resolution Signals on Meshes"
date: 2018-11-30 19:01:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Semantic_Segmentation
author: Jingwei Huang, Haotian Zhang, Li Yi, Thomas Funkhouser, Matthias Nie&#xdf;ner, Leonidas Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce, TextureNet, a neural network architecture designed to extract features from high-resolution signals associated with 3D surface meshes (e.g., color texture maps). The key idea is to utilize a 4-rotational symmetric (4-RoSy) field to define a domain for convolution on a surface. Though 4-RoSy fields have several properties favorable for convolution on surfaces (low distortion, few singularities, consistent parameterization, etc.), orientations are ambiguous up to 4-fold rotation at any sample point. So, we introduce a new convolutional operator invariant to the 4-RoSy ambiguity and use it in a network to extract features from high-resolution signals on geodesic neighborhoods of a surface. In comparison to alternatives, such as PointNet based methods which lack a notion of orientation, the coherent structure given by these neighborhoods results in significantly stronger features. As an example application, we demonstrate the benefits of our architecture for 3D semantic segmentation of textured 3D meshes. The results show that our method outperforms all existing methods on the basis of mean IoU by a significant margin in both geometry-only (6.4%) and RGB+Geometry (6.9-8.2%) settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00020](http://arxiv.org/abs/1812.00020)

##### PDF
[http://arxiv.org/pdf/1812.00020](http://arxiv.org/pdf/1812.00020)

