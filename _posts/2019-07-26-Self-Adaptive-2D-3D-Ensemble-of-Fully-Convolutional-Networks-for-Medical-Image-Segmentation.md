---
layout: post
title: "Self-Adaptive 2D-3D Ensemble of Fully Convolutional Networks for Medical Image Segmentation"
date: 2019-07-26 14:14:53
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Maria G. Baldeon Calisto, Susana K. Lai-Yuen
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation is a critical step in medical image analysis. Fully Convolutional Networks (FCNs) have emerged as powerful segmentation models achieving state-of-the-art results in various medical image datasets. Network architectures are usually designed manually for a specific segmentation task so applying them to other medical datasets requires extensive experience and time. Moreover, the segmentation requires handling large volumetric data that results in big and complex architectures. Recently, methods that automatically design neural networks for medical image segmentation have been presented; however, most approaches either do not fully consider volumetric information or do not optimize the size of the network. In this paper, we propose a novel self-adaptive 2D-3D ensemble of FCNs for medical image segmentation that incorporates volumetric information and optimizes both the model's performance and size. The model is composed of an ensemble of a 2D FCN that extracts intra-slice information, and a 3D FCN that exploits inter-slice information. The architectures of the 2D and 3D FCNs are automatically adapted to a medical image dataset using a multiobjective evolutionary based algorithm that minimizes both the segmentation error and number of parameters in the network. The proposed 2D-3D FCN ensemble was tested on the task of prostate segmentation on the image dataset from the PROMISE12 Grand Challenge. The resulting network is ranked in the top 10 submissions, surpassing the performance of other automatically-designed architectures while being considerably smaller in size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11587](http://arxiv.org/abs/1907.11587)

##### PDF
[http://arxiv.org/pdf/1907.11587](http://arxiv.org/pdf/1907.11587)

