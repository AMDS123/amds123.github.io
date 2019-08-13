---
layout: post
title: "Left Ventricle Quantification Using Direct Regression with Segmentation Regularization and Ensembles of Pretrained 2D and 3D CNNs"
date: 2019-08-12 14:46:00
categories: arXiv_CV
tags: arXiv_CV Regularization Segmentation CNN Transfer_Learning RNN Classification
author: Nils Gessert, Alexander Schlaefer
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiac left ventricle (LV) quantification provides a tool for diagnosing cardiac diseases. Automatic calculation of all relevant LV indices from cardiac MR images is an intricate task due to large variations among patients and deformation during the cardiac cycle. Typical methods are based on segmentation of the myocardium or direct regression from MR images. To consider cardiac motion and deformation, recurrent neural networks and spatio-temporal convolutional neural networks (CNNs) have been proposed. We study an approach combining state-of-the-art models and emphasizing transfer learning to account for the small dataset provided for the LVQuan19 challenge. We compare 2D spatial and 3D spatio-temporal CNNs for LV indices regression and cardiac phase classification. To incorporate segmentation information, we propose an architecture-independent segmentation-based regularization. To improve the robustness further, we employ a search scheme that identifies the optimal ensemble from a set of architecture variants. Evaluating on the LVQuan19 Challenge training dataset with 5-fold cross-validation, we achieve mean absolute errors of 111 +- 76mm^2, 1.84 +- 0.9mm and 1.22 +- 0.6mm for area, dimension and regional wall thickness regression, respectively. The error rate for cardiac phase classification is 6.7%.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.04181](https://arxiv.org/abs/1908.04181)

##### PDF
[https://arxiv.org/pdf/1908.04181](https://arxiv.org/pdf/1908.04181)

