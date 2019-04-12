---
layout: post
title: "A Grounded Unsupervised Universal Part-of-Speech Tagger for Low-Resource Languages"
date: 2019-04-10 20:22:31
categories: arXiv_AI
tags: arXiv_AI
author: Ronald Cardenas, Ying Lin, Heng Ji, Jonathan May
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised part of speech (POS) tagging is often framed as a clustering problem, but practical taggers need to \textit{ground} their clusters as well. Grounding generally requires reference labeled data, a luxury a low-resource language might not have. In this work, we describe an approach for low-resource unsupervised POS tagging that yields fully grounded output and requires no labeled training data. We find the classic method of Brown et al. (1992) clusters well in our use case and employ a decipherment-based approach to grounding. This approach presumes a sequence of cluster IDs is a `ciphertext' and seeks a POS tag-to-cluster ID mapping that will reveal the POS sequence. We show intrinsically that, despite the difficulty of the task, we obtain reasonable performance across a variety of languages. We also show extrinsically that incorporating our POS tagger into a name tagger leads to state-of-the-art tagging performance in Sinhalese and Kinyarwanda, two languages with nearly no labeled POS data available. We further demonstrate our tagger's utility by incorporating it into a true `zero-resource' variant of the Malopa (Ammar et al., 2016) dependency parser model that removes the current reliance on multilingual resources and gold POS tags for new languages. Experiments show that including our tagger makes up much of the accuracy lost when gold POS tags are unavailable.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05426](http://arxiv.org/abs/1904.05426)

##### PDF
[http://arxiv.org/pdf/1904.05426](http://arxiv.org/pdf/1904.05426)

