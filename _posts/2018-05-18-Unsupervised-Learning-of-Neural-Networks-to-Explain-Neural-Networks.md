---
layout: post
title: "Unsupervised Learning of Neural Networks to Explain Neural Networks"
date: 2018-05-18 23:02:14
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN
author: Quanshi Zhang, Yu Yang, Yuchen Liu, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an unsupervised method to learn a neural network, namely an explainer, to interpret a pre-trained convolutional neural network (CNN), i.e., explaining knowledge representations hidden in middle conv-layers of the CNN. Given feature maps of a certain conv-layer of the CNN, the explainer performs like an auto-encoder, which first disentangles the feature maps into object-part features and then inverts object-part features back to features of higher conv-layers of the CNN. More specifically, the explainer contains interpretable conv-layers, where each filter disentangles the representation of a specific object part from chaotic input feature maps. As a paraphrase of CNN features, the disentangled representations of object parts help people understand the logic inside the CNN. We also learn the explainer to use object-part features to reconstruct features of higher CNN layers, in order to minimize loss of information during the feature disentanglement. More crucially, we learn the explainer via network distillation without using any annotations of sample labels, object parts, or textures for supervision. We have applied our method to different types of CNNs for evaluation, and explainers have significantly boosted the interpretability of CNN features.

##### Abstract (translated by Google)
本文提出了一种用于学习神经网络的无监督方法，即解释器来解释预先训练的卷积神经网络（CNN），即解释隐藏在CNN的中间卷积层中的知识表示。给定CNN的某个conv-layer的特征映射，解释器像自动编码器一样执行，首先将特征映射分解为对象部分特征，然后将对象部分特征反转回到CNN。更具体地说，解释器包含可解释的信息层，其中每个过滤器从混沌输入特征图中解开特定对象部分的表示。作为CNN特征的解释，对象部分的解开表示有助于人们理解CNN内部的逻辑。我们还学习解释器使用对象部分特征来重建较高CNN层的特征，以便在特征解开期间最小化信息的丢失。更重要的是，我们通过网络蒸馏来学习解释器，而不使用样本标签，对象部件或纹理的任何注释来进行监督。我们已经将我们的方法应用于不同类型的CNN进行评估，并且解释者显着提高了CNN功能的可解释性。

##### URL
[https://arxiv.org/abs/1805.07468](https://arxiv.org/abs/1805.07468)

##### PDF
[https://arxiv.org/pdf/1805.07468](https://arxiv.org/pdf/1805.07468)

