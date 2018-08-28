---
layout: post
title: "Adversarially Regularising Neural NLI Models to Integrate Logical Background Knowledge"
date: 2018-08-26 18:36:20
categories: arXiv_AI
tags: arXiv_AI Adversarial Knowledge Inference Language_Model
author: Pasquale Minervini, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples are inputs to machine learning models designed to cause the model to make a mistake. They are useful for understanding the shortcomings of machine learning models, interpreting their results, and for regularisation. In NLP, however, most example generation strategies produce input text by using known, pre-specified semantic transformations, requiring significant manual effort and in-depth understanding of the problem and domain. In this paper, we investigate the problem of automatically generating adversarial examples that violate a set of given First-Order Logic constraints in Natural Language Inference (NLI). We reduce the problem of identifying such adversarial examples to a combinatorial optimisation problem, by maximising a quantity measuring the degree of violation of such constraints and by using a language model for generating linguistically-plausible examples. Furthermore, we propose a method for adversarially regularising neural NLI models for incorporating background knowledge. Our results show that, while the proposed method does not always improve results on the SNLI and MultiNLI datasets, it significantly and consistently increases the predictive accuracy on adversarially-crafted datasets -- up to a 79.6% relative improvement -- while drastically reducing the number of background knowledge violations. Furthermore, we show that adversarial examples transfer among model architectures, and that the proposed adversarial training procedure improves the robustness of NLI models to adversarial examples.

##### Abstract (translated by Google)
对抗性示例是机器学习模型的输入，旨在使模型出错。它们有助于理解机器学习模型的缺点，解释其结果以及正规化。然而，在NLP中，大多数示例生成策略通过使用已知的，预先指定的语义变换来生成输入文本，这需要大量的手动工作并且深入理解问题和域。在本文中，我们研究了在自然语言推理（NLI）中自动生成违反一组给定的一阶逻辑约束的对抗性示例的问题。我们通过最大化测量这种约束的违反程度的数量并通过使用语言模型来生成语言合理的示例，将识别这种对抗性示例的问题减少到组合优化问题。此外，我们提出了一种用于对神经NLI模型进行对抗正则化以结合背景知识的方法。我们的结果表明，虽然所提出的方法并不总能改善SNLI和MultiNLI数据集的结果，但它显着且一致地提高了对抗数据集的预测准确性 - 相对改善高达79.6％ - 同时大幅减少数量背景知识违规。此外，我们展示了对抗性示例在模型体系结构之间转移，并且所提出的对抗性训练过程提高了NLI模型对对抗性示例的鲁棒性。

##### URL
[http://arxiv.org/abs/1808.08609](http://arxiv.org/abs/1808.08609)

##### PDF
[http://arxiv.org/pdf/1808.08609](http://arxiv.org/pdf/1808.08609)

