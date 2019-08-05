---
layout: post
title: "Adversarial Camera Alignment Network for Unsupervised Cross-camera Person Re-identification"
date: 2019-08-02 13:58:26
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial GAN Tracking Person_Re-identification
author: Lei Qi, Lei Wang, Jing Huo, Yinghuan Shi, Yang Gao
mathjax: true
---

* content
{:toc}

##### Abstract
In person re-identification (Re-ID), supervised methods usually need a large amount of expensive label information, while unsupervised ones are still unable to deliver satisfactory identification performance. In this paper, we introduce a novel person Re-ID task called unsupervised cross-camera person Re-ID, which only needs the within-camera (intra-camera) label information but not cross-camera (inter-camera) labels which are more expensive to obtain. In real-world applications, the intra-camera label information can be easily captured by tracking algorithms or few manual annotations. In this situation, the main challenge becomes the distribution discrepancy across different camera views, caused by the various body pose, occlusion, image resolution, illumination conditions, and background noises in different cameras. To address this situation, we propose a novel Adversarial Camera Alignment Network (ACAN) for unsupervised cross-camera person Re-ID. It consists of the camera-alignment task and the supervised within-camera learning task. To achieve the camera alignment, we develop a Multi-Camera Adversarial Learning (MCAL) to map images of different cameras into a shared subspace. Particularly, we investigate two different schemes, including the existing GRL (i.e., gradient reversal layer) scheme and the proposed scheme called "other camera equiprobability" (OCE), to conduct the multi-camera adversarial task. Based on this shared subspace, we then leverage the within-camera labels to train the network. Extensive experiments on five large-scale datasets demonstrate the superiority of ACAN over multiple state-of-the-art unsupervised methods that take advantage of labeled source domains and generated images by GAN-based models. In particular, we verify that the proposed multi-camera adversarial task does contribute to the significant improvement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00862](http://arxiv.org/abs/1908.00862)

##### PDF
[http://arxiv.org/pdf/1908.00862](http://arxiv.org/pdf/1908.00862)

