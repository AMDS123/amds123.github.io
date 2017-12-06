---
layout: post
title: "iVQA: Inverse Visual Question Answering"
date: 2017-10-10 01:22:52
categories: arXiv_CV
tags: arXiv_CV VQA
author: Feng Liu, Tao Xiang, Timothy M. Hospedales, Wankou Yang, Changyin Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, visual question answering (VQA) has become topical as a long-term goal to drive computer vision and multi-disciplinary AI research. The premise of VQA's significance, is that both the image and textual question need to be well understood and mutually grounded in order to infer the correct answer. However, current VQA models perhaps `understand' less than initially hoped, and instead master the easier task of exploiting cues given away in the question and biases in the answer distribution. In this paper we propose the inverse problem of VQA (iVQA), and explore its suitability as a benchmark for visuo-linguistic understanding. The iVQA task is to generate a question that corresponds to a given image and answer pair. Since the answers are less informative than the questions, and the questions have less learnable bias, an iVQA model needs to better understand the image to be successful. We pose question generation as a multi-modal dynamic inference process and propose an iVQA model that can gradually adjust its focus of attention guided by both a partially generated question and the answer. For evaluation, apart from existing linguistic metrics, we propose a new ranking metric. This metric compares the ground truth question's rank among a list of distractors, which allows the drawbacks of different algorithms and sources of error to be studied. Experimental results show that our model can generate diverse, grammatically correct and content correlated questions that match the given answer.

##### Abstract (translated by Google)
近年来，视觉问答（VQA）已成为推动计算机视觉和多学科人工智能研究的长期目标。 VQA意义的前提是图像和文本问题需要被理解和相互基础以推断正确的答案。然而，目前的VQA模型可能比最初希望的“理解”要少，而是掌握了更容易利用提供给线索的线索的问题和偏见。在本文中，我们提出VQA（iVQA）的逆问题，并探讨其适用性作为视觉语言理解的基准。 iVQA的任务是产生一个对应于给定的图像和答案对的问题。由于答案比问题的信息量少，而且问题的学习偏差较小，所以iVQA模型需要更好地理解图像才能获得成功。我们提出问题生成为一个多模式动态推理过程，并提出一个iVQA模型，可以逐渐调整其关注的焦点，既是一个部分产生的问题和答案。对于评估，除了现有的语言指标，我们提出了一个新的排名指标。这个度量将地面真值问题的等级比作干扰列表，这就允许研究不同算法和误差源的缺点。实验结果表明，我们的模型可以产生不同的，语法正确和内容相关的问题，匹配给定的答案。

##### URL
[https://arxiv.org/abs/1710.03370](https://arxiv.org/abs/1710.03370)

