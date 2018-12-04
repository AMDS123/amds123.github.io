---
layout: post
title: "Domain Alignment with Triplets"
date: 2018-12-03 16:46:29
categories: arXiv_CV
tags: arXiv_CV Embedding Relation
author: Weijian Deng, Liang Zheng, Jianbin Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep domain adaptation methods can reduce the distribution discrepancy by learning domain-invariant embedddings. However, these methods only focus on aligning the whole data distributions, without considering the class-level relations among source and target images. Thus, a target embeddings of a bird might be aligned to source embeddings of an airplane. This semantic misalignment can directly degrade the classifier performance on the target dataset. To alleviate this problem, we present a similarity constrained alignment (SCA) method for unsupervised domain adaptation. When aligning the distributions in the embedding space, SCA enforces a similarity-preserving constraint to maintain class-level relations among the source and target images, i.e., if a source image and a target image are of the same class label, their corresponding embeddings are supposed to be aligned nearby, and vise versa. In the absence of target labels, we assign pseudo labels for target images. Given labeled source images and pseudo-labeled target images, the similarity-preserving constraint can be implemented by minimizing the triplet loss. With the joint supervision of domain alignment loss and similarity-preserving constraint, we train a network to obtain domain-invariant embeddings with two critical characteristics, intra-class compactness and inter-class separability. Extensive experiments conducted on the two datasets well demonstrate the effectiveness of SCA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00893](http://arxiv.org/abs/1812.00893)

##### PDF
[http://arxiv.org/pdf/1812.00893](http://arxiv.org/pdf/1812.00893)

