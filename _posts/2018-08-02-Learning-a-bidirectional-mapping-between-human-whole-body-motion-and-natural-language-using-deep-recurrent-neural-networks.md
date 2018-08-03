---
layout: post
title: "Learning a bidirectional mapping between human whole-body motion and natural language using deep recurrent neural networks"
date: 2018-08-02 10:07:57
categories: arXiv_CL
tags: arXiv_CL Segmentation RNN Deep_Learning
author: Matthias Plappert, Christian Mandery, Tamim Asfour
mathjax: true
---

* content
{:toc}

##### Abstract
Linking human whole-body motion and natural language is of great interest for the generation of semantic representations of observed human behaviors as well as for the generation of robot behaviors based on natural language input. While there has been a large body of research in this area, most approaches that exist today require a symbolic representation of motions (e.g. in the form of motion primitives), which have to be defined a-priori or require complex segmentation algorithms. In contrast, recent advances in the field of neural networks and especially deep learning have demonstrated that sub-symbolic representations that can be learned end-to-end usually outperform more traditional approaches, for applications such as machine translation. In this paper we propose a generative model that learns a bidirectional mapping between human whole-body motion and natural language using deep recurrent neural networks (RNNs) and sequence-to-sequence learning. Our approach does not require any segmentation or manual feature engineering and learns a distributed representation, which is shared for all motions and descriptions. We evaluate our approach on 2,846 human whole-body motions and 6,187 natural language descriptions thereof from the KIT Motion-Language Dataset. Our results clearly demonstrate the effectiveness of the proposed model: We show that our model generates a wide variety of realistic motions only from descriptions thereof in form of a single sentence. Conversely, our model is also capable of generating correct and detailed natural language descriptions from human motions.

##### Abstract (translated by Google)
将人体全身运动与自然语言联系起来对于生成观察到的人类行为的语义表示以及基于自然语言输入的机器人行为的生成具有极大的兴趣。虽然在该领域已经进行了大量研究，但是现在存在的大多数方法需要运动的符号表示（例如以运动图元的形式），其必须先验地定义或者需要复杂的分割算法。相比之下，神经网络领域的最新进展，特别是深度学习已经证明，对于诸如机器翻译之类的应用，可以端到端学习的子符号表示通常优于更传统的方法。在本文中，我们提出了一个生成模型，该模型使用深度递归神经网络（RNN）和序列到序列学习来学习人体全身运动和自然语言之间的双向映射。我们的方法不需要任何分段或手动特征工程，并且学习分布式表示，这对于所有动作和描述都是共享的。我们从KIT运动语言数据集中评估我们对2,846个人体全身运动和6,187个自然语言描述的方法。我们的结果清楚地证明了所提出的模型的有效性：我们表明我们的模型仅通过单句形式的描述产生各种各样的逼真运动。相反，我们的模型也能够从人类运动中生成正确和详细的自然语言描述。

##### URL
[http://arxiv.org/abs/1705.06400](http://arxiv.org/abs/1705.06400)

##### PDF
[http://arxiv.org/pdf/1705.06400](http://arxiv.org/pdf/1705.06400)

