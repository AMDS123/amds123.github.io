---
layout: post
title: "Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications"
date: 2019-05-02 03:30:17
categories: arXiv_CL
tags: arXiv_CL Adversarial Knowledge_Graph Knowledge Embedding Optimization Prediction Relation
author: Pouya Pezeshkpour, Yifan Tian, Sameer Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Representing entities and relations in an embedding space is a well-studied approach for machine learning on relational data. Existing approaches, however, primarily focus on improving accuracy and overlook other aspects such as robustness and interpretability. In this paper, we propose adversarial modifications for link prediction models: identifying the fact to add into or remove from the knowledge graph that changes the prediction for a target fact after the model is retrained. Using these single modifications of the graph, we identify the most influential fact for a predicted link and evaluate the sensitivity of the model to the addition of fake facts. We introduce an efficient approach to estimate the effect of such modifications by approximating the change in the embeddings when the knowledge graph changes. To avoid the combinatorial search over all possible facts, we train a network to decode embeddings to their corresponding graph components, allowing the use of gradient-based optimization to identify the adversarial modification. We use these techniques to evaluate the robustness of link prediction models (by measuring sensitivity to additional facts), study interpretability through the facts most responsible for predictions (by identifying the most influential neighbors), and detect incorrect facts in the knowledge base.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00563](http://arxiv.org/abs/1905.00563)

##### PDF
[http://arxiv.org/pdf/1905.00563](http://arxiv.org/pdf/1905.00563)

