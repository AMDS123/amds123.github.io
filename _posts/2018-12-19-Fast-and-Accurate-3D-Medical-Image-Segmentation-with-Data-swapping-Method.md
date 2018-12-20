---
layout: post
title: "Fast and Accurate 3D Medical Image Segmentation with Data-swapping Method"
date: 2018-12-19 08:49:50
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Haruki Imai, Samuel Matzek, Tung D. Le, Yasushi Negishi, Kiyokuni Kawachiya
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network models used for medical image segmentation are large because they are trained with high-resolution three-dimensional (3D) images. Graphics processing units (GPUs) are widely used to accelerate the trainings. However, the memory on a GPU is not large enough to train the models. A popular approach to tackling this problem is patch-based method, which divides a large image into small patches and trains the models with these small patches. However, this method would degrade the segmentation quality if a target object spans multiple patches. In this paper, we propose a novel approach for 3D medical image segmentation that utilizes the data-swapping, which swaps out intermediate data from GPU memory to CPU memory to enlarge the effective GPU memory size, for training high-resolution 3D medical images without patching. We carefully tuned parameters in the data-swapping method to obtain the best training performance for 3D U-Net, a widely used deep neural network model for medical image segmentation. We applied our tuning to train 3D U-Net with full-size images of 192 x 192 x 192 voxels in brain tumor dataset. As a result, communication overhead, which is the most important issue, was reduced by 17.1%. Compared with the patch-based method for patches of 128 x 128 x 128 voxels, our training for full-size images achieved improvement on the mean Dice score by 4.48% and 5.32 % for detecting whole tumor sub-region and tumor core sub-region, respectively. The total training time was reduced from 164 hours to 47 hours, resulting in 3.53 times of acceleration.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07816](http://arxiv.org/abs/1812.07816)

##### PDF
[http://arxiv.org/pdf/1812.07816](http://arxiv.org/pdf/1812.07816)

