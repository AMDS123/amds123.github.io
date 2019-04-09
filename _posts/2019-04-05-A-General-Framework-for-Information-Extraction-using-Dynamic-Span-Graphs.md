---
layout: post
title: "A General Framework for Information Extraction using Dynamic Span Graphs"
date: 2019-04-05 21:52:18
categories: arXiv_CL
tags: arXiv_CL RNN Relation
author: Yi Luan, Dave Wadden, Luheng He, Amy Shah, Mari Ostendorf, Hannaneh Hajishirzi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a general framework for several information extraction tasks that share span representations using dynamically constructed span graphs. The graphs are constructed by selecting the most confident entity spans and linking these nodes with confidence-weighted relation types and coreferences. The dynamic span graph allows coreference and relation type confidences to propagate through the graph to iteratively refine the span representations. This is unlike previous multi-task frameworks for information extraction in which the only interaction between tasks is in the shared first-layer LSTM. Our framework significantly outperforms the state-of-the-art on multiple information extraction tasks across multiple datasets reflecting different domains. We further observe that the span enumeration approach is good at detecting nested span entities, with significant F1 score improvement on the ACE dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03296](http://arxiv.org/abs/1904.03296)

##### PDF
[http://arxiv.org/pdf/1904.03296](http://arxiv.org/pdf/1904.03296)

