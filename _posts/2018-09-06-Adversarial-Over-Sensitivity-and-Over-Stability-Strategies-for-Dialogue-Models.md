---
layout: post
title: "Adversarial Over-Sensitivity and Over-Stability Strategies for Dialogue Models"
date: 2018-09-06 16:27:32
categories: arXiv_AI
tags: arXiv_AI Adversarial
author: Tong Niu, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
We present two categories of model-agnostic adversarial strategies that reveal the weaknesses of several generative, task-oriented dialogue models: Should-Not-Change strategies that evaluate over-sensitivity to small and semantics-preserving edits, as well as Should-Change strategies that test if a model is over-stable against subtle yet semantics-changing modifications. We next perform adversarial training with each strategy, employing a max-margin approach for negative generative examples. This not only makes the target dialogue model more robust to the adversarial inputs, but also helps it perform significantly better on the original inputs. Moreover, training on all strategies combined achieves further improvements, achieving a new state-of-the-art performance on the original task (also verified via human evaluation). In addition to adversarial training, we also address the robustness task at the model-level, by feeding it subword units as both inputs and outputs, and show that the resulting model is equally competitive, requires only 1/4 of the original vocabulary size, and is robust to one of the adversarial strategies (to which the original model is vulnerable) even without adversarial training.

##### Abstract (translated by Google)
我们提出了两类与模型无关的对抗性策略，揭示了几种生成性，面向任务的对话模型的弱点：评估过度敏感性的“不应变”策略，以及对于保留小编辑和保留语义的编辑，以及应变策略测试一个模型是否过于稳定，以防止细微但语义变化的修改。接下来，我们将针对每种策略进行对抗性训练，采用最大边际方法进行负面生成示例。这不仅使目标对话模型对对抗性输入更加稳健，而且还有助于其在原始输入上表现更好。此外，所有策略的培训相结合，实现了进一步的改进，在原始任务上实现了最新的先进性能（也通过人工评估验证）。除了对抗性训练之外，我们还通过将子词单位作为输入和输出提供来解决模型级别的稳健性任务，并且表明所得模型具有同等竞争力，仅需要原始词汇量的1/4，即使没有对抗性训练，对于其中一种对抗策略（原始模型易受攻击）也是健壮的。

##### URL
[http://arxiv.org/abs/1809.02079](http://arxiv.org/abs/1809.02079)

##### PDF
[http://arxiv.org/pdf/1809.02079](http://arxiv.org/pdf/1809.02079)

