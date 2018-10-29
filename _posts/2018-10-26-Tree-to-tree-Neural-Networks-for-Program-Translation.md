---
layout: post
title: "Tree-to-tree Neural Networks for Program Translation"
date: 2018-10-26 03:51:27
categories: arXiv_AI
tags: arXiv_AI Attention
author: Xinyun Chen, Chang Liu, Dawn Song
mathjax: true
---

* content
{:toc}

##### Abstract
Program translation is an important tool to migrate legacy code in one language into an ecosystem built in a different language. In this work, we are the first to employ deep neural networks toward tackling this problem. We observe that program translation is a modular procedure, in which a sub-tree of the source tree is translated into the corresponding target sub-tree at each step. To capture this intuition, we design a tree-to-tree neural network to translate a source tree into a target one. Meanwhile, we develop an attention mechanism for the tree-to-tree model, so that when the decoder expands one non-terminal in the target tree, the attention mechanism locates the corresponding sub-tree in the source tree to guide the expansion of the decoder. We evaluate the program translation capability of our tree-to-tree model against several state-of-the-art approaches. Compared against other neural translation models, we observe that our approach is consistently better than the baselines with a margin of up to 15 points. Further, our approach can improve the previous state-of-the-art program translation approaches by a margin of 20 points on the translation of real-world projects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.03691](http://arxiv.org/abs/1802.03691)

##### PDF
[http://arxiv.org/pdf/1802.03691](http://arxiv.org/pdf/1802.03691)

