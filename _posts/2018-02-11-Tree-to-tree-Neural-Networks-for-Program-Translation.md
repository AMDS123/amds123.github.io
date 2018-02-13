---
layout: post
title: "Tree-to-tree Neural Networks for Program Translation"
date: 2018-02-11 04:42:03
categories: arXiv_AI
tags: arXiv_AI Attention
author: Xinyun Chen, Chang Liu, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
Program translation is an important tool to migrate legacy code in one language into an ecosystem built in a different language. In this work, we are the first to consider employing deep neural networks toward tackling this problem. We observe that program translation is a modular procedure, in which a sub-tree of the source tree is translated into the corresponding target sub-tree at each step. To capture this intuition, we design a tree-to-tree neural network as an encoder-decoder architecture to translate a source tree into a target one. Meanwhile, we develop an attention mechanism for the tree-to-tree model, so that when the decoder expands one non-terminal in the target tree, the attention mechanism locates the corresponding sub-tree in the source tree to guide the expansion of the decoder. We evaluate the program translation capability of our tree-to-tree model against several state-of-the-art approaches. Compared against other neural translation models, we observe that our approach is consistently better than the baselines with a margin of up to 15 points. Further, our approach can improve the previous state-of-the-art program translation approaches by a margin of 20 points on the translation of real-world projects.

##### Abstract (translated by Google)
程序翻译是将一种语言的遗留代码迁移到以不同语言构建的生态系统中的重要工具。在这项工作中，我们首先考虑采用深度神经网络来解决这个问题。我们观察到程序转换是一个模块化过程，其中源树的子树在每一步都被转换成相应的目标子树。为了捕捉这种直觉，我们设计了一个树到树的神经网络作为编码器 - 解码器架构来将源树翻译成目标树。同时，我们开发了一个树到树模型的注意机制，以便当解码器扩展目标树中的一个非终端时，注意机制在源树中定位相应的子树来引导解码器。我们用几种最先进的方法评估了我们树与树模型的程序转换能力。与其他神经翻译模型相比，我们观察到我们的方法始终优于具有高达15分的边际的基线。此外，我们的方法可以在现实世界项目的翻译上将先前的最先进的程序翻译方法改进20分。

##### URL
[http://arxiv.org/abs/1802.03691](http://arxiv.org/abs/1802.03691)

##### PDF
[http://arxiv.org/pdf/1802.03691](http://arxiv.org/pdf/1802.03691)

