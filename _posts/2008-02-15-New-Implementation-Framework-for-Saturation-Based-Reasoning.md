---
layout: post
title: "New Implementation Framework for Saturation-Based Reasoning"
date: 2008-02-15 01:51:29
categories: arXiv_CV
tags: arXiv_CV Inference
author: Alexandre Riazanov
mathjax: true
---

* content
{:toc}

##### Abstract
The saturation-based reasoning methods are among the most theoretically developed ones and are used by most of the state-of-the-art first-order logic reasoners. In the last decade there was a sharp increase in performance of such systems, which I attribute to the use of advanced calculi and the intensified research in implementation techniques. However, nowadays we are witnessing a slowdown in performance progress, which may be considered as a sign that the saturation-based technology is reaching its inherent limits. The position I am trying to put forward in this paper is that such scepticism is premature and a sharp improvement in performance may potentially be reached by adopting new architectural principles for saturation. The top-level algorithms and corresponding designs used in the state-of-the-art saturation-based theorem provers have (at least) two inherent drawbacks: the insufficient flexibility of the used inference selection mechanisms and the lack of means for intelligent prioritising of search directions. In this position paper I analyse these drawbacks and present two ideas on how they could be overcome. In particular, I propose a flexible low-cost high-precision mechanism for inference selection, intended to overcome problems associated with the currently used instances of clause selection-based procedures. I also outline a method for intelligent prioritising of search directions, based on probing the search space by exploring generalised search directions. I discuss some technical issues related to implementation of the proposed architectural principles and outline possible solutions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/0802.2127](https://arxiv.org/abs/0802.2127)

##### PDF
[https://arxiv.org/pdf/0802.2127](https://arxiv.org/pdf/0802.2127)

