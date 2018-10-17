---
layout: post
title: "Optimizing Heuristics for Tableau-based OWL Reasoners"
date: 2018-10-15 19:06:14
categories: arXiv_AI
tags: arXiv_AI Ontology Optimization
author: Razieh Mehri, Volker Haarslev, Hamidreza Chinaei
mathjax: true
---

* content
{:toc}

##### Abstract
Optimization techniques play a significant role in improving description logic reasoners covering the Web Ontology Language (OWL). These techniques are essential to speed up these reasoners. Many of the optimization techniques are based on heuristic choices. Optimal heuristic selection makes these techniques more effective. The FaCT++ OWL reasoner and its Java version JFact implement an optimization technique called ToDo list which is a substitute for a traditional top-down approach in tableau-based reasoners. The ToDo list mechanism allows one to arrange the order of applying different rules by giving each a priority. Compared to a top-down approach, the ToDo list technique has a better control over the application of expansion rules. Learning the proper heuristic order for applying rules in ToDo lis} will have a great impact on reasoning speed. We use a binary SVM technique to build our learning model. The model can help to choose ontology-specific order sets to speed up OWL reasoning. On average, our learning approach tested with 40 selected ontologies achieves a speedup of two orders of magnitude when compared to the worst rule ordering choice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06617](http://arxiv.org/abs/1810.06617)

##### PDF
[http://arxiv.org/pdf/1810.06617](http://arxiv.org/pdf/1810.06617)

