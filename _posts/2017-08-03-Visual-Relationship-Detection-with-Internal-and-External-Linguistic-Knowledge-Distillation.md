---
layout: post
title: "Visual Relationship Detection with Internal and External Linguistic Knowledge Distillation"
date: 2017-08-03 00:11:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Detection Relation
author: Ruichi Yu, Ang Li, Vlad I. Morariu, Larry S. Davis
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding visual relationships involves identifying the subject, the object, and a predicate relating them. We leverage the strong correlations between the predicate and the (subj,obj) pair (both semantically and spatially) to predict the predicates conditioned on the subjects and the objects. Modeling the three entities jointly more accurately reflects their relationships, but complicates learning since the semantic space of visual relationships is huge and the training data is limited, especially for the long-tail relationships that have few instances. To overcome this, we use knowledge of linguistic statistics to regularize visual model learning. We obtain linguistic knowledge by mining from both training annotations (internal knowledge) and publicly available text, e.g., Wikipedia (external knowledge), computing the conditional probability distribution of a predicate given a (subj,obj) pair. Then, we distill the knowledge into a deep model to achieve better generalization. Our experimental results on the Visual Relationship Detection (VRD) and Visual Genome datasets suggest that with this linguistic knowledge distillation, our model outperforms the state-of-the-art methods significantly, especially when predicting unseen relationships (e.g., recall improved from 8.45% to 19.17% on VRD zero-shot testing set).

##### Abstract (translated by Google)
理解视觉关系涉及识别主题，对象和与之相关的谓词。我们利用谓词和（subj，obj）对（语义上和空间上）之间的强相关性来预测主体和客体的谓词。由于视觉关系的语义空间巨大且训练数据有限，特别是对于实例较少的长尾关系，联合对这三个实体的建模更加准确地反映了它们之间的关系，但使学习变得复杂。为了克服这一点，我们使用语言统计知识来规范视觉模型学习。我们通过从训练注释（内部知识）和公开可用文本（例如维基百科（外部知识））中挖掘获得语言知识，计算给定（subj，obj）对的谓词的条件概率分布。然后，我们把知识提炼成一个深层次的模型来实现更好的泛化。我们关于视觉关系检测（VRD）和视觉基因组数据集的实验结果表明，在这种语言知识蒸馏的情况下，我们的模型显着优于最先进的方法，特别是当预测不可见的关系时（例如，召回从8.45％到VRD零点测试集的19.17％）。

##### URL
[https://arxiv.org/abs/1707.09423](https://arxiv.org/abs/1707.09423)

##### PDF
[https://arxiv.org/pdf/1707.09423](https://arxiv.org/pdf/1707.09423)

