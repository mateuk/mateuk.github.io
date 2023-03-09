---
title: "Samsung R&D Institute Poland submission to WMT20 News Translation Task"
collection: publications
excerpt: ''
venue: 'Fifth Conference on Machine Translation (WMT20 @ EMNLP 2020)'
paperurl: 'https://aclanthology.org/2020.wmt-1.16.pdf'
---

[**[Paper]**](https://aclanthology.org/2020.wmt-1.16.pdf)

This paper describes the submission to the WMT20 shared news translation task by Samsung R&D Institute Poland. We submitted systems for six language directions: English to Czech, Czech to English, English to Polish, Polish to English, English to Inuktitut and Inuktitut to English. For each, we trained a single-direction model. However, directions including English, Polish and Czech were derived from a common multilingual base, which was later fine-tuned on each particular direction. For all the translation directions, we used a similar training regime, with iterative training corpora improvement through back-translation and model ensembling. For the En → Cs direction, we additionally leveraged document-level information by re-ranking the beam output with a separate model.
