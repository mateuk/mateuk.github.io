---
title: "Towards Unified Uni- and Multi-modal News Headline Generation"
collection: publications
excerpt: ''
authors: "**Mateusz Krubiński**, Pavel Pecina"
venue: 'Findings of the Association for Computational Linguistics: EACL 2024 (EACL 2024)'
paperurl: 'https://aclanthology.org/2024.findings-eacl.30.pdf'
---

[**[Paper]**](https://aclanthology.org/2024.findings-eacl.30.pdf) [**[Code]**](https://github.com/ufal/UNMHG)

Thanks to the recent progress in vision-language modeling and the evolving nature of news consumption, the tasks of automatic summarization and headline generation based on multimodal news articles have been gaining popularity. One of the limitations of the current approaches is caused by the commonly used sophisticated modular architectures built upon hierarchical cross-modal encoders and modality-specific decoders, which restrict the model’s applicability to specific data modalities – once trained on, e.g., text+video pairs there is no straightforward way to apply the model to text+image or text-only data. In this work, we propose a unified task formulation that utilizes a simple encoder-decoder model to generate headlines from uni- and multi-modal news articles. This model is trained jointly on data of several modalities and extends the textual decoder to handle the multimodal output.

