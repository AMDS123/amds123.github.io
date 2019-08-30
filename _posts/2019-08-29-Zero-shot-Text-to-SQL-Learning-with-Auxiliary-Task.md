---
layout: post
title: "Zero-shot Text-to-SQL Learning with Auxiliary Task"
date: 2019-08-29 05:01:39
categories: arXiv_AI
tags: arXiv_AI Regularization Attention
author: Shuaichen Chang, Pengfei Liu, Yun Tang, Jing Huang, Xiaodong He, Bowen Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen great success in the use of neural seq2seq models on the text-to-SQL task. However, little work has paid attention to how these models generalize to realistic unseen data, which naturally raises a question: does this impressive performance signify a perfect generalization model, or are there still some limitations? 
 In this paper, we first diagnose the bottleneck of text-to-SQL task by providing a new testbed, in which we observe that existing models present poor generalization ability on rarely-seen data. The above analysis encourages us to design a simple but effective auxiliary task, which serves as a supportive model as well as a regularization term to the generation task to increase the models generalization. Experimentally, We evaluate our models on a large text-to-SQL dataset WikiSQL. Compared to a strong baseline coarse-to-fine model, our models improve over the baseline by more than 3% absolute in accuracy on the whole dataset. More interestingly, on a zero-shot subset test of WikiSQL, our models achieve 5% absolute accuracy gain over the baseline, clearly demonstrating its superior generalizability.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11052](http://arxiv.org/abs/1908.11052)

##### PDF
[http://arxiv.org/pdf/1908.11052](http://arxiv.org/pdf/1908.11052)

