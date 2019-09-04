---
layout: post
title: "Domain Randomization and Pyramid Consistency: Simulation-to-Real Generalization without Accessing Target Domain Data"
date: 2019-09-02 23:33:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Xiangyu Yue, Yang Zhang, Sicheng Zhao, Alberto Sangiovanni-Vincentelli, Kurt Keutzer, Boqing Gong
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to harness the potential of simulation for the semantic segmentation of real-world self-driving scenes in a domain generalization fashion. The segmentation network is trained without any data of target domains and tested on the unseen target domains. To this end, we propose a new approach of domain randomization and pyramid consistency to learn a model with high generalizability. First, we propose to randomize the synthetic images with the styles of real images in terms of visual appearances using auxiliary datasets, in order to effectively learn domain-invariant representations. Second, we further enforce pyramid consistency across different "stylized" images and within an image, in order to learn domain-invariant and scale-invariant features, respectively. Extensive experiments are conducted on the generalization from GTA and SYNTHIA to Cityscapes, BDDS and Mapillary; and our method achieves superior results over the state-of-the-art techniques. Remarkably, our generalization results are on par with or even better than those obtained by state-of-the-art simulation-to-real domain adaptation methods, which access the target domain data at training time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00889](http://arxiv.org/abs/1909.00889)

##### PDF
[http://arxiv.org/pdf/1909.00889](http://arxiv.org/pdf/1909.00889)

