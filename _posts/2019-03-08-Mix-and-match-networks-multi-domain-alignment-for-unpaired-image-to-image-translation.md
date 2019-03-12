---
layout: post
title: "Mix and match networks: multi-domain alignment for unpaired image-to-image translation"
date: 2019-03-08 17:27:29
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Yaxing Wang, Luis Herranz, Joost van de Weijer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of inferring unseen cross-domain and cross-modal image-to-image translations between multiple domains and modalities. We assume that only some of the pairwise translations have been seen (i.e. trained) and infer the remaining unseen translations (where training pairs are not available). We propose mix and match networks, an approach where multiple encoders and decoders are aligned in such a way that the desired translation can be obtained by simply cascading the source encoder and the target decoder, even when they have not interacted during the training stage (i.e. unseen). The main challenge lies in the alignment of the latent representations at the bottlenecks of encoder-decoder pairs. We propose an architecture with several tools to encourage alignment, including autoencoders and robust side information and latent consistency losses. We show the benefits of our approach in terms of effectiveness and scalability compared with other pairwise image-to-image translation approaches. We also propose zero-pair cross-modal image translation, a challenging setting where the objective is inferring semantic segmentation from depth (and vice-versa) without explicit segmentation-depth pairs, and only from two (disjoint) segmentation-RGB and depth-segmentation training sets. We observe that certain part of the shared information between unseen domains might not be reachable, so we further propose a variant that leverages pseudo-pairs to exploit all shared information.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.04294](https://arxiv.org/abs/1903.04294)

##### PDF
[https://arxiv.org/pdf/1903.04294](https://arxiv.org/pdf/1903.04294)

