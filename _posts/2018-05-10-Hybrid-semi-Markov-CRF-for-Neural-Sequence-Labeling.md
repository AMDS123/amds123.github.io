---
layout: post
title: "Hybrid semi-Markov CRF for Neural Sequence Labeling"
date: 2018-05-10 06:14:36
categories: arXiv_CL
tags: arXiv_CL Knowledge Recognition
author: Zhi-Xiu Ye, Zhen-Hua Ling
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes hybrid semi-Markov conditional random fields (SCRFs) for neural sequence labeling in natural language processing. Based on conventional conditional random fields (CRFs), SCRFs have been designed for the tasks of assigning labels to segments by extracting features from and describing transitions between segments instead of words. In this paper, we improve the existing SCRF methods by employing word-level and segment-level information simultaneously. First, word-level labels are utilized to derive the segment scores in SCRFs. Second, a CRF output layer and an SCRF output layer are integrated into an unified neural network and trained jointly. Experimental results on CoNLL 2003 named entity recognition (NER) shared task show that our model achieves state-of-the-art performance when no external knowledge is used.

##### Abstract (translated by Google)
本文在自然语言处理中提出了用于神经序列标记的混合半马尔可夫条件随机场（SCRF）。基于传统的条件随机场（CRF），SCRF已经被设计用于通过从段中提取特征并且描述段之间的转变而不是词来将标签分配给段。在本文中，我们通过同时使用字级和段级信息来改进现有的SCRF方法。首先，利用词级标签来导出SCRF中的分数分数。其次，CRF输出层和SCRF输出层被集成到统一的神经网络中并且被共同训练。 CoNLL 2003命名实体识别（NER）共享任务的实验结果表明，当没有外部知识时，我们的模型达到了最先进的性能。

##### URL
[http://arxiv.org/abs/1805.03838](http://arxiv.org/abs/1805.03838)

##### PDF
[http://arxiv.org/pdf/1805.03838](http://arxiv.org/pdf/1805.03838)

