---
layout: post
title: "View Inter-Prediction GAN: Unsupervised Representation Learning for 3D Shapes by Learning Global Shape Memories to Support Local View Predictions"
date: 2018-11-07 03:25:50
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Represenation_Learning RNN Prediction
author: Zhizhong Han, Mingyang Shang, Yu-Shen Liu, Matthias Zwicker
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present a novel unsupervised representation learning approach for 3D shapes, which is an important research challenge as it avoids the manual effort required for collecting supervised data. Our method trains an RNN-based neural network architecture to solve multiple view inter-prediction tasks for each shape. Given several nearby views of a shape, we define view inter-prediction as the task of predicting the center view between the input views, and reconstructing the input views in a low-level feature space. The key idea of our approach is to implement the shape representation as a shape-specific global memory that is shared between all local view inter-predictions for each shape. Intuitively, this memory enables the system to aggregate information that is useful to better solve the view inter-prediction tasks for each shape, and to leverage the memory as a view-independent shape representation. Our approach obtains the best results using a combination of L_2 and adversarial losses for the view inter-prediction task. We show that VIP-GAN outperforms state-of-the-art methods in unsupervised 3D feature learning on three large scale 3D shape benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.02744](http://arxiv.org/abs/1811.02744)

##### PDF
[http://arxiv.org/pdf/1811.02744](http://arxiv.org/pdf/1811.02744)

