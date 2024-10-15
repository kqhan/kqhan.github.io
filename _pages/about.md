---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a first-year Ph.D. student at UCLA advised by Prof. Yizhou Sun.

I received my CS bachelor degree at Zhejiang University, advised by Prof. Yang Yang at AINet Lab. Fortunately, I also receive guidance from Prof. Carl Yang at Emory Graph Mining Lab.

I am excited to discuss and collaborate with individuals from diverse backgrounds. Please feel free to email me at: kqhan@cs.ucla.edu 

Recent Research
======

LLM reasoning
=======
The goal is to improve the reasoning ability of LLMs in multiple domains. 
Reasoning is the key foundation for ensuring the efficacy and reliability of language models.
While Large Language Models (LLMs) have demonstrated remarkable proficiency in certain reasoning tasks.
LLMs often experience hallucinations and unreliable reasoning, especially when they lack external knowledge.
I am working on evaluating and improving LLM reasoning by tackling challenges in robustness, structure, and efficiency.

To evaluate the robustness reasoning ability of LLMs, we propose the Concept-Reversed Winograd Schema Challenge Dataset (CR-WSC). 
In addition to avoiding simple semantic associations of words, it is  an adversarial dataset tailored specifically for LLMs, which is \textit{non-LLM-proof}: challenging to solve with LLMs. 
In CR-WSC, I expose vulnerabilities in LLMs' reasoning through adversarial evaluation, showing how subtle concept changes can lead to errors.
we propose a robust prompting method, called Abstraction-of-Thought (AoT), to first abstract the adversarial question to a normalized reasoning question, thus facilitating robust reasoning. Experimental results show that AoT significantly improves reasoning performance and robustness.
Recognizing the gap in LLMs' ability to handle graph reasoning tasks, I developed GraphLLM, an approach that integrates graph learning models with LLMs to better interpret and reason on graph data. This method improves performance on fundamental graph reasoning tasks by over 50%, showcasing a significant step forward in the field.

I also tackled the efficiency challenges posed by large-scale LLMs in the context of TAGs. My solution, GraphAdapter, employs a graph neural network (GNN) as a lightweight, efficient adapter for LLMs, reducing computational costs and improving accuracy in various TAG-related tasks. This approach bridges the gap between billion-scale LLMs and efficient, scalable graph-based reasoning, making it adaptable to multiple models like GPT-2 and RoBERTa.

AI for science
========
I am also exploring how AI could be applied in science. AI can analyze vast amounts of data quickly, identify patterns, and automate complex processes, which accelerates discoveries and enhances precision in research.

Graph
========


Publications
=======
Please refer to my Google Scholar profile for the lastest publications and preprints.

Academic service
======
Reviewers of IEEE Transactions on Neural Networks and Learning Systems(TNNLS)

Selected Awards
======
National Scholarship (Twice)

<!-- Education/advised/hobby/dataset -->
