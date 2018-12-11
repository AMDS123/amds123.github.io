---
layout: post
title: "Exclusive Independent Probability Estimation using Deep 3D Fully Convolutional DenseNets: Application to IsoIntense Infant Brain MRI Segmentation"
date: 2018-12-10 05:55:31
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Deep_Learning Prediction
author: Seyed Raein Hashemi, Sanjay P. Prabhu, Simon K. Warfield, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
The most recent fast and accurate image segmentation methods are built upon fully convolutional deep neural networks. In this paper, we propose new deep learning strategies for DenseNets to improve segmenting images with subtle differences in intensity values and features. We aim to segment brain tissue on infant brain MRI at about 6 months of age where white matter and gray matter of the developing brain show similar T1 and T2 relaxation times, thus appear to have similar intensity values on both T1- and T2-weighted MRI scans. Brain tissue segmentation at this age is, therefore, very challenging. To this end, we propose an exclusive multi-label training strategy to segment the mutually exclusive brain tissues with similarity loss functions that automatically balance the training based on class prevalence. Using our proposed training strategy based on similarity loss functions and patch prediction fusion we decrease the number of parameters in the network, reduce the complexity of the training process focusing the attention on less number of tasks, while mitigating the effects of data imbalance between labels and inaccuracies near patch borders. By taking advantage of these strategies we were able to perform fast image segmentation (90 seconds per 3D volume), using a network with less parameters than many state-of-the-art networks, overcoming issues such as 3Dvs2D training and large vs small patch size selection, while achieving the top performance in segmenting brain tissue among all methods tested in first and second round submissions of the isointense infant brain MRI segmentation (iSeg) challenge according to the official challenge test results. Our proposed strategy improves the training process through balanced training and by reducing its complexity while providing a trained model that works for any size input image and is fast and more accurate than many state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08168](http://arxiv.org/abs/1809.08168)

##### PDF
[http://arxiv.org/pdf/1809.08168](http://arxiv.org/pdf/1809.08168)

