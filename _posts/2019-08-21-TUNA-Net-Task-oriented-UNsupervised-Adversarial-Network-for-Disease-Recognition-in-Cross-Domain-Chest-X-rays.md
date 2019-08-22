---
layout: post
title: "TUNA-Net: Task-oriented UNsupervised Adversarial Network for Disease Recognition in Cross-Domain Chest X-rays"
date: 2019-08-21 15:31:54
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Recognition
author: Yuxing Tang, Youbao Tang, Veit Sandfort, Jing Xiao, Ronald M. Summers
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we exploit the unsupervised domain adaptation problem for radiology image interpretation across domains. Specifically, we study how to adapt the disease recognition model from a labeled source domain to an unlabeled target domain, so as to reduce the effort of labeling each new dataset. To address the shortcoming of cross-domain, unpaired image-to-image translation methods which typically ignore class-specific semantics, we propose a task-driven, discriminatively trained, cycle-consistent generative adversarial network, termed TUNA-Net. It is able to preserve 1) low-level details, 2) high-level semantic information and 3) mid-level feature representation during the image-to-image translation process, to favor the target disease recognition task. The TUNA-Net framework is general and can be readily adapted to other learning tasks. We evaluate the proposed framework on two public chest X-ray datasets for pneumonia recognition. The TUNA-Net model can adapt labeled adult chest X-rays in the source domain such that they appear as if they were drawn from pediatric X-rays in the unlabeled target domain, while preserving the disease semantics. Extensive experiments show the superiority of the proposed method as compared to state-of-the-art unsupervised domain adaptation approaches. Notably, TUNA-Net achieves an AUC of 96.3% for pediatric pneumonia classification, which is very close to that of the supervised approach (98.1%), but without the need for labels on the target domain.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07926](http://arxiv.org/abs/1908.07926)

##### PDF
[http://arxiv.org/pdf/1908.07926](http://arxiv.org/pdf/1908.07926)

