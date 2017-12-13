---
layout: post
title: "End-To-End Memory Networks"
date: 2015-11-24 19:41:57
categories: arXiv_CV
tags: arXiv_CV Attention RNN Language_Model Memory_Networks
author: Sainbayar Sukhbaatar, Arthur Szlam, Jason Weston, Rob Fergus
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a neural network with a recurrent attention model over a possibly large external memory. The architecture is a form of Memory Network (Weston et al., 2015) but unlike the model in that work, it is trained end-to-end, and hence requires significantly less supervision during training, making it more generally applicable in realistic settings. It can also be seen as an extension of RNNsearch to the case where multiple computational steps (hops) are performed per output symbol. The flexibility of the model allows us to apply it to tasks as diverse as (synthetic) question answering and to language modeling. For the former our approach is competitive with Memory Networks, but with less supervision. For the latter, on the Penn TreeBank and Text8 datasets our approach demonstrates comparable performance to RNNs and LSTMs. In both cases we show that the key concept of multiple computational hops yields improved results.

##### Abstract (translated by Google)
我们在可能较大的外部存储器上引入一个带有反复注意模型的神经网络。该架构是记忆网络的一种形式（Weston et al。，2015），但与该工作中的模型不同，它是端到端的训练，因此在训练期间需要显着减少监督，使其更符合实际情况。它也可以看作是对每个输出符号执行多个计算步骤（跳数）的情况下RNNsearch的扩展。模型的灵活性使我们能够将其应用于（综合）问题回答和语言建模等多种任务。对于前者，我们的方法与记忆网络相比具有竞争力，但是监督较少。对于后者，在Penn TreeBank和Text8数据集上，我们的方法表现出与RNN和LSTM相当的性能。在这两种情况下，我们都表明多个计算跳数的关键概念会产生更好的结果。

##### URL
[https://arxiv.org/abs/1503.08895](https://arxiv.org/abs/1503.08895)

##### PDF
[https://arxiv.org/pdf/1503.08895](https://arxiv.org/pdf/1503.08895)

