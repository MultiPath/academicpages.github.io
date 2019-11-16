---
title: "Universal Neural Machine Translation for Extremely Low Resource Languages"
collection: publications
permalink: /publication/universal-nmt
excerpt: '**Jiatao Gu**, Hany Hassan, Jacob Devlin and Victor O.K. Li'
date: 2018-06-01
venue: 'Conference of the North American Chapter
        of the Association for Computational Linguistics: Human Language Technologie (NAACL-HLT).'
---

![png](/images/universal_nmt.png)<br>
**Abstract** <br>
In this paper, we propose a new universal machine translation approach focusing on languages with a limited amount of parallel data. Our proposed approach utilizes a transfer-learning approach to share lexical and sentence level representations across multiple source languages into one target language. The lexical part is shared through a Universal Lexical Representation to support multi-lingual word-level sharing. The sentence-level sharing is represented by a model of experts from all source languages that share the source encoders with all other languages. This enables the low-resource language to utilize the lexical and sentence representations of the higher resource languages. Our approach is able to achieve 23 BLEU on Romanian-English WMT2016 using a tiny parallel corpus of 6k sentences, compared to the 18 BLEU of strong baseline system which uses multi-lingual training and back-translation. Furthermore, we show that the proposed approach can achieve almost 20 BLEU on the same dataset through fine-tuning a pre-trained multi-lingual system in a zero-shot setting.

[[paper]](https://arxiv.org/pdf/1802.05368.pdf) [code]

Please cite as:
```bibtex
@article{gu2018universal,
  title={Universal neural machine translation for extremely low resource languages},
  author={Gu, Jiatao and Hassan, Hany and Devlin, Jacob and Li, Victor OK},
  journal={arXiv preprint arXiv:1802.05368},
  year={2018}
}
```