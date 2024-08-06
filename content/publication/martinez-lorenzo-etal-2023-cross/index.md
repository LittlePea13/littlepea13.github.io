---
title: 'Cross-lingual AMR Aligner: Paying Attention to Cross-Attention'
authors:
- Abelardo Carlos Martı́nez Lorenzo
- Pere Llu\ś Huguet Cabot
- Roberto Navigli
date: '2023-07-01'
publishDate: '2024-08-06T11:26:57.524736Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2023*'
doi: 10.18653/v1/2023.findings-acl.109
abstract: This paper introduces a novel aligner for Abstract Meaning Representation
  (AMR) graphs that can scale cross-lingually, and is thus capable of aligning units
  and spans in sentences of different languages. Our approach leverages modern Transformer-based
  parsers, which inherently encode alignment information in their cross-attention
  weights, allowing us to extract this information during parsing. This eliminates
  the need for English-specific rules or the Expectation Maximization (EM) algorithm
  that have been used in previous approaches. In addition, we propose a guided supervised
  method using alignment to further enhance the performance of our aligner. We achieve
  state-of-the-art results in the benchmarks for AMR alignment and demonstrate our
  aligner′s ability to obtain them across multiple languages. Our code will be available
  at 
  [r̆lhttps://www.github.com/babelscape/AMR-alignment](l̆https://www.github.com/babelscape/AMR-alignment).
links:
- name: URL
  url: https://aclanthology.org/2023.findings-acl.109
---
