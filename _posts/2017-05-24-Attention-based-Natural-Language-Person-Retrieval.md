---
layout: post
title: "Attention-based Natural Language Person Retrieval"
date: 2017-05-24 18:36:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Caption CNN Image_Classification RNN Classification Deep_Learning
author: Tao Zhou, Muhao Chen, Jie Yu, Demetri Terzopoulos
mathjax: true
---

* content
{:toc}

##### Abstract
Following the recent progress in image classification and captioning using deep learning, we develop a novel natural language person retrieval system based on an attention mechanism. More specifically, given the description of a person, the goal is to localize the person in an image. To this end, we first construct a benchmark dataset for natural language person retrieval. To do so, we generate bounding boxes for persons in a public image dataset from the segmentation masks, which are then annotated with descriptions and attributes using the Amazon Mechanical Turk. We then adopt a region proposal network in Faster R-CNN as a candidate region generator. The cropped images based on the region proposals as well as the whole images with attention weights are fed into Convolutional Neural Networks for visual feature extraction, while the natural language expression and attributes are input to Bidirectional Long Short- Term Memory (BLSTM) models for text feature extraction. The visual and text features are integrated to score region proposals, and the one with the highest score is retrieved as the output of our system. The experimental results show significant improvement over the state-of-the-art method for generic object retrieval and this line of research promises to benefit search in surveillance video footage.

##### Abstract (translated by Google)
随着最近在图像分类和使用深度学习的字幕方面的进展，我们开发了一种基于注意机制的新型自然语言人物检索系统。更具体地，给定人的描述，目标是将人物本地化为图像。为此，我们首先构建了一个用于自然语言人物检索的基准数据集。为此，我们从分段掩码为公共图像数据集中的人生成边界框，然后使用Amazon Mechanical Turk对描述和属性进行注释。然后，我们在快速R-CNN中采用区域提议网络作为候选区域生成器。基于区域提议的裁剪图像以及具有注意权重的整个图像被馈送到用于视觉特征提取的卷积神经网络，而自然语言表达和属性被输入到用于文本的双向长短期记忆（BLSTM）模型。特征提取。视觉和文本功能被集成到得分区域提案中，并且具有最高得分的那个被检索作为我们系统的输出。实验结果显示了对通用对象检索的最新方法的显着改进，并且这一系列研究有望使监控录像中的搜索受益。

##### URL
[https://arxiv.org/abs/1705.08923](https://arxiv.org/abs/1705.08923)

##### PDF
[https://arxiv.org/pdf/1705.08923](https://arxiv.org/pdf/1705.08923)

