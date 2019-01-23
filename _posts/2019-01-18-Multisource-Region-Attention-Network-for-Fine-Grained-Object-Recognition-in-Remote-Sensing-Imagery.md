---
layout: post
title: "Multisource Region Attention Network for Fine-Grained Object Recognition in Remote Sensing Imagery"
date: 2019-01-18 19:43:33
categories: arXiv_CV
tags: arXiv_CV Attention Classification Recognition
author: Gencer Sumbul, Ramazan Gokberk Cinbis, Selim Aksoy
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained object recognition concerns the identification of the type of an object among a large number of closely related sub-categories. Multisource data analysis, that aims to leverage the complementary spectral, spatial, and structural information embedded in different sources, is a promising direction towards solving the fine-grained recognition problem that involves low between-class variance, small training set sizes for rare classes, and class imbalance. However, the common assumption of co-registered sources may not hold at the pixel level for small objects of interest. We present a novel methodology that aims to simultaneously learn the alignment of multisource data and the classification model in a unified framework. The proposed method involves a multisource region attention network that computes per-source feature representations, assigns attention scores to candidate regions sampled around the expected object locations by using these representations, and classifies the objects by using an attention-driven multisource representation that combines the feature representations and the attention scores from all sources. All components of the model are realized using deep neural networks and are learned in an end-to-end fashion. Experiments using RGB, multispectral, and LiDAR elevation data for classification of street trees showed that our approach achieved 64.2% and 47.3% accuracies for the 18-class and 40-class settings, respectively, which correspond to 13% and 14.3% improvement relative to the commonly used feature concatenation approach from multiple sources.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06403](http://arxiv.org/abs/1901.06403)

##### PDF
[http://arxiv.org/pdf/1901.06403](http://arxiv.org/pdf/1901.06403)

