---
layout: post
title: "An Incremental Turn-Taking Model For Task-Oriented Dialog Systems"
date: 2019-05-28 13:38:29
categories: arXiv_CL
tags: arXiv_CL Tracking Prediction
author: Andrei C. Coman, Koichiro Yoshino, Yukitoshi Murase, Satoshi Nakamura, Giuseppe Riccardi
mathjax: true
---

* content
{:toc}

##### Abstract
In a human-machine dialog scenario, deciding the appropriate time for the machine to take the turn is an open research problem. In contrast, humans engaged in conversations are able to timely decide when to interrupt the speaker for competitive or non-competitive reasons. In state-of-the-art turn-by-turn dialog systems the decision on the next dialog action is taken at the end of the utterance. In this paper, we propose a token-by-token prediction of the dialog state from incremental transcriptions of the user utterance. To identify the point of maximal understanding in an ongoing utterance, we a) implement an incremental Dialog State Tracker which is updated on a token basis (iDST) b) re-label the Dialog State Tracking Challenge 2 (DSTC2) dataset and c) adapt it to the incremental turn-taking experimental scenario. The re-labeling consists of assigning a binary value to each token in the user utterance that allows to identify the appropriate point for taking the turn. Finally, we implement an incremental Turn Taking Decider (iTTD) that is trained on these new labels for the turn-taking decision. We show that the proposed model can achieve a better performance compared to a deterministic handcrafted turn-taking algorithm.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11806](https://arxiv.org/abs/1905.11806)

##### PDF
[https://arxiv.org/pdf/1905.11806](https://arxiv.org/pdf/1905.11806)

