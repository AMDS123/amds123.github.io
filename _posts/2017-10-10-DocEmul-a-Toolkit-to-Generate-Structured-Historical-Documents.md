---
layout: post
title: "DocEmul: a Toolkit to Generate Structured Historical Documents"
date: 2017-10-10 09:40:19
categories: arXiv_CV
tags: arXiv_CV CNN
author: Samuele Capobianco, Simone Marinai
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a toolkit to generate structured synthetic documents emulating the actual document production process. Synthetic documents can be used to train systems to perform document analysis tasks. In our case we address the record counting task on handwritten structured collections containing a limited number of examples. Using the DocEmul toolkit we can generate a larger dataset to train a deep architecture to predict the number of records for each page. The toolkit is able to generate synthetic collections and also perform data augmentation to create a larger trainable dataset. It includes one method to extract the page background from real pages which can be used as a substrate where records can be written on the basis of variable structures and using cursive fonts. Moreover, it is possible to extend the synthetic collection by adding random noise, page rotations, and other visual variations. We performed some experiments on two different handwritten collections using the toolkit to generate synthetic data to train a Convolutional Neural Network able to count the number of records in the real collections.

##### Abstract (translated by Google)
我们提出了一个工具包来生成模拟实际文档生成过程的结构化合成文档。合成文件可以用来训练系统执行文件分析任务。在我们的例子中，我们解决了手写结构化集合的记录计数任务，其中包含有限数量的示例。使用DocEmul工具包，我们可以生成更大的数据集来训练深层架构，以预测每个页面的记录数量。该工具包能够生成合成的集合，还可以执行数据增强以创建更大的可训练数据集。它包括从真实页面中提取页面背景的一种方法，其可以用作基底，其中可以基于变量结构和使用草书字体来写入记录。此外，可以通过添加随机噪声，页面旋转和其他视觉变化来扩展合成集合。我们使用工具包对两个不同的手写集合进行了一些实验，以生成合成数据来训练一个卷积神经网络，它能够计算真实集合中的记录数量。

##### URL
[https://arxiv.org/abs/1710.03474](https://arxiv.org/abs/1710.03474)

##### PDF
[https://arxiv.org/pdf/1710.03474](https://arxiv.org/pdf/1710.03474)

