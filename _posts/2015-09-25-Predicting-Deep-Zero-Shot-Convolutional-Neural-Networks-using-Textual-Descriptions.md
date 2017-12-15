---
layout: post
title: "Predicting Deep Zero-Shot Convolutional Neural Networks using Textual Descriptions"
date: 2015-09-25 16:20:44
categories: arXiv_CV
tags: arXiv_CV Embedding CNN
author: Jimmy Ba, Kevin Swersky, Sanja Fidler, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
One of the main challenges in Zero-Shot Learning of visual categories is gathering semantic attributes to accompany images. Recent work has shown that learning from textual descriptions, such as Wikipedia articles, avoids the problem of having to explicitly define these attributes. We present a new model that can classify unseen categories from their textual description. Specifically, we use text features to predict the output weights of both the convolutional and the fully connected layers in a deep convolutional neural network (CNN). We take advantage of the architecture of CNNs and learn features at different layers, rather than just learning an embedding space for both modalities, as is common with existing approaches. The proposed model also allows us to automatically generate a list of pseudo- attributes for each visual category consisting of words from Wikipedia articles. We train our models end-to-end us- ing the Caltech-UCSD bird and flower datasets and evaluate both ROC and Precision-Recall curves. Our empirical results show that the proposed model significantly outperforms previous methods.

##### Abstract (translated by Google)
零视觉类别学习中的一个主要挑战是收集语义属性以伴随图像。最近的工作表明，从诸如维基百科文章的文本描述中学习，避免了必须明确定义这些属性的问题。我们提出了一个新的模型，可以从他们的文本描述分类看不见的类别。具体而言，我们使用文本特征来预测深度​​卷积神经网络（CNN）中的卷积层和完全连接层的输出权重。我们利用CNN的体系结构，在不同的层次上学习特性，而不是像现有的方法一样学习两种模式的嵌入空间。所提出的模型还允许我们自动生成每个视觉类别的伪属性列表，包括维基百科文章中的单词。我们使用Caltech-UCSD鸟和花数据集端对端地训练我们的模型，并评估ROC和Precision-Recall曲线。我们的实证结果表明，该模型显着优于以前的方法。

##### URL
[https://arxiv.org/abs/1506.00511](https://arxiv.org/abs/1506.00511)

##### PDF
[https://arxiv.org/pdf/1506.00511](https://arxiv.org/pdf/1506.00511)

