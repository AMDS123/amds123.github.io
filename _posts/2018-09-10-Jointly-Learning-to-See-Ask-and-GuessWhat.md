---
layout: post
title: "Jointly Learning to See, Ask, and GuessWhat"
date: 2018-09-10 15:46:58
categories: arXiv_CV
tags: arXiv_CV Reinforcement_Learning
author: Aashish Venkatesh, Ravi Shekhar, Tim Baumg&#xe4;rtner, Elia Bruni, Raffaella Bernardi, Raquel Fern&#xe1;ndez
mathjax: true
---

* content
{:toc}

##### Abstract
We are interested in understanding how the ability to ground language in vision interacts with other abilities at play in dialogue, such as asking a series of questions to obtain the necessary information to perform a certain task. With this aim, we develop a Questioner agent in the context of the GuessWhat?! game. Our model exploits a neural network architecture to build a continuous representation of the dialogue state that integrates information from the visual and linguistic modalities and conditions future action. To play the GuessWhat?! game, the Questioner agent has to be able to do both, ask questions and guess a target object in the visual environment. In our architecture, these two capabilities are considered jointly as a supervised multi-task learning problem, to which cooperative learning can be further applied. We show that the introduction of our new architecture combined with these learning regimes yields an increase of 19.5% in task success accuracy with respect to a baseline model that treats submodules independently. With this increase, we reach an accuracy comparable to state-of-the-art models that use reinforcement learning, with the advantage that our architecture is entirely differentiable and thus easier to train. This suggests that combining our approach with reinforcement learning could lead to further improvements in the future. Finally, we present a range of analyses that examine the quality of the dialogues and shed light on the internal dynamics of the model.

##### Abstract (translated by Google)
我们有兴趣了解视觉中的语言能力如何与对话中的其他能力相互作用，例如询问一系列问题以获得执行某项任务所需的信息。为此，我们在GuessWhat的背景下开发了一个Questioner代理？！游戏。我们的模型利用神经网络架构来构建对话状态的连续表示，其整合来自视觉和语言模态的信息并且调节未来行动。玩GuessWhat？！游戏中，提问者代理必须能够做到这两者，在视觉环境中提出问题并猜测目标对象。在我们的体系结构中，这两种功能被联合视为一种受监督的多任务学习问题，可以进一步应用协作学习。我们表明，与独立处理子模块的基线模型相比，引入我们的新架构与这些学习机制相比，任务成功准确率提高了19.5％。随着这种增加，我们达到了与使用强化学习的最先进模型相当的精度，其优势在于我们的架构完全可以区分，因此更容易训练。这表明将我们的方法与强化学习相结合可以在未来进一步改进。最后，我们提出了一系列分析，检查对话的质量，并阐明模型的内部动态。

##### URL
[http://arxiv.org/abs/1809.03408](http://arxiv.org/abs/1809.03408)

##### PDF
[http://arxiv.org/pdf/1809.03408](http://arxiv.org/pdf/1809.03408)

