---
layout: post
title: "Soft Contextual Data Augmentation for Neural Machine Translation"
date: 2019-05-25 05:28:03
categories: arXiv_CL
tags: arXiv_CL Embedding Deep_Learning Language_Model
author: Jinhua Zhu, Fei Gao, Lijun Wu, Yingce Xia, Tao Qin, Wengang Zhou, Xueqi Cheng, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
While data augmentation is an important trick to boost the accuracy of deep learning methods in computer vision tasks, its study in natural language tasks is still very limited. In this paper, we present a novel data augmentation method for neural machine translation. Different from previous augmentation methods that randomly drop, swap or replace words with other words in a sentence, we softly augment a randomly chosen word in a sentence by its contextual mixture of multiple related words. More accurately, we replace the one-hot representation of a word by a distribution (provided by a language model) over the vocabulary, i.e., replacing the embedding of this word by a weighted combination of multiple semantically similar words. Since the weights of those words depend on the contextual information of the word to be replaced, the newly generated sentences capture much richer information than previous augmentation methods. Experimental results on both small scale and large scale machine translation datasets demonstrate the superiority of our method over strong baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10523](http://arxiv.org/abs/1905.10523)

##### PDF
[http://arxiv.org/pdf/1905.10523](http://arxiv.org/pdf/1905.10523)

