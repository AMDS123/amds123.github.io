---
layout: post
title: "A Bag-of-Words Equivalent Recurrent Neural Network for Action Recognition"
date: 2017-03-23 14:46:46
categories: arXiv_CV
tags: arXiv_CV Sparse Action_Recognition Classification Recognition
author: Alexander Richard (1), Juergen Gall (1) ((1) University of Bonn)
mathjax: true
---

* content
{:toc}

##### Abstract
The traditional bag-of-words approach has found a wide range of applications in computer vision. The standard pipeline consists of a generation of a visual vocabulary, a quantization of the features into histograms of visual words, and a classification step for which usually a support vector machine in combination with a non-linear kernel is used. Given large amounts of data, however, the model suffers from a lack of discriminative power. This applies particularly for action recognition, where the vast amount of video features needs to be subsampled for unsupervised visual vocabulary generation. Moreover, the kernel computation can be very expensive on large datasets. In this work, we propose a recurrent neural network that is equivalent to the traditional bag-of-words approach but enables for the application of discriminative training. The model further allows to incorporate the kernel computation into the neural network directly, solving the complexity issue and allowing to represent the complete classification system within a single network. We evaluate our method on four recent action recognition benchmarks and show that the conventional model as well as sparse coding methods are outperformed.

##### Abstract (translated by Google)
传统的词袋方法已经在计算机视觉中找到了广泛的应用。标准流水线包括视觉词汇的生成，将特征量化为视觉词的直方图，以及分类步骤，通常使用支持向量机结合非线性核心。但是，如果有大量的数据，模型就会缺乏区分能力。这特别适用于动作识别，其中大量的视频特征需要被二次抽样用于无监督的视觉词汇生成。此外，在大型数据集上内核计算可能非常昂贵。在这项工作中，我们提出了一个循环的神经网络，相当于传统的袋装词的方法，但能够应用歧视性训练。该模型还允许直接将内核计算并入神经网络，解决了复杂性问题，并允许在单个网络中表示完整的分类系统。我们评估我们的方法在四个最近的行动识别基准，并表明传统的模式以及稀疏编码方法跑赢大众。

##### URL
[https://arxiv.org/abs/1703.08089](https://arxiv.org/abs/1703.08089)

##### PDF
[https://arxiv.org/pdf/1703.08089](https://arxiv.org/pdf/1703.08089)

