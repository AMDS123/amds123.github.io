---
layout: post
title: "Hierarchical Scene Parsing by Weakly Supervised Learning with Image Descriptions"
date: 2018-01-27 03:25:40
categories: arXiv_CV
tags: arXiv_CV Image_Caption Weakly_Supervised CNN Deep_Learning Relation
author: Ruimao Zhang, Liang Lin, Guangrun Wang, Meng Wang, Wangmeng Zuo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates a fundamental problem of scene understanding: how to parse a scene image into a structured configuration (i.e., a semantic object hierarchy with object interaction relations). We propose a deep architecture consisting of two networks: i) a convolutional neural network (CNN) extracting the image representation for pixel-wise object labeling and ii) a recursive neural network (RsNN) discovering the hierarchical object structure and the inter-object relations. Rather than relying on elaborative annotations (e.g., manually labeled semantic maps and relations), we train our deep model in a weakly-supervised learning manner by leveraging the descriptive sentences of the training images. Specifically, we decompose each sentence into a semantic tree consisting of nouns and verb phrases, and apply these tree structures to discover the configurations of the training images. Once these scene configurations are determined, then the parameters of both the CNN and RsNN are updated accordingly by back propagation. The entire model training is accomplished through an Expectation-Maximization method. Extensive experiments show that our model is capable of producing meaningful scene configurations and achieving more favorable scene labeling results on two benchmarks (i.e., PASCAL VOC 2012 and SYSU-Scenes) compared with other state-of-the-art weakly-supervised deep learning methods. In particular, SYSU-Scenes contains more than 5000 scene images with their semantic sentence descriptions, which is created by us for advancing research on scene parsing.

##### Abstract (translated by Google)
本文研究了场景理解的基本问题：如何将场景图像解析为结构化配置（即具有对象交互关系的语义对象层次结构）。我们提出了一个由两个网络组成的深层架构：一个卷积神经网络（CNN）提取像素对象标记的图像表示和ii）发现分层对象结构和对象间关系的递归神经网络（RsNN） 。我们通过利用训练图像的描述性句子，以弱监督的学习方式训练我们的深层模型，而不是依靠精细的注释（例如，手动标记的语义图和关系）。具体而言，我们将每个句子分解成由名词和动词短语组成的语义树，并将这些树结构应用于发现训练图像的配置。一旦确定了这些场景配置，则通过反向传播相应地更新CNN和RsNN的参数。整个模型训练是通过期望最大化方法完成的。大量的实验表明，与其他先进的弱监督深度学习方法相比，我们的模型能够产生有意义的场景配置，并在两个基准（即PASCAL VOC 2012和SYSU-Scenes）上实现更有利的场景标记结果。特别是SYSU-Scenes包含了超过5000个带有语义描述的场景图像，这是我们为了推进场景解析研究而创建的。

##### URL
[http://arxiv.org/abs/1709.09490](http://arxiv.org/abs/1709.09490)

##### PDF
[http://arxiv.org/pdf/1709.09490](http://arxiv.org/pdf/1709.09490)

