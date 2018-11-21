---
layout: post
title: "CGNet: A Light-weight Context Guided Network for Semantic Segmentation"
date: 2018-11-20 12:04:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Tianyi Wu, Sheng Tang, Rui Zhang, Yongdong Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The demand of applying semantic segmentation model on mobile devices has been increasing rapidly. Current state-of-the-art networks have enormous amount of parameters hence unsuitable for mobile devices, while other small memory footprint models ignore the inherent characteristic of semantic segmentation. To tackle this problem, we propose a novel Context Guided Network (CGNet), which is a light-weight network for semantic segmentation on mobile devices. We first propose the Context Guided (CG) block, which learns the joint feature of both local feature and surrounding context, and further improves the joint feature with the global context. Based on the CG block, we develop Context Guided Network (CGNet), which captures contextual information in all stages of the network and is specially tailored for increasing segmentation accuracy. CGNet is also elaborately designed to reduce the number of parameters and save memory footprint. Under an equivalent number of parameters, the proposed CGNet significantly outperforms existing segmentation networks. Extensive experiments on Cityscapes and CamVid datasets verify the effectiveness of the proposed approach. Specifically, without any post-processing, CGNet achieves 64.8% mean IoU on Cityscapes with less than 0.5 M parameters, and has a frame-rate of 50 fps on one NVIDIA Tesla K80 card for 2048 $\times$ 1024 high-resolution images. The source code for the complete system are publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08201](http://arxiv.org/abs/1811.08201)

##### PDF
[http://arxiv.org/pdf/1811.08201](http://arxiv.org/pdf/1811.08201)

