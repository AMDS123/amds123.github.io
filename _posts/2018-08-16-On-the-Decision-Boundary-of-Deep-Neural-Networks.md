---
layout: post
title: "On the Decision Boundary of Deep Neural Networks"
date: 2018-08-16 09:25:50
categories: arXiv_AI
tags: arXiv_AI Adversarial Deep_Learning
author: Yu Li, Peter Richtarik, Lizhong Ding, Xin Gao
mathjax: true
---

* content
{:toc}

##### Abstract
While deep learning models and techniques have achieved great empirical success, our understanding of the source of success in many aspects remains very limited. In an attempt to bridge the gap, we investigate the decision boundary of a production deep learning architecture with weak assumptions on both the training data and the model. We demonstrate, both theoretically and empirically, that the last weight layer of a neural network converges to a linear SVM trained on the output of the last hidden layer, for both the binary case and the multi-class case with the commonly used cross-entropy loss. Furthermore, we show empirically that training a neural network as a whole, instead of only fine-tuning the last weight layer, may result in better bias constant for the last weight layer, which is important for generalization. In addition to facilitating the understanding of deep learning, our result can be helpful for solving a broad range of practical problems of deep learning, such as catastrophic forgetting and adversarial attacking. The experiment codes are available at https://github.com/lykaust15/NN_decision_boundary

##### Abstract (translated by Google)
虽然深度学习模型和技术取得了很大的经验成功，但我们对许多方面成功来源的理解仍然非常有限。为了弥合差距，我们研究了生产深度学习架构的决策边界，对训练数据和模型都有微弱的假设。我们在理论上和经验上证明，对于二元情形和具有常用交叉熵的多类情况，神经网络的最后权重层收敛于在最后隐藏层的输出上训练的线性SVM。失利。此外，我们凭经验证明，训练神经网络作为一个整体，而不是仅微调最后一个权重层，可能会导致最后一个权重层的偏置常数更好，这对于推广非常重要。除了促进对深度学习的理解之外，我们的结果还有助于解决深度学习的广泛实际问题，例如灾难性遗忘和对抗性攻击。实验代码可在https://github.com/lykaust15/NN_decision_boundary上找到

##### URL
[http://arxiv.org/abs/1808.05385](http://arxiv.org/abs/1808.05385)

##### PDF
[http://arxiv.org/pdf/1808.05385](http://arxiv.org/pdf/1808.05385)

