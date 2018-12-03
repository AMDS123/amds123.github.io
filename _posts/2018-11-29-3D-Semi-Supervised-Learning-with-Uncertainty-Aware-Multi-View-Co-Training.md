---
layout: post
title: "3D Semi-Supervised Learning with Uncertainty-Aware Multi-View Co-Training"
date: 2018-11-29 21:58:53
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Attention Deep_Learning Prediction
author: Yingda Xia, Fengze Liu, Dong Yang, Jinzheng Cai, Lequan Yu, Zhuotun Zhu, Daguang Xu, Alan Yuille, Holger Roth
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel framework, uncertainty-aware multi-view co-training (UMCT), to address semi-supervised learning on 3D data, such as volumetric data in medical imaging. The original co-training method was applied to non-visual data. It requires different sources, or representations, of the data, which are called different views and differ from viewpoint in computer vision. Co-training was recently applied to visual tasks where the views were deep networks learnt by adversarial training. In our work, targeted at 3D data, co-training is achieved by exploiting multi-viewpoint consistency. We generate different views by rotating the 3D data and utilize asymmetrical 3D kernels to further encourage diversified features of each sub-net. In addition, we propose an uncertainty-aware attention mechanism to estimate the reliability of each view prediction with Bayesian deep learning. As one view requires the supervision from other views in co-training, our self-adaptive approach computes a confidence score for the prediction of each unlabeled sample, in order to assign a reliable pseudo label and thus achieve better performance. We show the effectiveness of our proposed method on several open datasets from medical image segmentation tasks (NIH pancreas &amp; LiTS liver tumor dataset). A method based on our approach achieved the state-of-the-art performances on both the LiTS liver tumor segmentation and the Medical Segmentation Decathlon (MSD) challenge, demonstrating the robustness and value of our framework even when fully supervised training is feasible.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12506](http://arxiv.org/abs/1811.12506)

##### PDF
[http://arxiv.org/pdf/1811.12506](http://arxiv.org/pdf/1811.12506)

