---
layout: post
title: "Memory-Augmented Neural Networks for Knowledge Tracing from the Perspective of Learning and Forgetting"
date: 2018-10-01 02:56:16
categories: arXiv_CV
tags: arXiv_CV Knowledge Deep_Learning
author: Heonseok Ha, Uiwon Hwang, Yongjun Hong, Sungroh Yoon
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge tracing (KT) refers to a machine learning technique to assess a student's level of understanding (or knowledge state) based on the student's past performance in exercise-solving. KT accepts a series of question-answer pairs as an input and iteratively updates the knowledge state of the student, eventually returning the probability of the student solving a given question. To estimate the accurate knowledge state, a KT model should imitate the learning and forgetting mechanisms of the student. Deep learning-based KT models, proposed recently, show a higher predictive performance than traditional machine learning-based KT models due to the representative power of neural networks. The dynamic key value memory network (DKVMN), a kind of memory augmented neural network (MANN), is a state-of-the-art KT model, but it has some limitations. DKVMN does not utilize information from a current knowledge state and overestimates the amount of forgetting when updating the knowledge state. To improve the learning and forgetting mechanism of the DKVMN, we propose a knowledge tracing model that incorporates: (1) an adaptive knowledge growth depending on the current knowledge state, and (2) an additional loss term that can regularize the degree of forgetting. To measure the degree of forgetting of the KT model, we define a positive update ratio (PUR) that can complement the predictive performance metric (AUC). According to our experiments using four public benchmarks, the proposed approaches outperform the original DKVMN in terms of both AUC (predictive performance) and PUR (degree of forgetting).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.10768](https://arxiv.org/abs/1805.10768)

##### PDF
[https://arxiv.org/pdf/1805.10768](https://arxiv.org/pdf/1805.10768)

