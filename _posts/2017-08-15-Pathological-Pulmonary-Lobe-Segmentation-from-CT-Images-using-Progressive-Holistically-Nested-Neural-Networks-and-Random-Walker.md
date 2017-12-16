---
layout: post
title: "Pathological Pulmonary Lobe Segmentation from CT Images using Progressive Holistically Nested Neural Networks and Random Walker"
date: 2017-08-15 14:11:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Deep_Learning
author: Kevin George, Adam P. Harrison, Dakai Jin, Ziyue Xu, Daniel J. Mollura
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic pathological pulmonary lobe segmentation(PPLS) enables regional analyses of lung disease, a clinically important capability. Due to often incomplete lobe boundaries, PPLS is difficult even for experts, and most prior art requires inference from contextual information. To address this, we propose a novel PPLS method that couples deep learning with the random walker (RW) algorithm. We first employ the recent progressive holistically-nested network (P-HNN) model to identify potential lobar boundaries, then generate final segmentations using a RW that is seeded and weighted by the P-HNN output. We are the first to apply deep learning to PPLS. The advantages are independence from prior airway/vessel segmentations, increased robustness in diseased lungs, and methodological simplicity that does not sacrifice accuracy. Our method posts a high mean Jaccard score of 0.888$\pm$0.164 on a held-out set of 154 CT scans from lung-disease patients, while also significantly (p < 0.001) outperforming a state-of-the-art method.

##### Abstract (translated by Google)
自动病理性肺叶分割（PPLS）能够对肺部疾病进行区域分析，这是一种临床上重要的功能。由于经常是不完整的波瓣边界，所以即使对于专家来说PPLS也是困难的，并且大多数现有技术需要从背景信息中推断。为了解决这个问题，我们提出了一种新的PPLS方法，将深度学习与随机游走（RW）算法相结合。我们首先使用最近的渐进全层嵌套网络（P-HNN）模型来识别潜在的叶片边界，然后使用由P-HNN输出进行播种和加权的RW生成最终的分割。我们是第一个将深度学习应用于PPLS的人。优点是独立于先前的气道/血管分割，提高了患病肺部的鲁棒性，以及不牺牲准确性的方法简单性。我们的方法在来自肺病患者的154次CT扫描中显示出高平均Jaccard得分为0.888美元/小时0.164美元，同时显着（p <0.001）超过最先进的方法。

##### URL
[https://arxiv.org/abs/1708.04503](https://arxiv.org/abs/1708.04503)

##### PDF
[https://arxiv.org/pdf/1708.04503](https://arxiv.org/pdf/1708.04503)

