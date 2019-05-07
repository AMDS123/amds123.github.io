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


##### URL
[https://arxiv.org/abs/1503.08895](https://arxiv.org/abs/1503.08895)

##### PDF
[https://arxiv.org/pdf/1503.08895](https://arxiv.org/pdf/1503.08895)

