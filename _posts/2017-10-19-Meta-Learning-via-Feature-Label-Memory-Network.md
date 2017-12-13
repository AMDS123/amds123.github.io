---
layout: post
title: "Meta-Learning via Feature-Label Memory Network"
date: 2017-10-19 12:08:59
categories: arXiv_CV
tags: arXiv_CV Inference Classification Deep_Learning Prediction
author: Dawit Mureja, Hyunsin Park, Chang D. Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning typically requires training a very capable architecture using large datasets. However, many important learning problems demand an ability to draw valid inferences from small size datasets, and such problems pose a particular challenge for deep learning. In this regard, various researches on "meta-learning" are being actively conducted. Recent work has suggested a Memory Augmented Neural Network (MANN) for meta-learning. MANN is an implementation of a Neural Turing Machine (NTM) with the ability to rapidly assimilate new data in its memory, and use this data to make accurate predictions. In models such as MANN, the input data samples and their appropriate labels from previous step are bound together in the same memory locations. This often leads to memory interference when performing a task as these models have to retrieve a feature of an input from a certain memory location and read only the label information bound to that location. In this paper, we tried to address this issue by presenting a more robust MANN. We revisited the idea of meta-learning and proposed a new memory augmented neural network by explicitly splitting the external memory into feature and label memories. The feature memory is used to store the features of input data samples and the label memory stores their labels. Hence, when predicting the label of a given input, our model uses its feature memory unit as a reference to extract the stored feature of the input, and based on that feature, it retrieves the label information of the input from the label memory unit. In order for the network to function in this framework, a new memory-writingmodule to encode label information into the label memory in accordance with the meta-learning task structure is designed. Here, we demonstrate that our model outperforms MANN by a large margin in supervised one-shot classification tasks using Omniglot and MNIST datasets.

##### Abstract (translated by Google)
深入学习通常需要使用大型数据集来训练一个非常有能力的架构然而，许多重要的学习问题都要求能够从小尺寸的数据集中得出有效的推论，而这些问题对深度学习提出了特别的挑战。在这方面，各种关于“元学习”的研究正在积极进行。最近的工作已经提出了用于元学习的记忆增强神经网络（MANN）。 MANN是一个神经图灵机（NTM）的实现，能够快速吸收内存中的新数据，并使用这些数据做出准确的预测。在诸如MANN的模型中，输入数据样本及其上一步的相应标签在相同的存储位置绑定在一起。这在执行任务时经常导致内存干扰，因为这些模型必须从某个存储器位置检索输入的特征，并且只读取绑定到该位置的标签信息。在本文中，我们试图通过提供更强大的MANN来解决这个问题。我们重新审视元学习的思想，并提出了一个新的记忆增强神经网络，明确地将外部记忆分为特征和标记记忆。特征存储器用于存储输入数据样本的特征，标签存储器存储其标签。因此，当预测给定输入的标签时，我们的模型使用其特征存储单元作为参考来提取所存储的输入特征，并基于该特征从标签存储单元中检索输入的标签信息。为了使网络在此框架中运行，设计了一种新的内存写模块，根据元学习任务结构将标签信息编码到标签内存中。在这里，我们证明了我们的模型在使用Omniglot和MNIST数据集的监督一次分类任务中大大优于MANN。

##### URL
[https://arxiv.org/abs/1710.07110](https://arxiv.org/abs/1710.07110)

##### PDF
[https://arxiv.org/pdf/1710.07110](https://arxiv.org/pdf/1710.07110)

