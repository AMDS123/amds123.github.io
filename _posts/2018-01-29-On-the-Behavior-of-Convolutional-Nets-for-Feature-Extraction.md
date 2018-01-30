---
layout: post
title: "On the Behavior of Convolutional Nets for Feature Extraction"
date: 2018-01-29 11:56:36
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding CNN Transfer_Learning Represenation_Learning Classification
author: Dario Garcia-Gasulla, Ferran Par&#xe9;s, Armand Vilalta, Jonatan Moreno, Eduard Ayguad&#xe9;, Jes&#xfa;s Labarta, Ulises Cort&#xe9;s, Toyotaro Suzumura
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are representation learning techniques. During training, a deep net is capable of generating a descriptive language of unprecedented size and detail in machine learning. Extracting the descriptive language coded within a trained CNN model (in the case of image data), and reusing it for other purposes is a field of interest, as it provides access to the visual descriptors previously learnt by the CNN after processing millions of images, without requiring an expensive training phase. Contributions to this field (commonly known as feature representation transfer or transfer learning) have been purely empirical so far, extracting all CNN features from a single layer close to the output and testing their performance by feeding them to a classifier. This approach has provided consistent results, although its relevance is limited to classification tasks. In a completely different approach, in this paper we statistically measure the discriminative power of every single feature found within a deep CNN, when used for characterizing every class of 11 datasets. We seek to provide new insights into the behavior of CNN features, particularly the ones from convolutional layers, as this can be relevant for their application to knowledge representation and reasoning. Our results confirm that low and middle level features may behave differently to high level features, but only under certain conditions. We find that all CNN features can be used for knowledge representation purposes both by their presence or by their absence, doubling the information a single CNN feature may provide. We also study how much noise these features may include, and propose a thresholding approach to discard most of it. All these insights have a direct application to the generation of CNN embedding spaces.

##### Abstract (translated by Google)
深度神经网络是表示学习技术。在训练期间，深度网络能够产生机器学习中空前大小和细节的描述性语言。提取在训练的CNN模型（在图像数据的情况下）内编码的描述性语言，并将其用于其他目的是一个感兴趣的领域，因为它提供了在处理数百万个图像之后访问之前由CNN学习的视觉描述符，而不需要昂贵的训练阶段。对这一领域的贡献（通常称为特征表示转移或转移学习）迄今为止是纯粹的经验，从接近输出的单层中提取所有CNN特征，并通过将它们馈送给分类器来测试其性能。这种方法提供了一致的结果，尽管其相关性仅限于分类任务。在一个完全不同的方法中，在本文中，我们统计测量深CNN中发现的每个单一特征的判别能力，用于表征11个数据集中的每一类。我们试图为CNN特征的行为提供新的见解，特别是来自卷积层的特征，因为这可能与其在知识表示和推理中的应用有关。我们的研究结果证实，低层和中层功能的行为可能与高层功能不同，但只能在特定条件下使用。我们发现，所有的CNN特征都可以用于知识表示的目的，无论是通过它们的存在还是通过它们的缺失，将CNN特征可能提供的信息加倍。我们也研究了这些特征可能包含多少噪声，并提出了一个阈值方法来丢弃它的大部分。所有这些见解都直接应用于CNN嵌入空间的生成。

##### URL
[http://arxiv.org/abs/1703.01127](http://arxiv.org/abs/1703.01127)

##### PDF
[http://arxiv.org/pdf/1703.01127](http://arxiv.org/pdf/1703.01127)

