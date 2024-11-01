---
title: "Masked and Permuted Implicit Context Learning for Scene Text Recognition"
collection: publications
permalink: /publication/2023-08-15-masked-and-permuted-implicit-context-learning-for-scene-text-recognition
excerpt: 'Scene Text Recognition (STR) grapples with the complexities introduced by variations in text styles, shapes, and back-
grounds. Though the integration of linguistic information enhances the performance of STR models, existing methods
base on either permuted language modeling (PLM) or masked language modeling (MLM). Each, however, has its pitfalls:
PLM’s autoregressive decoding lacks foresight into subsequent characters, while MLM, although providing a compre-
hensive view of the text, sometimes overlooks inter-character dependencies. Addressing these challenges, we propose a
masked and permuted implicit context learning network for STR, which unifies PLM and MLM within a single decoding
architecture, inheriting the advantages of both approaches. We utilize the training procedure of PLM, and to integrate
MLM, we incorporate word length information into the decoding process and replace the undetermined characters with
mask tokens. Besides, perturbation training is employed to train a more robust model against potential length prediction errors. Our empirical evaluations demonstrate the per-
formance of our model. It not only achieves superior performance on the common benchmarks, but also achieves a
substantial improvement of 9.1% on the more challenging Union14M-Benchmark.'
date: 2023-08-15
venue: 'Under Review'
paperurl: ''
---
Scene Text Recognition (STR) grapples with the complexities introduced by variations in text styles, shapes, and back-
grounds. Though the integration of linguistic information enhances the performance of STR models, existing methods
base on either permuted language modeling (PLM) or masked language modeling (MLM). Each, however, has its pitfalls:
PLM’s autoregressive decoding lacks foresight into subsequent characters, while MLM, although providing a compre-
hensive view of the text, sometimes overlooks inter-character dependencies. Addressing these challenges, we propose a
masked and permuted implicit context learning network for STR, which unifies PLM and MLM within a single decoding
architecture, inheriting the advantages of both approaches. We utilize the training procedure of PLM, and to integrate
MLM, we incorporate word length information into the decoding process and replace the undetermined characters with
mask tokens. Besides, perturbation training is employed to train a more robust model against potential length prediction errors. Our empirical evaluations demonstrate the per-
formance of our model. It not only achieves superior performance on the common benchmarks, but also achieves a
substantial improvement of 9.1% on the more challenging Union14M-Benchmark.
