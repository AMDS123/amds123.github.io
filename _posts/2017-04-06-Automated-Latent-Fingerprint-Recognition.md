---
layout: post
title: "Automated Latent Fingerprint Recognition"
date: 2017-04-06 16:47:16
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Kai Cao, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Latent fingerprints are one of the most important and widely used evidence in law enforcement and forensic agencies worldwide. Yet, NIST evaluations show that the performance of state-of-the-art latent recognition systems is far from satisfactory. An automated latent fingerprint recognition system with high accuracy is essential to compare latents found at crime scenes to a large collection of reference prints to generate a candidate list of possible mates. In this paper, we propose an automated latent fingerprint recognition algorithm that utilizes Convolutional Neural Networks (ConvNets) for ridge flow estimation and minutiae descriptor extraction, and extract complementary templates (two minutiae templates and one texture template) to represent the latent. The comparison scores between the latent and a reference print based on the three templates are fused to retrieve a short candidate list from the reference database. Experimental results show that the rank-1 identification accuracies (query latent is matched with its true mate in the reference database) are 64.7% for the NIST SD27 and 75.3% for the WVU latent databases, against a reference database of 100K rolled prints. These results are the best among published papers on latent recognition and competitive with the performance (66.7% and 70.8% rank-1 accuracies on NIST SD27 and WVU DB, respectively) of a leading COTS latent Automated Fingerprint Identification System (AFIS). By score-level (rank-level) fusion of our system with the commercial off-the-shelf (COTS) latent AFIS, the overall rank-1 identification performance can be improved from 64.7% and 75.3% to 73.3% (74.4%) and 76.6% (78.4%) on NIST SD27 and WVU latent databases, respectively.

##### Abstract (translated by Google)
潜指纹是全球执法和法医机构最重要，最广泛使用的证据之一。然而，NIST的评估表明，最先进的潜在识别系统的性能远远不能令人满意。具有高精确度的自动化潜指纹识别系统对于比较在犯罪现场发现的晚期和大量参考图片以产生可能的配偶的候选列表是非常重要的。在本文中，我们提出了一种利用卷积神经网络（ConvNets）进行脊流估计和细节描述符提取的自动潜指纹识别算法，并提取互补模板（两个细节模板和一个纹理模板）来表示潜在的。基于三个模板的潜在和参考印刷品之间的比较分数被融合以从参考数据库中检索短的候选列表。实验结果表明，与参考数据库中的真实伴侣相匹配的一级识别精度（NIST SD27为64.7％，WVU潜伏数据库为75.3％）与100K滚动打印的参考数据库相比较。这些结果在潜在识别和与性能相竞争（NIST SD27和WVU DB分别达到66.7％和70.8％的一级精度）领先的COTS潜在自动指纹识别系统（AFIS）中是最好的。通过将我们的系统与商业现货（COTS）潜在的AFIS进行评分级（rank-level）融合，总体一级识别性能可以从64.7％和75.3％提高到73.3％（74.4％）和NIST SD27和WVU潜在数据库分别为76.6％（78.4％）。

##### URL
[https://arxiv.org/abs/1704.01925](https://arxiv.org/abs/1704.01925)

##### PDF
[https://arxiv.org/pdf/1704.01925](https://arxiv.org/pdf/1704.01925)

