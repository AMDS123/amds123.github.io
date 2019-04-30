---
layout: post
title: "Self-Attention Capsule Networks for Image Classification"
date: 2019-04-29 08:04:46
categories: arXiv_CV
tags: arXiv_CV Salient Attention CNN Image_Classification Classification Relation
author: Assaf Hoogi, Brian Wilcox, Yachee Gupta, Daniel L. Rubin
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel architecture for image classification, called Self-Attention Capsule Networks (SACN). SACN is the first model that incorporates the Self-Attention mechanism as an integral layer within the Capsule Network (CapsNet). While the Self-Attention mechanism selects the more dominant image regions to focus on, the CapsNet analyzes the relevant features and their spatial correlations inside these regions only. The features are extracted in the convolutional layer. Then, the Self-Attention layer learns to suppress irrelevant regions based on features analysis, and highlights salient features useful for a specific task. The attention map is then fed into the CapsNet primary layer that is followed by a classification layer. The SACN proposed model was designed to use a relatively shallow CapsNet architecture to reduce computational load, and compensates for the absence of a deeper network by using the Self-Attention module to significantly improve the results. The proposed Self-Attention CapsNet architecture was extensively evaluated on five different datasets, mainly on three different medical sets, in addition to the natural MNIST and SVHN. The model was able to classify images and their patches with diverse and complex backgrounds better than the baseline CapsNet. As a result, the proposed Self-Attention CapsNet significantly improved classification performance within and across different datasets and outperformed the baseline CapsNet not only in classification accuracy but also in robustness.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12483](http://arxiv.org/abs/1904.12483)

##### PDF
[http://arxiv.org/pdf/1904.12483](http://arxiv.org/pdf/1904.12483)

