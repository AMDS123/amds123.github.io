---
layout: post
title: "Two-Stage Convolutional Neural Network Architecture for Lung Nodule Detection"
date: 2019-05-09 05:21:40
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Prediction Detection
author: Haichao Cao, Hong Liu, Enmin Song, Guangzhi Ma, Xiangyang Xu, Renchao Jin, Tengying Liu, Chih-Cheng Hung
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection of lung cancer is an effective way to improve the survival rate of patients. It is a critical step to have accurate detection of lung nodules in computed tomography (CT) images for the diagnosis of lung cancer. However, due to the heterogeneity of the lung nodules and the complexity of the surrounding environment, robust nodule detection has been a challenging task. In this study, we propose a two-stage convolutional neural network (TSCNN) architecture for lung nodule detection. The CNN architecture in the first stage is based on the improved UNet segmentation network to establish an initial detection of lung nodules. Simultaneously, in order to obtain a high recall rate without introducing excessive false positive nodules, we propose a novel sampling strategy, and use the offline hard mining idea for training and prediction according to the proposed cascaded prediction method. The CNN architecture in the second stage is based on the proposed dual pooling structure, which is built into three 3D CNN classification networks for false positive reduction. Since the network training requires a significant amount of training data, we adopt a data augmentation method based on random mask. Furthermore, we have improved the generalization ability of the false positive reduction model by means of ensemble learning. The proposed method has been experimentally verified on the LUNA dataset. Experimental results show that the proposed TSCNN architecture can obtain competitive detection performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03445](http://arxiv.org/abs/1905.03445)

##### PDF
[http://arxiv.org/pdf/1905.03445](http://arxiv.org/pdf/1905.03445)

