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


##### URL
[https://arxiv.org/abs/1709.07840](https://arxiv.org/abs/1709.07840)

##### PDF
[https://arxiv.org/pdf/1709.07840](https://arxiv.org/pdf/1709.07840)

