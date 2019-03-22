---
layout: post
title: "Robust Image Segmentation Quality Assessment without Ground Truth"
date: 2019-03-20 23:07:47
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Deep_Learning Prediction
author: Leixin Zhou, Wenxiang Deng, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning based image segmentation methods have achieved great success, even having human-level accuracy in some applications. However, due to the black box nature of deep learning, the best method may fail in some situations. Thus predicting segmentation quality without ground truth would be very crucial especially in clinical practice. Recently, people proposed to train neural networks to estimate the quality score by regression. Although it can achieve promising prediction accuracy, the network suffers robustness problem, e.g. it is vulnerable to adversarial attacks. In this paper, we propose to alleviate this problem by utilizing the difference between the input image and the reconstructed image, which is reconstructed from the segmentation to be assessed. The deep learning based reconstruction network (REC-Net) is trained with the input image masked by the ground truth segmentation against the original input image as the target. The rationale behind is that the trained REC-Net can best reconstruct the input image masked by accurate segmentation. The quality score regression network (REG-Net) is then trained with difference images and the corresponding segmentations as input. In this way, the regression network may have lower chance to overfit to the undesired image features from the original input image, and thus is more robust. Results on ACDC17 dataset demonstrated our method is promising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08773](http://arxiv.org/abs/1903.08773)

##### PDF
[http://arxiv.org/pdf/1903.08773](http://arxiv.org/pdf/1903.08773)

