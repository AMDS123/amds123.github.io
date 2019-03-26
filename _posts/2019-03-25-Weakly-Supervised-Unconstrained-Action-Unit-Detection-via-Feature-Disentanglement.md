---
layout: post
title: "Weakly-Supervised Unconstrained Action Unit Detection via Feature Disentanglement"
date: 2019-03-25 06:16:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Classification Detection
author: Zhiwen Shao, Jianfei Cai, Tat-Jen Cham, Xuequan Lu, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Facial action unit (AU) detection in the wild is a challenging problem, with current methods either depending on impractical labor-intensive labeling by experts, or inaccurate pseudo labels. In this paper, we aim to exploit accurate AU labels from a well-constrained source domain for training an AU detector for the target domain of unconstrained in-the-wild images. Instead of attempting to map directly from source to target domains, we propose to generate a new feature domain to combine source-domain facial inner landmark features (denoted as shape features) with target-domain global pose and texture features (denoted as texture features), so as to train target AU detector with source AU labels. Specifically, we first disentangle the rich features learned from images into shape features and texture features by introducing a novel shape adversarial loss and a shape classification loss. After swapping the shape features of unpaired source and target images, the combined source shape features and target texture features are translated to the new domain by learning a mapping that maximizes the AU detector performance. A further disentanglement and swap is applied to cross-cyclically reconstruct the original rich features. Moreover, our framework can also be naturally extended for use with pseudo AU labels. Extensive experiments show that our method soundly outperforms the baseline, upper-bound methods and state-of-the-art approaches on the challenging benchmark dataset EmotioNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10143](http://arxiv.org/abs/1903.10143)

##### PDF
[http://arxiv.org/pdf/1903.10143](http://arxiv.org/pdf/1903.10143)

