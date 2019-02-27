---
layout: post
title: "Design of intentional backdoors in sequential models"
date: 2019-02-26 14:43:14
categories: arXiv_AI
tags: arXiv_AI Adversarial Reinforcement_Learning RNN Classification Detection
author: Zhaoyuan Yang, Naresh Iyer, Johan Reimann, Nurali Virani
mathjax: true
---

* content
{:toc}

##### Abstract
Recent work has demonstrated robust mechanisms by which attacks can be orchestrated on machine learning models. In contrast to adversarial examples, backdoor or trojan attacks embed surgically modified samples with targeted labels in the model training process to cause the targeted model to learn to misclassify chosen samples in the presence of specific triggers, while keeping the model performance stable across other nominal samples. However, current published research on trojan attacks mainly focuses on classification problems, which ignores sequential dependency between inputs. In this paper, we propose methods to discreetly introduce and exploit novel backdoor attacks within a sequential decision-making agent, such as a reinforcement learning agent, by training multiple benign and malicious policies within a single long short-term memory (LSTM) network. We demonstrate the effectiveness as well as the damaging impact of such attacks through initial outcomes generated from our approach, employed on grid-world environments. We also provide evidence as well as intuition on how the trojan trigger and malicious policy is activated. Challenges with network size and unintentional triggers are identified and analogies with adversarial examples are also discussed. In the end, we propose potential approaches to defend against or serve as early detection for such attacks. Results of our work can also be extended to many applications of LSTM and recurrent networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.09972](http://arxiv.org/abs/1902.09972)

##### PDF
[http://arxiv.org/pdf/1902.09972](http://arxiv.org/pdf/1902.09972)

