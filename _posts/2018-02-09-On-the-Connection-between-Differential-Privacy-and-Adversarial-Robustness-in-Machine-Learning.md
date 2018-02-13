---
layout: post
title: "On the Connection between Differential Privacy and Adversarial Robustness in Machine Learning"
date: 2018-02-09 22:24:50
categories: arXiv_AI
tags: arXiv_AI Adversarial Prediction
author: Mathias Lecuyer, Vaggelis Atlidakis, Roxana Geambasu, Daniel Hsu, Suman Jana
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial examples in machine learning has been a topic of intense research interest, with attacks and defenses being developed in a tight back-and-forth. Most past defenses are best-effort, heuristic approaches that have all been shown to be vulnerable to sophisticated attacks. More recently, rigorous defenses that provide formal guarantees have emerged, but are hard to scale or generalize. A rigorous and general foundation for designing defenses is required to get us off this arms race trajectory. We propose leveraging differential privacy (DP) as a formal building block for robustness against adversarial examples. We observe that the semantic of DP is closely aligned with the formal definition of robustness to adversarial examples. We propose PixelDP, a strategy for learning robust deep neural networks based on formal DP guarantees. PixelDP networks give theoretical guarantees for a subset of their predictions regarding the robustness against adversarial perturbations of bounded size. Our evaluation with MNIST, CIFAR-10, and CIFAR-100 shows that PixelDP networks achieve accuracy under attack on par with the best-performing defense to date, but additionally certify robustness against meaningful-size 1-norm and 2-norm attacks for 40-60% of their predictions. Our experience points to DP as a rigorous, broadly applicable, and mechanism-rich foundation for robust machine learning.

##### Abstract (translated by Google)
机器学习中的对抗例子一直是研究兴趣浓厚的话题，攻击和防御正在紧密地来回发展。过去的大部分防御措施都是尽力而为的启发式方法，它们都被证明容易受到复杂的攻击。最近，出现了提供正式保证的严格防御措施，但难以扩展或推广。为了让我们摆脱这个军备竞赛的轨道，需要一个设计防御的严谨而一般的基础。我们建议将差分隐私（DP）作为一个正式的构建模块，以对抗对抗性示例。我们观察到DP的语义与对抗例子的稳健性的正式定义密切相关。我们提出PixelDP，一种基于正式DP保证的学习鲁棒深度神经网络的策略。 PixelDP网络为他们预测关于对抗有限大小的对抗扰动的鲁棒性提供了理论保证。我们对MNIST，CIFAR-10和CIFAR-100的评估表明，PixelDP网络在达到目前最佳性能防御的攻击下达到了准确性，但另外还证明了针对40尺寸的有意义大小的1-范数和2-范数攻击的鲁棒性-60％的预测。我们的经验表明DP是一个严格，广泛适用且机制丰富的机器学习基础。

##### URL
[http://arxiv.org/abs/1802.03471](http://arxiv.org/abs/1802.03471)

##### PDF
[http://arxiv.org/pdf/1802.03471](http://arxiv.org/pdf/1802.03471)

