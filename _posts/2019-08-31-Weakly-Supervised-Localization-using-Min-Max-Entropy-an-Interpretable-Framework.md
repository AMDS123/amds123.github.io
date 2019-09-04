---
layout: post
title: "Weakly Supervised Localization using Min-Max Entropy: an Interpretable Framework"
date: 2019-08-31 14:54:43
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Weakly_Supervised CNN Classification Deep_Learning Prediction
author: Soufiane Belharbi, J&#xe9;r&#xf4;me Rony, Jose Dolz, Ismail Ben Ayed, Luke McCaffrey, Eric Granger
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object localization (WSOL) models aim to locate objects of interest in an image after being trained only on data with coarse image level labels. Deep learning models for WSOL rely typically on convolutional attention maps with no constraints on the regions of interest which allows them to select any region, making them vulnerable to false positive regions. This issue occurs in many application domains, e.g., medical image analysis, where interpretability is central to the prediction. In order to improve the localization reliability, we propose a deep learning framework for WSOL with pixel level localization. It is composed of two sequential sub-networks: a localizer that localizes regions of interest; followed by a classifier that classifies them. Within its end-to-end training, we incorporate the prior knowledge stating that in an agnostic-class setup an image is more likely to contain relevant --object of interest-- and irrelevant regions --noise--. Based on the conditional entropy (CE) measured at the classifier, the localizer is driven to spot relevant regions (low CE), and irrelevant regions (high CE). Our framework is able to recover large discriminative regions using our recursive erasing algorithm that we incorporate within the backpropagation during training. Moreover, the framework handles intrinsically multi-instances. Experimental results on public datasets with medical images (GlaS colon cancer) and natural images (Caltech-UCSD Birds-200-2011, Oxford flower 102) show that, compared to state of the art WSOL methods, our framework can provide significant improvements in terms of image-level classification, pixel-level localization, and robustness to overfitting when dealing with few training samples. A public reproducible PyTorch implementation is provided in: https://github.com/sbelharbi/wsol-min-max-entropy-interpretability .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12934](http://arxiv.org/abs/1907.12934)

##### PDF
[http://arxiv.org/pdf/1907.12934](http://arxiv.org/pdf/1907.12934)

