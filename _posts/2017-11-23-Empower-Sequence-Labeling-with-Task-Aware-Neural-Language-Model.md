---
layout: post
title: "Empower Sequence Labeling with Task-Aware Neural Language Model"
date: 2017-11-23 23:12:40
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Transfer_Learning Language_Model Recognition
author: Liyuan Liu, Jingbo Shang, Frank F. Xu, Xiang Ren, Huan Gui, Jian Peng, Jiawei Han
mathjax: true
---

* content
{:toc}

##### Abstract
Linguistic sequence labeling is a general modeling approach that encompasses a variety of problems, such as part-of-speech tagging and named entity recognition. Recent advances in neural networks (NNs) make it possible to build reliable models without handcrafted features. However, in many cases, it is hard to obtain sufficient annotations to train these models. In this study, we develop a novel neural framework to extract abundant knowledge hidden in raw texts to empower the sequence labeling task. Besides word-level knowledge contained in pre-trained word embeddings, character-aware neural language models are incorporated to extract character-level knowledge. Transfer learning techniques are further adopted to mediate different components and guide the language model towards the key knowledge. Comparing to previous methods, these task-specific knowledge allows us to adopt a more concise model and conduct more efficient training. Different from most transfer learning methods, the proposed framework does not rely on any additional supervision. It extracts knowledge from self-contained order information of training sequences. Extensive experiments on benchmark datasets demonstrate the effectiveness of leveraging character-level knowledge and the efficiency of co-training. For example, on the CoNLL03 NER task, model training completes in about 6 hours on a single GPU, reaching F1 score of 91.71$\pm$0.10 without using any extra annotation.

##### Abstract (translated by Google)
语言序列标注是一种通用的建模方法，包括各种问题，如词性标注和命名实体识别。神经网络（NN）的最新进展使得可以在没有手工特征的情况下构建可靠的模型。但是，在许多情况下，很难获得足够的注释来训练这些模型。在这项研究中，我们开发了一个新的神经框架，以提取丰富的知识隐藏在原始文本授权序列标签任务。除了预先训练的词嵌入中包含的单词级知识，还包含了字符感知神经语言模型以提取特征级知识。转移学习技术进一步被用来调解不同的组件，并引导语言模型走向关键知识。与以前的方法相比，这些特定任务的知识使我们能够采用更简洁的模型并进行更有效的培训。与大多数转移学习方法不同，所提出的框架不依赖任何额外的监督。它从训练序列的自足订单信息中提取知识。基准数据集的大量实验证明了利用字符级知识的有效性和共同训练的效率。例如，在CoNLL03 NER任务上，模型训练在一个GPU上大约在6个小时内完成，达到91.71 $ \ pm $ 0.10的F1得分，而不使用任何额外的注释。

##### URL
[https://arxiv.org/abs/1709.04109](https://arxiv.org/abs/1709.04109)

##### PDF
[https://arxiv.org/pdf/1709.04109](https://arxiv.org/pdf/1709.04109)

