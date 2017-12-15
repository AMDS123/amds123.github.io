---
layout: post
title: "Neural Multi-Step Reasoning for Question Answering on Semi-Structured Tables"
date: 2017-02-21 21:24:26
categories: arXiv_SD
tags: arXiv_SD Weakly_Supervised CNN Deep_Learning
author: Till Haug, Octavian-Eugen Ganea, Paulina Grnarova
mathjax: true
---

* content
{:toc}

##### Abstract
Advances in natural language processing tasks have gained momentum in recent years due to the increasingly popular neural network methods. In this paper, we explore deep learning techniques for answering multi-step reasoning questions that operate on semi-structured tables. Challenges here arise from the level of logical compositionality expressed by questions, as well as the domain openness. Our approach is weakly supervised, trained on question-answer-table triples without requiring intermediate strong supervision. It performs two phases: first, machine understandable logical forms (programs) are generated from natural language questions following the work of [Pasupat and Liang, 2015]. Second, paraphrases of logical forms and questions are embedded in a jointly learned vector space using word and character convolutional neural networks. A neural scoring function is further used to rank and retrieve the most probable logical form (interpretation) of a question. Our best single model achieves 34.8% accuracy on the WikiTableQuestions dataset, while the best ensemble of our models pushes the state-of-the-art score on this task to 38.7%, thus slightly surpassing both the engineered feature scoring baseline, as well as the Neural Programmer model of [Neelakantan et al., 2016].

##### Abstract (translated by Google)
由于日益流行的神经网络方法，自然语言处理任务的进展近年来得到了推动。在本文中，我们探索深度学习技术来回答在半结构化表格上操作的多步推理问题。这里面临的挑战来自于问题表达的逻辑组合性水平以及域的开放性。我们的方法是弱监督的，在问答表三倍的情况下训练，而不需要中间的强有力的监督。它执行两个阶段：首先，机器可理解的逻辑形式（程序）是在[Pasupat和Liang，2015]的工作之后从自然语言问题生成的。其次，逻辑形式和问题的解释被嵌入在使用字和字符卷积神经网络的联合学习向量空间中。神经评分函数进一步用于排序和检索问题的最可能的逻辑形式（解释）。我们最好的单一模型在WikiTableQuestions数据集上达到了34.8％的准确性，而我们模型的最佳集合将此任务的最新成绩推到了38.7％，因此略微超过了设计特征评分基准，以及神经程序员模型[Neelakantan等，2016]。

##### URL
[https://arxiv.org/abs/1702.06589](https://arxiv.org/abs/1702.06589)

##### PDF
[https://arxiv.org/pdf/1702.06589](https://arxiv.org/pdf/1702.06589)

