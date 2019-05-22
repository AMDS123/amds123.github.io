---
layout: post
title: "Task Decomposition and Synchronization for Semantic Biomedical Image Segmentation"
date: 2019-05-21 15:59:04
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Semantic_Segmentation Classification Prediction
author: Xuhua Ren, Lichi Zhang, Sahar Ahmad, Dong Nie, Fan Yang, Lei Xiang, Qian Wang, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation is essentially important to biomedical image analysis. Many recent works mainly focus on integrating the Fully Convolutional Network (FCN) architecture with sophisticated convolution implementation and deep supervision. In this paper, we propose to decompose the single segmentation task into three subsequent sub-tasks, including (1) pixel-wise image segmentation, (2) prediction of the class labels of the objects within the image, and (3) classification of the scene the image belonging to. While these three sub-tasks are trained to optimize their individual loss functions of different perceptual levels, we propose to let them interact by the task-task context ensemble. Moreover, we propose a novel sync-regularization to penalize the deviation between the outputs of the pixel-wise segmentation and the class prediction tasks. These effective regularizations help FCN utilize context information comprehensively and attain accurate semantic segmentation, even though the number of the images for training may be limited in many biomedical applications. We have successfully applied our framework to three diverse 2D/3D medical image datasets, including Robotic Scene Segmentation Challenge 18 (ROBOT18), Brain Tumor Segmentation Challenge 18 (BRATS18), and Retinal Fundus Glaucoma Challenge (REFUGE18). We have achieved top-tier performance in all three challenges.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08720](http://arxiv.org/abs/1905.08720)

##### PDF
[http://arxiv.org/pdf/1905.08720](http://arxiv.org/pdf/1905.08720)

