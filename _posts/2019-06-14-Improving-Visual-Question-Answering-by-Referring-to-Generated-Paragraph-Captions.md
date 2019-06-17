---
layout: post
title: "Improving Visual Question Answering by Referring to Generated Paragraph Captions"
date: 2019-06-14 14:14:42
categories: arXiv_CL
tags: arXiv_CL Image_Caption QA Attention Caption VQA
author: Hyounghun Kim, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Paragraph-style image captions describe diverse aspects of an image as opposed to the more common single-sentence captions that only provide an abstract description of the image. These paragraph captions can hence contain substantial information of the image for tasks such as visual question answering. Moreover, this textual information is complementary with visual information present in the image because it can discuss both more abstract concepts and more explicit, intermediate symbolic information about objects, events, and scenes that can directly be matched with the textual question and copied into the textual answer (i.e., via easier modality match). Hence, we propose a combined Visual and Textual Question Answering (VTQA) model which takes as input a paragraph caption as well as the corresponding image, and answers the given question based on both inputs. In our model, the inputs are fused to extract related information by cross-attention (early fusion), then fused again in the form of consensus (late fusion), and finally expected answers are given an extra score to enhance the chance of selection (later fusion). Empirical results show that paragraph captions, even when automatically generated (via an RL-based encoder-decoder model), help correctly answer more visual questions. Overall, our joint model, when trained on the Visual Genome dataset, significantly improves the VQA performance over a strong baseline model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06216](https://arxiv.org/abs/1906.06216)

##### PDF
[https://arxiv.org/pdf/1906.06216](https://arxiv.org/pdf/1906.06216)

