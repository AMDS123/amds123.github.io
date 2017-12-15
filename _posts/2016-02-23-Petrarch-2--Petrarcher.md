---
layout: post
title: "Petrarch 2 : Petrarcher"
date: 2016-02-23 17:05:06
categories: arXiv_SD
tags: arXiv_SD
author: Clayton Norris
mathjax: true
---

* content
{:toc}

##### Abstract
PETRARCH 2 is the fourth generation of a series of Event-Data coders stemming from research by Phillip Schrodt. Each iteration has brought new functionality and usability, and this is no exception.Petrarch 2 takes much of the power of the original Petrarch's dictionaries and redirects it into a faster and smarter core logic. Earlier iterations handled sentences largely as a list of words, incorporating some syntactic information here and there. Petrarch 2 now views the sentence entirely on the syntactic level. It receives the syntactic parse of a sentence from the Stanford CoreNLP software, and stores this data as a tree structure of linked nodes, where each node is a Phrase object. Prepositional, noun, and verb phrases each have their own version of this Phrase class, which deals with the logic particular to those kinds of phrases. Since this is an event coder, the core of the logic focuses around the verbs: who is acting, who is being acted on, and what is happening. The theory behind this new structure and its logic is founded in Generative Grammar, Information Theory, and Lambda-Calculus Semantics.

##### Abstract (translated by Google)
PETRARCH 2是Phillip Schrodt研究的第四代事件数据编码器。每一次迭代都带来了新的功能和可用性，这也不例外.Perarch 2很大程度上接受了Petrarch原版字典的大部分功能，并将其重定向到一个更快更智能的核心逻辑。早些时候的迭代处理句子的时候主要是把单词列表放进去，在这里和那里结合了一些句法信息。 Petrarch 2现在完全在句法层面看这个句子。它接收来自Stanford CoreNLP软件的句子的句法分析，并将该数据存储为链接节点的树形结构，其中每个节点是Phrase对象。介词，名词和动词短语每个都有自己的这个短语类的版本，它处理这些短语的特定逻辑。由于这是一个事件编码器，逻辑的核心围绕着动词：谁在演戏，谁正在演戏，发生了什么。这个新结构及其逻辑的理论基础是生成语法，信息理论和Lambda微积分语义学。

##### URL
[https://arxiv.org/abs/1602.07236](https://arxiv.org/abs/1602.07236)

##### PDF
[https://arxiv.org/pdf/1602.07236](https://arxiv.org/pdf/1602.07236)

