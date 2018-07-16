---
layout: post
title: "CascadeCNN: Pushing the Performance Limits of Quantisation in Convolutional Neural Networks"
date: 2018-07-13 13:21:18
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Alexandros Kouris, Stylianos I. Venieris, Christos-Savvas Bouganis
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents CascadeCNN, an automated toolflow that pushes the quantisation limits of any given CNN model, aiming to perform high-throughput inference. A two-stage architecture tailored for any given CNN-FPGA pair is generated, consisting of a low- and high-precision unit in a cascade. A confidence evaluation unit is employed to identify misclassified cases from the excessively low-precision unit and forward them to the high-precision unit for re-processing. Experiments demonstrate that the proposed toolflow can achieve a performance boost up to 55% for VGG-16 and 48% for AlexNet over the baseline design for the same resource budget and accuracy, without the need of retraining the model or accessing the training data.

##### Abstract (translated by Google)
这项工作提出了CascadeCNN，这是一个自动化工具流程，可以推动任何给定CNN模型的量化限制，旨在执行高吞吐量推理。生成为任何给定CNN-FPGA对量身定制的两级架构，由级联中的低精度和高精度单元组成。采用置信度评估单元从过低精度的单元中识别错误分类的情况，并将它们转发到高精度单元进行重新处理。实验表明，对于相同的资源预算和准确度，所提出的工具流可以使VGG-16的性能提升高达55％，而AlexNet的性能提升高达基线设计的48％，而无需重新训练模型或访问训练数据。

##### URL
[http://arxiv.org/abs/1807.05053](http://arxiv.org/abs/1807.05053)

##### PDF
[http://arxiv.org/pdf/1807.05053](http://arxiv.org/pdf/1807.05053)

