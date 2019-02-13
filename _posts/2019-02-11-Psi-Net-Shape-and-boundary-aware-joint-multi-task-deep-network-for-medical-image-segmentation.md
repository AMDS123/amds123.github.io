---
layout: post
title: "Psi-Net: Shape and boundary aware joint multi-task deep network for medical image segmentation"
date: 2019-02-11 19:11:49
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Prediction Detection
author: Balamurali Murugesan, Kaushik Sarveswaran, Sharath M Shankaranarayana, Keerthi Ram, Mohanasankar Sivaprakasam
mathjax: true
---

* content
{:toc}

##### Abstract
Medical image segmentation is a primary task in many applications, and the accuracy of the segmentation is a necessity. Recently, many deep learning networks derived from U-Net have been extensively used and have achieved notable results. To further improve and refine the performance of U-Net, parallel decoders along with mask prediction decoder have been carried out and have shown significant improvement with additional advantages. In our work, we utilize the advantages of using a combination of contour and distance map as regularizers. In turn, we propose a novel architecture Psi-Net with a single encoder and three parallel decoders, one decoder to learn the mask and other two to learn the auxiliary tasks of contour detection and distance map estimation. The learning of these auxiliary tasks helps in capturing the shape and boundary. We also propose a new joint loss function for the proposed architecture. The loss function consists of a weighted combination of Negative likelihood and Mean Square Error loss. We have used two publicly available datasets: 1) Origa dataset for the task of optic cup and disc segmentation and 2) Endovis segment dataset for the task of polyp segmentation to evaluate our model. We have conducted extensive experiments using our network to show our model gives better results in terms of segmentation, boundary and shape metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.04099](http://arxiv.org/abs/1902.04099)

##### PDF
[http://arxiv.org/pdf/1902.04099](http://arxiv.org/pdf/1902.04099)

