---
layout: post
title: "PointGrow: Autoregressively Learned Point Cloud Generation with Self-Attention"
date: 2018-10-12 16:08:32
categories: arXiv_CV
tags: arXiv_CV Attention Face Relation
author: Yongbin Sun, Yue Wang, Ziwei Liu, Joshua E. Siegel, Sanjay E. Sarma
mathjax: true
---

* content
{:toc}

##### Abstract
A point cloud is an agile 3D representation, efficiently modeling an object's surface geometry. However, these surface-centric properties also pose challenges on designing tools to recognize and synthesize point clouds. This work presents a novel autoregressive model, PointGrow, which generates realistic point cloud samples from scratch or conditioned on given semantic contexts. Our model operates recurrently, with each point sampled according to a conditional distribution given its previously-generated points. Since point cloud object shapes are typically encoded by long-range interpoint dependencies, we augment our model with dedicated self-attention modules to capture these relations. Extensive evaluation demonstrates that PointGrow achieves satisfying performance on both unconditional and conditional point cloud generation tasks, with respect to fidelity, diversity and semantic preservation. Further, conditional PointGrow learns a smooth manifold of given image conditions where 3D shape interpolation and arithmetic calculation can be performed inside. Code and models are available at: this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05591](https://arxiv.org/abs/1810.05591)

##### PDF
[https://arxiv.org/pdf/1810.05591](https://arxiv.org/pdf/1810.05591)

