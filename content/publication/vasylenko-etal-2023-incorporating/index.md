---
title: Incorporating Graph Information in Transformer-based AMR Parsing
authors:
- Pavlo Vasylenko
- Pere Lluı́s Huguet Cabot
- Abelardo Carlos Mart\ńez Lorenzo
- Roberto Navigli
date: '2023-07-01'
publishDate: '2024-08-06T11:26:57.531827Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2023*'
doi: 10.18653/v1/2023.findings-acl.125
abstract: Abstract Meaning Representation (AMR) is a Semantic Parsing formalism that
  aims at providing a semantic graph abstraction representing a given text. Current
  approaches are based on autoregressive language models such as BART or T5, fine-tuned
  through Teacher Forcing to obtain a linearized version of the AMR graph from a sentence.
  In this paper, we present LeakDistill, a model and method that explores a modification
  to the Transformer architecture, using structural adapters to explicitly incorporate
  graph information into the learned representations and improve AMR parsing performance.
  Our experiments show how, by employing word-to-node alignment to embed graph structural
  information into the encoder at training time, we can obtain state-of-the-art AMR
  parsing through self-knowledge distillation, even without the use of additional
  data. We release the code at 
  [r̆lhttp://www.github.com/sapienzanlp/LeakDistill](l̆http://www.github.com/sapienzanlp/LeakDistill).
links:
- name: URL
  url: https://aclanthology.org/2023.findings-acl.125
---
