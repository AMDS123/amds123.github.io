---
layout: post
title: "A Unified Mammogram Analysis Method via Hybrid Deep Supervision"
date: 2018-08-31 09:32:52
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Rongzhao Zhang, Han Zhang, Albert C. S. Chung
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic mammogram classification and mass segmentation play a critical role in a computer-aided mammogram screening system. In this work, we present a unified mammogram analysis framework for both whole-mammogram classification and segmentation. Our model is designed based on a deep U-Net with residual connections, and equipped with the novel hybrid deep supervision (HDS) scheme for end-to-end multi-task learning. As an extension of deep supervision (DS), HDS not only can force the model to learn more discriminative features like DS, but also seamlessly integrates segmentation and classification tasks into one model, thus the model can benefit from both pixel-wise and image-wise supervisions. We extensively validate the proposed method on the widely-used INbreast dataset. Ablation study corroborates that pixel-wise and image-wise supervisions are mutually beneficial, evidencing the efficacy of HDS. The results of 5-fold cross validation indicate that our unified model matches state-of-the-art performance on both mammogram segmentation and classification tasks, which achieves an average segmentation Dice similarity coefficient (DSC) of 0.85 and a classification accuracy of 0.89. The code is available at https://github.com/angrypudding/hybrid-ds.

##### Abstract (translated by Google)
自动乳房X线照片分类和质量分割在计算机辅助乳房X线照片筛查系统中起着关键作用。在这项工作中，我们提出了一个统一的乳房X线照片分析框架，用于整个乳房X线照片分类和分割。我们的模型是基于具有剩余连接的深U-Net设计的，并且配备了用于端到端多任务学习的新型混合深度监视（HDS）方案。作为深度监督（DS）的延伸，HDS不仅可以强制模型学习更多的辨别功能，如DS，还可以将分割和分类任务无缝集成到一个模型中，因此模型可以从像素和图像中受益。明智的监督。我们在广泛使用的INbreast数据集上广泛验证了所提出的方法。消融研究证实，像素方式和图像方式的监督是互利的，证明了HDS的功效。 5次交叉验证的结果表明，我们的统一模型匹配乳房X线照片分割和分类任务的最新性能，实现了0.85的平均分割骰子相似系数（DSC）和0.89的分类精度。该代码可在https://github.com/angrypudding/hybrid-ds上找到。

##### URL
[http://arxiv.org/abs/1808.10646](http://arxiv.org/abs/1808.10646)

##### PDF
[http://arxiv.org/pdf/1808.10646](http://arxiv.org/pdf/1808.10646)

