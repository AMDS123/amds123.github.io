---
layout: post
title: "Model compression for faster structural separation of macromolecules captured by Cellular Electron Cryo-Tomography"
date: 2018-01-31 18:39:41
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Prediction
author: Jialiang Guo, Bo Zhou, Xiangrui Zeng, Zachary Freyberg, Min Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Electron Cryo-Tomography (ECT) enables 3D visualization of macromolecule structure inside single cells. Macromolecule classification approaches based on convolutional neural networks (CNN) were developed to separate millions of macromolecules captured from ECT systematically. However, given the fast accumulation of ECT data, it will soon become necessary to use CNN models to efficiently and accurately separate substantially more macromolecules at the prediction stage, which requires additional computational costs. To speed up the prediction, we compress classification models into compact neural networks with little in accuracy for deployment. Specifically, we propose to perform model compression through knowledge distillation. Firstly, a complex teacher network is trained to generate soft labels with better classification feasibility followed by training of customized student networks with simple architectures using the soft label to compress model complexity. Our tests demonstrate that our compressed models significantly reduce the number of parameters and time cost while maintaining similar classification accuracy.

##### Abstract (translated by Google)
电子冷冻层析成像（ECT）使单细胞内的大分子结构的三维可视化成为可能。开发了基于卷积神经网络（CNN）的大分子分类方法，系统地从ECT中分离出数以百万计的大分子。但是，由于ECT数据的快速积累，很快将有必要使用CNN模型在预测阶段有效且精确地分离更多的大分子，这需要额外的计算成本。为了加速预测，我们将分类模型压缩成紧凑的神经网络，部署的准确性很低。具体而言，我们建议通过知识蒸馏来进行模型压缩。首先，训练复杂的教师网络以生成具有更好的分类可行性的软标签，然后使用软标签来训练定制的学生网络，使用软标签来压缩模型的复杂性。我们的测试表明，我们的压缩模​​型显着减少了参数和时间成本的数量，同时保持类似的分类精度。

##### URL
[http://arxiv.org/abs/1801.10597](http://arxiv.org/abs/1801.10597)

##### PDF
[http://arxiv.org/pdf/1801.10597](http://arxiv.org/pdf/1801.10597)

