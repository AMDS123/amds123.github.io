---
layout: post
title: "Combating Uncertainty with Novel Losses for Automatic Left Atrium Segmentation"
date: 2018-12-14 07:47:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Transfer_Learning Classification Prediction Detection
author: Xin Yang, Na Wang, Yi Wang, Xu Wang, Reza Nezafat, Dong Ni, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting left atrium in MR volume holds great potentials in promoting the treatment of atrial fibrillation. However, the varying anatomies, artifacts and low contrasts among tissues hinder the advance of both manual and automated solutions. In this paper, we propose a fully-automated framework to segment left atrium in gadolinium-enhanced MR volumes. The region of left atrium is firstly automatically localized by a detection module. Our framework then originates with a customized 3D deep neural network to fully explore the spatial dependency in the region for segmentation. To alleviate the risk of low training efficiency and potential overfitting, we enhance our deep network with the transfer learning and deep supervision strategy. Main contribution of our network design lies in the composite loss function to combat the boundary ambiguity and hard examples. We firstly adopt the Overlap loss to encourage network reduce the overlap between the foreground and background and thus sharpen the predictions on boundary. We then propose a novel Focal Positive loss to guide the learning of voxel-specific threshold and emphasize the foreground to improve classification sensitivity. Further improvement is obtained with an recursive training scheme. With ablation studies, all the introduced modules prove to be effective. The proposed framework achieves an average Dice of 92.24 in segmenting left atrium with pulmonary veins on 20 testing volumes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05807](http://arxiv.org/abs/1812.05807)

##### PDF
[http://arxiv.org/pdf/1812.05807](http://arxiv.org/pdf/1812.05807)

