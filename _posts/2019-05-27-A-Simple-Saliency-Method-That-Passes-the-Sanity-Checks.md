---
layout: post
title: "A Simple Saliency Method That Passes the Sanity Checks"
date: 2019-05-27 23:15:11
categories: arXiv_AI
tags: arXiv_AI Salient Classification
author: Arushi Gupta, Sanjeev Arora
mathjax: true
---

* content
{:toc}

##### Abstract
There is great interest in *saliency methods* (also called *attribution methods*), which give "explanations" for a deep net's decision, by assigning a *score* to each feature/pixel in the input. Their design usually involves credit-assignment via the gradient of the output with respect to input. Recently Adebayo et al. [<a href="https://export.arxiv.org/abs/1810.03292">arXiv:1810.03292</a>] questioned the validity of many of these methods since they do not pass simple *sanity checks* which test whether the scores shift/vanish when layers of the trained net are randomized, or when the net is retrained using random labels for inputs. 
 We propose a simple fix to existing saliency methods that helps them pass sanity checks, which we call *competition for pixels*. This involves computing saliency maps for all possible labels in the classification task, and using a simple competition among them to identify and remove less relevant pixels from the map. The simplest variant of this is *Competitive Gradient $\odot$ Input (CGI)*: it is efficient, requires no additional training, and uses only the input and gradient. Some theoretical justification is provided for it (especially for ReLU networks) and its performance is empirically demonstrated.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.12152](http://arxiv.org/abs/1905.12152)

##### PDF
[http://arxiv.org/pdf/1905.12152](http://arxiv.org/pdf/1905.12152)

