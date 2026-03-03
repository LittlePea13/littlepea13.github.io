---
title: 'Optimizing LLMs for Italian: Reducing Token Fertility and Enhancing Efficiency
  Through Vocabulary Adaptation'
authors:
- Luca Moroni
- Giovanni Puccetti
- Pere-Lluís Huguet Cabot
- Andrei Stefan Bejgu
- Alessio Miaschi
- Edoardo Barba
- Felice Dell′Orletta
- Andrea Esuli
- Roberto Navigli
date: '2025-04-01'
publishDate: '2026-03-03T11:37:48.005778Z'
publication_types:
- article-journal
publication: '*Findings of the Association for Computational Linguistics: NAACL 2025*'
doi: 10.18653/v1/2025.findings-naacl.371
abstract: "The number of pretrained Large Language Models (LLMs) is increasing steadily,
  though the majority are designed predominantly for the English language. While state-of-the-art
  LLMs can handle other languages, due to language contamination or some degree of
  multilingual pretraining data, they are not optimized for non-English languages,
  leading to inefficient encoding (high token ``fertility'') and slower inference
  speed.In this work, we thoroughly compare a variety of vocabulary adaptation techniques
  for optimizing English LLMs for the Italian language, and put forward Semantic Alignment
  Vocabulary Adaptation (SAVA), a novel method that leverages neural mapping for vocabulary
  substitution. SAVA achieves competitive performance across multiple downstream tasks,
  enhancing grounded alignment strategies. We adapt two LLMs: Mistral-7B-v0.1, reducing
  token fertility by 25%, and Llama-3.1-8B, optimizing the vocabulary and reducing
  the number of parameters by 1 billion. We show that, following the adaptation of
  the vocabulary, these models can recover their performance with a relatively limited
  stage of continual training on the target language. Finally, we test the capabilities
  of the adapted models on various multi-choice and generative tasks."
links:
- name: URL
  url: https://aclanthology.org/2025.findings-naacl.371/
---
