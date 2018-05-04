---
layout: post
title: "Towards Diverse Text Generation with Inverse Reinforcement Learning"
date: 2018-04-30 15:04:21
categories: arXiv_AI
tags: arXiv_AI Adversarial Text_Generation Reinforcement_Learning
author: Zhan Shi, Xinchi Chen, Xipeng Qiu, Xuanjing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Text generation is a crucial task in NLP. Recently, several adversarial generative models have been proposed to improve the exposure bias problem in text generation. Though these models gain great success, they still suffer from the problems of reward sparsity and mode collapse. In order to address these two problems, in this paper, we employ inverse reinforcement learning (IRL) for text generation. Specifically, the IRL framework learns a reward function on training data, and then an optimal policy to maximum the expected total reward. Similar to the adversarial models, the reward and policy function in IRL are optimized alternately. Our method has two advantages: (1) the reward function can produce more dense reward signals. (2) the generation policy, trained by "entropy regularized" policy gradient, encourages to generate more diversified texts. Experiment results demonstrate that our proposed method can generate higher quality texts than the previous methods.

##### Abstract (translated by Google)
文本生成是NLP中的关键任务。近来，已经提出了几种对抗生成模型来改善文本生成中的暴露偏差问题。尽管这些模型取得了巨大的成功，但它们仍然存在着稀疏性和模式崩溃的问题。为了解决这两个问题，在本文中，我们使用反向强化学习（IRL）来生成文本。具体而言，IRL框架学习了关于训练数据的奖励函数，然后获得了最大化预期总奖励的最优策略。与敌对模型类似，IRL中的奖励和政策功能交替优化。我们的方法有两个优点：（1）奖励函数可以产生更多稠密的奖励信号。 （2）通过“熵正则化”政策梯度进行培训的发电政策鼓励产生更多样化的文本。实验结果表明，我们提出的方法可以产生比以前的方法更高质量的文本。

##### URL
[https://arxiv.org/abs/1804.11258](https://arxiv.org/abs/1804.11258)

##### PDF
[https://arxiv.org/pdf/1804.11258](https://arxiv.org/pdf/1804.11258)

