---
layout: post
title: "Learning to Communicate Implicitly By Actions"
date: 2019-02-17 14:05:21
categories: arXiv_AI
tags: arXiv_AI
author: Zheng Tian, Shihao Zou, Tim Warr, Lisheng Wu, Jun Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In situations where explicit communication is limited, a human collaborator is typically able to learn to: (i) infer the meaning behind their partner's actions and (ii) balance between taking actions that are exploitative given their current understanding of the state vs. those that can convey private information about the state to their partner. The first component of this learning process has been well-studied in multi-agent systems, whereas the second --- which is equally crucial for a successful collaboration --- has not. In this work, we complete the learning process and introduce our novel algorithm, Policy Belief Learning ("PBL"), which mimics both components mentioned above. A belief module models the other agent's private information by observing their actions, whilst a policy module makes use of the inferred private information to return a distribution over actions. They are mutually reinforced with each other and iteratively learned. We use a novel auxiliary reward to encourage information exchange by actions. We evaluate our approach on the non-competitive bidding problem from contract bridge and show that by self-play agents are able to effectively collaborate with implicit communication, and PBL outperforms several meaningful baselines that have been considered.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.04444](http://arxiv.org/abs/1810.04444)

##### PDF
[http://arxiv.org/pdf/1810.04444](http://arxiv.org/pdf/1810.04444)

