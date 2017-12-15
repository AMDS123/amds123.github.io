---
layout: post
title: "Incremental Active Opinion Learning Over a Stream of Opinionated Documents"
date: 2015-09-03 22:11:10
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Face
author: Max Zimmermann, Eirini Ntoutsi, Myra Spiliopoulou
mathjax: true
---

* content
{:toc}

##### Abstract
Applications that learn from opinionated documents, like tweets or product reviews, face two challenges. First, the opinionated documents constitute an evolving stream, where both the author's attitude and the vocabulary itself may change. Second, labels of documents are scarce and labels of words are unreliable, because the sentiment of a word depends on the (unknown) context in the author's mind. Most of the research on mining over opinionated streams focuses on the first aspect of the problem, whereas for the second a continuous supply of labels from the stream is assumed. Such an assumption though is utopian as the stream is infinite and the labeling cost is prohibitive. To this end, we investigate the potential of active stream learning algorithms that ask for labels on demand. Our proposed ACOSTREAM 1 approach works with limited labels: it uses an initial seed of labeled documents, occasionally requests additional labels for documents from the human expert and incrementally adapts to the underlying stream while exploiting the available labeled documents. In its core, ACOSTREAM consists of a MNB classifier coupled with "sampling" strategies for requesting class labels for new unlabeled documents. In the experiments, we evaluate the classifier performance over time by varying: (a) the class distribution of the opinionated stream, while assuming that the set of the words in the vocabulary is fixed but their polarities may change with the class distribution; and (b) the number of unknown words arriving at each moment, while the class polarity may also change. Our results show that active learning on a stream of opinionated documents, delivers good performance while requiring a small selection of labels

##### Abstract (translated by Google)
从诸如推文或产品评论等自以为是的文档中学习的应用程序面临着两个挑战。首先，自以为是的文件构成了一个演变的过程，作者的态度和词汇本身都可能发生变化。其次，文献的标签是稀缺的，文字的标签是不可靠的，因为一个词的情感取决于作者头脑中的（未知）情境。大多数关于肆意采矿的研究都集中在问题的第一个方面，而第二个研究则假设了从这个流向中连续提供标签。这样的假设虽然是乌托邦式的，流程是无限的，标签成本是高昂的。为此，我们研究需求标签的主动流学习算法的潜力。我们提议的ACOSTREAM 1方法使用有限的标签：它使用标签文档的初始种子，偶尔会请求来自人类专家的文档的附加标签，并在利用可用标签文档的同时逐渐适应底层流。在其核心，ACOSTREAM由一个MNB分类器和“抽样”策略组成，用于请求新的未标记文档的类别标签。在实验中，我们通过改变分类器的性能来评估分类器的性能：（a）自由流的类分布，同时假设词汇集中的词组是固定的，但是它们的极性可能会随着类别分布而改变;和（b）每个时刻到达的未知单词的数量，而类别极性也可能改变。我们的研究结果表明，积极的学习在一系列的意见文件，提供良好的性能，同时要求少量的标签选择

##### URL
[https://arxiv.org/abs/1509.01288](https://arxiv.org/abs/1509.01288)

##### PDF
[https://arxiv.org/pdf/1509.01288](https://arxiv.org/pdf/1509.01288)

