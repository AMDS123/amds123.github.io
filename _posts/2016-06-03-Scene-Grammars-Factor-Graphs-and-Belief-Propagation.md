---
layout: post
title: "Scene Grammars, Factor Graphs, and Belief Propagation"
date: 2016-06-03 23:49:02
categories: arXiv_CV
tags: arXiv_CV Face Inference Relation
author: Jeroen Chua, Pedro F. Felzenszwalb
mathjax: true
---

* content
{:toc}

##### Abstract
We consider a class of probabilistic grammars for generating scenes with multiple objects. Probabilistic scene grammars capture relationships between objects using compositional rules that provide important contextual cues for inference with ambiguous data. We show how to represent the distribution defined by a probabilistic scene grammar using a factor graph. We also show how to efficiently perform message passing in this factor graph. This leads to an efficient approach for inference with a grammar model using belief propagation as the underlying computational engine. Inference with belief propagation naturally combines bottom-up and top-down contextual information and leads to a robust algorithm for aggregating evidence. We show experiments on two different applications to demonstrate the generality of the framework. The first application involves detecting curves in noisy images, and we address this problem using a grammar that generates a collection of curves using a first-order Markov process. The second application involves localizing faces and parts of faces in images. In this case, we use a grammar that captures spatial relationships between the parts of a face. In both applications the same framework leads to robust inference algorithms that can effectively combine weak local information to reason about a scene.

##### Abstract (translated by Google)
我们考虑用于生成具有多个对象的场景的一类概率语法。概率场景语法使用组合规则来捕获对象之间的关系，所述组合规则提供用于模糊数据的推断的重要上下文线索。我们展示了如何使用因子图表示由概率场景语法定义的分布。我们还展示了如何在这个因子图中有效地执行消息传递。这导致了一种使用信念传播作为基础计算引擎的用语法模型进行推理的有效方法。信念传播的推理自然地结合了自下而上和自上而下的上下文信息，并导致了用于汇总证据的鲁棒算法。我们展示两个不同的应用程序的实验来演示框架的一般性。第一个应用涉及在噪声图像中检测曲线，并且我们使用一个语法来解决这个问题，该语法使用一阶马尔科夫过程生成一组曲线。第二个应用涉及定位图像中的人脸和部分人脸。在这种情况下，我们使用捕捉脸部各部分之间空间关系的语法。在这两个应用程序中，相同的框架导致强大的推理算法，可以有效地结合弱局部信息来推理场景。

##### URL
[https://arxiv.org/abs/1606.01307](https://arxiv.org/abs/1606.01307)

##### PDF
[https://arxiv.org/pdf/1606.01307](https://arxiv.org/pdf/1606.01307)

