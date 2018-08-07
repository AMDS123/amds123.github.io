---
layout: post
title: "Inverse Visual Question Answering: A New Benchmark and VQA Diagnosis Tool"
date: 2018-03-16 07:58:21
categories: arXiv_CV
tags: arXiv_CV QA Reinforcement_Learning VQA
author: Feng Liu, Tao Xiang, Timothy M. Hospedales, Wankou Yang, Changyin Sun
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, visual question answering (VQA) has become topical. The premise of VQA's significance as a benchmark in AI, is that both the image and textual question need to be well understood and mutually grounded in order to infer the correct answer. However, current VQA models perhaps `understand' less than initially hoped, and instead master the easier task of exploiting cues given away in the question and biases in the answer distribution. In this paper we propose the inverse problem of VQA (iVQA). The iVQA task is to generate a question that corresponds to a given image and answer pair. We propose a variational iVQA model that can generate diverse, grammatically correct and content correlated questions that match the given answer. Based on this model, we show that iVQA is an interesting benchmark for visuo-linguistic understanding, and a more challenging alternative to VQA because an iVQA model needs to understand the image better to be successful. As a second contribution, we show how to use iVQA in a novel reinforcement learning framework to diagnose any existing VQA model by way of exposing its belief set: the set of question-answer pairs that the VQA model would predict true for a given image. This provides a completely new window into what VQA models `believe' about images. We show that existing VQA models have more erroneous beliefs than previously thought, revealing their intrinsic weaknesses. Suggestions are then made on how to address these weaknesses going forward.

##### Abstract (translated by Google)
近年来，视觉问答（VQA）已成为热门话题。 VQA作为人工智能基准的重要性的前提是，图像和文本问题需要得到很好的理解和相互依据才能推断出正确的答案。然而，当前的VQA模型可能比最初希望的“理解”更少，而是掌握了利用问题中给出的线索和答案分布中的偏差的更容易的任务。在本文中，我们提出了VQA（iVQA）的逆问题。 iVQA任务是生成与给定图像和答案对相对应的问题。我们提出了一种变分iVQA模型，该模型可以生成与给定答案匹配的多样，语法正确和内容相关的问题。基于此模型，我们表明iVQA是一个有趣的基于语言理解的基准，是VQA的一个更具挑战性的替代方案，因为iVQA模型需要更好地理解图像才能获得成功。作为第二个贡献，我们展示了如何在新的强化学习框架中使用iVQA来通过暴露其信念集来诊断任何现有的VQA模型：VQA模型将为给定图像预测真实的问答集对。这为VQA模型“相信”图像提供了一个全新的窗口。我们表明，现有的VQA模型比以前认为的更有错误的信念，揭示了它们内在的弱点。然后就如何解决这些弱点提出建议。

##### URL
[https://arxiv.org/abs/1803.06936](https://arxiv.org/abs/1803.06936)

##### PDF
[https://arxiv.org/pdf/1803.06936](https://arxiv.org/pdf/1803.06936)

