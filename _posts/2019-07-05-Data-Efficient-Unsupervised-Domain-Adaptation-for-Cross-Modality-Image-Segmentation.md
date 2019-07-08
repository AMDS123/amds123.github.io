---
layout: post
title: "Data Efficient Unsupervised Domain Adaptation for Cross-Modality Image Segmentation"
date: 2019-07-05 10:47:39
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Deep_Learning
author: Cheng Ouyang, Konstantinos Kamnitsas, Carlo Biffi, Jinming Duan, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models trained on medical images from a source domain (e.g. imaging modality) often fail when deployed on images from a different target domain, despite imaging common anatomical structures. Deep unsupervised domain adaptation (UDA) aims to improve the performance of a deep neural network model on a target domain, using solely unlabelled target domain data and labelled source domain data. However, current state-of-the-art methods exhibit reduced performance when target data is scarce. In this work, we introduce a new data efficient UDA method for multi-domain medical image segmentation. The proposed method combines a novel VAE-based feature prior matching, which is data-efficient, and domain adversarial training to learn a shared domain-invariant latent space which is exploited during segmentation. Our method is evaluated on a public multi-modality cardiac image segmentation dataset by adapting from the labelled source domain (3D MRI) to the unlabelled target domain (3D CT). We show that by using only one single unlabelled 3D CT scan, the proposed architecture outperforms the state-of-the-art in the same setting. Finally, we perform ablation studies on prior matching and domain adversarial training to shed light on the theoretical grounding of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02766](http://arxiv.org/abs/1907.02766)

##### PDF
[http://arxiv.org/pdf/1907.02766](http://arxiv.org/pdf/1907.02766)

