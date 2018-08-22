---
layout: post
title: "Automatic Generation of Text Descriptive Comments for Code Blocks"
date: 2018-08-21 12:53:52
categories: arXiv_AI
tags: arXiv_AI RNN
author: Yuding Liang, Kenny Q. Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework to automatically generate descriptive comments for source code blocks. While this problem has been studied by many researchers previously, their methods are mostly based on fixed template and achieves poor results. Our framework does not rely on any template, but makes use of a new recursive neural network called Code-RNN to extract features from the source code and embed them into one vector. When this vector representation is input to a new recurrent neural network (Code-GRU), the overall framework generates text descriptions of the code with accuracy (Rouge-2 value) significantly higher than other learning-based approaches such as sequence-to-sequence model. The Code-RNN model can also be used in other scenario where the representation of code is required.

##### Abstract (translated by Google)
我们提出了一个框架来自动生成源代码块的描述性注释。虽然之前许多研究人员已经研究过这个问题，但他们的方法大多是基于固定模板而且效果不佳。我们的框架不依赖于任何模板，而是利用称为Code-RNN的新递归神经网络从源代码中提取特征并将它们嵌入到一个向量中。当此向量表示输入到新的递归神经网络（Code-GRU）时，整个框架生成的代码文本描述具有准确性（Rouge-2值），显着高于其他基于学习的方法，如序列到序列模型。 Code-RNN模型还可以用于需要代码表示的其他场景中。

##### URL
[http://arxiv.org/abs/1808.06880](http://arxiv.org/abs/1808.06880)

##### PDF
[http://arxiv.org/pdf/1808.06880](http://arxiv.org/pdf/1808.06880)

