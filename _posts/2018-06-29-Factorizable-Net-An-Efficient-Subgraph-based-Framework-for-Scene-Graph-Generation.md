---
layout: post
title: "Factorizable Net: An Efficient Subgraph-based Framework for Scene Graph Generation"
date: 2018-06-29 17:10:58
categories: arXiv_CV
tags: arXiv_CV Inference Detection Relation Recognition
author: Yikang Li, Wanli Ouyang, Bolei Zhou, Yawen Cui, Jianping Shi, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Generating scene graph to describe all the relations inside an image gains increasing interests these years. However, most of the previous methods use complicated structures with slow inference speed or rely on the external data, which limits the usage of the model in real-life scenarios. To improve the efficiency of scene graph generation, we propose a subgraph-based connection graph to concisely represent the scene graph during the inference. A bottom-up clustering method is first used to factorize the entire scene graph into subgraphs, where each subgraph contains several objects and a subset of their relationships. By replacing the numerous relationship representations of the scene graph with fewer subgraph and object features, the computation in the intermediate stage is significantly reduced. In addition, spatial information is maintained by the subgraph features, which is leveraged by our proposed Spatial-weighted Message Passing~(SMP) structure and Spatial-sensitive Relation Inference~(SRI) module to facilitate the relationship recognition. On the recent Visual Relationship Detection and Visual Genome datasets, our method outperforms the state-of-the-art method in both accuracy and speed.

##### Abstract (translated by Google)
生成场景图来描述图像内部的所有关系，这些年来越来越受到关注。然而，大多数先前的方法使用具有慢推理速度的复杂结构或依赖于外部数据，这限制了模型在现实场景中的使用。为了提高场景图生成的效率，我们提出了一个基于子图的连接图，以便在推理过程中简洁地表示场景图。自下而上的聚类方法首先用于将整个场景图分解为子图，其中每个子图包含多个对象及其关系的子集。通过用较少的子图和对象特征替换场景图的众多关系表示，中间阶段的计算显着减少。此外，空间信息由子图的特征维护，我们提出的空间加权消息传递〜（SMP）结构和空间敏感关系推理〜（SRI）模块利用这些特征来促进关系识别。在最近的视觉关系检测和视觉基因组数据集中，我们的方法在准确性和速度方面都优于最先进的方法。

##### URL
[http://arxiv.org/abs/1806.11538](http://arxiv.org/abs/1806.11538)

##### PDF
[http://arxiv.org/pdf/1806.11538](http://arxiv.org/pdf/1806.11538)

