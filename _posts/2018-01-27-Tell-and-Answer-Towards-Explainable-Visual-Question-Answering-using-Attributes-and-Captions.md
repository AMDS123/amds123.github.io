---
layout: post
title: "Tell-and-Answer: Towards Explainable Visual Question Answering using Attributes and Captions"
date: 2018-01-27 05:34:37
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection QA Attention Caption Inference Detection VQA
author: Qing Li, Jianlong Fu, Dongfei Yu, Tao Mei, Jiebo Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Visual Question Answering (VQA) has attracted attention from both computer vision and natural language processing communities. Most existing approaches adopt the pipeline of representing an image via pre-trained CNNs, and then using the uninterpretable CNN features in conjunction with the question to predict the answer. Although such end-to-end models might report promising performance, they rarely provide any insight, apart from the answer, into the VQA process. In this work, we propose to break up the end-to-end VQA into two steps: explaining and reasoning, in an attempt towards a more explainable VQA by shedding light on the intermediate results between these two steps. To that end, we first extract attributes and generate descriptions as explanations for an image using pre-trained attribute detectors and image captioning models, respectively. Next, a reasoning module utilizes these explanations in place of the image to infer an answer to the question. The advantages of such a breakdown include: (1) the attributes and captions can reflect what the system extracts from the image, thus can provide some explanations for the predicted answer; (2) these intermediate results can help us identify the inabilities of both the image understanding part and the answer inference part when the predicted answer is wrong. We conduct extensive experiments on a popular VQA dataset and dissect all results according to several measurements of the explanation quality. Our system achieves comparable performance with the state-of-the-art, yet with added benefits of explainability and the inherent ability to further improve with higher quality explanations.

##### Abstract (translated by Google)
视觉问答（VQA）引起了计算机视觉和自然语言处理社区的关注。大多数现有方法采用通过预先训练的CNN表示图像的流水线，然后结合问题使用不可解释的CNN特征来预测答案。虽然这种端到端模型可能会报告有前途的性能，但除了答案之外，它们很少能够提供任何有关VQA流程的见解。在这项工作中，我们建议将端到端的VQA分解为两个步骤：解释和推理，试图通过揭示这两个步骤之间的中间结果来解释更可解释的VQA。为此，我们首先分别使用预先训练的属性检测器和图像字幕模型提取属性并生成描述作为图像的解释。接下来，推理模块利用这些解释代替图像来推断问题的答案。这种细分的优点包括：（1）属性和字幕可以反映系统从图像中提取的内容，从而可以为预测的答案提供一些解释; （2）当预测答案错误时，这些中间结果可以帮助我们识别图像理解部分和答案推理部分的无能。我们对流行的VQA数据集进行了大量实验，并根据解释质量的几个测量结果剖析了所有结果。我们的系统与最先进的系统实现了相当的性能，同时具有可解释性的附加优势以及通过更高质量的解释进一步改进的固有能力。

##### URL
[https://arxiv.org/abs/1801.09041](https://arxiv.org/abs/1801.09041)

##### PDF
[https://arxiv.org/pdf/1801.09041](https://arxiv.org/pdf/1801.09041)

