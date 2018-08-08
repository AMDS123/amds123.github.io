---
layout: post
title: "Coloring with Words: Guiding Image Colorization Through Text-based Palette Generation"
date: 2018-08-07 06:40:18
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Hyojin Bahng, Seungjoo Yoo, Wonwoong Cho, David K. Park, Ziming Wu, Xiaojuan Ma, Jaegul Choo
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel approach to generate multiple color palettes that reflect the semantics of input text and then colorize a given grayscale image according to the generated color palette. In contrast to existing approaches, our model can understand rich text, whether it is a single word, a phrase, or a sentence, and generate multiple possible palettes from it. For this task, we introduce our manually curated dataset called Palette-and-Text (PAT). Our proposed model called Text2Colors consists of two conditional generative adversarial networks: the text-to-palette generation networks and the palette-based colorization networks. The former captures the semantics of the text input and produce relevant color palettes. The latter colorizes a grayscale image using the generated color palette. Our evaluation results show that people preferred our generated palettes over ground truth palettes and that our model can effectively reflect the given palette when colorizing an image.

##### Abstract (translated by Google)
本文提出了一种新的方法来生成多个调色板，这些调色板反映输入文本的语义，然后根据生成的调色板着色给定的灰度图像。与现有方法相比，我们的模型可以理解富文本，无论是单个单词，短语还是句子，并从中生成多个可能的调色板。对于此任务，我们将介绍名为Palette-and-Text（PAT）的手动策划数据集。我们提出的名为Text2Colors的模型由两个条件生成对抗网络组成：文本到调色板生成网络和基于调色板的着色网络。前者捕获文本输入的语义并生成相关的调色板。后者使用生成的调色板为灰度图像着色。我们的评估结果表明，人们更喜欢我们生成的调色板而不是地面实况调色板，并且我们的模型可以在着色图像时有效地反映给定的调色板。

##### URL
[http://arxiv.org/abs/1804.04128](http://arxiv.org/abs/1804.04128)

##### PDF
[http://arxiv.org/pdf/1804.04128](http://arxiv.org/pdf/1804.04128)

