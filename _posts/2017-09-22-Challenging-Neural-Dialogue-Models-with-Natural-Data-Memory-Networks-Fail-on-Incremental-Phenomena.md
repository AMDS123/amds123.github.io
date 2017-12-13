---
layout: post
title: "Challenging Neural Dialogue Models with Natural Data: Memory Networks Fail on Incremental Phenomena"
date: 2017-09-22 16:43:48
categories: arXiv_CV
tags: arXiv_CV Face Memory_Networks
author: Igor Shalyminov, Arash Eshghi, Oliver Lemon
mathjax: true
---

* content
{:toc}

##### Abstract
Natural, spontaneous dialogue proceeds incrementally on a word-by-word basis; and it contains many sorts of disfluency such as mid-utterance/sentence hesitations, interruptions, and self-corrections. But training data for machine learning approaches to dialogue processing is often either cleaned-up or wholly synthetic in order to avoid such phenomena. The question then arises of how well systems trained on such clean data generalise to real spontaneous dialogue, or indeed whether they are trainable at all on naturally occurring dialogue data. To answer this question, we created a new corpus called bAbI+ by systematically adding natural spontaneous incremental dialogue phenomena such as restarts and self-corrections to the Facebook AI Research's bAbI dialogues dataset. We then explore the performance of a state-of-the-art retrieval model, MemN2N, on this more natural dataset. Results show that the semantic accuracy of the MemN2N model drops drastically; and that although it is in principle able to learn to process the constructions in bAbI+, it needs an impractical amount of training data to do so. Finally, we go on to show that an incremental, semantic parser -- DyLan -- shows 100% semantic accuracy on both bAbI and bAbI+, highlighting the generalisation properties of linguistically informed dialogue models.

##### Abstract (translated by Google)
自然的，自发的对话逐字逐渐进行;它含有诸如中期话语/句子踌躇，中断和自我纠正等多种不良行为。但是，为了避免这种现象，训练用于机器学习方法的对话处理数据通常要么被清理，要么全部是合成的。接下来的问题出现在这样的清洁数据上的系统培训如何被推广到真正的自发对话，或者实际上他们是否可以根据自然发生的对话数据进行培训。为了回答这个问题，我们创建了一个名为bAbI +的新语料库，系统地在Facebook AI Research的bAbI对话数据集中添加了重启和自校正等自然增量对话现象。然后，我们在这个更自然的数据集上探索最先进的检索模型MemN2N的性能。结果表明，MemN2N模型的语义准确性急剧下降，尽管原则上能够学习处理bAbI +中的构造，但是需要不切实际的数量的训练数据来这样做。最后，我们继续说明一个增量的语义解析器DyLan在bAbI和bAbI +上都显示出100％的语义准确性，突出了语言知识对话模型的泛化特性。

##### URL
[https://arxiv.org/abs/1709.07840](https://arxiv.org/abs/1709.07840)

##### PDF
[https://arxiv.org/pdf/1709.07840](https://arxiv.org/pdf/1709.07840)

