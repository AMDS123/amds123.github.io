---
layout: post
title: "Building a Neural Semantic Parser from a Domain Ontology"
date: 2018-12-25 05:30:18
categories: arXiv_CL
tags: arXiv_CL Face Ontology
author: Jianpeng Cheng, Siva Reddy, Mirella Lapata
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic parsing is the task of converting natural language utterances into machine interpretable meaning representations which can be executed against a real-world environment such as a database. Scaling semantic parsing to arbitrary domains faces two interrelated challenges: obtaining broad coverage training data effectively and cheaply; and developing a model that generalizes to compositional utterances and complex intentions. We address these challenges with a framework which allows to elicit training data from a domain ontology and bootstrap a neural parser which recursively builds derivations of logical forms. In our framework meaning representations are described by sequences of natural language templates, where each template corresponds to a decomposed fragment of the underlying meaning representation. Although artificial, templates can be understood and paraphrased by humans to create natural utterances, resulting in parallel triples of utterances, meaning representations, and their decompositions. These allow us to train a neural semantic parser which learns to compose rules in deriving meaning representations. We crowdsource training data on six domains, covering both single-turn utterances which exhibit rich compositionality, and sequential utterances where a complex task is procedurally performed in steps. We then develop neural semantic parsers which perform such compositional tasks. In general, our approach allows to deploy neural semantic parsers quickly and cheaply from a given domain ontology.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10037](http://arxiv.org/abs/1812.10037)

##### PDF
[http://arxiv.org/pdf/1812.10037](http://arxiv.org/pdf/1812.10037)

