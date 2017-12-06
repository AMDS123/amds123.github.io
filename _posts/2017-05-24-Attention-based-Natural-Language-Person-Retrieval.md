---
layout: post
title: 'Attention-based Natural Language Person Retrieval'
date: 2017-05-24 18:36:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Caption CNN RNN Deep_Learning
author: Tao Zhou, Muhao Chen, Jie Yu, Demetri Terzopoulos
---

* content
{:toc}

##### Abstract
Following the recent progress in image classification and captioning using deep learning, we develop a novel natural language person retrieval system based on an attention mechanism. More specifically, given the description of a person, the goal is to localize the person in an image. To this end, we first construct a benchmark dataset for natural language person retrieval. To do so, we generate bounding boxes for persons in a public image dataset from the segmentation masks, which are then annotated with descriptions and attributes using the Amazon Mechanical Turk. We then adopt a region proposal network in Faster R-CNN as a candidate region generator. The cropped images based on the region proposals as well as the whole images with attention weights are fed into Convolutional Neural Networks for visual feature extraction, while the natural language expression and attributes are input to Bidirectional Long Short- Term Memory (BLSTM) models for text feature extraction. The visual and text features are integrated to score region proposals, and the one with the highest score is retrieved as the output of our system. The experimental results show significant improvement over the state-of-the-art method for generic object retrieval and this line of research promises to benefit search in surveillance video footage.

##### Abstract (translated by Google)
随着近年来深度学习图像分类和字幕的进展，我们开发了一种基于注意机制的新型自然语言人物检索系统。更具体地说，给定一个人的描述，目标是将该人定位在图像中。为此，我们首先构建一个自然语言人检索的基准数据集。为此，我们从分割掩模为公共图像数据集中的人员生成边界框，然后使用Amazon Mechanical Turk为其描述和属性注释。然后，我们采用R-CNN更快的区域提案网络作为候选区域生成器。基于区域提议的裁剪图像以及具有注意权重的整个图像被馈送到用于视觉特征提取的卷积神经网络，而自然语言表达和属性被输入到用于文本的双向长期短期存储器（BLSTM）模型特征提取。将视觉和文本特征整合到评分区域提案中，得分最高的评分作为系统的输出。实验结果表明，相对于最先进的通用对象检索方法而言，这种方法有了显着的改进，而且这一系列的研究有望在监视录像中进行搜索。

##### URL
[https://arxiv.org/abs/1705.08923](https://arxiv.org/abs/1705.08923)

