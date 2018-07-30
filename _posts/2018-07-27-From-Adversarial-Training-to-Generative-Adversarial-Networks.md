---
layout: post
title: "From Adversarial Training to Generative Adversarial Networks"
date: 2018-07-27 06:50:43
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Quantitative
author: Xuanqing Liu, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we are interested in two seemingly different concepts: \textit{adversarial training} and \textit{generative adversarial networks (GANs)}. Particularly, how these techniques help to improve each other. To this end, we analyze the limitation of adversarial training as the defense method, starting from questioning how well the robustness of a model can generalize. Then, we successfully improve the generalizability via data augmentation by the ``fake'' images sampled from generative adversarial networks. After that, we are surprised to see that the resulting robust classifier leads to a better generator, for free. We intuitively explain this interesting phenomenon and leave the theoretical analysis for future work. Motivated by these observations, we propose a system that combines generator, discriminator, and adversarial attacker in a single network. After end-to-end training and fine tuning, our method can simultaneously improve the robustness of classifiers, measured by accuracy under strong adversarial attacks; and the quality of generators, evaluated both aesthetically and quantitatively. In terms of the classifier, we achieve better robustness than the state-of-the-art adversarial training algorithm proposed in (Madry etla., 2017), while our generator achieves competitive performance compared with SN-GAN (Miyato and Koyama, 2018). Source code is publicly available online at \url{https://github.com/anonymous}.

##### Abstract (translated by Google)
在本文中，我们对两个看似不同的概念感兴趣：\ textit {adversarial training}和\ textit {generative adversarial networks（GANs）}。特别是，这些技术如何有助于相互改进。为此，我们分析了对抗性训练作为防御方法的局限性，从质疑模型的稳健性可以概括得多。然后，我们通过从生成对抗网络中采样的“假”图像，通过数据增强成功地提高了普遍性。之后，我们惊讶地发现，由此产生的强大分类器可以免费获得更好的发生器。我们直观地解释了这个有趣的现象，并为未来的工作留下了理论分析。受这些观察的启发，我们提出了一种在单个网络中结合发生器，鉴别器和对抗性攻击者的系统。在端到端训练和微调之后，我们的方法可以同时提高分类器的鲁棒性，在强对抗性攻击下通过准确度来衡量;和发电机的质量，在美学和数量上进行评估。就分类器而言，我们实现了比（Madry etla。，2017）中提出的最先进的对抗训练算法更好的鲁棒性，而我们的发电机与SN-GAN（Miyato和Koyama，2018）相比实现了竞争性能。 。源代码可在\ url {https://github.com/anonymous}在线公开获取。

##### URL
[http://arxiv.org/abs/1807.10454](http://arxiv.org/abs/1807.10454)

##### PDF
[http://arxiv.org/pdf/1807.10454](http://arxiv.org/pdf/1807.10454)

