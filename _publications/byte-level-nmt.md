---
title: "Neural Machine Translation with Byte-Level Subwords"
collection: publications
permalink: /publication/byte-level-nmt
excerpt: 'Changhan Wang, Kyunghyun Cho and **Jiatao Gu**'
date: 2020-02-07
venue: 'The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI).'
---

![png](/images/byte_example.png)<br>
**Abstract** <br>
Almost all existing machine translation models are built on top of character-based vocabularies: characters, subwords or words.
However, characters (and words) are usually long-tail distributed, especially for noisy
texts or character-rich languages like Japanese
and Chinese, which inflates the vocabulary
with rare symbols. In pursuit of extreme
compactness, byte vocabulary was explored,
but its high computational cost becomes a blocker in practice. In this paper, we investigate byte-level subwords, specifically byte-level BPE (BBPE), which is similarly compact
with character set and generic without out-of-vocabulary tokens, but is more efficient than
pure bytes. And we claim that contextualizing BBPE embeddings is beneficial, which can be
simply implemented by 1-layer convolution or
GRU. Our empirical results show that BBPE
can perform better than char-level BPE with
less than 25% of the volume. In the multilingual setting, BBPE enlarges vocabulary sharing among different languages and achieves better performance in universal many-to-En
models.

[[paper]](https://arxiv.org/pdf/1909.03341.pdf) [code]

Please cite as:
```bibtex
@article{wang2019neural,
  title={Neural Machine Translation with Byte-Level Subwords},
  author={Wang, Changhan and Cho, Kyunghyun and Gu, Jiatao},
  journal={arXiv preprint arXiv:1909.03341},
  year={2019}
}
```