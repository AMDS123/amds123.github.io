---
layout: post
title: "A Novel Domain Adaptation Framework for Medical Image Segmentation"
date: 2018-10-11 04:03:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation GAN
author: Amir Gholami, Shashank Subramanian, Varun Shenoy, Naveen Himthani, Xiangyu Yue, Sicheng Zhao, Peter Jin, George Biros, Kurt Keutzer
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a segmentation framework that uses deep neural networks and introduce two innovations. First, we describe a biophysics-based domain adaptation method. Second, we propose an automatic method to segment white and gray matter, and cerebrospinal fluid, in addition to tumorous tissue. Regarding our first innovation, we use a domain adaptation framework that combines a novel multispecies biophysical tumor growth model with a generative adversarial model to create realistic looking synthetic multimodal MR images with known segmentation. Regarding our second innovation, we propose an automatic approach to enrich available segmentation data by computing the segmentation for healthy tissues. This segmentation, which is done using diffeomorphic image registration between the BraTS training data and a set of prelabeled atlases, provides more information for training and reduces the class imbalance problem. Our overall approach is not specific to any particular neural network and can be used in conjunction with existing solutions. We demonstrate the performance improvement using a 2D U-Net for the BraTS'18 segmentation challenge. Our biophysics based domain adaptation achieves better results, as compared to the existing state-of-the-art GAN model used to create synthetic data for training.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05732](https://arxiv.org/abs/1810.05732)

##### PDF
[https://arxiv.org/pdf/1810.05732](https://arxiv.org/pdf/1810.05732)

