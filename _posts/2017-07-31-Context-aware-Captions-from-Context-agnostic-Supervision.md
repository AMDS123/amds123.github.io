---
layout: post
title: "Context-aware Captions from Context-agnostic Supervision"
date: 2017-07-31 23:29:36
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption
author: Ramakrishna Vedantam, Samy Bengio, Kevin Murphy, Devi Parikh, Gal Chechik
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce an inference technique to produce discriminative context-aware image captions (captions that describe differences between images or visual concepts) using only generic context-agnostic training data (captions that describe a concept or an image in isolation). For example, given images and captions of "siamese cat" and "tiger cat", we generate language that describes the "siamese cat" in a way that distinguishes it from "tiger cat". Our key novelty is that we show how to do joint inference over a language model that is context-agnostic and a listener which distinguishes closely-related concepts. We first apply our technique to a justification task, namely to describe why an image contains a particular fine-grained category as opposed to another closely-related category of the CUB-200-2011 dataset. We then study discriminative image captioning to generate language that uniquely refers to one of two semantically-similar images in the COCO dataset. Evaluations with discriminative ground truth for justification and human studies for discriminative image captioning reveal that our approach outperforms baseline generative and speaker-listener approaches for discrimination.

##### Abstract (translated by Google)
我们引入一种推理技术，只使用通用的与上下文无关的训练数据（单独描述一个概念或图像的字幕）来产生区分性的上下文感知图像字幕（描述图像或视觉概念之间差异的字幕）。例如，给出了“暹罗猫”和“老虎猫”的图像和标题，我们用与“老虎猫”区分开来的方式生成描述“暹罗猫”的语言。我们的关键新颖之处在于我们展示了如何对一个与上下文无关的语言模型和一个区分密切相关概念的监听者进行联合推理。我们首先将我们的技术应用于一个理由任务，即描述为什么图像包含一个特定的细粒度类别，而不是另一个与CUB-200-2011数据集紧密相关的类别。然后，我们研究区分性图像字幕以生成唯一地指代COCO数据集中的两个语义相似图像中的一个的语言。用歧视性的基本事实进行评估，对于区分性图像字幕的理由和人类研究来说，我们的方法胜过基线生成和说话者倾听者的歧视方法。

##### URL
[https://arxiv.org/abs/1701.02870](https://arxiv.org/abs/1701.02870)

