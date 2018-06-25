---
layout: post
title: "Efficient Semantic Segmentation using Gradual Grouping"
date: 2018-06-22 07:11:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Nikitha Vallurupalli, Sriharsha Annamaneni, Girish Varma, C V Jawahar, Manu Mathew, Soyeb Nagori
mathjax: true
---

* content
{:toc}

##### Abstract
Deep CNNs for semantic segmentation have high memory and run time requirements. Various approaches have been proposed to make CNNs efficient like grouped, shuffled, depth-wise separable convolutions. We study the effectiveness of these techniques on a real-time semantic segmentation architecture like ERFNet for improving run time by over 5X. We apply these techniques to CNN layers partially or fully and evaluate the testing accuracies on Cityscapes dataset. We obtain accuracy vs parameters/FLOPs trade offs, giving accuracy scores for models that can run under specified runtime budgets. We further propose a novel training procedure which starts out with a dense convolution but gradually evolves towards a grouped convolution. We show that our proposed training method and efficient architecture design can improve accuracies by over 8% with depth wise separable convolutions applied on the encoder of ERFNet and attaching a light weight decoder. This results in a model which has a 5X improvement in FLOPs while only suffering a 4% degradation in accuracy with respect to ERFNet.

##### Abstract (translated by Google)
用于语义分割的深层CNN具有高内存和运行时间要求。已经提出了各种方法来使CNN像分组的，混洗的，深度方向可分离的卷积一样高效。我们研究这些技术在像ERFNet这样的实时语义分割体系结构上的有效性，以将运行时间提高5倍以上。我们将这些技术部分或全部应用于CNN图层，并评估Cityscapes数据集的测试精度。我们获得准确性与参数/ FLOP的权衡，为在指定的运行时预算下运行的模型提供准确性分数。我们进一步提出了一种新的训练过程，该过程始于密集卷积，但逐渐演变为分组卷积。我们表明，我们提出的训练方法和高效的架构设计可以提高精度超过8％，深度明智的可分卷积应用于ERFNet的编码器和附加轻量级解码器。这导致了一个模型，其FLOPs的改进度提高了5倍，而ERFNet的准确度只有4％的降低。

##### URL
[http://arxiv.org/abs/1806.08522](http://arxiv.org/abs/1806.08522)

##### PDF
[http://arxiv.org/pdf/1806.08522](http://arxiv.org/pdf/1806.08522)

