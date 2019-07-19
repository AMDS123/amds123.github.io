---
layout: post
title: "On the Evaluation of Conditional GANs"
date: 2019-07-11 17:41:57
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Terrance DeVries, Adriana Romero, Luis Pineda, Graham W. Taylor, Michal Drozdzal
mathjax: true
---

* content
{:toc}

##### Abstract
Conditional Generative Adversarial Networks (cGANs) are finding increasingly widespread use in many application domains. Despite outstanding progress, quantitative evaluation of such models often involves multiple distinct metrics to assess different desirable properties such as image quality, intra-conditioning diversity, and conditional consistency, making model benchmarking challenging. In this paper, we propose the Frechet Joint Distance (FJD), which implicitly captures the above mentioned properties in a single metric. FJD is defined as the Frechet Distance of the joint distribution of images and conditionings, making it less sensitive to the often limited per-conditioning sample size. As a result, it scales more gracefully to stronger forms of conditioning such as pixel-wise or multi-modal conditioning. We evaluate FJD on a modified version of the dSprite dataset as well as on the large scale COCO-Stuff dataset, and consistently highlight its benefits when compared to currently established metrics. Moreover, we use the newly introduced metric to compare existing cGAN-based models, with varying conditioning strengths, and show that FJD can be used as a promising single metric for model benchmarking.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.08175](http://arxiv.org/abs/1907.08175)

##### PDF
[http://arxiv.org/pdf/1907.08175](http://arxiv.org/pdf/1907.08175)

