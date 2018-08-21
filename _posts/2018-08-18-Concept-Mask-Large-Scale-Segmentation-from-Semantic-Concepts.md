---
layout: post
title: "Concept Mask: Large-Scale Segmentation from Semantic Concepts"
date: 2018-08-18 02:26:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Embedding Semantic_Segmentation Relation
author: Yufei Wang, Zhe Lin, Xiaohui Shen, Jianming Zhang, Scott Cohen
mathjax: true
---

* content
{:toc}

##### Abstract
Existing works on semantic segmentation typically consider a small number of labels, ranging from tens to a few hundreds. With a large number of labels, training and evaluation of such task become extremely challenging due to correlation between labels and lack of datasets with complete annotations. We formulate semantic segmentation as a problem of image segmentation given a semantic concept, and propose a novel system which can potentially handle an unlimited number of concepts, including objects, parts, stuff, and attributes. We achieve this using a weakly and semi-supervised framework leveraging multiple datasets with different levels of supervision. We first train a deep neural network on a 6M stock image dataset with only image-level labels to learn visual-semantic embedding on 18K concepts. Then, we refine and extend the embedding network to predict an attention map, using a curated dataset with bounding box annotations on 750 concepts. Finally, we train an attention-driven class agnostic segmentation network using an 80-category fully annotated dataset. We perform extensive experiments to validate that the proposed system performs competitively to the state of the art on fully supervised concepts, and is capable of producing accurate segmentations for weakly learned and unseen concepts.

##### Abstract (translated by Google)
关于语义分割的现有工作通常考虑少量标签，范围从几十到几百。由于标签之间的相关性以及缺少具有完整注释的数据集，因此对于大量标签，对此类任务的培训和评估变得极具挑战性。我们将语义分割表示为给定语义概念的图像分割问题，并提出一种新颖的系统，它可以处理无限数量的概念，包括对象，部件，东西和属性。我们使用弱和半监督框架来实现这一目标，该框架利用具有不同监督级别的多个数据集。我们首先在6M图像数据集上训练深度神经网络，仅使用图像级标签来学习18K概念的视觉语义嵌入。然后，我们使用带有750个概念的边界框注释的策划数据集来优化和扩展嵌入网络以预测注意力图。最后，我们使用80类完全注释的数据集训练注意力驱动的类不可知分割网络。我们进行了大量实验，以验证所提出的系统在完全监督的概念上与现有技术相比具有竞争力，并且能够为弱学习和看不见的概念产生准确的分割。

##### URL
[http://arxiv.org/abs/1808.06032](http://arxiv.org/abs/1808.06032)

##### PDF
[http://arxiv.org/pdf/1808.06032](http://arxiv.org/pdf/1808.06032)

