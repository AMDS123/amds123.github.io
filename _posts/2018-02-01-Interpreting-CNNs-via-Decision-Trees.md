---
layout: post
title: "Interpreting CNNs via Decision Trees"
date: 2018-02-01 01:47:15
categories: arXiv_CV
tags: arXiv_CV GAN CNN Prediction Quantitative
author: Quanshi Zhang, Yu Yang, Ying Nian Wu, Song-Chun Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method to learn a decision tree to quantitatively explain the logic of each prediction of a pre-trained convolutional neural networks (CNNs). Our method boosts the following two aspects of network interpretability. 1) In the CNN, each filter in a high conv-layer must represent a specific object part, instead of describing mixed patterns without clear meanings. 2) People can explain each specific prediction made by the CNN at the semantic level using a decision tree, i.e., which filters (or object parts) are used for prediction and how much they contribute in the prediction. To conduct such a quantitative explanation of a CNN, our method learns explicit representations of object parts in high conv-layers of the CNN and mines potential decision modes memorized in fully-connected layers. The decision tree organizes these potential decision modes in a coarse-to-fine manner. Experiments have demonstrated the effectiveness of the proposed method.

##### Abstract (translated by Google)
本文提出了一种学习决策树的方法来定量解释预先训练的卷积神经网络（CNN）的每个预测的逻辑。我们的方法提高了网络可解释性的两个方面。 1）在CNN中，高频层中的每个过滤器必须表示一个特定的对象部分，而不是描述没有明确含义的混合模式。 2）人们可以使用决策树来解释由CNN在语义层次上做出的每个特定的预测，即，哪些过滤器（或对象部分）被用于预测，以及他们在预测中贡献了多少。为了对CNN进行这样的量化解释，我们的方法学习CNN的高频层中的对象部分的显式表示，并挖掘存储在完全连接层中的潜在决策模式。决策树以粗放的方式组织这些潜在的决策模式。实验已经证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1802.00121](http://arxiv.org/abs/1802.00121)

##### PDF
[http://arxiv.org/pdf/1802.00121](http://arxiv.org/pdf/1802.00121)

