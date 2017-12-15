---
layout: post
title: "Actor-Action Semantic Segmentation with Grouping Process Models"
date: 2015-12-30 18:07:45
categories: arXiv_CV
tags: arXiv_CV Video_Caption Segmentation Semantic_Segmentation Inference
author: Chenliang Xu, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
Actor-action semantic segmentation made an important step toward advanced video understanding problems: what action is happening; who is performing the action; and where is the action in space-time. Current models for this problem are local, based on layered CRFs, and are unable to capture long-ranging interaction of video parts. We propose a new model that combines these local labeling CRFs with a hierarchical supervoxel decomposition. The supervoxels provide cues for possible groupings of nodes, at various scales, in the CRFs to encourage adaptive, high-order groups for more effective labeling. Our model is dynamic and continuously exchanges information during inference: the local CRFs influence what supervoxels in the hierarchy are active, and these active nodes influence the connectivity in the CRF; we hence call it a grouping process model. The experimental results on a recent large-scale video dataset show a large margin of 60% relative improvement over the state of the art, which demonstrates the effectiveness of the dynamic, bidirectional flow between labeling and grouping.

##### Abstract (translated by Google)
演员动作语义分割向高级视频理解问题迈出了重要的一步：正在发生什么行为;谁正在执行该行动;这个时间在哪里呢？这个问题的当前模型是基于分层CRF的本地模型，并且不能捕获视频部分的长期交互。我们提出了一个新的模型，结合这些局部标记CRF与分层超体素分解。超体素为CRF中各种尺度的节点分组提供线索，以鼓励自适应的高阶群体进行更有效的标记。我们的模型是动态的，在推理过程中不断交换信息：局部CRFs影响层次中的超体素是活跃的，这些活跃节点影响CRF中的连通性;我们称之为分组过程模型。在最近的大规模视频数据集上的实验结果显示相对于现有技术的相对改进幅度大幅提高了60％，这证明了标记和分组之间的动态双向流动的有效性。

##### URL
[https://arxiv.org/abs/1512.09041](https://arxiv.org/abs/1512.09041)

##### PDF
[https://arxiv.org/pdf/1512.09041](https://arxiv.org/pdf/1512.09041)

