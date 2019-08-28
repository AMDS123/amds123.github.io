---
layout: post
title: "Weakly-Supervised Unconstrained Action Unit Detection via Latent Feature Domain"
date: 2019-08-27 07:55:35
categories: arXiv_CV
tags: arXiv_CV Adversarial Detection
author: Zhiwen Shao, Jianfei Cai, Tat-Jen Cham, Xuequan Lu, Lizhuang Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Facial action unit (AU) detection in the wild is a challenging problem, with current methods either depending on impractical labor-intensive labeling by experts, or inaccurate pseudo labels. In this paper, we propose an end-to-end weakly-supervised AU detection framework for unconstrained target-domain images by exploiting available and accurate AU labels from a well-constrained source domain. Instead of mapping directly from source to target domains in the image space, which could result in well-trained image synthesis results but losing transferred AU information, we generate a latent feature domain where we combine source-domain landmark-related features with target-domain landmark-free features. Since facial inner-landmarks are highly relevant to AUs, we can train target-domain AU detection with source-domain AU labels in the latent feature domain. The mapping from source and target domains to the latent domain is learned by maximizing the AU detection performance. Moreover, to disentangle the images into landmark-related features and landmark-free features, we introduce a novel landmark adversarial loss which can solve the multi-player minimax game in adversarial learning. Our framework can also be naturally extended for use with pseudo AU labels. Extensive experiments show that our method soundly outperforms the baselines, upper-bounds and state-of-the-art approaches on the challenging BP4D and EmotioNet benchmarks. The code for our method is available at https://github.com/ZhiwenShao/ADLD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10143](http://arxiv.org/abs/1903.10143)

##### PDF
[http://arxiv.org/pdf/1903.10143](http://arxiv.org/pdf/1903.10143)

