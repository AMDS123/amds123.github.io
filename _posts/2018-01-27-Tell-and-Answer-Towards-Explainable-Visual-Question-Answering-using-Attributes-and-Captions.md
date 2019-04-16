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


##### URL
[https://arxiv.org/abs/1801.09041](https://arxiv.org/abs/1801.09041)

##### PDF
[https://arxiv.org/pdf/1801.09041](https://arxiv.org/pdf/1801.09041)

