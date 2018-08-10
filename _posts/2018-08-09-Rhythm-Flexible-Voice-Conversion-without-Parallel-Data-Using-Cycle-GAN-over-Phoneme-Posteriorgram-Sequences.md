---
layout: post
title: "Rhythm-Flexible Voice Conversion without Parallel Data Using Cycle-GAN over Phoneme Posteriorgram Sequences"
date: 2018-08-09 12:32:23
categories: arXiv_SD
tags: arXiv_SD Adversarial GAN
author: Cheng-chieh Yeh, Po-chun Hsu, Ju-chieh Chou, Hung-yi Lee, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Speaking rate refers to the average number of phonemes within some unit time, while the rhythmic patterns refer to duration distributions for realizations of different phonemes within different phonetic structures. Both are key components of prosody in speech, which is different for different speakers. Models like cycle-consistent adversarial network (Cycle-GAN) and variational auto-encoder (VAE) have been successfully applied to voice conversion tasks without parallel data. However, due to the neural network architectures and feature vectors chosen for these approaches, the length of the predicted utterance has to be fixed to that of the input utterance, which limits the flexibility in mimicking the speaking rates and rhythmic patterns for the target speaker. On the other hand, sequence-to-sequence learning model was used to remove the above length constraint, but parallel training data are needed. In this paper, we propose an approach utilizing sequence-to-sequence model trained with unsupervised Cycle-GAN to perform the transformation between the phoneme posteriorgram sequences for different speakers. In this way, the length constraint mentioned above is removed to offer rhythm-flexible voice conversion without requiring parallel data. Preliminary evaluation on two datasets showed very encouraging results.

##### Abstract (translated by Google)
说话率是指某个单位时间内音素的平均数量，而节奏模式是指不同语音结构中不同音素的实现的持续时间分布。两者都是演讲中韵律的关键组成部分，对于不同的演讲者来说是不同的。周期一致的对抗网络（Cycle-GAN）和变分自动编码器（VAE）等模型已成功应用于没有并行数据的语音转换任务。然而，由于为这些方法选择的神经网络架构和特征向量，预测话语的长度必须固定为输入话语的长度，这限制了模仿目标讲话者的讲话率和节奏模式的灵活性。另一方面，序列到序列学习模型用于去除上述长度约束，但是需要并行训练数据。在本文中，我们提出了一种利用无监督Cycle-GAN训练的序列到序列模型来执行不同说话者的音素后序列序列之间的转换的方法。以这种方式，去除上述长度约束以提供节奏灵活的语音转换而不需要并行数据。对两个数据集的初步评估显示非常令人鼓舞的结果

##### URL
[http://arxiv.org/abs/1808.03113](http://arxiv.org/abs/1808.03113)

##### PDF
[http://arxiv.org/pdf/1808.03113](http://arxiv.org/pdf/1808.03113)

