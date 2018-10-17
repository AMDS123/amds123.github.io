---
layout: post
title: "Deep Recurrent Level Set for Segmenting Brain Tumors"
date: 2018-10-10 21:33:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: T. Hoang Ngan Le, Raajitha Gummadi, Marios Savvides
mathjax: true
---

* content
{:toc}

##### Abstract
Variational Level Set (VLS) has been a widely used method in medical segmentation. However, segmentation accuracy in the VLS method dramatically decreases when dealing with intervening factors such as lighting, shadows, colors, etc. Additionally, results are quite sensitive to initial settings and are highly dependent on the number of iterations. In order to address these limitations, the proposed method incorporates VLS into deep learning by defining a novel end-to-end trainable model called as Deep Recurrent Level Set (DRLS). The proposed DRLS consists of three layers, i.e, Convolutional layers, Deconvolutional layers with skip connections and LevelSet layers. Brain tumor segmentation is taken as an instant to illustrate the performance of the proposed DRLS. Convolutional layer learns visual representation of brain tumor at different scales. Since brain tumors occupy a small portion of the image, deconvolutional layers are designed with skip connections to obtain a high quality feature map. Level-Set Layer drives the contour towards the brain tumor. In each step, the Convolutional Layer is fed with the LevelSet map to obtain a brain tumor feature map. This in turn serves as input for the LevelSet layer in the next step. The experimental results have been obtained on BRATS2013, BRATS2015 and BRATS2017 datasets. The proposed DRLS model improves both computational time and segmentation accuracy when compared to the the classic VLS-based method. Additionally, a fully end-to-end system DRLS achieves state-of-the-art segmentation on brain tumors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04752](https://arxiv.org/abs/1810.04752)

##### PDF
[https://arxiv.org/pdf/1810.04752](https://arxiv.org/pdf/1810.04752)

