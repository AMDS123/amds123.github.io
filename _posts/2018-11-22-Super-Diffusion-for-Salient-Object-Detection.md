---
layout: post
title: "Super Diffusion for Salient Object Detection"
date: 2018-11-22 06:50:28
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Detection Relation
author: Peng Jiang, Zhiyi Pan, Nuno Vasconcelos, Baoquan Chen, Jingliang Peng
mathjax: true
---

* content
{:toc}

##### Abstract
One major branch of saliency object detection methods is diffusion-based which construct a graph model on a given image and diffuse seed saliency values to the whole graph by a diffusion matrix. While their performance is sensitive to specific feature spaces and scales used for the diffusion matrix definition, little work has been published to systematically promote the robustness and accuracy of salient object detection under the generic mechanism of diffusion. In this work, we firstly present a novel view of the working mechanism of the diffusion process based on mathematical analysis, which reveals that the diffusion process is actually computing the similarity of nodes with respect to the seeds based on diffusion maps. Following this analysis, we propose super diffusion, a novel inclusive learning-based framework for salient object detection, which makes the optimum and robust performance by integrating a large pool of feature spaces, scales and even features originally computed for non-diffusion-based salient object detection. A closed-form solution of the optimal parameters for the integration is determined through supervised learning. At the local level, we propose to promote each individual diffusion before the integration. Our mathematical analysis reveals the close relationship between saliency diffusion and spectral clustering. Based on this, we propose to re-synthesize each individual diffusion matrix from the most discriminative eigenvectors and the constant eigenvector (for saliency normalization). The proposed framework is implemented and experimented on prevalently used benchmark datasets, consistently leading to state-of-the-art performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09038](http://arxiv.org/abs/1811.09038)

##### PDF
[http://arxiv.org/pdf/1811.09038](http://arxiv.org/pdf/1811.09038)

