---
layout: post
title: "Rearranging the Familiar: Testing Compositional Generalization in Recurrent Networks"
date: 2018-07-19 17:23:13
categories: arXiv_AI
tags: arXiv_AI
author: Jo&#xe3;o Loula, Marco Baroni, Brenden M. Lake
mathjax: true
---

* content
{:toc}

##### Abstract
Systematic compositionality is the ability to recombine meaningful units with regular and predictable outcomes, and it's seen as key to humans' capacity for generalization in language. Recent work has studied systematic compositionality in modern seq2seq models using generalization to novel navigation instructions in a grounded environment as a probing tool, requiring models to quickly bootstrap the meaning of new words. We extend this framework here to settings where the model needs only to recombine well-trained functional words (such as "around" and "right") in novel contexts. Our findings confirm and strengthen the earlier ones: seq2seq models can be impressively good at generalizing to novel combinations of previously-seen input, but only when they receive extensive training on the specific pattern to be generalized (e.g., generalizing from many examples of "X around right" to "jump around right"), while failing when generalization requires novel application of compositional rules (e.g., inferring the meaning of "around right" from those of "right" and "around").

##### Abstract (translated by Google)
系统的组合性是将有意义的单元与常规和可预测的结果重新组合的能力，并且它被视为人类语言泛化能力的关键。最近的工作研究了现代seq2seq模型中的系统组合性，使用在基础环境中作为探测工具的新颖导航指令的概括，要求模型快速引导新词的含义。我们将此框架扩展到模型仅需要在新环境中重新组合训练有素的功能词（例如“周围”和“右”）的设置。我们的研究结果证实并加强了早期的研究：seq2seq模型可以非常好地推广到先前看到的输入的新颖组合，但只有当他们接受关于特定模式的广泛训练时才会被推广（例如，从许多“X”的例子中推广）在右边“向右”跳“右边”，而在泛化需要新颖的组合规则应用时失败（例如，从“右”和“周围”的那些推断“右边”的含义）。

##### URL
[http://arxiv.org/abs/1807.07545](http://arxiv.org/abs/1807.07545)

##### PDF
[http://arxiv.org/pdf/1807.07545](http://arxiv.org/pdf/1807.07545)

