---
layout: post
title: "Multi-step Cascaded Networks for Brain Tumor Segmentation"
date: 2019-08-16 08:39:13
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Xiangyu Li, Gongning Luo, Kuanquan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic brain tumor segmentation method plays an extremely important role in the whole process of brain tumor diagnosis and treatment. In this paper, we propose a multi-step cascaded network which takes the hierarchical topology of the brain tumor substructures into consideration and segments the substructures from coarse to fine , i,e, each step of the the multi-step network is responsible for the segmentation of a specific substructure of the tumor, such as the whole tumor,tumor core and enhancing tumor, the result of the former step is utilized as the prior information for the next step to guide the finer segmentation process. The whole network is trained in an end-to-end fashion. Besides, to alleviate the gradient vanishing issue and reduce overfitting, we added several auxiliary outputs as a kind of deep supervision for each step and introduced several data augmentation strategies, respectively, which proved to be quite efficient for brain tumor segmentation. Lastly, focal loss is utilized to solve the problem of remarkably imbalance of the tumor regions and background. Our model is tested on the BraTS 2019 validation dataset, the preliminary results of mean dice coefficients are 0.882, 0.797, 0.753 for the whole tumor, tumor core and enhancing tumor respectively. Code will be available at this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05887](https://arxiv.org/abs/1908.05887)

##### PDF
[https://arxiv.org/pdf/1908.05887](https://arxiv.org/pdf/1908.05887)

