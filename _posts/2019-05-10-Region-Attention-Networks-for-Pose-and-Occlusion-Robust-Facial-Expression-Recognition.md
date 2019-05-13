---
layout: post
title: "Region Attention Networks for Pose and Occlusion Robust Facial Expression Recognition"
date: 2019-05-10 11:18:13
categories: arXiv_CV
tags: arXiv_CV Attention CNN Recognition
author: Kai Wang, Xiaojiang Peng, Jianfei Yang, Debin Meng, Yu Qiao
mathjax: true
---

* content
{:toc}

##### Abstract
Occlusion and pose variations, which can change facial appearance significantly, are two major obstacles for automatic Facial Expression Recognition (FER). Though automatic FER has made substantial progresses in the past few decades, occlusion-robust and pose-invariant issues of FER have received relatively less attention, especially in real-world scenarios. This paper addresses the real-world pose and occlusion robust FER problem with three-fold contributions. First, to stimulate the research of FER under real-world occlusions and variant poses, we build several in-the-wild facial expression datasets with manual annotations for the community. Second, we propose a novel Region Attention Network (RAN), to adaptively capture the importance of facial regions for occlusion and pose variant FER. The RAN aggregates and embeds varied number of region features produced by a backbone convolutional neural network into a compact fixed-length representation. Last, inspired by the fact that facial expressions are mainly defined by facial action units, we propose a region biased loss to encourage high attention weights for the most important regions. We validate our RAN and region biased loss on both our built test datasets and four popular datasets: FERPlus, AffectNet, RAF-DB, and SFEW. Extensive experiments show that our RAN and region biased loss largely improve the performance of FER with occlusion and variant pose. Our method also achieves state-of-the-art results on FERPlus, AffectNet, RAF-DB, and SFEW. Code and the collected test data will be publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04075](http://arxiv.org/abs/1905.04075)

##### PDF
[http://arxiv.org/pdf/1905.04075](http://arxiv.org/pdf/1905.04075)

