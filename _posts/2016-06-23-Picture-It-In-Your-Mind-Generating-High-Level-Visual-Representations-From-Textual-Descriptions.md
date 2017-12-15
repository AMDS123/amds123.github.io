---
layout: post
title: "Picture It In Your Mind: Generating High Level Visual Representations From Textual Descriptions"
date: 2016-06-23 12:25:09
categories: arXiv_CL
tags: arXiv_CL
author: Fabio Carrara, Andrea Esuli, Tiziano Fagni, Fabrizio Falchi, Alejandro Moreo Fernández
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we tackle the problem of image search when the query is a short textual description of the image the user is looking for. We choose to implement the actual search process as a similarity search in a visual feature space, by learning to translate a textual query into a visual representation. Searching in the visual feature space has the advantage that any update to the translation model does not require to reprocess the, typically huge, image collection on which the search is performed. We propose Text2Vis, a neural network that generates a visual representation, in the visual feature space of the fc6-fc7 layers of ImageNet, from a short descriptive text. Text2Vis optimizes two loss functions, using a stochastic loss-selection method. A visual-focused loss is aimed at learning the actual text-to-visual feature mapping, while a text-focused loss is aimed at modeling the higher-level semantic concepts expressed in language and countering the overfit on non-relevant visual components of the visual loss. We report preliminary results on the MS-COCO dataset.

##### Abstract (translated by Google)
在本文中，当查询是用户正在查找的图像的简短文本描述时，我们解决了图像搜索的问题。我们选择将实际的搜索过程作为视觉特征空间中的相似性搜索来实现，通过学习将文本查询翻译成视觉表示。在视觉特征空间中进行搜索具有以下优点：对翻译模型的任何更新都不需要重新处理在其上执行搜索的，通常是巨大的图像集合。我们提出了Text2Vis，一个神经网络，在一个简短的描述性文本中，在ImageNet的fc6-fc7图层的视觉特征空间中生成一个视觉表示。 Text2Vis使用随机损失选择方法来优化两个损失函数。以视觉为中心的损失旨在学习实际的文本到视觉特征映射，而以文本为中心的损失旨在模拟用语言表达的更高级的语义概念，并且反对在不相关的视觉组件上的视力丧失。我们报告MS-COCO数据集的初步结果。

##### URL
[https://arxiv.org/abs/1606.07287](https://arxiv.org/abs/1606.07287)

##### PDF
[https://arxiv.org/pdf/1606.07287](https://arxiv.org/pdf/1606.07287)

