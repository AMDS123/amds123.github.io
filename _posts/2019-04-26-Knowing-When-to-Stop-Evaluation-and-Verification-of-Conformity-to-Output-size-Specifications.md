---
layout: post
title: "Knowing When to Stop: Evaluation and Verification of Conformity to Output-size Specifications"
date: 2019-04-26 18:12:56
categories: arXiv_AI
tags: arXiv_AI Image_Caption Caption
author: Chenglong Wang, Rudy Bunel, Krishnamurthy Dvijotham, Po-Sen Huang, Edward Grefenstette, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
Models such as Sequence-to-Sequence and Image-to-Sequence are widely used in real world applications. While the ability of these neural architectures to produce variable-length outputs makes them extremely effective for problems like Machine Translation and Image Captioning, it also leaves them vulnerable to failures of the form where the model produces outputs of undesirable length. This behavior can have severe consequences such as usage of increased computation and induce faults in downstream modules that expect outputs of a certain length. Motivated by the need to have a better understanding of the failures of these models, this paper proposes and studies the novel output-size modulation problem and makes two key technical contributions. First, to evaluate model robustness, we develop an easy-to-compute differentiable proxy objective that can be used with gradient-based algorithms to find output-lengthening inputs. Second and more importantly, we develop a verification approach that can formally verify whether a network always produces outputs within a certain length. Experimental results on Machine Translation and Image Captioning show that our output-lengthening approach can produce outputs that are 50 times longer than the input, while our verification approach can, given a model and input domain, prove that the output length is below a certain size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12004](http://arxiv.org/abs/1904.12004)

##### PDF
[http://arxiv.org/pdf/1904.12004](http://arxiv.org/pdf/1904.12004)

