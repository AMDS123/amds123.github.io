---
layout: post
title: "Leveraging Multi-grained Sentiment Lexicon Information for Neural Sequence Models"
date: 2018-12-04 17:01:52
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention Sentiment_Classification Embedding RNN Classification
author: Yan Zeng, Yangyang Lan, Yazhou Hao, Chen Li, Qinhua Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
Neural sequence models have achieved great success in sentence-level sentiment classification. However, some models are exceptionally complex or based on expensive features. Some other models recognize the value of existed linguistic resource but utilize it insufficiently. This paper proposes a novel and general method to incorporate lexicon information, including sentiment lexicons(+/-), negation words and intensifiers. Words are annotated in fine-grained and coarse-grained labels. The proposed method first encodes the fine-grained labels into sentiment embedding and concatenates it with word embedding. Second, the coarse-grained labels are utilized to enhance the attention mechanism to give large weight on sentiment-related words. Experimental results show that our method can increase classification accuracy for neural sequence models on both SST-5 and MR dataset. Specifically, the enhanced Bi-LSTM model can even compare with a Tree-LSTM which uses expensive phrase-level annotations. Further analysis shows that in most cases the lexicon resource can offer the right annotations. Besides, the proposed method is capable of overcoming the effect from inevitably wrong annotations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01527](http://arxiv.org/abs/1812.01527)

##### PDF
[http://arxiv.org/pdf/1812.01527](http://arxiv.org/pdf/1812.01527)

