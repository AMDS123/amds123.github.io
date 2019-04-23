---
layout: post
title: "Synaptic Partner Assignment Using Attentional Voxel Association Networks"
date: 2019-04-22 16:49:41
categories: arXiv_CV
tags: arXiv_CV Attention CNN
author: Nicholas Turner, Kisuk Lee, Ran Lu, Jingpeng Wu, Dodam Ih, H. Sebastian Seung
mathjax: true
---

* content
{:toc}

##### Abstract
Connectomics aims to recover a complete set of synaptic connections within a dataset imaged by electron microscopy. Most systems for locating synapses use voxelwise classifier models, and train these classifiers to reproduce binary masks of synaptic clefts. However, only recent work has included a way to identify the synaptic partners that communicate at synaptic cleft segments. Here, we present a novel method for associating synaptic cleft segments with their synaptic partners using a convolutional network trained to associate the mask of a cleft with the voxels of its synaptic partners. The network takes the local image context and a mask of a single cleft segment as input. It is trained to produce two volumes of output: one which labels the voxels of the presynaptic partner within the input image, and another similar volume for the postsynaptic partner. The cleft mask acts as an attentional gating signal for the network, in that two clefts with the same local image context often have different partners. We find that an implementation of this approach performs well on a dataset of mouse somatosensory cortex, and evaluate it as part of a combined system to predict both clefts and connections.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09947](http://arxiv.org/abs/1904.09947)

##### PDF
[http://arxiv.org/pdf/1904.09947](http://arxiv.org/pdf/1904.09947)

