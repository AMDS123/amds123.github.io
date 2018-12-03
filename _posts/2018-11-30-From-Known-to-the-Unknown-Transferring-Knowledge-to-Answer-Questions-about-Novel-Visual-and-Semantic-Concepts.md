---
layout: post
title: "From Known to the Unknown: Transferring Knowledge to Answer Questions about Novel Visual and Semantic Concepts"
date: 2018-11-30 13:00:37
categories: arXiv_CV
tags: arXiv_CV Knowledge QA Attention Embedding Inference VQA
author: Moshiur R Farazi, Salman H Khan, Nick Barnes
mathjax: true
---

* content
{:toc}

##### Abstract
Current Visual Question Answering (VQA) systems can answer intelligent questions about `Known' visual content. However, their performance drops significantly when questions about visually and linguistically `Unknown' concepts are presented during inference (`Open-world' scenario). A practical VQA system should be able to deal with novel concepts in real world settings. To address this problem, we propose an exemplar-based approach that transfers learning (i.e., knowledge) from previously `Known' concepts to answer questions about the `Unknown'. We learn a highly discriminative joint embedding space, where visual and semantic features are fused to give a unified representation. Once novel concepts are presented to the model, it looks for the closest match from an exemplar set in the joint embedding space. This auxiliary information is used alongside the given Image-Question pair to refine visual attention in a hierarchical fashion. Since handling the high dimensional exemplars on large datasets can be a significant challenge, we introduce an efficient matching scheme that uses a compact feature description for search and retrieval. To evaluate our model, we propose a new split for VQA, separating Unknown visual and semantic concepts from the training set. Our approach shows significant improvements over state-of-the-art VQA models on the proposed Open-World VQA dataset and standard VQA datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12772](http://arxiv.org/abs/1811.12772)

##### PDF
[http://arxiv.org/pdf/1811.12772](http://arxiv.org/pdf/1811.12772)

