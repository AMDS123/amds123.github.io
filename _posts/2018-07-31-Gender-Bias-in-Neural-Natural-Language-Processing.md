---
layout: post
title: "Gender Bias in Neural Natural Language Processing"
date: 2018-07-31 09:27:27
categories: arXiv_CL
tags: arXiv_CL Embedding Optimization RNN Language_Model Gradient_Descent
author: Kaiji Lu, Piotr Mardziel, Fangjing Wu, Preetam Amancharla, Anupam Datta
mathjax: true
---

* content
{:toc}

##### Abstract
We examine whether neural natural language processing (NLP) systems reflect historical biases in training data. We define a general benchmark to quantify gender bias in a variety of neural NLP tasks. Our empirical evaluation with state-of-the-art neural coreference resolution and textbook RNN-based language models trained on benchmark datasets finds significant gender bias in how models view occupations. We then mitigate bias with CDA: a generic methodology for corpus augmentation via causal interventions that breaks associations between gendered and gender-neutral words. We empirically show that CDA effectively decreases gender bias while preserving accuracy. We also explore the space of mitigation strategies with CDA, a prior approach to word embedding debiasing (WED), and their compositions. We show that CDA outperforms WED, drastically so when word embeddings are trained. For pre-trained embeddings, the two methods can be effectively composed. We also find that as training proceeds on the original data set with gradient descent the gender bias grows as the loss reduces, indicating that the optimization encourages bias; CDA mitigates this behavior.

##### Abstract (translated by Google)
我们检查神经自然语言处理（NLP）系统是否反映了训练数据中的历史偏差。我们定义了一个通用基准来量化各种神经NLP任务中的性别偏差。我们使用最先进的神经共指分辨率和基于RNN的教科书语言模型进行经验评估，在基准数据集上进行培训，发现模型对职业的看法存在显着的性别偏差。然后，我们通过CDA缓解偏见：通过因果干预来破坏语料库的通用方法，这种干预措施打破了性别和性别中性词之间的关联。我们凭经验证明，CDA有效地减少了性别偏见，同时保持了准确性。我们还用CDA探索了缓解策略的空间，CDA是一种先前的嵌入式去除（WED）方法及其组合。我们证明CDA的性能远远高于WED，因此在训练单词嵌入时也是如此。对于预先训练的嵌入，可以有效地组合这两种方法。我们还发现随着对具有梯度下降的原始数据集的训练的进行，性别偏差随着损失的减少而增加，表明优化会促使偏差; CDA缓解了这种行为。

##### URL
[http://arxiv.org/abs/1807.11714](http://arxiv.org/abs/1807.11714)

##### PDF
[http://arxiv.org/pdf/1807.11714](http://arxiv.org/pdf/1807.11714)

