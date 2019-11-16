---
title: "Insertion-based Decoding with automatically Inferred Generation Order"
collection: journals
permalink: /publication/insertion-based-decoding
excerpt: '**Jiatao Gu**, Qi Liu and Kyunghyun Cho'
date: 2019-11-04
venue: 'Transactions of the Association for Computational Linguistics (TACL)'
---

![png](/images/InDIGO.png)
**Abstract** <br>
Conventional neural autoregressive decoding commonly assumes a fixed left-to-right
generation order, which may be sub-optimal.
In this work, we propose a novel decoding algorithm – InDIGO – which supports
flexible sequence generation in arbitrary orders through insertion operations. We extend
Transformer, a state-of-the-art sequence generation model, to efficiently implement the
proposed approach, enabling it to be trained
with either a pre-defined generation order or
adaptive orders obtained from beam-search.
Experiments on four real-world tasks, including word order recovery, machine translation, image caption and code generation,
demonstrate that our algorithm can generate
sequences following arbitrary orders, while
achieving competitive or even better performance compared to the conventional left-toright generation. The generated sequences
show that InDIGO adopts adaptive generation orders based on input information.

[[arxiv]](https://arxiv.org/pdf/1902.01370.pdf) [code]


Please cite as:
```bibtex
@article{gu2019insertion,
  title={Insertion-based decoding with automatically inferred generation order},
  author={Gu, Jiatao and Liu, Qi and Cho, Kyunghyun},
  journal={arXiv preprint arXiv:1902.01370},
  year={2019}
}
```