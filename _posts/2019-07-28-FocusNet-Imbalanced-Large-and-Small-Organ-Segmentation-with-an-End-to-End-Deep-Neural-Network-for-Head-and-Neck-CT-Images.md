---
layout: post
title: "FocusNet: Imbalanced Large and Small Organ Segmentation with an End-to-End Deep Neural Network for Head and Neck CT Images"
date: 2019-07-28 09:45:19
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Yunhe Gao, Rui Huang, Ming Chen, Zhe Wang, Jincheng Deng, Yuanyuan Chen, Yiwei Yang, Jie Zhang, Chanjuan Tao, Hongsheng Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an end-to-end deep neural network for solving the problem of imbalanced large and small organ segmentation in head and neck (HaN) CT images. To conduct radiotherapy planning for nasopharyngeal cancer, more than 10 organs-at-risk (normal organs) need to be precisely segmented in advance. However, the size ratio between large and small organs in the head could reach hundreds. Directly using such imbalanced organ annotations to train deep neural networks generally leads to inaccurate small-organ label maps. We propose a novel end-to-end deep neural network to solve this challenging problem by automatically locating, ROI-pooling, and segmenting small organs with specifically designed small-organ sub-networks while maintaining the accuracy of large organ segmentation. A strong main network with densely connected atrous spatial pyramid pooling and squeeze-and-excitation modules is used for segmenting large organs, where large organs' label maps are directly output. For small organs, their probabilistic locations instead of label maps are estimated by the main network. High-resolution and multi-scale feature volumes for each small organ are ROI-pooled according to their locations and are fed into small-organ networks for accurate segmenting small organs. Our proposed network is extensively tested on both collected real data and the \emph{MICCAI Head and Neck Auto Segmentation Challenge 2015} dataset, and shows superior performance compared with state-of-the-art segmentation methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12056](http://arxiv.org/abs/1907.12056)

##### PDF
[http://arxiv.org/pdf/1907.12056](http://arxiv.org/pdf/1907.12056)

