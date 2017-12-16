---
layout: post
title: "Text-Independent Speaker Verification Using 3D Convolutional Neural Networks"
date: 2017-11-06 23:11:13
categories: arXiv_CV
tags: arXiv_CV CNN
author: Amirsina Torfi, Nasser M. Nasrabadi, Jeremy Dawson
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a novel method using 3D Convolutional Neural Network (3D-CNN) architecture has been proposed for speaker verification in the text-independent setting. At the development phase, a CNN is trained to classify speakers at the utterance-level. In the enrollment stage, the trained network is utilized to directly create a speaker model for each speaker based on the extracted features. Finally, in the evaluation phase, the extracted features from the test utterance will be compared to the stored speaker model to verify the claimed identity. One of the main challenges is the creation of the speaker models. Previously-reported approaches create speaker models based on averaging the extracted features from utterances of the speaker, which is known as a d-vector system. In our paper, we propose an adaptive feature learning by utilizing the 3D-CNNs for direct speaker model creation in which, for both development and enrollment phases, an identical number of spoken utterances per speaker is fed to the network for representing the speaker utterances and creation of the speaker model. This leads to simultaneously capturing the speaker-related information and building a more robust system to cope with within-speaker variation. We demonstrate that the proposed method significantly outperforms the traditional d-vector verification system. Moreover, we empirically show that the proposed method is more effective than the end-to-end learning method.

##### Abstract (translated by Google)
在本文中，提出了一种使用三维卷积神经网络（3D-CNN）体系结构的新颖方法用于在独立于文本的设置中的说话者验证。在发展阶段，有线电视新闻网被训练在讲话级对讲话人进行分类。在登记阶段，利用训练好的网络，根据提取的特征，为每个说话人直接建立说话人模型。最后，在评估阶段，从测试话语中提取的特征将与存储的讲话者模型进行比较，以验证声称的身份。主要挑战之一是扬声器模型的创建。先前报道的方法基于对从说话者的话语中提取的特征进行平均（其被称为d向量系统）来创建说话者模型。在我们的论文中，我们提出了一个自适应的特征学习，利用3D-CNN进行直接说话人模型创建，其中，对于发展阶段和登记阶段，每个说话人的相同数量的口头发言被馈送到网络以表示发言者的话语，说话人模型的创建。这导致同时捕获与讲话人相关的信息，并建立更强大的系统来应对讲话人内的变化。我们证明了所提出的方法明显优于传统的d向量验证系统。此外，我们经验地表明，提出的方法比端到端的学习方法更有效。

##### URL
[https://arxiv.org/abs/1705.09422](https://arxiv.org/abs/1705.09422)

##### PDF
[https://arxiv.org/pdf/1705.09422](https://arxiv.org/pdf/1705.09422)

