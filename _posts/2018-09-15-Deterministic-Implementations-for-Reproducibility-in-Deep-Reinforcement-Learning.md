---
layout: post
title: "Deterministic Implementations for Reproducibility in Deep Reinforcement Learning"
date: 2018-09-15 08:53:28
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Prabhat Nagarajan, Garrett Warnell, Peter Stone
mathjax: true
---

* content
{:toc}

##### Abstract
While deep reinforcement learning (DRL) has led to numerous successes in recent years, reproducing these successes can be extremely challenging. One reproducibility challenge particularly relevant to DRL is nondeterminism in the training process, which can substantially affect the results. Motivated by this challenge, we study the positive impacts of deterministic implementations in eliminating nondeterminism in training. To do so, we consider the particular case of the deep Q-learning algorithm, for which we produce a deterministic implementation by identifying and controlling all sources of nondeterminism in the training process. One by one, we then allow individual sources of nondeterminism to affect our otherwise deterministic implementation, and measure the impact of each source on the variance in performance. We find that individual sources of nondeterminism can substantially impact the performance of agent, illustrating the benefits of deterministic implementations. In addition, we also discuss the important role of deterministic implementations in achieving exact replicability of results.

##### Abstract (translated by Google)
虽然深度强化学习（DRL）近年来取得了许多成功，但复制这些成功可能极具挑战性。与DRL特别相关的一个可重复性挑战是培训过程中的不确定性，这可能会对结果产生重大影响。受此挑战的启发，我们研究了确定性实施在消除培训中的非确定性方面的积极影响。为此，我们考虑深度Q学习算法的特殊情况，为此我们通过识别和控制训练过程中的所有非确定性来源来产生确定性实现。然后，我们逐一允许个别的非确定性来源影响我们的确定性实施，并衡量每个来源对绩效差异的影响。我们发现不确定性的各个来源可以显着影响代理的性能，说明确定性实现的好处。此外，我们还讨论了确定性实现在实现结果的精确可复制性方面的重要作用。

##### URL
[http://arxiv.org/abs/1809.05676](http://arxiv.org/abs/1809.05676)

##### PDF
[http://arxiv.org/pdf/1809.05676](http://arxiv.org/pdf/1809.05676)

