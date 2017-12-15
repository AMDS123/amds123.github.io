---
layout: post
title: "Learning Local Image Descriptors with Deep Siamese and Triplet Convolutional Networks by Minimising Global Loss Functions"
date: 2016-08-01 06:47:57
categories: arXiv_CV
tags: arXiv_CV Embedding CNN Classification Gradient_Descent
author: Vijay Kumar B G, Gustavo Carneiro, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Recent innovations in training deep convolutional neural network (ConvNet) models have motivated the design of new methods to automatically learn local image descriptors. The latest deep ConvNets proposed for this task consist of a siamese network that is trained by penalising misclassification of pairs of local image patches. Current results from machine learning show that replacing this siamese by a triplet network can improve the classification accuracy in several problems, but this has yet to be demonstrated for local image descriptor learning. Moreover, current siamese and triplet networks have been trained with stochastic gradient descent that computes the gradient from individual pairs or triplets of local image patches, which can make them prone to overfitting. In this paper, we first propose the use of triplet networks for the problem of local image descriptor learning. Furthermore, we also propose the use of a global loss that minimises the overall classification error in the training set, which can improve the generalisation capability of the model. Using the UBC benchmark dataset for comparing local image descriptors, we show that the triplet network produces a more accurate embedding than the siamese network in terms of the UBC dataset errors. Moreover, we also demonstrate that a combination of the triplet and global losses produces the best embedding in the field, using this triplet network. Finally, we also show that the use of the central-surround siamese network trained with the global loss produces the best result of the field on the UBC dataset. Pre-trained models are available online at this https URL

##### Abstract (translated by Google)
近来在深度卷积神经网络（ConvNet）模型训练中的创新已经促使设计自动学习局部图像描述符的新方法。为此任务提出的最新深度网络包括一个通过惩罚对局部图像补丁的错误分类而训练的暹罗网络。目前机器学习的结果表明，用三元网络替代这种连体可以提高分类精度的几个问题，但是对于局部图像描述符学习还没有得到证明。此外，目前的连体和三重网络已经用随机梯度下降训练，计算从局部图像块的单个对或三元组的梯度，这可能使其倾向于过拟合。在本文中，我们首先提出使用三重网络的局部图像描述符学习问题。此外，我们还提出使用全局损失来最小化训练集中的总分类错误，这可以提高模型的泛化能力。使用UBC基准数据集来比较局部图像描述符，我们显示三重网络在UBC数据集错误方面产生比暹罗网络更精确的嵌入。此外，我们还证明，使用这个三重网络，三重和全局损失的组合在现场产生了最好的嵌入。最后，我们还表明，使用受到全球损失训练的中央 - 环绕暹罗网络在UBC数据集上产生了最好的场地效果。预先训练的模型可通过此https URL在线获得

##### URL
[https://arxiv.org/abs/1512.09272](https://arxiv.org/abs/1512.09272)

##### PDF
[https://arxiv.org/pdf/1512.09272](https://arxiv.org/pdf/1512.09272)

