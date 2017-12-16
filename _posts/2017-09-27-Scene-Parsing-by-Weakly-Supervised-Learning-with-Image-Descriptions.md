---
layout: post
title: "Scene Parsing by Weakly Supervised Learning with Image Descriptions"
date: 2017-09-27 13:17:41
categories: arXiv_CV
tags: arXiv_CV Image_Caption Weakly_Supervised CNN Deep_Learning Relation
author: Ruimao Zhang, Liang Lin, Guangrun Wang, Meng Wang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates a fundamental problem of scene understanding: how to parse a scene image into a structured configuration (i.e., a semantic object hierarchy with object interaction relations). We propose a deep architecture consisting of two networks: i) a convolutional neural network (CNN) extracting the image representation for pixel-wise object labeling and ii) a recursive neural network (RsNN) discovering the hierarchical object structure and the inter-object relations. Rather than relying on elaborative annotations (e.g., manually labeled semantic maps and relations), we train our deep model in a weakly-supervised learning manner by leveraging the descriptive sentences of the training images. Specifically, we decompose each sentence into a semantic tree consisting of nouns and verb phrases, and apply these tree structures to discover the configurations of the training images. Once these scene configurations are determined, then the parameters of both the CNN and RsNN are updated accordingly by back propagation. The entire model training is accomplished through an Expectation-Maximization method. Extensive experiments show that our model is capable of producing meaningful and structured scene configurations, and achieving more favorable scene labeling results on PASCAL VOC 2012 and SYSU-Scenes datasets compared to other state-of-the-art weakly-supervised deep learning methods. In particular, SYSU-Scenes is a dedicated dataset released by us to facilitate further research on scene parsing, which contains more than 5000 scene images with their sentence-based semantic descriptions.

##### Abstract (translated by Google)
本文研究了场景理解的基本问题：如何将场景图像解析为结构化配置（即具有对象交互关系的语义对象层次结构）。我们提出了一个由两个网络组成的深层架构：一个卷积神经网络（CNN）提取像素对象标记的图像表示和ii）发现分层对象结构和对象间关系的递归神经网络（RsNN） 。我们通过利用训练图像的描述性句子，以弱监督的学习方式训练我们的深层模型，而不是依靠精细的注释（例如，手动标记的语义图和关系）。具体而言，我们将每个句子分解成由名词和动词短语组成的语义树，并将这些树结构应用于发现训练图像的配置。一旦确定了这些场景配置，则通过反向传播相应地更新CNN和RsNN的参数。整个模型训练是通过期望最大化方法完成的。大量的实验表明，与其他先进的弱监督深度学习方法相比，我们的模型能够产生有意义和结构化的场景配置，并且在PASCAL VOC 2012和SYSU-Scenes数据集上获得更有利的场景标记结果。特别是SYSU-Scenes是我们发布的一个专用数据集，用于进一步研究场景解析，其中包含超过5000个场景图像以及基于句子的语义描述。

##### URL
[https://arxiv.org/abs/1709.09490](https://arxiv.org/abs/1709.09490)

##### PDF
[https://arxiv.org/pdf/1709.09490](https://arxiv.org/pdf/1709.09490)

