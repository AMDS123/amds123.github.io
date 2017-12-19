---
layout: post
title: "Deep Learning for Semantic Part Segmentation with High-Level Guidance"
date: 2015-11-24 14:22:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Face CNN Semantic_Segmentation Deep_Learning Quantitative Detection
author: S. Tsogkas, I. Kokkinos, G. Papandreou, A. Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we address the task of segmenting an object into its parts, or semantic part segmentation. We start by adapting a state-of-the-art semantic segmentation system to this task, and show that a combination of a fully-convolutional Deep CNN system coupled with Dense CRF labelling provides excellent results for a broad range of object categories. Still, this approach remains agnostic to high-level constraints between object parts. We introduce such prior information by means of the Restricted Boltzmann Machine, adapted to our task and train our model in an discriminative fashion, as a hidden CRF, demonstrating that prior information can yield additional improvements. We also investigate the performance of our approach ``in the wild'', without information concerning the objects' bounding boxes, using an object detector to guide a multi-scale segmentation scheme. We evaluate the performance of our approach on the Penn-Fudan and LFW datasets for the tasks of pedestrian parsing and face labelling respectively. We show superior performance with respect to competitive methods that have been extensively engineered on these benchmarks, as well as realistic qualitative results on part segmentation, even for occluded or deformable objects. We also provide quantitative and extensive qualitative results on three classes from the PASCAL Parts dataset. Finally, we show that our multi-scale segmentation scheme can boost accuracy, recovering segmentations for finer parts.

##### Abstract (translated by Google)
在这项工作中，我们解决了将对象分割成其部分或者语义部分分割的任务。我们首先将最先进的语义分割系统应用于这项任务，并且证明了全深度CNN系统与密集CRF标签结合的组合为广泛的对象类别提供了极好的结果。尽管如此，这种方法仍然与对象部分之间的高级约束无关。我们通过受限玻尔兹曼机器引入这些先验信息，适应我们的任务，并以歧视的方式训练我们的模型，作为隐藏的CRF，证明先前的信息可​​以产生额外的改进。我们还调查了我们在野外的方法的性能，没有关于物体边界框的信息，使用一个物体检测器来指导多尺度分割方案。我们分别在Penn-Fudan和LFW数据集上评估我们的方法在行人分析和面部标记任务中的性能。我们展示了在这些基准上广泛设计的竞争方法的优越性能，以及在零件分割方面的实际定性结果，即使是被遮挡或可变形的物体。我们还提供了PASCAL Parts数据集的三个类的定量和广泛的定性结果。最后，我们展示了我们的多尺度分割方案可以提高准确性，恢复更精细部分的分割。

##### URL
[https://arxiv.org/abs/1505.02438](https://arxiv.org/abs/1505.02438)

##### PDF
[https://arxiv.org/pdf/1505.02438](https://arxiv.org/pdf/1505.02438)

