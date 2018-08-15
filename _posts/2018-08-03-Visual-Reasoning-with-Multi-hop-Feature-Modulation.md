---
layout: post
title: "Visual Reasoning with Multi-hop Feature Modulation"
date: 2018-08-03 14:32:02
categories: arXiv_CV
tags: arXiv_CV CNN VQA
author: Florian Strub, Mathieu Seurin, Ethan Perez, Harm de Vries, J&#xe9;r&#xe9;mie Mary, Philippe Preux, Aaron Courville, Olivier Pietquin
mathjax: true
---

* content
{:toc}

##### Abstract
Recent breakthroughs in computer vision and natural language processing have spurred interest in challenging multi-modal tasks such as visual question-answering and visual dialogue. For such tasks, one successful approach is to condition image-based convolutional network computation on language via Feature-wise Linear Modulation (FiLM) layers, i.e., per-channel scaling and shifting. We propose to generate the parameters of FiLM layers going up the hierarchy of a convolutional network in a multi-hop fashion rather than all at once, as in prior work. By alternating between attending to the language input and generating FiLM layer parameters, this approach is better able to scale to settings with longer input sequences such as dialogue. We demonstrate that multi-hop FiLM generation achieves state-of-the-art for the short input sequence task ReferIt --- on-par with single-hop FiLM generation --- while also significantly outperforming prior state-of-the-art and single-hop FiLM generation on the GuessWhat?! visual dialogue task.

##### Abstract (translated by Google)
最近计算机视觉和自然语言处理方面的突破激发了人们对挑战多模式任务（如视觉问答和视觉对话）的兴趣。对于这样的任务，一种成功的方法是通过特征线性调制（FiLM）层（即，每通道缩放和移位）来调节语言上基于图像的卷积网络计算。我们建议以多跳方式生成在卷积网络的层次结构上的FiLM层的参数，而不是像在先前的工作中那样一次生成。通过在参与语言输入和生成FiLM层参数之间交替，这种方法能够更好地扩展到具有较长输入序列的设置，例如对话。我们证明了多跳FiLM生成实现了短输入序列任务的最新技术参考 - 与单跳FiLM生成相媲美 - 同时也明显优于先前的先进技术GuessWhat上的单跳FiLM生成？！视觉对话任务。

##### URL
[http://arxiv.org/abs/1808.04446](http://arxiv.org/abs/1808.04446)

##### PDF
[http://arxiv.org/pdf/1808.04446](http://arxiv.org/pdf/1808.04446)

