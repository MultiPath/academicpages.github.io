---
title: "Neural Machine Translation with Gumbel-Greedy Decoding"
collection: publications
permalink: /publication/gumbel-greedy-decoding
excerpt: '**Jiatao Gu**, Daniel Jiwoong Im and Victor O.K. Li'
date: 2018-01-20
venue: 'The Thirty-Second AAAI Conference on Artificial Intelligence (AAAI).'
---

![png](/images/gumbel_decoding.png)<br>
**Abstract** <br>
Previous neural machine translation models used some heuristic search algorithms (e.g., beam search) in order to avoid solving the maximum a posteriori problem over translation sentences at test phase. In this paper, we propose the Gumbel-Greedy Decoding which trains a generative network to predict translation under a trained model. We solve such a problem using the Gumbel-Softmax reparameterization, which makes our generative network differentiable and trainable through standard stochastic gradient methods. We empirically demonstrate that our proposed model is effective for generating sequences of discrete words.

[paper] [code]

Please cite as:
```bibtex

```