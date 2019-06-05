---
layout: post
title: "Boosting Entity Linking Performance by Leveraging Unlabeled Documents"
date: 2019-06-04 07:49:46
categories: arXiv_AI
tags: arXiv_AI
author: Phong Le, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Modern entity linking systems rely on large collections of documents specifically annotated for the task (e.g., AIDA CoNLL). In contrast, we propose an approach which exploits only naturally occurring information: unlabeled documents and Wikipedia. Our approach consists of two stages. First, we construct a high recall list of candidate entities for each mention in an unlabeled document. Second, we use the candidate lists as weak supervision to constrain our document-level entity linking model. The model treats entities as latent variables and, when estimated on a collection of unlabelled texts, learns to choose entities relying both on local context of each mention and on coherence with other entities in the document. The resulting approach rivals fully-supervised state-of-the-art systems on standard test sets. It also approaches their performance in the very challenging setting: when tested on a test set sampled from the data used to estimate the supervised systems. By comparing to Wikipedia-only training of our model, we demonstrate that modeling unlabeled documents is beneficial.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01250](http://arxiv.org/abs/1906.01250)

##### PDF
[http://arxiv.org/pdf/1906.01250](http://arxiv.org/pdf/1906.01250)

