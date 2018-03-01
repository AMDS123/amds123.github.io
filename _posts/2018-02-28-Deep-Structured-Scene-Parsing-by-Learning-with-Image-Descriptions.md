---
layout: post
title: "Deep Structured Scene Parsing by Learning with Image Descriptions"
date: 2018-02-28 02:38:51
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN RNN Relation
author: Liang Lin, Guangrun Wang, Rui Zhang, Ruimao Zhang, Xiaodan Liang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses a fundamental problem of scene understanding: How to parse the scene image into a structured configuration (i.e., a semantic object hierarchy with object interaction relations) that finely accords with human perception. We propose a deep architecture consisting of two networks: i) a convolutional neural network (CNN) extracting the image representation for pixelwise object labeling and ii) a recursive neural network (RNN) discovering the hierarchical object structure and the inter-object relations. Rather than relying on elaborative user annotations (e.g., manually labeling semantic maps and relations), we train our deep model in a weakly-supervised manner by leveraging the descriptive sentences of the training images. Specifically, we decompose each sentence into a semantic tree consisting of nouns and verb phrases, and facilitate these trees discovering the configurations of the training images. Once these scene configurations are determined, then the parameters of both the CNN and RNN are updated accordingly by back propagation. The entire model training is accomplished through an Expectation-Maximization method. Extensive experiments suggest that our model is capable of producing meaningful and structured scene configurations and achieving more favorable scene labeling performance on PASCAL VOC 2012 over other state-of-the-art weakly-supervised methods.

##### Abstract (translated by Google)
本文讨论场景理解的一个基本问题：如何将场景图像解析为与人类感知完美契合的结构化配置（即具有对象交互关系的语义对象层次结构）。我们提出了一个由两个网络组成的深层架构：i）卷积神经网络（CNN）提取像素对象标记的图像表示; ii）发现分层对象结构和对象间关系的递归神经网络（RNN）。我们不是依靠详尽的用户注释（例如手动标注语义地图和关系），而是通过利用训练图像的描述性句子以弱监督的方式训练我们的深层模型。具体来说，我们将每个句子分解成一个由名词和动词短语组成的语义树，并且便于这些树发现训练图像的配置。一旦确定了这些场景配置，则通过反向传播相应地更新CNN和RNN的参数。整个模型训练通过期望最大化方法完成。大量的实验表明，我们的模型能够产生有意义和结构化的场景配置，并且在PASCAL VOC 2012上比其他最先进的弱监督方法获得更有利的场景标记性能。

##### URL
[http://arxiv.org/abs/1604.02271](http://arxiv.org/abs/1604.02271)

##### PDF
[http://arxiv.org/pdf/1604.02271](http://arxiv.org/pdf/1604.02271)

