---
layout: post
title: "Asymmetric Loss Functions and Deep Densely Connected Networks for Highly Imbalanced Medical Image Segmentation: Application to Multiple Sclerosis Lesion Detection"
date: 2018-12-13 22:02:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Prediction Detection
author: Seyed Raein Hashemi, Seyed Sadegh Mohseni Salehi, Deniz Erdogmus, Sanjay P. Prabhu, Simon K. Warfield, Ali Gholipour
mathjax: true
---

* content
{:toc}

##### Abstract
Fully convolutional deep neural networks have been asserted to be fast and precise frameworks with great potential in image segmentation. One of the major challenges in training such networks raises when data is unbalanced, which is common in many medical imaging applications such as lesion segmentation where lesion class voxels are often much lower in numbers than non-lesion voxels. A trained network with unbalanced data may make predictions with high precision and low recall, being severely biased towards the non-lesion class which is particularly undesired in most medical applications where FNs are more important than FPs. Various methods have been proposed to address this problem, more recently similarity loss functions and focal loss. In this work we trained fully convolutional deep neural networks using an asymmetric similarity loss function to mitigate the issue of data imbalance and achieve much better tradeoff between precision and recall. To this end, we developed a 3D FC-DenseNet with large overlapping image patches as input and an asymmetric similarity loss layer based on Tversky index (using Fbeta scores). We used large overlapping image patches as inputs for intrinsic and extrinsic data augmentation, a patch selection algorithm, and a patch prediction fusion strategy using B-spline weighted soft voting to account for the uncertainty of prediction in patch borders. We applied this method to MS lesion segmentation based on two different datasets of MSSEG and ISBI longitudinal MS lesion segmentation challenge, where we achieved top performance in both challenges. Our network trained with focal loss ranked first according to the ISBI challenge overall score and resulted in the lowest reported lesion false positive rate among all submitted methods. Our network trained with the asymmetric similarity loss led to the lowest surface distance and the best lesion true positive rate.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.11078](http://arxiv.org/abs/1803.11078)

##### PDF
[http://arxiv.org/pdf/1803.11078](http://arxiv.org/pdf/1803.11078)

