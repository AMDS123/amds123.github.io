---
layout: post
title: "Analysis of classifiers' robustness to adversarial perturbations"
date: 2016-03-28 22:50:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge Classification
author: Alhussein Fawzi, Omar Fawzi, Pascal Frossard
mathjax: true
---

* content
{:toc}

##### Abstract
The goal of this paper is to analyze an intriguing phenomenon recently discovered in deep networks, namely their instability to adversarial perturbations (Szegedy et. al., 2014). We provide a theoretical framework for analyzing the robustness of classifiers to adversarial perturbations, and show fundamental upper bounds on the robustness of classifiers. Specifically, we establish a general upper bound on the robustness of classifiers to adversarial perturbations, and then illustrate the obtained upper bound on the families of linear and quadratic classifiers. In both cases, our upper bound depends on a distinguishability measure that captures the notion of difficulty of the classification task. Our results for both classes imply that in tasks involving small distinguishability, no classifier in the considered set will be robust to adversarial perturbations, even if a good accuracy is achieved. Our theoretical framework moreover suggests that the phenomenon of adversarial instability is due to the low flexibility of classifiers, compared to the difficulty of the classification task (captured by the distinguishability). Moreover, we show the existence of a clear distinction between the robustness of a classifier to random noise and its robustness to adversarial perturbations. Specifically, the former is shown to be larger than the latter by a factor that is proportional to \sqrt{d} (with d being the signal dimension) for linear classifiers. This result gives a theoretical explanation for the discrepancy between the two robustness properties in high dimensional problems, which was empirically observed in the context of neural networks. To the best of our knowledge, our results provide the first theoretical work that addresses the phenomenon of adversarial instability recently observed for deep networks. Our analysis is complemented by experimental results on controlled and real-world data.

##### Abstract (translated by Google)
本文的目的是分析最近在深度网络中发现的一个有趣的现象，即它们对对抗性扰动的不稳定性（Szegedy et al。，2014）。为分析分类器对敌对扰动的鲁棒性提供了理论框架，并展示了分类器鲁棒性的基本上界。具体而言，我们建立了分类器对对抗扰动鲁棒性的一般上界，然后说明了线性和二次分类器族的上界。在这两种情况下，我们的上限取决于一个可区分性的度量​​，这个度量体现了分类任务难度的概念。我们对这两个类的结果意味着，在涉及较小区分性的任务中，即使准确度很高，所考虑的分类器中的分类器也不会对抗对抗性扰动。我们的理论框架还表明，对抗性不稳定现象是由于分类器的灵活性较低，而分类任务的困难（由可区分性所捕获）。此外，我们还证明了分类器对随机噪声的鲁棒性以及对敌对扰动的鲁棒性存在明显的区别。具体来说，前者表现为比后者大一个与线性分类器的\ sqrt {d}（其中d是信号维数）成正比的因子。这个结果给出了高维问题中两个鲁棒特性之间的差异的理论解释，这是在神经网络的背景下经验观察到的。就我们所知，我们的研究结果提供了第一个理论工作，解决了最近在深度网络中观测到的对抗性不稳定现象。我们的分析结果是受控和实际数据的实验结果的补充。

##### URL
[https://arxiv.org/abs/1502.02590](https://arxiv.org/abs/1502.02590)

##### PDF
[https://arxiv.org/pdf/1502.02590](https://arxiv.org/pdf/1502.02590)

