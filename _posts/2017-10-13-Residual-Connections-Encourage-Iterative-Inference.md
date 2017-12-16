---
layout: post
title: "Residual Connections Encourage Iterative Inference"
date: 2017-10-13 01:39:32
categories: arXiv_CV
tags: arXiv_CV Represenation_Learning Inference Deep_Learning
author: Stanisław Jastrzebski, Devansh Arpit, Nicolas Ballas, Vikas Verma, Tong Che, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Residual networks (Resnets) have become a prominent architecture in deep learning. However, a comprehensive understanding of Resnets is still a topic of ongoing research. A recent view argues that Resnets perform iterative refinement of features. We attempt to further expose properties of this aspect. To this end, we study Resnets both analytically and empirically. We formalize the notion of iterative refinement in Resnets by showing that residual architectures naturally encourage features to move along the negative gradient of loss during the feedforward phase. In addition, our empirical analysis suggests that Resnets are able to perform both representation learning and iterative refinement. In general, a Resnet block tends to concentrate representation learning behavior in the first few layers while higher layers perform iterative refinement of features. Finally we observe that sharing residual layers naively leads to representation explosion and hurts generalization performance, and show that simple existing strategies can help alleviating this problem.

##### Abstract (translated by Google)
剩余网络（Resnets）已经成为深入学习的重要架构。然而，对Resnets的全面理解仍然是一个正在进行的研究的话题。最近的观点认为，Resnets执行功能的迭代改进。我们试图进一步揭露这方面的特性。为此，我们分析和经验研究Resnets。我们通过展示剩余体系结构在前馈阶段自然地鼓励特征沿着负向梯度的损失移动来形式化Resnets中迭代改进的概念。此外，我们的实证分析表明，Resnets能够执行表示学习和迭代细化。一般来说，一个Resnet块倾向于把表现学习行为集中在前几层，而较高层则对特征进行迭代改进。最后我们观察到，天真地共享剩余层会导致表示的爆炸，并且损害泛化性能，并且表明简单的现有策略可以帮助缓解这个问题。

##### URL
[https://arxiv.org/abs/1710.04773](https://arxiv.org/abs/1710.04773)

##### PDF
[https://arxiv.org/pdf/1710.04773](https://arxiv.org/pdf/1710.04773)

