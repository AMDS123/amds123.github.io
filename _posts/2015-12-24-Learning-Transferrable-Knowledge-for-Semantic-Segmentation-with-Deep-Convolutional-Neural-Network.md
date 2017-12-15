---
layout: post
title: "Learning Transferrable Knowledge for Semantic Segmentation with Deep Convolutional Neural Network"
date: 2015-12-24 22:33:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention CNN Semantic_Segmentation
author: Seunghoon Hong, Junhyuk Oh, Bohyung Han, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel weakly-supervised semantic segmentation algorithm based on Deep Convolutional Neural Network (DCNN). Contrary to existing weakly-supervised approaches, our algorithm exploits auxiliary segmentation annotations available for different categories to guide segmentations on images with only image-level class labels. To make the segmentation knowledge transferrable across categories, we design a decoupled encoder-decoder architecture with attention model. In this architecture, the model generates spatial highlights of each category presented in an image using an attention model, and subsequently generates foreground segmentation for each highlighted region using decoder. Combining attention model, we show that the decoder trained with segmentation annotations in different categories can boost the performance of weakly-supervised semantic segmentation. The proposed algorithm demonstrates substantially improved performance compared to the state-of-the-art weakly-supervised techniques in challenging PASCAL VOC 2012 dataset when our model is trained with the annotations in 60 exclusive categories in Microsoft COCO dataset.

##### Abstract (translated by Google)
我们提出了一种基于深度卷积神经网络（DCNN）的弱监督语义分割算法。与现有的弱监督方法相反，我们的算法利用可用于不同类别的辅助分割注释来引导图像上仅具有图像级别类别标签的分割。为了使分割知识跨类别转移，我们设计了一个具有注意模型的解耦编码器 - 解码器体系结构。在这个架构中，模型使用注意模型生成图像中呈现的每个类别的空间亮点，随后使用解码器为每个高亮区域生成前景分割。结合注意模型，我们发现用不同类别的分词注解训练的解码器可以提高弱监督语义分割的性能。与我们现有技术的弱监督技术相比，当我们的模型在Microsoft COCO数据集中使用60个独占类别中的注释进行训练时，所提出的算法表现出大大改善的性能，用于挑战PASCAL VOC 2012数据集。

##### URL
[https://arxiv.org/abs/1512.07928](https://arxiv.org/abs/1512.07928)

##### PDF
[https://arxiv.org/pdf/1512.07928](https://arxiv.org/pdf/1512.07928)

