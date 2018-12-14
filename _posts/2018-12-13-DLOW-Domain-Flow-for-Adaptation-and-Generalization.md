---
layout: post
title: "DLOW: Domain Flow for Adaptation and Generalization"
date: 2018-12-13 13:31:59
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Semantic_Segmentation Inference
author: Rui Gong, Wen Li, Yuhua Chen, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a domain flow generation(DLOW) approach to model the domain shift between two domains by generating a continuous sequence of intermediate domains flowing from one domain to the other. The benefits of our DLOW model are two-fold. First, it is able to transfer source images into different styles in the intermediate domains. The transferred images smoothly bridge the gap between source and target domains, thus easing the domain adaptation task. Second, when multiple target domains are provided in the training phase, our DLOW model can be learnt to generate new styles of images that are unseen in the training data. We implement our DLOW model based on the state-of-the-art CycleGAN. A domainness variable is introduced to guide the model to generate the desired intermediate domain images. In the inference phase, a flow of various styles of images can be obtained by varying the domainness variable. We demonstrate the effectiveness of our approach for both cross-domain semantic segmentation and the style generalization tasks on benchmark datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05418](http://arxiv.org/abs/1812.05418)

##### PDF
[http://arxiv.org/pdf/1812.05418](http://arxiv.org/pdf/1812.05418)

