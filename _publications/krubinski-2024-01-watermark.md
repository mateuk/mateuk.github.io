---
title: "Watermark Text Pattern Spotting in Document Images"
collection: publications
excerpt: ''
authors: "**Mateusz Krubiński**, Stefan Matcovici, Diana Grigore, Daniel Voinea, Alin-Ionut Popa"
venue: 'The 4th Workshop on Scientific Document Understanding (SDU @ AAAI-2024)'
paperurl: 'https://assets.amazon.science/c0/40/c080259e41c7926b8d2554ae085f/watermark-text-pattern-spotting-in-document-images.pdf'
---

[**[Paper]**](https://assets.amazon.science/c0/40/c080259e41c7926b8d2554ae085f/watermark-text-pattern-spotting-in-document-images.pdf)

Watermark text spotting in document images can offer access to an often unexplored source of information, providing crucial evidence about a record’s scope, audience and sometimes even authenticity. Stemming from the problem of text spotting, detecting and understanding watermarks in documents inherits the same hardships - in the wild, writing can come in various fonts, sizes and forms, making generic recognition a very difficult problem. To address the lack of resources in this field and propel further research, we propose a novel benchmark (K-Watermark) containing 65, 447 data samples generated using 𝒲render, a watermark text patterns rendering procedure. A validity study using humans raters yields an authenticity score of 0.51 against pre-generated watermarked documents. To prove the usefulness of the dataset and rendering technique, we developed an end-to-end solution (𝒲extract) for detecting the bounding box instances of watermark text, while predicting the depicted text. To deal with this specific task, we introduce a variance minimization loss and a hierarchical self-attention mechanism. To the best of our knowledge, we are the first to propose an evaluation benchmark and a complete solution for retrieving watermarks from documents surpassing baselines by 5 AP points in detection and 4 points in character accuracy.

