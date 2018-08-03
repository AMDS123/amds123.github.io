---
layout: post
title: "Dynamic Adaptation on Non-Stationary Visual Domains"
date: 2018-08-02 09:49:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Classification
author: Sindi Shkodrani, Michael Hofmann, Efstratios Gavves
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation aims to learn models on a supervised source domain that perform well on an unsupervised target. Prior work has examined domain adaptation in the context of stationary domain shifts, i.e. static data sets. However, with large-scale or dynamic data sources, data from a defined domain is not usually available all at once. For instance, in a streaming data scenario, dataset statistics effectively become a function of time. We introduce a framework for adaptation over non-stationary distribution shifts applicable to large-scale and streaming data scenarios. The model is adapted sequentially over incoming unsupervised streaming data batches. This enables improvements over several batches without the need for any additionally annotated data. To demonstrate the effectiveness of our proposed framework, we modify associative domain adaptation to work well on source and target data batches with unequal class distributions. We apply our method to several adaptation benchmark datasets for classification and show improved classifier accuracy not only for the currently adapted batch, but also when applied on future stream batches. Furthermore, we show the applicability of our associative learning modifications to semantic segmentation, where we achieve competitive results.

##### Abstract (translated by Google)
域适应旨在学习在无监督目标上表现良好的受监督源域上的模型。先前的工作已经在静止域移位（即静态数据集）的背景下检查了域自适应。但是，对于大规模或动态数据源，来自定义域的数据通常不会同时可用。例如，在流数据场景中，数据集统计有效地成为时间的函数。我们引入了适用于大规模和流数据场景的非平稳分布转换的适应框架。在输入的无监督流数据批次上顺序地调整模型。这样可以在几个批次中进行改进，而无需任何额外的注释数据。为了证明我们提出的框架的有效性，我们修改了关联域自适应，以便在具有不相等类分布的源和目标数据批处理中很好地工作。我们将我们的方法应用于几个适应性基准数据集以进行分类，并且不仅针对当前适应的批次，而且当应用于未来的流批次时，显示出改进的分类器准确性。此外，我们展示了我们的联想学习修改对语义分割的适用性，我们在其中获得了竞争结果。

##### URL
[http://arxiv.org/abs/1808.00736](http://arxiv.org/abs/1808.00736)

##### PDF
[http://arxiv.org/pdf/1808.00736](http://arxiv.org/pdf/1808.00736)

