---
layout: post
title: "Augmenting a BiLSTM tagger with a Morphological Lexicon and a Lexical Category Identification Step"
date: 2019-07-21 21:27:44
categories: arXiv_CL
tags: arXiv_CL RNN
author: Stein&#xfe;&#xf3;r Steingr&#xed;msson, &#xd6;rvar K&#xe1;rason, Hrafn Loftsson
mathjax: true
---

* content
{:toc}

##### Abstract
Previous work on using BiLSTM models for PoS tagging has primarily focused on small tagsets. We evaluate BiLSTM models for tagging Icelandic, a morphologically rich language, using a relatively large tagset. Our baseline BiLSTM model achieves higher accuracy than any previously published tagger not taking advantage of a morphological lexicon. When we extend the model by incorporating such data, we outperform previous state-of-the-art results by a significant margin. We also report on work in progress that attempts to address the problem of data sparsity inherent in morphologically detailed, fine-grained tagsets. We experiment with training a separate model on only the lexical category and using the coarse-grained output tag as an input for the main model. This method further increases the accuracy and reduces the tagging errors by 21.3% compared to previous state-of-the-art results. Finally, we train and test our tagger on a new gold standard for Icelandic.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09038](http://arxiv.org/abs/1907.09038)

##### PDF
[http://arxiv.org/pdf/1907.09038](http://arxiv.org/pdf/1907.09038)

