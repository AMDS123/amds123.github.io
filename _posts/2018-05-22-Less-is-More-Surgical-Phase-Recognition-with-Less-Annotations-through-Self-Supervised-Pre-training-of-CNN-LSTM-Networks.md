---
layout: post
title: "Less is More: Surgical Phase Recognition with Less Annotations through Self-Supervised Pre-training of CNN-LSTM Networks"
date: 2018-05-22 13:28:59
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Recognition
author: Gaurav Yengera, Didier Mutter, Jacques Marescaux, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time algorithms for automatically recognizing surgical phases are needed to develop systems that can provide assistance to surgeons, enable better management of operating room (OR) resources and consequently improve safety within the OR. State-of-the-art surgical phase recognition algorithms using laparoscopic videos are based on fully supervised training. This limits their potential for widespread application, since creation of manual annotations is an expensive process considering the numerous types of existing surgeries and the vast amount of laparoscopic videos available. In this work, we propose a new self-supervised pre-training approach based on the prediction of remaining surgery duration (RSD) from laparoscopic videos. The RSD prediction task is used to pre-train a convolutional neural network (CNN) and long short-term memory (LSTM) network in an end-to-end manner. Our proposed approach utilizes all available data and reduces the reliance on annotated data, thereby facilitating the scaling up of surgical phase recognition algorithms to different kinds of surgeries. Additionally, we present EndoN2N, an end-to-end trained CNN-LSTM model for surgical phase recognition and evaluate the performance of our approach on a dataset of 120 Cholecystectomy laparoscopic videos (Cholec120). This work also presents the first systematic study of self-supervised pre-training approaches to understand the amount of annotations required for surgical phase recognition. Interestingly, the proposed RSD pre-training approach leads to performance improvement even when all the training data is manually annotated and outperforms the single pre-training approach for surgical phase recognition presently published in the literature. It is also observed that end-to-end training of CNN-LSTM networks boosts surgical phase recognition performance.

##### Abstract (translated by Google)
需要实时算法来自动识别手术阶段，以开发可以为外科医生提供帮助的系统，从而更好地管理手术室（OR）资源，从而提高手术室内的安全性。使用腹腔镜视频的最先进的手术相位识别算法基于完全监督训练。这限制了它们广泛应用的潜力，因为手动注释的创建是一个昂贵的过程，考虑到现有手术的众多类型和大量的腹腔镜视频。在这项工作中，我们提出了一种基于预测腹腔镜视频剩余手术持续时间（RSD）的新的自我监督预训练方法。 RSD预测任务用于以端到端的方式预先训练卷积神经网络（CNN）和长期短期记忆（LSTM）网络。我们提出的方法利用了所有可用的数据并减少了对注释数据的依赖，从而有助于将手术阶段识别算法扩展到不同类型的手术。此外，我们展示EndoN2N，一种端到端训练的CNN-LSTM手术相识别模型，并评估我们的方法在120例胆囊切除术腹腔镜视频（Cholec120）数据集上的表现。这项工作还提出了第一个系统研究自我监督的预训练方法，以了解手术阶段识别所需的注释量。有趣的是，所提出的RSD预训练方法导致性能改善，即使所有训练数据都是手动注释的，并且胜过目前在文献中公开的用于手术相识别的单训练前方法。还观察到CNN-LSTM网络的端对端训练可以提高手术相识别性能。

##### URL
[https://arxiv.org/abs/1805.08569](https://arxiv.org/abs/1805.08569)

##### PDF
[https://arxiv.org/pdf/1805.08569](https://arxiv.org/pdf/1805.08569)

