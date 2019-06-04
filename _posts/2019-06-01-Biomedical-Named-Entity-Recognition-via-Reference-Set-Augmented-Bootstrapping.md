---
layout: post
title: "Biomedical Named Entity Recognition via Reference-Set Augmented Bootstrapping"
date: 2019-06-01 20:07:11
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Joel Mathew, Shobeir Fakhraei, Jos&#xe9; Luis Ambite
mathjax: true
---

* content
{:toc}

##### Abstract
We present a weakly-supervised data augmentation approach to improve Named Entity Recognition (NER) in a challenging domain: extracting biomedical entities (e.g., proteins) from the scientific literature. First, we train a neural NER (NNER) model over a small seed of fully-labeled examples. Second, we use a reference set of entity names (e.g., proteins in UniProt) to identify entity mentions with high precision, but low recall, on an unlabeled corpus. Third, we use the NNER model to assign weak labels to the corpus. Finally, we retrain our NNER model iteratively over the augmented training set, including the seed, the reference-set examples, and the weakly-labeled examples, which improves model performance. We show empirically that this augmented bootstrapping process significantly improves NER performance, and discuss the factors impacting the efficacy of the approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00282](http://arxiv.org/abs/1906.00282)

##### PDF
[http://arxiv.org/pdf/1906.00282](http://arxiv.org/pdf/1906.00282)

