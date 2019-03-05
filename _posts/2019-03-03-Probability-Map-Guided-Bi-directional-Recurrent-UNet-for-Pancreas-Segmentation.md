---
layout: post
title: "Probability Map Guided Bi-directional Recurrent UNet for Pancreas Segmentation"
date: 2019-03-03 15:13:33
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jun Li, Xiaozhu Lin, Hui Che, Hao Li, Xiaohua Qian
mathjax: true
---

* content
{:toc}

##### Abstract
Pancreatic cancer is one of the most lethal cancers as incidence approximates mortality. A method for accurately segmenting the pancreas can assist doctors in the diagnosis and treatment of pancreatic cancer. In the current widely used approaches, the 2D method ignores the spatial information of the pancreas, and the 3D model is limited by high resource consumption and GPU memory occupancy. To address these issues, we propose a bi-directional recurrent UNet (PBR-UNet) based on probability graph guidance, which consists of a feature extraction network for efficiently extracting pixel-level probability map as guidance and a bi-directional recurrent network for precise segmentation. The context information of adjacent slices is interconnected to form a chain structure. We integrate contextual information into the entire segmentation network through bi-directional loops to avoid the loss of spatial information in propagation. Additionally, an iterator is applied in the process of propagation, which is used to update the guided probability map after each propagation. We solve the problem that the 2D network loses three-dimensional information and combines the probability map of the adjacent slices into the segmentation as spatial information, avoiding large computational resource consumption caused by direct use of the 3D network. We used Dice similarity coefficients (DSC) to evaluate our approach on NIH pancreatic datasets and eventually achieved a competitive result of 83.02%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00923](http://arxiv.org/abs/1903.00923)

##### PDF
[http://arxiv.org/pdf/1903.00923](http://arxiv.org/pdf/1903.00923)

