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
近年来，视觉问答（VQA）已成为热门话题。 VQA作为AI基准的重要前提是，图像和文本问题都需要被理解并相互基础，以便推断出正确的答案。然而，目前的VQA模型可能比最初希望的要“理解”更少，而是掌握了更容易的任务，即利用提供给问题的线索和答案分布中的偏见。在本文中，我们提出了VQA（iVQA）的逆问题。 iVQA任务是生成一个与给定图像和答案对相对应的问题。我们提出了一种变化的iVQA模型，可以生成与给定答案匹配的多样的，语法正确和内容相关的问题。基于此模型，我们展示了iVQA是视觉语言理解的一个有趣基准，也是VQA更具挑战性的替代方案，因为iVQA模型需要更好地理解图像才能取得成功。作为第二个贡献，我们展示了如何在一个新的强化学习框架中使用iVQA，通过揭示它的信念集来诊断任何现有的VQA模型：VQA模型预测给定图像真实的问题 - 答案对集合。这为VQA模型“相信”图像提供了一个全新的窗口。我们发现现有的VQA模型比以前想象的更加错误的信念，揭示了它们的内在弱点。然后就如何解决今后的这些弱点提出建议。

##### URL
[https://arxiv.org/abs/1803.06936](https://arxiv.org/abs/1803.06936)

##### PDF
[https://arxiv.org/pdf/1803.06936](https://arxiv.org/pdf/1803.06936)

