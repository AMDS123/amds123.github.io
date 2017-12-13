---
layout: post
title: "Visualizing and Understanding Curriculum Learning for Long Short-Term Memory Networks"
date: 2016-11-18 19:38:59
categories: arXiv_CV
tags: arXiv_CV Sentiment RNN Prediction Memory_Networks
author: Volkan Cirik, Eduard Hovy, Louis-Philippe Morency
mathjax: true
---

* content
{:toc}

##### Abstract
Curriculum Learning emphasizes the order of training instances in a computational learning setup. The core hypothesis is that simpler instances should be learned early as building blocks to learn more complex ones. Despite its usefulness, it is still unknown how exactly the internal representation of models are affected by curriculum learning. In this paper, we study the effect of curriculum learning on Long Short-Term Memory (LSTM) networks, which have shown strong competency in many Natural Language Processing (NLP) problems. Our experiments on sentiment analysis task and a synthetic task similar to sequence prediction tasks in NLP show that curriculum learning has a positive effect on the LSTM's internal states by biasing the model towards building constructive representations i.e. the internal representation at the previous timesteps are used as building blocks for the final prediction. We also find that smaller models significantly improves when they are trained with curriculum learning. Lastly, we show that curriculum learning helps more when the amount of training data is limited.

##### Abstract (translated by Google)
课程学习强调了计算机学习环境中训练实例的顺序。核心假设是，应该尽早学习更简单的实例，学习更复杂的实例。尽管它的有用性，模型的内部表示是如何受到课程学习的影响仍然是未知的。在本文中，我们研究了课程学习对长期短期记忆（LSTM）网络的影响，这些网络在许多自然语言处理（NLP）问题中表现出强大的竞争力。我们对情感分析任务的实验以及类似于自然语言处理中序列预测任务的综合任务表明，课程学习通过偏向于构建建设性表示的模型对于内部状态具有积极的作用，即前一时间步的内部表示被用作建筑阻止最终的预测。我们还发现，小型模型在课程学习方面得到了很大的提高。最后，我们表明，当培训数据量有限时，课程学习更有帮助。

##### URL
[https://arxiv.org/abs/1611.06204](https://arxiv.org/abs/1611.06204)

##### PDF
[https://arxiv.org/pdf/1611.06204](https://arxiv.org/pdf/1611.06204)

