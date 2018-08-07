---
layout: post
title: "Context-aware Captions from Context-agnostic Supervision"
date: 2017-07-31 23:29:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption Inference Language_Model
author: Ramakrishna Vedantam, Samy Bengio, Kevin Murphy, Devi Parikh, Gal Chechik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an inference technique to produce discriminative context-aware image captions (captions that describe differences between images or visual concepts) using only generic context-agnostic training data (captions that describe a concept or an image in isolation). For example, given images and captions of "siamese cat" and "tiger cat", we generate language that describes the "siamese cat" in a way that distinguishes it from "tiger cat". Our key novelty is that we show how to do joint inference over a language model that is context-agnostic and a listener which distinguishes closely-related concepts. We first apply our technique to a justification task, namely to describe why an image contains a particular fine-grained category as opposed to another closely-related category of the CUB-200-2011 dataset. We then study discriminative image captioning to generate language that uniquely refers to one of two semantically-similar images in the COCO dataset. Evaluations with discriminative ground truth for justification and human studies for discriminative image captioning reveal that our approach outperforms baseline generative and speaker-listener approaches for discrimination.

##### Abstract (translated by Google)
我们引入了一种推理技术，仅使用通用的上下文无关训练数据（单独描述概念或图像的标题）来产生具有辨别力的上下文感知图像标题（描述图像或视觉概念之间差异的标题）。例如，给定“暹罗猫”和“老虎猫”的图像和标题，我们生成的语言描述了“暹罗猫”，以区别于“老虎猫”。我们的关键新颖之处在于，我们展示了如何对与上下文无关的语言模型进行联合推理，以及区分密切相关概念的倾听者。我们首先将我们的技术应用于理由任务，即描述图像包含特定细粒度类别的原因，而不是CUB-200-2011数据集的另一个密切相关的类别。然后，我们研究判别式图像字幕，以生成唯一引用COCO数据集中两个语义相似图像之一的语言。对歧视性图像字幕进行理由和人类研究的判别性基础事实的评估表明，我们的方法优于基线生成和说话者 - 听众的歧视方法。

##### URL
[https://arxiv.org/abs/1701.02870](https://arxiv.org/abs/1701.02870)

##### PDF
[https://arxiv.org/pdf/1701.02870](https://arxiv.org/pdf/1701.02870)

