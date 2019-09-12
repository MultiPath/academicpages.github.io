---
title: "Incorporating Copying Mechanism in Sequence-to-Sequence Learning"
collection: publications
permalink: /publication/incorporating-copying
excerpt: '**Jiatao Gu**, Zhengdong Lu, Hang Li and Victor O.K. Li'
date: 2016-07-04
venue: 'The 54th Annual Meeting of the Association for Computational Linguistics (ACL)'
---

![png](/images/acl2016.png)<br>
**Abstract** <br>
We address an important problem in sequence-to-sequence (Seq2Seq) learning referred to as copying, in which certain segments in the input sequence are selectively replicated in the output sequence. A similar phenomenon is observable in human language communication. For example, humans tend to repeat entity names or even long phrases in conversation. The challenge with regard to copying in Seq2Seq is that new machinery is needed to decide when to perform the operation. In this paper, we incorporate copying into neural network-based Seq2Seq learning and propose a new model called COPYNET with encoder-decoder structure. COPYNET can nicely integrate the regular way of word generation in the decoder with the new copy- ing mechanism which can choose sub-sequences in the input sequence and put them at proper places in the output sequence. Our empirical study on both synthetic data sets and real world data sets demonstrates the efficacy of COPYNET. For example, COPYNET can outperform regular RNN-based model with remark- able margins on text summarization tasks.

[[paper]](http://aclweb.org/anthology/P/P16/P16-1154.pdf) [code]

Please cite as:
```bibtex
@inproceedings{gu2016incorporating,
  author    = {Jiatao Gu and
               Zhengdong Lu and
               Hang Li and
               Victor O. K. Li},
  title     = {Incorporating Copying Mechanism in Sequence-to-Sequence Learning},
  booktitle = {Proceedings of the 54th Annual Meeting of the Association for Computational
               Linguistics, {ACL} 2016, August 7-12, 2016, Berlin, Germany, Volume
               1: Long Papers},
  year      = {2016}
}
```