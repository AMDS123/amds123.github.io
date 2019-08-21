---
layout: post
title: "Unsupervised Multi-modal Style Transfer for Cardiac MR Segmentation"
date: 2019-08-20 13:47:42
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Style_Transfer
author: Chen Chen, Cheng Ouyang, Giacomo Tarroni, Jo Schlemper, Huaqi Qiu, Wenjia Bai, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we present a fully automatic method to segment cardiac structures from late-gadolinium enhanced (LGE) images without using labelled LGE data for training, but instead by transferring the anatomical knowledge and features learned on annotated balanced steady-state free precession (bSSFP) images, which are easier to acquire. Our framework mainly consists of two neural networks: a multi-modal image translation network for style transfer and a cascaded segmentation network for image segmentation. The multi-modal image translation network generates realistic and diverse synthetic LGE images conditioned on a single annotated bSSFP image, forming a synthetic LGE training set. This set is then utilized to fine-tune the segmentation network pre-trained on labelled bSSFP images, achieving the goal of unsupervised LGE image segmentation. In particular, the proposed cascaded segmentation network is able to produce accurate segmentation by taking both shape prior and image appearance into account, achieving an average Dice score of 0.92 for the left ventricle, 0.83 for the myocardium, and 0.88 for the right ventricle on the test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07344](http://arxiv.org/abs/1908.07344)

##### PDF
[http://arxiv.org/pdf/1908.07344](http://arxiv.org/pdf/1908.07344)

