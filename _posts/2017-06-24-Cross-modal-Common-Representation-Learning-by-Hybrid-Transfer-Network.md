---
layout: post
title: "Cross-modal Common Representation Learning by Hybrid Transfer Network"
date: 2017-06-24 14:08:19
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Represenation_Learning Relation
author: Xin Huang, Yuxin Peng, Mingkuan Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
DNN-based cross-modal retrieval is a research hotspot to retrieve across different modalities as image and text, but existing methods often face the challenge of insufficient cross-modal training data. In single-modal scenario, similar problem is usually relieved by transferring knowledge from large-scale auxiliary datasets (as ImageNet). Knowledge from such single-modal datasets is also very useful for cross-modal retrieval, which can provide rich general semantic information that can be shared across different modalities. However, it is challenging to transfer useful knowledge from single-modal (as image) source domain to cross-modal (as image/text) target domain. Knowledge in source domain cannot be directly transferred to both two different modalities in target domain, and the inherent cross-modal correlation contained in target domain provides key hints for cross-modal retrieval which should be preserved during transfer process. This paper proposes Cross-modal Hybrid Transfer Network (CHTN) with two subnetworks: Modal-sharing transfer subnetwork utilizes the modality in both source and target domains as a bridge, for transferring knowledge to both two modalities simultaneously; Layer-sharing correlation subnetwork preserves the inherent cross-modal semantic correlation to further adapt to cross-modal retrieval task. Cross-modal data can be converted to common representation by CHTN for retrieval, and comprehensive experiment on 3 datasets shows its effectiveness.

##### Abstract (translated by Google)
基于DNN的跨模态检索是图像和文本等不同模式检索的研究热点，但现有方法常常面临跨模态训练数据不足的挑战。在单一情况下，类似的问题通常通过从大规模的辅助数据集（如ImageNet）传递知识来解决。来自这种单一模态数据集的知识对跨模态检索也是非常有用的，它可以提供可以在不同模态之间共享的丰富的一般语义信息。然而，将有用的知识从单一模式（如图像）源域转移到跨模式（如图像/文本）目标域是有挑战性的。源域知识不能直接转移到目标域的两种不同模态，而目标域所包含的固有交叉模态相关性为跨模态检索提供了关键线索，在转移过程中应该保留。本文提出了具有两个子网络的交叉模式混合传输网络（CHTN）：模式共享传输子网络利用源域和目标域的模式作为桥梁，将知识同时传输到两种模式;层共享相关子网保留了固有的跨模态语义相关性，进一步适应跨模态检索任务。将交叉模态数据转换为CHTN的共同表示进行检索，对3个数据集进行综合实验，验证其有效性。

##### URL
[https://arxiv.org/abs/1706.00153](https://arxiv.org/abs/1706.00153)

##### PDF
[https://arxiv.org/pdf/1706.00153](https://arxiv.org/pdf/1706.00153)

