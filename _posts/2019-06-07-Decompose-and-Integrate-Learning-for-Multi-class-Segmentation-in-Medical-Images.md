---
layout: post
title: "Decompose-and-Integrate Learning for Multi-class Segmentation in Medical Images"
date: 2019-06-07 05:10:35
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Yizhe Zhang, Michael T. C. Ying, Danny Z. Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation maps of medical images annotated by medical experts contain rich spatial information. In this paper, we propose to decompose annotation maps to learn disentangled and richer feature transforms for segmentation problems in medical images. Our new scheme consists of two main stages: decompose and integrate. Decompose: by annotation map decomposition, the original segmentation problem is decomposed into multiple segmentation sub-problems; these new segmentation sub-problems are modeled by training multiple deep learning modules, each with its own set of feature transforms. Integrate: a procedure summarizes the solutions of the modules in the previous stage; a final solution is then formed for the original segmentation problem. Multiple ways of annotation map decomposition are presented and a new end-to-end trainable K-to-1 deep network framework is developed for implementing our proposed "decompose-and-integrate" learning scheme. In experiments, we demonstrate that our decompose-and-integrate segmentation, utilizing state-of-the-art fully convolutional networks (e.g., DenseVoxNet in 3D and CUMedNet in 2D), improves segmentation performance on multiple 3D and 2D datasets. Ablation study confirms the effectiveness of our proposed learning scheme for medical images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.02901](http://arxiv.org/abs/1906.02901)

##### PDF
[http://arxiv.org/pdf/1906.02901](http://arxiv.org/pdf/1906.02901)

