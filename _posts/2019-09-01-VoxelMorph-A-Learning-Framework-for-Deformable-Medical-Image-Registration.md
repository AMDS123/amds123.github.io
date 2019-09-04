---
layout: post
title: "VoxelMorph: A Learning Framework for Deformable Medical Image Registration"
date: 2019-09-01 21:57:19
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Guha Balakrishnan, Amy Zhao, Mert R. Sabuncu, John Guttag, Adrian V. Dalca
mathjax: true
---

* content
{:toc}

##### Abstract
We present VoxelMorph, a fast learning-based framework for deformable, pairwise medical image registration. Traditional registration methods optimize an objective function for each pair of images, which can be time-consuming for large datasets or rich deformation models. In contrast to this approach, and building on recent learning-based methods, we formulate registration as a function that maps an input image pair to a deformation field that aligns these images. We parameterize the function via a convolutional neural network (CNN), and optimize the parameters of the neural network on a set of images. Given a new pair of scans, VoxelMorph rapidly computes a deformation field by directly evaluating the function. In this work, we explore two different training strategies. In the first (unsupervised) setting, we train the model to maximize standard image matching objective functions that are based on the image intensities. In the second setting, we leverage auxiliary segmentations available in the training data. We demonstrate that the unsupervised model's accuracy is comparable to state-of-the-art methods, while operating orders of magnitude faster. We also show that VoxelMorph trained with auxiliary data improves registration accuracy at test time, and evaluate the effect of training set size on registration. Our method promises to speed up medical image analysis and processing pipelines, while facilitating novel directions in learning-based registration and its applications. Our code is freely available at voxelmorph.csail.mit.edu.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.05231](http://arxiv.org/abs/1809.05231)

##### PDF
[http://arxiv.org/pdf/1809.05231](http://arxiv.org/pdf/1809.05231)

