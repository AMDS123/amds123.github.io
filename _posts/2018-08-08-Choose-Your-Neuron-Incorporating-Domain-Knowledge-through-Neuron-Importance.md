---
layout: post
title: "Choose Your Neuron: Incorporating Domain Knowledge through Neuron-Importance"
date: 2018-08-08 17:00:43
categories: arXiv_CV
tags: arXiv_CV Knowledge Caption CNN Classification Prediction
author: Ramprasaath R. Selvaraju, Prithvijit Chattopadhyay, Mohamed Elhoseiny, Tilak Sharma, Dhruv Batra, Devi Parikh, Stefan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Individual neurons in convolutional neural networks supervised for image-level classification tasks have been shown to implicitly learn semantically meaningful concepts ranging from simple textures and shapes to whole or partial objects - forming a "dictionary" of concepts acquired through the learning process. In this work we introduce a simple, efficient zero-shot learning approach based on this observation. Our approach, which we call Neuron Importance-AwareWeight Transfer (NIWT), learns to map domain knowledge about novel "unseen" classes onto this dictionary of learned concepts and then optimizes for network parameters that can effectively combine these concepts - essentially learning classifiers by discovering and composing learned semantic concepts in deep networks. Our approach shows improvements over previous approaches on the CUBirds and AWA2 generalized zero-shot learning benchmarks. We demonstrate our approach on a diverse set of semantic inputs as external domain knowledge including attributes and natural language captions. Moreover by learning inverse mappings, NIWT can provide visual and textual explanations for the predictions made by the newly learned classifiers and provide neuron names. Our code is available at https://github.com/ramprs/neuron-importance-zsl.

##### Abstract (translated by Google)
已经证明，用于图像级分类任务的卷积神经网络中的各个神经元隐含地学习从简单纹理和形状到整个或部分对象的语义上有意义的概念 - 形成通过学习过程获得的概念的“字典”。在这项工作中，我们基于这种观察引入了一种简单，有效的零射击学习方法。我们的方法，我们称之为神经元重要性 - 感知力传递（NIWT），学习将关于小说“看不见”类的领域知识映射到这个学习概念词典，然后优化网络参数，可以有效地结合这些概念 - 基本上通过发现学习分类器并在深层网络中编写学习的语义概念。我们的方法显示了对CUBirds和AWA2广义零射击学习基准的先前方法的改进。我们将各种语义输入的方法展示为外部领域知识，包括属性和自然语言标题。此外，通过学习逆映射，NIWT可以为新学习的分类器提供的预测提供视觉和文本解释，并提供神经元名称。我们的代码可在https://github.com/ramprs/neuron-importance-zsl上找到。

##### URL
[http://arxiv.org/abs/1808.02861](http://arxiv.org/abs/1808.02861)

##### PDF
[http://arxiv.org/pdf/1808.02861](http://arxiv.org/pdf/1808.02861)

