---
layout: post
title: "Deep Features for Tissue-Fold Detection in Histopathology Images"
date: 2019-03-17 01:25:10
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Morteza Babaie, H.R. Tizhoosh
mathjax: true
---

* content
{:toc}

##### Abstract
Whole slide imaging (WSI) refers to the digitization of a tissue specimen which enables pathologists to explore high-resolution images on a monitor rather than through a microscope. The formation of tissue folds occur during tissue processing. Their presence may not only cause out-of-focus digitization but can also negatively affect the diagnosis in some cases. In this paper, we have compared five pre-trained convolutional neural networks (CNNs) of different depths as feature extractors to characterize tissue folds. We have also explored common classifiers to discriminate folded tissue against the normal tissue in hematoxylin and eosin (H\&amp;E) stained biopsy samples. In our experiments, we manually select the folded area in roughly 2.5mm $\times$ 2.5mm patches at $20$x magnification level as the training data. The ``DenseNet'' with 201 layers alongside an SVM classifier outperformed all other configurations. Based on the leave-one-out validation strategy, we achieved $96.3\%$ accuracy, whereas with augmentation the accuracy increased to $97.2\%$. We have tested the generalization of our method with five unseen WSIs from the NIH (National Cancer Institute) dataset. The accuracy for patch-wise detection was $81\%$. One folded patch within an image suffices to flag the entire specimen for visual inspection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07011](http://arxiv.org/abs/1903.07011)

##### PDF
[http://arxiv.org/pdf/1903.07011](http://arxiv.org/pdf/1903.07011)

