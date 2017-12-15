---
layout: post
title: "Writer-independent Feature Learning for Offline Signature Verification using Deep Convolutional Neural Networks"
date: 2016-04-04 18:26:48
categories: arXiv_CV
tags: arXiv_CV CNN
author: Luiz G. Hafemann, Robert Sabourin, Luiz S. Oliveira
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic Offline Handwritten Signature Verification has been researched over the last few decades from several perspectives, using insights from graphology, computer vision, signal processing, among others. In spite of the advancements on the field, building classifiers that can separate between genuine signatures and skilled forgeries (forgeries made targeting a particular signature) is still hard. We propose approaching the problem from a feature learning perspective. Our hypothesis is that, in the absence of a good model of the data generation process, it is better to learn the features from data, instead of using hand-crafted features that have no resemblance to the signature generation process. To this end, we use Deep Convolutional Neural Networks to learn features in a writer-independent format, and use this model to obtain a feature representation on another set of users, where we train writer-dependent classifiers. We tested our method in two datasets: GPDS-960 and Brazilian PUC-PR. Our experimental results show that the features learned in a subset of the users are discriminative for the other users, including across different datasets, reaching close to the state-of-the-art in the GPDS dataset, and improving the state-of-the-art in the Brazilian PUC-PR dataset.

##### Abstract (translated by Google)
自动离线手写签名验证在过去几十年里从多个角度进行了研究，使用了来自于图形学，计算机视觉，信号处理等领域的见解。尽管在这个领域有了进步，但是能够区分真正的签名和熟练的伪造者（针对特定签名的伪造）之间的建筑分类器仍然是困难的。我们建议从特征学习的角度来解决这个问题。我们的假设是，在没有良好的数据生成过程模型的情况下，最好从数据中学习特征，而不是使用与签名生成过程不相似的手工特征。为此，我们使用深度卷积神经网络以独立于书写器的格式学习特征，并使用这个模型来获得另一组用户的特征表示，在那里我们训练依赖于书写器的分类器。我们在两个数据集中测试了我们的方法：GPDS-960和巴西的PUC-PR。我们的实验结果表明，在用户子集中学习的特征对于其他用户（包括跨不同数据集）具有区别性，达到了接近GPDS数据集中最先进的水平，并改善了状态在巴西PUC-PR数据集中启动。

##### URL
[https://arxiv.org/abs/1604.00974](https://arxiv.org/abs/1604.00974)

##### PDF
[https://arxiv.org/pdf/1604.00974](https://arxiv.org/pdf/1604.00974)

