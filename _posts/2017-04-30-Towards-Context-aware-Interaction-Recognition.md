---
layout: post
title: "Towards Context-aware Interaction Recognition"
date: 2017-04-30 23:55:42
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Language_Model Recognition
author: Bohan Zhuang, Lingqiao Liu, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing how objects interact with each other is a crucial task in visual recognition. If we define the context of the interaction to be the objects involved, then most current methods can be categorized as either: (i) training a single classifier on the combination of the interaction and its context; or (ii) aiming to recognize the interaction independently of its explicit context. Both methods suffer limitations: the former scales poorly with the number of combinations and fails to generalize to unseen combinations, while the latter often leads to poor interaction recognition performance due to the difficulty of designing a context-independent interaction classifier. To mitigate those drawbacks, this paper proposes an alternative, context-aware interaction recognition framework. The key to our method is to explicitly construct an interaction classifier which combines the context, and the interaction. The context is encoded via word2vec into a semantic space, and is used to derive a classification result for the interaction. The proposed method still builds one classifier for one interaction (as per type (ii) above), but the classifier built is adaptive to context via weights which are context dependent. The benefit of using the semantic space is that it naturally leads to zero-shot generalizations in which semantically similar contexts (subjectobject pairs) can be recognized as suitable contexts for an interaction, even if they were not observed in the training set.

##### Abstract (translated by Google)
认识到物体如何相互作用是视觉识别的关键任务。如果我们将交互的上下文定义为涉及的对象，那么大多数当前的方法可以被分类为：（i）在交互及其上下文的组合上训练单个分类器;或者（ii）旨在独立于其明确的上下文来识别交互。两种方法都受到限制：前者与组合的数目不匹配，不能推广到看不见的组合，而后者通常由于设计与上下文无关的交互分类器的困难而导致较差的交互识别性能。为了减轻这些缺点，本文提出了一种替代的上下文感知交互识别框架。我们方法的关键是明确地构造一个结合上下文和交互的交互分类器。上下文通过word2vec编码成语义空间，用于派生出交互的分类结果。所提出的方法仍然为一次交互建立一个分类器（按照上面的类型（ii）），但是建立的分类器通过与上下文相关的权重来适应上下文。使用语义空间的好处是它自然地导致零炮概括，其中在语义上相似的上下文（主体对象）可以被识别为用于交互的合适的上下文，即使它们在训练集中没有被观察到。

##### URL
[https://arxiv.org/abs/1703.06246](https://arxiv.org/abs/1703.06246)

##### PDF
[https://arxiv.org/pdf/1703.06246](https://arxiv.org/pdf/1703.06246)

