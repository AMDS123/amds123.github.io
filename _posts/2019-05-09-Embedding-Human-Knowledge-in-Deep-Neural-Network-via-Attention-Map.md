---
layout: post
title: "Embedding Human Knowledge in Deep Neural Network via Attention Map"
date: 2019-05-09 11:32:44
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention Embedding Inference Classification Deep_Learning Recognition
author: Masahiro Mitsuhara, Hiroshi Fukui, Yusuke Sakashita, Takanori Ogata, Tsubasa Hirakawa, Takayoshi Yamashita, Hironobu Fujiyoshi
mathjax: true
---

* content
{:toc}

##### Abstract
Human-in-the-loop (HITL), which introduces human knowledge to machine learning, has been used in fine-grained recognition to estimate categories from the difference of local features. The conventional HITL approach has been successfully applied in non-deep machine learning, but it is difficult to use it with deep learning due to the enormous number of model parameters. To tackle this problem, in this paper, we propose using the Attention Branch Network (ABN) which is a visual explanation model. ABN applies an attention map for visual explanation to an attention mechanism. First, we manually modify the attention map obtained from ABN on the basis of human knowledge. Then, we use the modified attention map to an attention mechanism that enables ABN to adjust the recognition score. Second, for applying HITL to deep learning, we propose a fine-tuning approach that uses the modified attention map. Our fine-tuning updates the attention and perception branches of the ABN by using the training loss calculated from the attention map output from the ABN along with the modified attention map. This fine-tuning enables the ABN to output an attention map corresponding to human knowledge. Additionally, we use the updated attention map with its embedded human knowledge as an attention mechanism and inference at the perception branch, which improves the performance of ABN. Experimental results with the ImageNet dataset, CUB-200-2010 dataset, and IDRiD demonstrate that our approach clarifies the attention map in terms of visual explanation and improves the classification performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03540](http://arxiv.org/abs/1905.03540)

##### PDF
[http://arxiv.org/pdf/1905.03540](http://arxiv.org/pdf/1905.03540)

