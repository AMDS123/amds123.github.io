---
layout: post
title: "Dynamic-structured Semantic Propagation Network"
date: 2018-03-16 03:28:22
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Semantic_Segmentation Optimization Inference Prediction Relation
author: Xiaodan Liang, Hongfei Zhou, Eric Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic concept hierarchy is still under-explored for semantic segmentation due to the inefficiency and complicated optimization of incorporating structural inference into dense prediction. This lack of modeling semantic correlations also makes prior works must tune highly-specified models for each task due to the label discrepancy across datasets. It severely limits the generalization capability of segmentation models for open set concept vocabulary and annotation utilization. In this paper, we propose a Dynamic-Structured Semantic Propagation Network (DSSPN) that builds a semantic neuron graph by explicitly incorporating the semantic concept hierarchy into network construction. Each neuron represents the instantiated module for recognizing a specific type of entity such as a super-class (e.g. food) or a specific concept (e.g. pizza). During training, DSSPN performs the dynamic-structured neuron computation graph by only activating a sub-graph of neurons for each image in a principled way. A dense semantic-enhanced neural block is proposed to propagate the learned knowledge of all ancestor neurons into each fine-grained child neuron for feature evolving. Another merit of such semantic explainable structure is the ability of learning a unified model concurrently on diverse datasets by selectively activating different neuron sub-graphs for each annotation at each step. Extensive experiments on four public semantic segmentation datasets (i.e. ADE20K, COCO-Stuff, Cityscape and Mapillary) demonstrate the superiority of our DSSPN over state-of-the-art segmentation models. Moreoever, we demonstrate a universal segmentation model that is jointly trained on diverse datasets can surpass the performance of the common fine-tuning scheme for exploiting multiple domain knowledge.

##### Abstract (translated by Google)
由于将结构推理并入稠密预测的效率低下和复杂优化，语义概念层次结构仍然处于语义分割的低层次。这种建模语义相关性的缺乏也使先前的作品必须针对每个任务调整高度指定的模型，这是由于数据集之间的标签差异。这严重限制了开放集合概念词汇和注释利用的分割模型的泛化能力。在本文中，我们提出了一个动态结构化的语义传播网络（DSSPN），它通过将语义概念层次明确地结合到网络构建中来构建语义神经元图。每个神经元代表用于识别诸如超级（例如食物）或特定概念（例如披萨）的特定类型的实体的实例化模块。在训练期间，DSSPN通过仅以原理方式激活每个图像的神经元的子图来执行动态结构的神经元计算图。提出了一种密集的语义增强神经块来将所有祖先神经元的学习知识传播到每个细粒度的子神经元中以进行特征演化。这种语义解释结构的另一个优点是通过在每个步骤选择性地为每个注释激活不同的神经元子图，在不同数据集上同时学习统一模型的能力。对四个公共语义分割数据集（即ADE20K，COCO-Stuff，Cityscape和Mapillary）进行的大量实验证明了我们的DSSPN优于最先进的分割模型。更重要的是，我们展示了一个通用的分割模型，它在不同的数据集上进行联合训练可以超越通用微调方案的性能，以利用多领域知识。

##### URL
[https://arxiv.org/abs/1803.06067](https://arxiv.org/abs/1803.06067)

##### PDF
[https://arxiv.org/pdf/1803.06067](https://arxiv.org/pdf/1803.06067)

