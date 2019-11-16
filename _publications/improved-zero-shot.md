---
title: "Improved Zero-shot Neural Machine Translation via Ignoring Spurious Correlations"
collection: publications
permalink: /publication/improved-zero-shot
excerpt: '**Jiatao Gu**^, Yong Wang^, Kyunghyun Cho, Victor O.K. Li'
date: 2019-07-28
venue: 'The 57th Annual Meeting of the Association for Computational Linguistics (ACL)'
---

![png](/images/zero-shot.png)
**Abstract** <br>
Zero-shot translation, translating between language pairs on which a Neural Machine Translation (NMT) system has never been trained, is
an emergent property when training the system
in multilingual settings. However, na¨ıve training for zero-shot NMT easily fails, and is sensitive to hyper-parameter setting. The performance typically lags far behind the more conventional pivot-based approach which translates twice using a third language as a pivot.
In this work, we address the degeneracy problem due to capturing spurious correlations by
quantitatively analyzing the mutual information between language IDs of the source and
decoded sentences. Inspired by this analysis,
we propose to use two simple but effective approaches: (1) decoder pre-training; (2) backtranslation. These methods show significant
improvement (4 ∼ 22 BLEU points) over the
vanilla zero-shot translation on three challenging multilingual datasets, and achieve similar or better results than the pivot-based approach.

[[arxiv]](https://arxiv.org/pdf/1906.01181.pdf) [code]

Please cite as:
```bibtex
@inproceedings{gu-etal-2019-improved,
    title = "Improved Zero-shot Neural Machine Translation via Ignoring Spurious Correlations",
    author = "Gu, Jiatao  and Wang, Yong  and Cho, Kyunghyun  and Li, Victor O.K.",
    booktitle = "Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics",
    month = jul,
    year = "2019",
    address = "Florence, Italy",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P19-1121",
    pages = "1258--1268"
}
```