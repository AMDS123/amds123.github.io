---
layout: post
title: "Towards Differentially Private Truth Discovery for Crowd Sensing Systems"
date: 2018-10-10 22:02:11
categories: arXiv_AI
tags: arXiv_AI
author: Yaliang Li, Houping Xiao, Zhan Qin, Chenglin Miao, Lu Su, Jing Gao, Kui Ren, Bolin Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, crowd sensing becomes increasingly more popular due to the ubiquitous usage of mobile devices. However, the quality of such human-generated sensory data varies significantly among different users. To better utilize sensory data, the problem of truth discovery, whose goal is to estimate user quality and infer reliable aggregated results through quality-aware data aggregation, has emerged as a hot topic. Although the existing truth discovery approaches can provide reliable aggregated results, they fail to protect the private information of individual users. Moreover, crowd sensing systems typically involve a large number of participants, making encryption or secure multi-party computation based solutions difficult to deploy. To address these challenges, in this paper, we propose an efficient privacy-preserving truth discovery mechanism with theoretical guarantees of both utility and privacy. The key idea of the proposed mechanism is to perturb data from each user independently and then conduct weighted aggregation among users' perturbed data. The proposed approach is able to assign user weights based on information quality, and thus the aggregated results will not deviate much from the true results even when large noise is added. We adapt local differential privacy definition to this privacy-preserving task and demonstrate the proposed mechanism can satisfy local differential privacy while preserving high aggregation accuracy. We formally quantify utility and privacy trade-off and further verify the claim by experiments on both synthetic data and a real-world crowd sensing system.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04760](https://arxiv.org/abs/1810.04760)

##### PDF
[https://arxiv.org/pdf/1810.04760](https://arxiv.org/pdf/1810.04760)

