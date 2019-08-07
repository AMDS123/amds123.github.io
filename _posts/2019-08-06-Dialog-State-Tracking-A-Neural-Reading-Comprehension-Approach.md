---
layout: post
title: "Dialog State Tracking: A Neural Reading Comprehension Approach"
date: 2019-08-06 04:01:42
categories: arXiv_CL
tags: arXiv_CL Attention Ontology Tracking Embedding
author: Shuyang Gao, Abhishek Sethi, Sanchit Aggarwal, Tagyoung Chung, Dilek Hakkani-Tur
mathjax: true
---

* content
{:toc}

##### Abstract
Dialog state tracking is used to estimate the current belief state of a dialog given all the preceding conversation. Machine reading comprehension, on the other hand, focuses on building systems that read passages of text and answer questions that require some understanding of passages. We formulate dialog state tracking as a reading comprehension task to answer the question $what\ is\ the\ state\ of\ the\ current\ dialog?$ after reading conversational context. In contrast to traditional state tracking methods where the dialog state is often predicted as a distribution over a closed set of all the possible slot values within an ontology, our method uses a simple attention-based neural network to point to the slot values within the conversation. Experiments on MultiWOZ-2.0 cross-domain dialog dataset show that our simple system can obtain similar accuracies compared to the previous more complex methods. By exploiting recent advances in contextual word embeddings, adding a model that explicitly tracks whether a slot value should be carried over to the next turn, and combining our method with a traditional joint state tracking method that relies on closed set vocabulary, we can obtain a joint-goal accuracy of $47.33\%$ on the standard test split, exceeding current state-of-the-art by $11.75\%$**.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.01946](https://arxiv.org/abs/1908.01946)

##### PDF
[https://arxiv.org/pdf/1908.01946](https://arxiv.org/pdf/1908.01946)

