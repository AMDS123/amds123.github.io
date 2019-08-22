---
layout: post
title: "Towards Better Understanding of Spontaneous Conversations: Overcoming Automatic Speech Recognition Errors With Intent Recognition"
date: 2019-08-21 14:20:35
categories: arXiv_CL
tags: arXiv_CL Knowledge Speech_Recognition Recognition
author: Piotr &#x17b;elasko, Jan Mizgajski, Miko&#x142;aj Morzy, Adrian Szymczak, Piotr Szyma&#x144;ski, &#x141;ukasz Augustyniak, Yishay Carmiel
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a method for correcting automatic speech recognition (ASR) errors using a finite state transducer (FST) intent recognition framework. Intent recognition is a powerful technique for dialog flow management in turn-oriented, human-machine dialogs. This technique can also be very useful in the context of human-human dialogs, though it serves a different purpose of key insight extraction from conversations. We argue that currently available intent recognition techniques are not applicable to human-human dialogs due to the complex structure of turn-taking and various disfluencies encountered in spontaneous conversations, exacerbated by speech recognition errors and scarcity of domain-specific labeled data. Without efficient key insight extraction techniques, raw human-human dialog transcripts remain significantly unexploited. 
 Our contribution consists of a novel FST for intent indexing and an algorithm for fuzzy intent search over the lattice - a compact graph encoding of ASR's hypotheses. We also develop a pruning strategy to constrain the fuzziness of the FST index search. Extracted intents represent linguistic domain knowledge and help us improve (rescore) the original transcript. We compare our method with a baseline, which uses only the most likely transcript hypothesis (best path), and find an increase in the total number of recognized intents by 25%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07888](http://arxiv.org/abs/1908.07888)

##### PDF
[http://arxiv.org/pdf/1908.07888](http://arxiv.org/pdf/1908.07888)

